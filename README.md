# IT-Helpdesk-Home-Lab-Portfolio
# Active Directory Home Lab

## Objective
Build a small enterprise-style domain environment to simulate IT Help Desk responsibilities.

## Tools Used
- Windows Server 2022
- Windows 10 VM
- VMware / VirtualBox

## Setup Steps

### 1. Installed Active Directory Domain Services
- Installed AD DS role via Server Manager
- Promoted server to Domain Controller
- Created domain: femilab.local

### 2. Created Organizational Units (OUs)
- IT-Users
- HR-Users
- Sales-Users

### 3. Created Users
- Created test users:
  - John IT (IT department)
  - Mary HR (HR department)

### 4. Group Policy Setup
- Password policy enforced
- Account lockout policy configured

## Screenshots
(Add screenshots here)

## Troubleshooting
- Fixed DNS resolution issues during domain join by setting preferred DNS to Domain Controller IP
