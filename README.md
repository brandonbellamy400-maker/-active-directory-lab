 # Active Directory Home Lab (Azure)

## 🎯 Objective
This lab focused on the deployment of a Windows Active Directory environment within Microsoft Azure. The goal was to simulate a corporate network to practice user management, security group implementation, and Group Policy Objects (GPOs).

### 🛠️ Tools & Technologies Used
- **Cloud Provider:** Microsoft Azure
- **Operating Systems:** Windows Server 2022 (Domain Controller), Windows 10/11 (Client Workstation)
- **Services:** Active Directory Domain Services (AD DS), Remote Desktop Protocol (RDP), Azure Virtual Networks.

## 📋 Project Steps

### 1. Azure Environment Setup
- Created a Virtual Network (VNet) and subnet for secure internal communication.
- Deployed a Windows Server VM to act as the Domain Controller (DC).
- Deployed a Windows Client VM to act as the workstation.

### 2. Domain Controller Configuration
 ![Server Manager Dashboard](<Server manager DashBoard- AWS LAB.jpg>)
- Installed **Active Directory Domain Services (AD DS)**.
- Promoted the server to a Domain Controller for a new forest (e.g., `mydomain.local`).
- Configured DNS to ensure proper name resolution across the environment.

### 3. User Management & Automation
 ![ADAC User Management](Screenshot%202026-04-23%20141636.png)
- Created Organizational Units (OUs) to mirror a business structure (HR, IT, Sales).
- Used a PowerShell script to bulk-create users to simulate a realistic corporate directory.

### 4. Security Implementation
- Joined the client workstation to the domain.
- Practiced account lockouts and password policy testing.
- Verified group memberships and access controls.

## 🧠 Key Takeaways
- Gained hands-on experience with **Identity and Access Management (IAM)**.
- Learned how to manage network resources in a cloud-hybrid environment.
- Improved understanding of how centralized management reduces security risks in an organization.
