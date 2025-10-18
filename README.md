
                      VPN Setup and Testing Report
                        ProtonVPN Free Edition
=====================================================================

Date of Experiment : October 2, 2025
Author             : Aman Rajak

=====================================================================
1. OVERVIEW
=====================================================================
This document contains a detailed report of my VPN setup and testing
experience using **ProtonVPN Free**, a simple and secure VPN service.
The goal of this task was to install a free VPN, connect to a remote
server, verify the IP change, check encrypted browsing, and observe
any speed or privacy differences before and after connection.

=====================================================================
2. PREREQUISITES
=====================================================================
+--------------------------------------------------------------+
| REQUIREMENT      | DESCRIPTION                              |
+--------------------------------------------------------------+
| VPN Provider     | ProtonVPN (Free Plan)                    |
| Device Used      | Windows 10 (64-bit)                      |
| Browser Used     | Google Chrome                            |
| Account Type     | Free Account                             |
| Test Website     | whatismyipaddress.com                    |
+--------------------------------------------------------------+

=====================================================================
3. STEPS FOLLOWED
=====================================================================

STEP 1 : CREATE ACCOUNT
--------------------------------------------------------------
- Opened https://protonvpn.com/
- Selected “Free Plan” and created a new account.
- Verified the email address and logged into the dashboard.

STEP 2 : DOWNLOAD AND INSTALL
--------------------------------------------------------------
- Downloaded the official ProtonVPN Windows client.
- Installed the application with admin rights.
- Launch icon appeared on Desktop and Start Menu.

STEP 3 : LOGIN AND CONNECT
--------------------------------------------------------------
- Opened ProtonVPN app and logged in.
- Selected **Free Server: Netherlands (NL-FREE#10)**.
- Connection status turned green with “Connected” message.
- The interface showed new IP and location.

STEP 4 : VERIFY IP CHANGE
--------------------------------------------------------------
Before connecting:
    IP Address : 103.xx.xx.xx
    Location   : India

After connecting:
    IP Address : 185.xx.xx.xx
    Location   : Netherlands

✔️  IP and location successfully changed.

STEP 5 : ENCRYPTED BROWSING TEST
--------------------------------------------------------------
- Visited https://www.bbc.com and https://wikipedia.org.
- Browser displayed padlock icon (HTTPS secured).
- ProtonVPN still showed “Connected”.
- Pages loaded smoothly with a minor delay (1–2 seconds).

STEP 6 : DISCONNECT AND COMPARE
--------------------------------------------------------------
- Disconnected from VPN app.
- Reloaded whatismyipaddress.com.
- IP reverted to Indian address.
- Browsing speed improved back to normal.
✔️  Connection difference clearly visible.

=====================================================================
4. PROTONVPN FEATURES
=====================================================================
+--------------------------------------------------------------+
| FEATURE           | DESCRIPTION                             |
+--------------------------------------------------------------+
| Encryption        | AES-256-bit industry-grade encryption    |
| Protocols         | OpenVPN (UDP/TCP), WireGuard             |
| No-Logs Policy    | Strict, based in Switzerland             |
| DNS Leak Protect  | Built-in; verified leak-free             |
| Kill Switch       | Available in free plan                   |
| Free Servers      | Japan, Netherlands, United States        |
+--------------------------------------------------------------+

=====================================================================
5. BENEFITS AND LIMITATIONS
=====================================================================

BENEFITS:
--------------------------------------------------------------
- Simple and beginner-friendly setup.
- Effectively hides real IP and geographic location.
- Protects browsing data on public Wi-Fi.
- Encrypts all traffic between device and VPN server.
- Reliable and stable connection.

LIMITATIONS:
--------------------------------------------------------------
- Limited server choices in free plan.
- Slightly reduced browsing speed.
- No P2P or streaming support for free users.
- Cannot manually choose specific city servers.

=====================================================================
6. OBSERVATIONS
=====================================================================
+--------------------------------------------------------------+
| PARAMETER      | WITHOUT VPN           | WITH VPN             |
+--------------------------------------------------------------+
| IP Address     | India (103.xx.xx.xx)  | Netherlands (185.xx) |
| Speed Feel     | Fast                  | Slightly Slower      |
| Encryption     | Normal ISP Route      | AES-256 Encrypted    |
| Location Seen  | Real Location         | Masked (VPN Server)  |
+---------------------------------------------------------------+

Notes:
- Minor delay of about 1–2 seconds observed during browsing.
- Encryption verified through HTTPS lock icon and ProtonVPN status.

=====================================================================
7. SCREENSHOTS (Stored in /screenshots Folder)
=====================================================================
1. vpn_connected.png      → ProtonVPN connected to Netherlands server.
2. ip_changed.png         → whatismyipaddress.com showing new IP.
3. vpn_disconnected.png   → VPN off, IP reverted to India.

=====================================================================
8. CONCLUSION
=====================================================================
Through this test, ProtonVPN Free successfully masked my IP address,
secured my internet connection, and maintained stable performance.
Despite limited servers and minor speed reduction, it is an excellent
free option for privacy protection and secure browsing.
=====================================================================
                           END OF REPORT
=====================================================================
