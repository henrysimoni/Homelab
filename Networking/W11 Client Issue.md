**Issue:** Windows 11 client had no internet connectivity during setup.

**Cause:** Client retained a DHCP lease from the previous VMware NAT subnet (192.168.150.0/24).

**Resolution:** Ran `ipconfig /release` and `ipconfig /renew` to obtain a new IP address on the 192.168.1.0/24 network.

**Takeaway:** Changing a network's subnet configuration may require clients to renew their DHCP leases.