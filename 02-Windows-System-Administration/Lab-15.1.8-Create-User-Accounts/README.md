# Lab 15.1.8: Create User Accounts

**Role:** System Administrator

## 🎯 Objective
To securely manage corporate user accounts by structuring Organizational Units (OUs), standardizing naming conventions, and implementing access restrictions for temporary employees.

## 🚀 Execution Steps
1. **Organizational Structure Setup:** 
   * Created Organizational Units (OUs) to separate and categorize different departments, enabling precise permission management for each group.
2. **User Account Provisioning:** 
   * Created new user accounts utilizing the standard `firstinitial + lastname` naming convention to maintain a professional and organized directory.
   * Configured the initial password policy to force users to change their password at the first logon.
3. **Applying Access Restrictions:** 
   * Configured specific limitations for temporary staff accounts. Set up **Logon Hours** to restrict access to working hours only, and configured **Account Expires** dates to ensure the accounts are automatically disabled after their contract ends.

## 📊 Results & Evidence
* Successfully deployed a structured Active Directory environment with standardized user accounts and hardened access controls for temporary staff.

> 📸 Create user<img width="1037" height="568" alt="image" src="https://github.com/user-attachments/assets/38a951f3-98a8-4462-b8b9-e87e69ca372b" />

> 📸 Set up Logon Hours<img width="1078" height="642" alt="image" src="https://github.com/user-attachments/assets/ba5ad369-ff0f-4d68-84e9-68113d5e36df" />


## 🧠 Key Takeaways
* **OU (Organizational Units) Management:** Categorizing users into OUs is essential for structuring the organization logically and allows administrators to delegate permissions and apply policies effectively based on departments.
* **Naming Conventions:** Utilizing a standard format like `firstinitial + lastname` prevents confusion in large organizations and maintains a professional system architecture.
* **First Logon Password Policy:** Forcing users to change their initial password ensures that IT administrators do not know the users' actual personal passwords, preventing blame-shifting in the event of a data breach.
* **Temporary Staff Restrictions:** Temporary accounts should never have 24/7 access or remain open indefinitely. Setting **Logon Hours** and **Account Expires** closes vulnerabilities, preventing hackers from exploiting the account after hours or after the employee's contract has terminated.
