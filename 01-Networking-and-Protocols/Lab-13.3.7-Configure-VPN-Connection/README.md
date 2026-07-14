# Lab 13.3.7: Configure a VPN Connection

**Role:** Network Administrator

## 🎯 Objective
To establish a secure, encrypted tunnel for remote access to the corporate network by configuring a client-side Virtual Private Network (VPN) using the SSTP protocol.

## 🚀 Execution Steps
1. **VPN Profile Setup:** 
   * Navigated to the Windows Network & Internet settings to add a new VPN connection, inputting the corporate VPN server address and defining a clear connection name.
2. **Protocol Configuration:** 
   * Configured the VPN type specifically to Secure Socket Tunneling Protocol (SSTP). This ensures the connection utilizes SSL/TLS encryption for maximum security.
   * Accessed the VPN adapter's Security properties to enforce **EAP-MSCHAP v2** as the required authentication protocol, ensuring credentials are encrypted during the login process.
3. **Authentication & Connection:** 
   * Entered the authorized user credentials (username and password) and initiated the connection. Verified that the workstation successfully authenticated and received an internal IP address from the VPN server.

## 📊 Results & Evidence
* Successfully configured and connected to the corporate VPN, enabling secure and encrypted remote access over an untrusted public network.

> 📸 Add VPN<img width="845" height="561" alt="image" src="https://github.com/user-attachments/assets/164c8fc0-3d11-40c0-ab48-61b69ba161e3" /><br>
> 📸 Set VPN Security<img width="1171" height="600" alt="image" src="https://github.com/user-attachments/assets/1b5e089a-dbde-4048-bbe4-ef74433ab860" />
> 📸 Sign in to connect VPN<img width="858" height="553" alt="image" src="https://github.com/user-attachments/assets/08610306-1343-4047-9a0f-9d0399087877" />

## 🧠 Key Takeaways
* **Secure Remote Access:** Learned that a VPN creates a private, encrypted tunnel over the public internet, allowing remote employees to securely access internal corporate resources (like file servers or intranet sites) as if they were physically sitting in the office.
* **SSTP Protocol Advantages:** Understood that SSTP is highly reliable for remote workers because it encapsulates traffic over HTTPS (Port 443). This allows the VPN connection to easily bypass most restrictive NAT routers, hotel Wi-Fi, and public firewalls without being blocked.
* **EAP-MSCHAP v2 Authentication:** Learned that while SSTP creates the secure tunnel, EAP-MSCHAP v2 protects the user's identity. It securely encrypts the username and password during the login handshake, preventing attackers from capturing plain-text credentials even if they intercept the initial connection.
