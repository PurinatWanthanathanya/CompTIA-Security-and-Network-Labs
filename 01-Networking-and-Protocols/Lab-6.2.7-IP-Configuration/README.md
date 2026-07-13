# Lab 6.2.7: Configure IP Addresses

**Role:** IT Administrator

## 🎯 Objective
To configure static IP addresses manually instead of relying on automated DHCP allocation, and to understand core network communication protocols.

## 🚀 Execution Steps
1. **Setting IP Address:** 
   * Accessed IPv4 Ethernet Properties within Advanced Network Settings to manually configure the static IP address and Subnet Mask.
2. **Testing Connection:** 
   * Utilized the `ping` command in the Command Prompt to verify connectivity between devices and ensure proper internet access.

## 📊 Results & Evidence
* Successfully configured the static IP and verified network connectivity with 0% packet loss during the ping test.
  (In this lab, the IP address we need to ping is the DNS server.)

 <img width="864" height="565" alt="image" src="https://github.com/user-attachments/assets/313b6ce2-5a3c-448e-8337-e8114239b5e1" />
 
 <img width="794" height="588" alt="image" src="https://github.com/user-attachments/assets/3892ff24-60d7-4de7-a703-de1f086e70e9" />


## 🧠 Key Takeaways
* **Subnetting (/24 vs /16):** Understood the difference in subnet masks. A `/24` network allocates 24 bits for the network and 8 bits for hosts (Subnet Mask: `255.255.255.0`), yielding 254 usable IPs (excluding Network and Broadcast addresses).[cite: 1] A `/16` network yields 65,534 usable IPs.
* **Default Gateway:** Learned that devices send traffic to a router acting as a default gateway when attempting to communicate with external networks or different IP subnets.
* **DNS (Domain Name System):** Realized the role of DNS in translating human-readable domain names (like .com or .ac.th) into IP addresses for machine communication.
