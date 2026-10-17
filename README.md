# Windows-Server-2022
Active Directory

Windows Server 2022 Infrastructure Project

This project focuses on building and configuring a Windows Server 2022 infrastructure in a virtualized environment using Hyper-V. The lab consists of two Windows Server 2022 virtual machines configured for domain services, network management, and infrastructure administration. Active Directory Domain Services is used to organize users, computers, and Organizational Units. DHCP and DNS provide network configuration and name resolution, while shared folders enable network file sharing. The project also includes DHCP failover configuration and Windows Server Backup for data protection.

Specifications

Hyper-V virtualization

Two Windows Server 2022 virtual machines

Active Directory Domain Services (AD DS)

Domain: rtsnetworking.local

Domain controller configuration

Organizational Units (OUs) for computers and users

Computer OUs for laptops and desktops

User OUs for IT Users and Sales Users

Static IPv4 address configuration

Shared folder configuration

Dynamic Host Configuration Protocol (DHCP)

DHCP scope configuration

DHCP address reservations

DHCP scope options for default gateway and DNS servers

DHCP failover configuration using load balance mode

Domain Name System (DNS) configuration

DNS Host (A) records

DNS Canonical Name (CNAME) records

Windows Server Backup installation and administration

Manual backup execution and verification

Windows Server infrastructure administration

Network services configuration and management

Screenshots

Screenshots documenting the project configuration will be available in the screenshots directory.

static-ip-configuration.png — Static IPv4 configuration

active-directory-ou.png — Active Directory Organizational Units

dhcp-scope-options.png — DHCP scope options and reservation

dhcp-server-overview.png — DHCP server overview

dhcp-failover-setup.png — DHCP failover configuration

dns-records.png — DNS A and CNAME records

shared-folders.png — Network shared folders

windows-server-backup.png — Windows Server Backup status

backup-drive.png — Server drive configuration

hyper-v-virtual-machines.png — Hyper-V virtual machines
