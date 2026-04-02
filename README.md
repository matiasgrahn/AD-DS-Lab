# AD-DS-Lab
"A practical lab for Identity and Access Management (IAM) featuring AD DS, GPO automation, and secure delegation of authority."

📌 Project overview

This project focuses on designing and implementing a secure Active Directory Domain Services (AD DS) environment using Windows Server 2022. The primary goal was to move beyond basic setup and implement enterprise-level security concepts, specifically the Principle of Least Privilege (PoLP) and Administrative Delegation.

The lab simulates a corporate IT infrastructure where support roles (Helpdesk) are granted granular permissions without compromising domain security.

🛠️ Technologies & Tools
* Operating System: Windows Server 2022
* Directory Services: Active Directory (AD DS)
* Policy Management: Group Policy Objects (GPO)
* Virtualization: VMware / VirtualBox
* Networking: DNS & Static IP configuration within a private lab network

🚀 Scenarios & Problem solving
1. Scenario: The "Forgotten Password" & Helpdesk Delegation
   *  Goal: Enable a Helpdesk technician to assist users with password resets without granting full Domain Admin privileges.
   *  Implementation: Used the Active Directory Delegation of Control Wizard to assign specific Reset Password permissions to         the "Helpdesk" user within a designated OU.
   *  Result: The technician could successfully reset user passwords and enforce "User must change password at next logon," but       was blocked from unauthorized actions like deleting accounts (following the Principle of Least Privilege).

2. Scenario: Automated Resource Access (GPO)
   * dd
   * dd
   * dd

3. Scenario: Workstation Hardening & Security
   * dd
   * dd
   * dd
4. Scenario: Core Infrastructure & Connectivity
   * dd
   * dd
   * dd
