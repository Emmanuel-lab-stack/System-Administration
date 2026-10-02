# Secura.Tech Active Directory Lab

A hands-on Windows Server administration project focused on deploying and managing an Active Directory domain in a virtualized laboratory environment.

## Overview

This project demonstrates the design and implementation of a Windows Server-based Active Directory environment for a fictional organization, **Secura.Tech**. The lab simulates a corporate IT environment where a system administrator manages user accounts, domain-joined computers, access permissions, security policies, and other essential IT services.

The environment is virtualized using **Linux KVM** and runs Windows Server. One server functions as the Domain Controller, while aUpgrade second Windows Server instance serves as the employee workstation.

The project provides practical exposure to Windows system administration, identity and access management, file services, and IT troubleshooting.

## Objectives

* Deploy and configure Windows Server in a virtualized environment.
* Install and configure Active Directory Domain Services (AD DS).
* Promote a server to a Domain Controller.
* Create and manage a domain environment.
* Join computers to the Active Directory domain.
* Manage users, groups, and user accounts.
* Configure Organizational Units (OUs) and administrative delegation.
* Configure file sharing and access permissions.
* Explore user profiles, home folders, and storage management.
* Develop practical troubleshooting and system administration skills.

## Lab Environment

| Component               | Description                              |
| ----------------------- | ---------------------------------------- |
| Organization            | Secura.Tech                              |
| Virtualization          | Linux KVM                                |
| Server operating system | Windows Server                           |
| Domain Controller       | secura                                   |
| Employee workstation    | PC1                                      |
| Active Directory domain | `secura.tech`                            |
| Directory service       | Active Directory Domain Services (AD DS) |

*Note: The employee workstation is a second Windows Server virtual machine used to simulate a domain-joined client. The operating system versions and configurations should reflect the actual lab deployment.*

## Technologies Used

* Windows Server
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers
* DNS
* Linux KVM
* IPv4 networking
* File Server and shared folders
* File Server Resource Manager (FSRM)
* Remote Desktop Protocol (RDP)
* PowerShell

## Project Tasks

The lab covers the following system administration activities:

1. Server installation and configuration
2. Static IP addressing
3. Installation of Active Directory Domain Services
4. Promotion of the server to a Domain Controller
5. Joining a device to the domain
6. User management and account creation
7. Account administration
8. Logon hours configuration
9. File and folder permissions
10. Read permissions
11. Shared folder configuration
12. Roaming user profiles
13. Home folder configuration
14. File Server Resource Manager
15. Storage quota management
16. File screening management
17. Storage report management
18. Organizational Units
19. Administrative delegation

Additional activities, including Group Policy administration, remote management, PowerShell administration, and troubleshooting, may be documented as they are completed.

## Repository Structure

The repository is organized to document the configuration process, administrative tasks, and practical results of the laboratory.

```text
Secura.Tech-Active-Directory-Lab/
├── README.md
├── documentation/
│   ├── overview.md
│   ├── server-installation.md
│   ├── active-directory.md
│   ├── user-management.md
│   ├── file-services.md
│   └── troubleshooting.md
└── screenshots/
    ├── server-installation/
    ├── active-directory/
    ├── user-management/
    └── file-services/
```

*The directory structure above is a suggested layout. Adjust the filenames and folders to match the files actually present in your repository.*

## Learning Outcomes

Through this project, I am developing practical skills in:

* Windows Server deployment and administration.
* Centralized identity and access management.
* Domain and user account administration.
* File sharing and access control.
* Storage management using FSRM.
* Virtual machine deployment using Linux KVM.
* Troubleshooting common Windows administration issues.
* Documenting technical configurations and administrative procedures.

## Project Status

**Status:** In progress.

The laboratory is being developed incrementally. Each completed task is documented with its configuration steps, relevant screenshots, and observations. Tasks that have not yet been completed will be added as the project progresses.

## Disclaimer

Secura.Tech is a fictional organization created solely for educational and portfolio purposes. All configurations and tests are performed within a controlled laboratory environment. This project is not affiliated with any real organization.

## Author

**Efekodo Emmanuel Onoriode**

Cybersecurity Graduate | Aspiring System Administrator and Cybersecurity Professional

This project demonstrates my ongoing practical learning in Windows Server administration, Active Directory, IT support, and enterprise infrastructure management.
