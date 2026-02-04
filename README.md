# Enterprise File Sharing Lab

## Overview
This lab demonstrates the configuration of secure file sharing between Windows Server 2025 and a Linux environment.
It covers user management, permissions, network file systems, automation scripts, and log analysis.

The purpose of this lab was to strengthen practical system administration skills across both Windows and Linux platforms.

## Environment
- Windows Server 2025 (Domain Controller)
- Linux Server (NFS + SSH)
- Linux Client
- Active Directory
- PowerShell
- Bash
- Task Scheduler & Cron

## Key Skills Demonstrated
- Active Directory user and group management
- NTFS and share permissions
- Group Policy configuration
- PowerShell automation
- NFS configuration
- SSH hardening
- Log analysis
- Cross-platform file sharing (SMB + CIFS)
- Scheduled tasks and cron jobs

## Project Documentation 
Detailed step-by-step documentation.  

### Windows Server Configuration
https://github.com/maxlaj456/enterprise-file-sharing-lab/blob/main/windows-server.md

### Linux Server Configuration

### Linux Client Configuration

## Security Focus
This lab follows several security best practices:
- Principle of Least Privilege
- Removal of inherited permissions
- Account lockout policies
- Disabled root SSH login
- Modified default SSH port
- Controlled network share access

## Reflection / Key Takeaways
This project strengthened practical administration skills across both Windows and Linux environments while reinforcing the importance of secure permission design and automation.

Key lessons:
- Over-permissioning creates security risks
- Automation improves monitoring and response
- Cross-platform interoperability is critical in modern infrastructure

### Disclaimer
All domain names, IP addresses, and credentials used in this project belong to an isolated lab environment created for educational purposes.

### Author
Maximilian Lajsic
Linkedin: https://www.linkedin.com/in/maximilian-lajsic-930554168/
