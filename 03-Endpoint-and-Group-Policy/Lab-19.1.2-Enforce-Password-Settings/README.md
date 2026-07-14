# Lab 19.1.2: Enforce Password Settings

**Role:** Security Administrator

## 🎯 Objective
To enhance endpoint security by enforcing strict password requirements and configuring account lockout policies to mitigate brute-force attacks.

## 🚀 Execution Steps
1. **Password Policy Configuration:** 
   * Accessed the Local Security Policy (or Group Policy) to enforce minimum password length and complexity requirements (requiring uppercase, lowercase, numbers, and special characters).
   * Configured password history and maximum password age to prevent users from indefinitely reusing the same compromised passwords.
2. **Account Lockout Policy (Brute-Force Prevention):** 
   * Set the Account Lockout Threshold to a specific number of failed logon attempts (e.g., 3 to 5 attempts).
   * Configured the Account Lockout Duration and the reset counter timer, ensuring the account remains locked for a sufficient period to disrupt automated brute-force tools.
3. **Policy Verification:** 
   * Validated the configurations by attempting to set a weak password (which was denied by the system) and testing the lockout mechanism with simulated failed logins.

## 📊 Results & Evidence
* Successfully established a robust authentication baseline that prevents the use of weak passwords and automatically defends against unauthorized guessing attacks.

> 📸 Configured password settings<img width="1255" height="617" alt="image" src="https://github.com/user-attachments/assets/f94291b3-f407-489b-b7c1-ca7eabeacd3d" />

> 📸 Set the account lockout<img width="1279" height="669" alt="image" src="https://github.com/user-attachments/assets/e2522a0b-d645-46dc-ab9e-576ef6aef937" />

## 🧠 Key Takeaways
* **Password Complexity & History:** Learned that relying on passwords alone is vulnerable. Forcing complexity and preventing password reuse (History) significantly reduces the success rate of dictionary attacks and credential stuffing.
* **Brute-Force Mitigation:** Understood that an Account Lockout Policy is the most direct defense against brute-force attacks. By locking the account after a few failed attempts, we mathematically eliminate the attacker's ability to guess thousands of passwords per minute.
* **Balancing Security and Usability:** Realized the importance of setting a reasonable lockout duration. Setting it too high might increase Helpdesk tickets for locked-out legitimate users, while setting it too low might allow attackers to resume their attack too quickly.
