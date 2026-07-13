# Lab 13.3.9: Local Firewall Settings

**Role:** IT Administrator

## 🎯 Objective
To secure the endpoint by configuring local firewall profiles based on network environments and managing application-specific firewall exceptions.

## 🚀 Execution Steps
1. **Network Profile Identification:** 
   * Differentiated the network connections into Domain (corporate), Private (home), and Public (cafes/airports) profiles, identifying Public networks as the highest risk environment.
2. **Firewall Hardening (Public Profile):** 
   * Enforced strict inbound blocking rules specifically for the Public Profile. This ensures the system is hidden from external scanning and unauthorized access attempts when connected to public Wi-Fi, without affecting the default configurations for the internal corporate network.
3. **Application Exceptions (Allow Apps):** 
   * Configured specific "Allow" rules (exceptions) to permit trusted applications to bypass the firewall and communicate freely, creating controlled entry points for legitimate traffic.

## 📊 Results & Evidence
* Successfully hardened the workstation's local firewall against external threats on public networks while maintaining seamless connectivity for authorized services like File/Printer sharing and Cloud Identity.
  
> 📸 <img width="1279" height="648" alt="image" src="https://github.com/user-attachments/assets/982855a5-3d8d-4921-9c7b-f402b3c3aa73" />


## 🧠 Key Takeaways
* **Network Profiles:** Understood that Windows categorizes networks into Domain, Private, and Public. The Public profile requires the most stringent security settings due to the untrusted nature of the environment.
* **Context-Aware Security:** Learned the importance of applying strict inbound blocking exclusively on public networks. This prevents strangers on the same Wi-Fi from scanning or breaching the machine, while keeping private network configurations intact.
* **Firewall Exceptions (Allowing Apps):** Realized that allowing an app through the firewall essentially opens a specific "window" for trusted traffic. This highlights the importance of only allowing absolutely necessary applications to minimize the attack surface.
