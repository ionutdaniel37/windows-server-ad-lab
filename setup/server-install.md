# Windows Server Installation & Initial Configuration

## Goal
The purpose of this step was to prepare a Windows Server machine to act as a reliable Domain Controller.

## Environment
- Hypervisor: VMware Workstation Player
- OS: Windows Server 2022 (Desktop Experience)
- Network mode: NAT

## Installation Notes
Windows Server was installed from ISO in a virtual machine, similar to a standard Windows 10/11 installation.

## Network Configuration
The server was configured with a static IP address.

- IP: 192.168.171.10
- Subnet mask: 255.255.255.0
- Gateway: 192.168.171.2
- DNS: 127.0.0.1

## Reasoning
Domain Controllers require a static IP address to ensure DNS and authentication stability.

## Validation
Configuration was validated using:
- ipconfig /all
- ping tests from the client VM
