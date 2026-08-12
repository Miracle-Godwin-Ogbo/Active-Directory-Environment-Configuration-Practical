# Active Directory Environment Configuration

## Overview

Hands-on Active Directory configuration completed as part of the CYBERGON cybersecurity training program using Windows Server 2022 in a VMware laboratory environment.

The project demonstrates the configuration of Organizational Units, user accounts, departmental security groups, group membership, and domain-level password policy through Group Policy Management.

## Environment

- **Operating System:** Windows Server 2022
- **Domain:** `Godwin.local`
- **Virtualization:** VMware
- **Directory Services:** Active Directory Domain Services
- **Management:** Active Directory Users and Computers
- **Policy Management:** Group Policy Management

## Active Directory Configuration

Three sector-based Organizational Units were created:

- `OMG-Bank`
- `OMG-HealthCare`
- `OMG-University`

Each sector contains four departmental security groups and their corresponding user accounts. Users were assigned to their respective departmental groups, with each user belonging to only one department according to the practical requirements.

### Screenshot 01 — Sector Organizational Units

![Organization Units](screenshots/Three-Sector-OUs.png)

Shows the three sector-based Organizational Units created under the `Godwin.local` domain.

### Screenshot 02 — Bank Users and Groups

![Bank-Department](screenshots/Bank-Department.png)

Shows the users and departmental security groups created under the `OMG-Bank` OU.

### Screenshot 03 — Bank Group Membership

![Bank-Group-Membership](screenshots/Bank-Department-Users.png)

Shows users added to their appropriate Bank departmental security group.

### Screenshot 04 — Healthcare Users and Groups

![HealthCare-Department](screenshots/HealthCare-Department.png)

Shows the users and departmental security groups created under the `OMG-HealthCare` OU.

### Screenshot 05 — Healthcare Group Membership

![HealthCare-Department-Users](screenshots/HealthCare-Department-Users.png)

Shows users added to their appropriate Healthcare departmental security group.

### Screenshot 06 — University Users and Groups

![University-Department](screenshots/University-Department.png)

Shows the users and departmental security groups created under the `OMG-University` OU.

### Screenshot 07 — University Group Membership

![University-Department-Users](screenshots/University-Department-Users.png)

Shows users added to their appropriate University departmental security group.

## Group Policy Configuration

The **Default Domain Policy** was configured through Group Policy Management to modify the domain password policy.

The following setting was disabled:

**Password must meet complexity requirements**

### Screenshot 08 — Default Domain Policy

![Default-Domain-Policy](screenshots/Default-Domain-Policy.png)

Shows the Default Domain Policy used for the password configuration.

### Screenshot 09 — Password Policy

![Password-Policy-Location](screenshots/Password-Policy-Location.png)

Shows the Password Policy section under Account Policies in the Group Policy Editor.

### Screenshot 10 — Password Complexity Disabled

![Password-Complexity-Disabled](screenshots/Password-Complexity-Disabled.png)

Shows that the password complexity requirement was disabled as required by the practical.

## Documentation

The complete practical report, including the detailed procedures and supporting evidence, is available below.

[View the Full Practical Report (PDF)](CYBERGON-Active-Directory-Practical-Report.pdf)

## Author

**Miracle Godwin Ogbo**

Junior Penetration Tester | Cybersecurity Student

## Disclaimer

This project was completed in a controlled VMware virtual laboratory environment for educational and cybersecurity training purposes.

The password complexity configuration was modified specifically to satisfy the requirements of the CYBERGON practical exercise and should not be considered a recommended production security configuration.
