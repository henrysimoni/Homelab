
# Homelab Progress Log

## October 2026 — Windows Server & Active Directory

### Virtualization & Networking
- Deployed Windows Server (DC01) and Windows 11 Pro (CLIENT01) using VMware Workstation Pro.
- Configured VMnet8 NAT networking (`192.168.1.0/24`).
- Configured a static IP for DC01 (`192.168.1.11`).
- Configured VMware DHCP for automatic client IP assignment.
- Troubleshot and resolved VMware NAT gateway IP conflict.

### Active Directory & DNS
- Installed Active Directory Domain Services (AD DS).
- Promoted DC01 to a domain controller for `ad.lab`.
- Configured forward and reverse DNS lookup zones.
- Verified DNS resolution and Active Directory SRV records.
- Confirmed domain controller discovery from CLIENT01.

### Windows 11 Client
- Installed and configured Windows 11 Pro.
- Configured DHCP networking with DC01 as the DNS server.
- Successfully joined CLIENT01 to the `ad.lab` domain.
- Verified CLIENT01 appears in Active Directory Users and Computers (ADUC).

### GitHub Documentation
- Created and organized the Homelab GitHub repository.
- Documented Active Directory, DNS, and networking configurations.
- Added screenshots and troubleshooting notes.
- Created a README and progress log.

## Next Steps
- [ ] Create organizational units (OUs), users, and security groups.
- [ ] Configure and test Group Policy Objects (GPOs).
- [ ] Configure file shares and NTFS permissions.
- [ ] Practice PowerShell administration and automation.
- [ ] Configure Windows Server DHCP.
- [ ] Explore Azure and Microsoft Entra ID.
