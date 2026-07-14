# Lab 17.2.6: Configure Linux

**Role:** System Administrator

## 🎯 Objective
To perform essential Linux administration tasks including account security (locking user accounts), secure file migration across user directories, and enforcing proper file ownership.

## 🚀 Execution Steps
1. **Account Security & Privilege Escalation:** 
   * Escalated privileges by switching to the `root` account to perform administrative tasks. 
   * Secured the system by locking Robert's user account to prevent unauthorized login access.
2. **File & Directory Management (Copy, Move, Remove):** 
   * Copied specific project files (`welcome` and `team_directory`) from Robert's old directory (`/home/rcronn/project_prcc`) to the project administrator's directory (`/home/cflynn`).
   * Moved the entire `project_prcc` directory to Maggie's directory (`/home/mbrown`) to transfer full project access.
   * Removed an unnecessary/unauthorized file (`personal_appointments`) from Robert's account using the `rm` command.
3. **Ownership Configuration (chown/chgrp):** 
   * Reconfigured file permissions for the newly migrated files in Corey's account (`/home/cflynn`). 
   * Changed the user owner to `cflynn` and the group owner to the `proj` group to ensure proper team access control.

## 📊 Results & Evidence
* Successfully secured an inactive user account, migrated critical project files to the appropriate team members, and corrected file ownership to maintain secure access control.

> 📸 Switching to root locking Robert's user account and copy project<img width="667" height="374" alt="image" src="https://github.com/user-attachments/assets/d907d6ad-c5a4-42c5-886b-e8cc355b0771" />

> 📸 Move Project and remove unauthorized file<img width="667" height="375" alt="image" src="https://github.com/user-attachments/assets/27cb81d0-45b2-41b9-a393-9a128a7998f2" />

> 📸 Change owner and group owner<br><img width="670" height="375" alt="image" src="https://github.com/user-attachments/assets/ec25b650-0ac1-4fe5-b043-f2d314825cc0" />

## 🧠 Key Takeaways
* **Account Lifecycle Management:** Locking an account is a critical security measure when an employee leaves or changes roles. It disables login capabilities while preserving the user's data for safe migration by administrators.
* **File Operations in Linux:** Gained hands-on experience using core utilities like `cp` (copy), `mv` (move), and `rm` (remove) to manage directories across different user home paths effectively.
* **Identity and Ownership Management:** Learned that when files are copied or moved by the `root` user, the ownership often defaults to root. It is mandatory to explicitly update the user and group ownership using `chown` and `chgrp` so the intended users (like `cflynn`) can actually access and manage their files.
