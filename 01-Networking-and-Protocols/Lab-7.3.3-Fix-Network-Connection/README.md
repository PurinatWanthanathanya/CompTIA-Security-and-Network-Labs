# Lab 7.3.3: Fix a Network Connection

**Role:** IT Administrator

## 🎯 Objective
To troubleshoot and resolve network connectivity issues by diagnosing physical layer disconnections and manually configuring IP settings when DHCP is unavailable.

## 🚀 Execution Steps
1. **Physical Layer Inspection:** 
   * Checked the network status for "Media disconnected" or "Unplugged" messages and verified the physical LAN cable and port connections.
2. **IP Configuration:** 
   * Encountered an "Unidentified network" status indicating no DHCP server was available to assign an IP automatically. Accessed Advanced Network Settings to assign a static IP manually, ensuring it did not conflict with reserved or existing IPs.
3. **Connectivity Verification:** 
   * Utilized the `ping` command to test DNS resolution and confirm successful connection to the internet.

## 📊 Results & Evidence
* Successfully restored network connectivity by resolving the physical disconnection and applying a valid static IP without IP conflicts.

> 📸 Plugged Ethernet<img width="871" height="613" alt="image" src="https://github.com/user-attachments/assets/757716d4-6b99-4583-9d9f-f465fb364d17" /><br>

> 📸 Network Unidentified<img width="1297" height="697" alt="image" src="https://github.com/user-attachments/assets/26b2215e-e234-43e5-a92a-f0f0787943df" />

> 📸 Configure Ip Address .15 being used by the server and beetween .30 and .34 being used by other workstation <img width="1300" height="676" alt="image" src="https://github.com/user-attachments/assets/7681c97c-26ea-4897-aa8c-6b3a7d03001c" />

> 📸 Ip Address: 192.168.0.33 is the office2 computer<img width="796" height="575" alt="image" src="https://github.com/user-attachments/assets/192eb5f5-0cad-48e2-9a5a-9134848bbbf2" />

## 🧠 Key Takeaways
* **Physical Layer Troubleshooting:** Learned that error messages like "Media disconnected" or "Unplugged" require immediate checking of physical components, such as broken LAN cables or closed network ports.
* **Handling DHCP Failures:** Understood that an "Unidentified network" status often signifies the absence of an automatic IP assigner (DHCP). In this scenario, manual IP configuration is necessary, and one must be strictly careful not to duplicate IPs already in use on the network.
