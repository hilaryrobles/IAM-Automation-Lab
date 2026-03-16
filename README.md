# 🔐 IAM Automation Lab

A hands-on Identity and Access Management lab simulating real world identity governance, 
access provisioning, and user lifecycle management using Microsoft Entra ID and PowerShell.

## 📌 Overview

This lab was built to bridge the gap between IAM theory and hands-on practice. 
Rather than just studying concepts, I wanted to simulate the kind of identity 
management work that happens in real enterprise environments, from onboarding users 
to enforcing access controls and automating repetitive provisioning tasks.

Coming from an IT Technician role where I work with Entra ID and Active Directory daily, 
I wanted to go deeper. This lab gave me the space to practice user lifecycle management, 
automate provisioning tasks with PowerShell, and explore identity governance concepts that 
are core to any IAM role.

## 🛠️ Tools & Environment

| Tool | Purpose |
|------|---------|
| VirtualBox | Creating and managing virtual machines |
| Windows Server 2022 | Active Directory Domain Controller |
| Microsoft Entra ID | Cloud identity and access management |
| Active Directory | On-premises identity management |
| PowerShell | Automation and scripting |
| Microsoft 365 | License assignment and productivity suite management |
| Microsoft Graph API | Programmatic interaction with Entra ID |

## 📂 Lab Breakdown

### 1. Environment Setup
> Setting up the lab environment including VirtualBox, Windows Server 2022, 
> and a free Microsoft Entra ID tenant.

This section covers the initial setup of the lab environment. A Windows Server 2022 
virtual machine is created in VirtualBox and promoted to a Domain Controller, 
establishing the on-premises foundation of the lab. A free Microsoft Entra ID tenant 
is also configured to handle cloud identity management.

**What is covered:**
- Installing and configuring VirtualBox
- Creating and configuring a Windows Server 2022 VM
- Promoting Windows Server to a Domain Controller
- Setting up a free Microsoft Entra ID tenant

*Screenshots and documentation coming soon*

### 2. User Lifecycle Management
> Simulating the full lifecycle of a user identity from onboarding to offboarding 
> across both Microsoft Entra ID and Active Directory.

This section covers the end to end process of managing a user identity. Starting 
from creating a new user account, assigning the appropriate licenses in Microsoft 365, 
and configuring group memberships, all the way through to offboarding, which includes 
disabling accounts, revoking licenses, and removing access. Both Entra ID and Active 
Directory are used to reflect how identity management works in a hybrid enterprise environment.

**What is covered:**
- Creating and configuring users in Entra ID and Active Directory
- Creating Organizational Units and Security Groups
- Assigning and managing Microsoft 365 licenses
- Managing group memberships and access
- Offboarding users and revoking access

*Screenshots and documentation coming soon*

### 3. Role Based Access Control (RBAC)
> Assigning and managing roles and permissions based on job function to enforce 
> the principle of least privilege.

This section focuses on making sure users only have the access they need to do their 
job and nothing more. Roles are assigned based on job function using Entra ID's built 
in RBAC model, and custom role assignments are explored to reflect real world scenarios 
where default roles do not always fit.

**What is covered:**
- Assigning built in Entra ID roles to users
- Creating and assigning custom roles
- Auditing role assignments to identify over provisioned accounts
- Enforcing least privilege across the environment

*Screenshots and documentation coming soon*

### 4. Access Provisioning & Deprovisioning
> Automating the process of granting and revoking access using PowerShell scripts 
> to reduce manual effort and human error.

Rather than relying on manual portal clicks, this section focuses on automating 
provisioning and deprovisioning tasks through PowerShell. Scripts are written to 
handle common IAM tasks such as bulk user creation, license assignment, group 
membership updates, and account deactivation. The goal is to simulate how these 
tasks are handled at scale in an enterprise environment.

**What is covered:**
- Writing PowerShell scripts to automate user provisioning
- Bulk creating and configuring users via script
- Automating license assignment and group membership
- Scripting the offboarding and deprovisioning process

*Scripts and documentation coming soon*

### 5. Conditional Access Policies
> Configuring policies in Microsoft Entra ID to enforce security controls and 
> restrict access based on user, location, and device conditions.

This section covers the configuration of Conditional Access policies to protect 
the environment from unauthorized access. Policies are set up to reflect real 
enterprise security requirements, ensuring that access is only granted under the 
right conditions.

**Policies configured:**
- Require MFA for all users
- Block access from outside the United States
- Require compliant and managed devices
- Block legacy authentication protocols

*Screenshots and documentation coming soon*

### 6. Identity Governance
> Using Microsoft Entra ID Access Reviews to ensure users retain only the access 
> they need over time.

Access does not manage itself. This section uses Entra ID Access Reviews to 
periodically review and certify user access rights across the environment. 
The goal is to identify and remove unnecessary or outdated access, which is 
one of the most important and often overlooked aspects of identity governance.

**What is covered:**
- Setting up Access Reviews for users and groups
- Reviewing and certifying access rights
- Automating access removal for users who no longer need it
- Documenting findings and remediation steps

*Screenshots and documentation coming soon*

## 💡 Key Takeaways

*To be updated as the lab progresses*

## 📚 References & Resources

- [Microsoft Entra ID Documentation](https://learn.microsoft.com/en-us/entra/identity/)
- [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
- [Microsoft 365 Admin Documentation](https://learn.microsoft.com/en-us/microsoft-365/)
- [Microsoft Graph PowerShell SDK](https://learn.microsoft.com/en-us/powershell/microsoftgraph/overview)
- [VirtualBox Documentation](https://www.virtualbox.org/wiki/Documentation)
- [Windows Server 2022 Evaluation](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022)

*This lab is actively being built. Check back for updates!*
