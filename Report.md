## Objective
To understand the role of Virtual Private Networks (VPNs) in protecting privacy and enabling secure communication by performing a hands-on VPN setup and usage test on Windows.

## Tools Used
- **VPN Client**: ProtonVPN (Free Tier)
- **Web Browser**: Brave Browser
- **Speed Test Website**: [Speedtest.net](https://www.speedtest.net/)
- **IP Verification Website**: [WhatIsMyIPAddress.com](https://whatismyipaddress.com/)

## Procedure

1. **VPN Selection and Setup**
   - Chose ProtonVPN as the free VPN service.
   - Created a free account on the ProtonVPN website.
   - Downloaded and installed the ProtonVPN Windows client.

2. **Connecting to the VPN**
   - Opened the ProtonVPN client.
   - Logged in using the registered account credentials.
   - Connected to the nearest VPN server for optimal performance.

3. **Verifying VPN Connection**
   - Before connecting, checked IP address on [WhatIsMyIPAddress.com] and recorded location.
   - After connecting to the VPN, refreshed the page to confirm IP address and location change.

4. **Encryption Confirmation**
   - Opened Brave Browser and navigated to [DuckDuckGo](https://duckduckgo.com/).
   - Checked the site security using Brave’s site info panel, confirming **"Connection is secure"** indicating HTTPS encryption.

5. **Speed Comparison**
   - **Without VPN**: Download – 162.84 Mbps, Upload – 64.88 Mbps.
   - **With VPN**: Download – 124.93 Mbps, Upload – 37.71 Mbps.
   - Observed decrease in speed due to VPN encryption and routing overhead.

6. **VPN Detection**
   - Speedtest.net detected VPN usage. This is expected behavior and does not reveal the real IP address.

7. **Research**
   - VPNs encrypt internet traffic between the device and VPN server, masking the user’s IP address from websites and ISPs.
   - Free VPN services may have limitations such as slower speeds, fewer server locations, and data caps.

## Observations
- The VPN successfully masked the IP address and changed the detected location.
- HTTPS encryption worked in conjunction with VPN encryption, adding an extra security layer.
- Internet speed reduced as expected when connected to the VPN.
- Some websites can detect VPN usage but cannot reveal the actual IP address unless the VPN is leaking data.

## Encryption and Privacy Features
- **Encryption Algorithm:** ChaCha20-Poly1305 for data encryption and authentication.
- **Security Strength:** Provides strong confidentiality, integrity, and performance.
- **Fallback Option:** May switch to OpenVPN with AES-256-GCM encryption if network conditions require.

## Benefits of VPN
- Protects online privacy by hiding IP address.
- Encrypts data, preventing interception on public Wi-Fi.
- Allows bypassing of geo-restrictions.
- Prevents ISP tracking of browsing activities.

## Limitations of VPN
- May reduce internet speed.
- Some free VPNs log user activity or limit data usage.
- Certain websites block traffic from known VPN servers.

## Conclusion
Using ProtonVPN on Windows successfully demonstrated how a VPN can enhance privacy and security. Although there was a reduction in internet speed, the VPN effectively encrypted traffic, masked the IP address, and ensured secure browsing. This hands-on experience confirmed the practical benefits of VPN technology while highlighting common limitations such as reduced speed and detection by some services.
