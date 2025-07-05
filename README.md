# Task 8: VPN Setup using Cloudflare WARP (1.1.1.1)

## Objective
To understand how VPNs enhance user privacy and secure communication by configuring and testing a free VPN service—Cloudflare WARP (1.1.1.1).

---

## Tools & Resources Used
- *VPN Client*: Cloudflare WARP (https://1.1.1.1/)
- *Testing Site*: [https://whatismyip.com](https://whatismyip.com)
- *Operating System*: Windows 10 
- *Network*: Home Wi-Fi

---

## Setup Steps

### Step 1: Download & Install Cloudflare WARP
- Navigated to [https://1.1.1.1](https://1.1.1.1/)
- Chose the appropriate installer for my system (Windows).
- Downloaded and installed the Cloudflare WARP client.

### Step 2: Launch and Connect
- Opened the WARP application.
- Selected *WARP mode* (not just 1.1.1.1 DNS).
- Switched the toggle button to *“Connected”* status.

### Step 3: Verify VPN Connection
- Opened [https://whatismyip.com](https://whatismyip.com)
- Noted the *IP address and location* with WARP enabled.
- Browsed websites to confirm stable and encrypted connectivity.

### Step 4: Disconnect and Compare
- Turned off the WARP VPN.
- Checked [https://whatismyip.com](https://whatismyip.com) again.
- Compared the *original IP address* with the *VPN-assigned IP*.
- Observed the difference in browsing speed (minor delay when VPN is on).

---

## Screenshots 
1) ![Screenshot 2025-07-05 140905](https://github.com/user-attachments/assets/2801a44b-6d12-429c-9eb3-0da52591e102)

2) ![Screenshot 2025-07-05 141019](https://github.com/user-attachments/assets/b0c9f758-c073-404c-8dd6-fcbf3e9f21a1)

3) ![image](https://github.com/user-attachments/assets/d61e71d6-5a0d-4a0d-8c7d-a3147174db04)

4) ![image](https://github.com/user-attachments/assets/e18ef24c-2ced-4058-aea9-0e8292cc641a)

---

## Research Summary

### What is a VPN?
A VPN (Virtual Private Network) creates a secure tunnel for your internet connection, encrypting your data and masking your IP address from external parties like ISPs, hackers, or trackers.

### How WARP Helps:
- Encrypts DNS and traffic to prevent eavesdropping.
- Routes traffic via Cloudflare's secure network for privacy.
- Protects from man-in-the-middle (MITM) attacks on public Wi-Fi.

### Limitations:
- May cause slight browsing latency.
- Does not guarantee full anonymity.
- Some websites might block known VPN traffic.

---

## Outcomes Achieved
- Gained practical experience in installing and using a VPN.
- Understood the difference in IP addresses before and after VPN usage.
- Experienced the privacy benefit and minor speed tradeoff.

---

## Conclusion
Cloudflare WARP is a user-friendly and efficient VPN service offering strong encryption and improved privacy. This task helped understand how VPNs function in real-world scenarios and their role in cybersecurity.
