# Active Directory Lab - Windows Server 2022

This repository documents my hands-on Active Directory lab built using Windows Server 2022 in VMware Workstation.

## Lab Overview
- Installed Active Directory Domain Services (AD DS)
- Configured DNS Server
- Assigned static IP address for the Domain Controller
- Created a department-based Organizational Unit (OU) structure (HR, IT, Sales)
- Created user accounts and security groups per department
- Configured and linked Group Policy Objects (GPOs) for password policy enforcement
- Verified network connectivity using `ipconfig` and `ping`

## Environment
- Windows Server 2022
- VMware Workstation (NAT networking)
- Active Directory Domain Services (AD DS)
- DNS Server role
- Group Policy Management

---

## Screenshots

### Server Manager Dashboard

![Server Manager Dashboard](Screenshoots/(AD%20DS%26DNS%20)

%20Server%20Manager%20Dashboard.png)

### AD DS Installation

![Server Roles Selection](Screenshoots/AD%20DS%20Installation%20-%20Server%20Roles.png)

![Installation Progress](Screenshoots/AD%20DS%20Installation%20Progress.png)

### Network Configuration

![Static IP Configuration](Screenshoots/Static%20IP%20Configuration.png)

![IP Verification](Screenshoots/ipconfig%20+%20ping.png)

### Organizational Unit Structure

![HR OU](Screenshoots/Active%20Directory%20Users%20%26%20Computers%20(HR%20OU)

.png)

![Sales OU](Screenshoots/Active%20Directory%20Users%20%26%20Computers%20(Sales%20OU)

.png)

### Group Policy Configuration

![HR Password Policy - Scope](Screenshoots/Group%20Policy%20Management-HR%20Password%20Policy.png)

![HR Password Policy - Settings](Screenshoots/Group%20Policy%20Management-HR%20Password%20Policy%20Settings.png)

![IT Password Policy](Screenshoots/Group%20Policy%20Management-IT%20Password%20Policy.png)

![Sales Password Policy](Screenshoots/Group%20Policy%20Management-Sales%20Password%20Policy.png)

---

## Skills Demonstrated
- Windows Server Administration
- Active Directory Domain Services (AD DS) deployment
- DNS Server configuration
- Organizational Unit (OU) design
- User & Security Group management
- Group Policy Object (GPO) creation and linking
- Static IP / network configuration
- VM-level troubleshooting
