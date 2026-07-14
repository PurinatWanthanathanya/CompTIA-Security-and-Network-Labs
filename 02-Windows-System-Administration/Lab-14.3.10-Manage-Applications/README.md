# Lab 14.3.10: Manage Applications

**Role:** System Administrator

## 🎯 Objective
To monitor system performance, resolve unresponsive applications, and ensure legacy software functionality using Task Manager and Compatibility Mode.

## 🚀 Execution Steps
1. **Process Management (Task Manager):** 
   * Launched Task Manager to monitor real-time system resources (CPU, Memory, and Disk usage). 
   * Identified an unresponsive/high-resource consuming process and safely terminated it using the "End task" function to restore system stability.
2. **Legacy Application Support (Compatibility Mode):** 
   * Investigated an older corporate application that failed to launch correctly on the modern Windows operating system. 
   * Accessed the executable file's Properties, navigated to the Compatibility tab, and configured **Compatibility Mode** to run the program in a previous Windows environment (e.g., Windows 7 or Windows 8).
3. **Startup Optimization:** 
   * Navigated to the Startup tab within Task Manager to identify and disable non-essential applications from launching at boot, significantly improving the endpoint's startup time.

## 📊 Results & Evidence
* Successfully restored system performance by terminating hung processes and enabled the legacy application to run flawlessly without needing to downgrade the operating system.

> 📸 Disable startup apps<br><img width="716" height="537" alt="image" src="https://github.com/user-attachments/assets/de593d5e-0e74-41d6-831a-2d86f9259aab" />

> 📸 Configure Compatibility Mode<img width="888" height="543" alt="image" src="https://github.com/user-attachments/assets/22c570ab-9d67-49a4-8acd-af7e30a7f75d" />

## 🧠 Key Takeaways
* **Task Manager as a Diagnostic Tool:** Learned that Task Manager is the first line of defense for troubleshooting system slowdowns, allowing IT staff to pinpoint exact resource bottlenecks and forcefully stop rogue applications.
* **Bridging the Gap with Compatibility Mode:** Understood that businesses often rely on legacy software that hasn't been updated. Compatibility Mode is a crucial feature that simulates older OS environments, allowing these essential tools to function on modern, secure operating systems.
* **Startup Impact:** Realized that managing startup items is a quick and highly effective way to optimize endpoint performance, freeing up RAM and CPU cycles for actual user productivity.
