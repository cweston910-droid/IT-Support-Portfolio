# Active Directory Home Lab & Systems Administration Lab

## Overview
Built a Windows Server 2019 Active Directory lab using UTM/QEMU to simulate Help Desk and junior systems administration tasks.

## Tools Used
- Windows Server 2019
- Windows 11 Client VM
- UTM / QEMU on macOS
- Active Directory Domain Services
- DNS Server
- DHCP Server
- Group Policy Management
- Active Directory Users and Computers
- File and Storage Services
- Microsoft Excel ticket log

## What I Configured
- Created the homeitlab.local domain
- Promoted DC01 to a domain controller
- Created OUs for IT, Help Desk, HR, Finance, Workstations, and Disabled Users
- Created users and security groups
- Joined CLIENT-01 to the domain
- Created TechniciansShare and tested group-based access
- Configured and tested Group Policy desktop wallpaper
- Created mock Help Desk tickets
- Installed and configured DHCP Server role and IPv4 scope options

## Troubleshooting Highlights
- Resolved Windows installation ISO conflict
- Fixed VM boot and Guest Tools issues
- Resolved DNS problems preventing domain discovery
- Troubleshot domain join credential and DNS issues
- Validated file share access and access denied behavior
- Documented UTM DHCP lease behavior as a virtualization limitation

- ## Skills Demonstrated
- Active Directory administration
- User provisioning and deprovisioning
- Password resets and account unlocks
- Security group administration
- Organizational Unit (OU) management
- DNS and DHCP administration
- Group Policy (GPO) deployment and troubleshooting
- SMB file share permissions
- Network drive mapping
- Windows domain management
- Help Desk ticket documentation
- Technical troubleshooting and root cause analysis

## Screenshots
The repository includes screenshots demonstrating:
- Active Directory OU structure
- User account creation
- Security group membership
- Domain join process
- Password reset procedures
- Account unlock procedures
- DHCP installation and configuration
- DHCP scope options
