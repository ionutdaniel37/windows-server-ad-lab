# Active Directory Domain Setup

## Goal
The goal of this step was to deploy Active Directory Domain Services and create a new domain.

## AD DS Installation
- Installed the Active Directory Domain Services role via Server Manager
- Included DNS Server role

## Domain Configuration
- Created a new forest
- Domain name: lab.local
- Functional level: Windows Server 2022
- DNS configured automatically

## Domain Controller Configuration
- Server promoted to Domain Controller
- Global Catalog enabled
- SYSVOL created successfully

## Post-Installation Checks
- Verified domain lab.local exists
- Verified DNS service is running
- Verified SYSVOL and NETLOGON shares

## Validation
The following checks were performed:
- Logged in using domain administrator account
- Opened Active Directory Users and Computers
- Verified DNS zone creation
