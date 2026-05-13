# IT Home Lab

A self-built enterprise IT environment covering both on-premise Active Directory and cloud-based Microsoft 365 administration. Built to develop hands-on skills that translate directly to IT support and system administration roles.

---

## What This Covers

### On-Premise — Active Directory
- Windows Server 2022 set up as a Domain Controller from scratch
- Users, computer accounts and Organizational Units (OUs)
- Security Groups with department-based access control
- Shared folders with NTFS permissions — users access only what they're authorized for
- Group Policy Objects (GPOs) — wallpaper enforcement, CMD block, Control Panel block, USB storage block, software deployment (7-Zip)

### Cloud — Microsoft 365
- **Entra ID** — user creation, license assignment, Security Groups, Microsoft 365 Groups, Distribution Groups, password reset, session revocation
- **Microsoft Intune** — device enrollment via Entra ID join, compliance policies (BitLocker, antivirus, Windows version, password), configuration profiles (USB block, CMD block, Control Panel block, wallpaper), app deployment, conditional access blocking non-compliant devices from email
- **SharePoint Online** — Team Site and Communication Site creation, Hub Sites, group-based permissions
- **Exchange Online** — shared mailbox setup, mailbox delegation (Full Access + Send As), mail flow rules (external email warning banner)

---

## Lab Setup

| Component | Details |
|---|---|
| Server | Windows Server 2022 on a VM |
| Client Machine | Dell Laptop — Windows 10 Enterprise, domain joined |
| Host Machine | Personal laptop (Win 11) hosting the VM |
| Cloud Tenant | Microsoft 365 E3 Trial |

---

## Report

Full documentation with screenshots of every configuration is available in the report below.

📄 [View Home Lab Report](./Sachin_Homelab_Report.pdf)

---

## Why I Built This

Desktop support and sysadmin roles expect real tool experience. This lab was built to go beyond theory — every item in this repo was configured hands-on, tested, and verified on actual hardware and a live Microsoft 365 tenant.

---

## Connect

- 📧 sachindongare058@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/sachin-dongare-a33922288/)
