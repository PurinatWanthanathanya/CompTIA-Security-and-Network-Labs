# Lab 19.2.7: Configure Microsoft Defender Antivirus

**Role:** Security Administrator

## 🎯 Objective
To secure the endpoint by configuring Microsoft Defender Antivirus, executing appropriate system scans, and setting up file exclusions to balance system security with application performance.

## 🚀 Execution Steps
1. **Antivirus Scan Execution:** 
   * Navigated to Virus & threat protection to perform manual scans. Utilized a Quick Scan for checking common threat areas (like startup folders and registries) and a Full Scan for a comprehensive analysis of all files on the system.
2. **Configuring Exclusions:** 
   * Accessed the Virus & threat protection settings to add specific folder and file exclusions. Configured the antivirus engine to ignore a trusted, resource-heavy developer directory to prevent false positives and reduce unnecessary CPU overhead.
3. **Protection Verification:** 
   * Verified that core security features, including Real-time protection and Cloud-delivered protection, were enabled and actively monitoring the system for zero-day threats.

## 📊 Results & Evidence
* Successfully completed system scans to ensure the endpoint is malware-free, and applied exclusions effectively without compromising overall system security.

> 📸 Add exclusions trusted files or services<img width="1073" height="624" alt="image" src="https://github.com/user-attachments/assets/e1160668-3701-4526-a703-0962c3fb7c17" />

## 🧠 Key Takeaways
* **Scan Types (Quick vs. Full):** Learned that a Quick Scan is efficient for daily baseline checks because it targets the most vulnerable areas, whereas a Full Scan is resource-intensive but necessary for deep forensic checks across all connected drives.
* **The Importance of Exclusions:** Understood that security should not break business operations. Adding exclusions for trusted applications, databases, or developer environments prevents the antivirus from degrading system performance or deleting safe files due to false positives.
* **Real-time vs. On-demand:** Realized that while manual scans are great for remediation, Real-time protection is the critical first line of defense that stops malicious files the moment they are downloaded or executed.
