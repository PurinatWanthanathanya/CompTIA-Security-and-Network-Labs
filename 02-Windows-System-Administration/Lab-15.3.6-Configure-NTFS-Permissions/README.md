# Lab 15.3.6: Configure NTFS Permissions

**Role:** System Administrator

## 🎯 Objective
To secure sensitive corporate data by configuring NTFS permissions, managing Access Control Lists (ACLs), and enforcing the Principle of Least Privilege (PoLP).

## 🚀 Execution Steps
1. **Access Control List (ACL) Configuration:** 
   * Accessed the Security tab of target folders to modify NTFS permissions. Assigned specific rights (Read, Write, Modify, Full Control) to designated user groups while explicitly denying access to unauthorized personnel.
2. **Disabling Inheritance:** 
   * Disabled permission inheritance on highly sensitive subfolders. Removed inherited permissions from the parent directory to prevent unauthorized users from accidentally gaining access to restricted files.
3. **Enforcing Least Privilege:** 
   * Applied explicit permissions based strictly on user roles, ensuring that each user or group was granted the absolute minimum level of access required to perform their daily tasks (e.g., granting 'Read' instead of 'Modify').

## 📊 Results & Evidence
* Successfully restricted unauthorized access to sensitive directories and verified that folder permissions strictly comply with the organization's security and PoLP policies.

> 📸 Disable inheritance<img width="1203" height="590" alt="image" src="https://github.com/user-attachments/assets/16f34bd1-835e-42df-a8ab-bd823f43ab2c" />
> 📸 Convert inherit permission to explicit permission<img width="1186" height="609" alt="image" src="https://github.com/user-attachments/assets/741271b3-ccfd-45c1-a679-3927fdf213fa" />
> 📸 Grant the group maximum access rights<img width="1143" height="616" alt="image" src="https://github.com/user-attachments/assets/c1b1d078-e547-4e34-a0ce-51d16aaa921d" />




## 🧠 Key Takeaways
* **NTFS Permissions & ACLs:** Learned that NTFS permissions provide granular, file-level security by using Access Control Lists (ACLs) to dictate exactly who can view, edit, or execute specific files.
* **Permission Inheritance:** Understood that by default, subfolders inherit permissions from their parent folders. Disabling inheritance is a critical security step when a subfolder (e.g., a manager's confidential folder) requires stricter security than the main department drive.
* **Principle of Least Privilege (PoLP):** This is a core cybersecurity concept. By giving users only the minimum access necessary for their job, we significantly reduce the potential damage from insider threats or compromised user accounts.
