# Password Sniffing using Wireshark

## Overview
Password sniffing involves capturing network traffic to detect sensitive information transmitted over insecure channels.

## Tools Used
- Wireshark
- Kali Linux

## Objective
To capture and analyze network packets and identify exposed credentials.

## Procedure
1. Start Wireshark on attacker machine
2. Begin packet capture
3. Perform login activity on another machine
4. Filter packets using HTTP/TCP
5. Analyze packets for credentials

## Screenshots
<img width="1574" height="816" alt="Entering-datas-in-a-website" src="https://github.com/user-attachments/assets/d5df3026-e40e-48ec-9841-d85397cd4c62" />
<img width="1850" height="984" alt="Capturing-https-datas" src="https://github.com/user-attachments/assets/a6fc0343-5199-45cc-ae08-67d58e5e4897" />
<img width="1919" height="1199" alt="Entering-anothe-data" src="https://github.com/user-attachments/assets/ebcbb4fa-5bca-4e19-91d7-a63daeb7416e" />
<img width="1914" height="1199" alt="Capturing-the-same-using-wireshark" src="https://github.com/user-attachments/assets/a0506b9d-ef86-4213-be8e-76f97530f261" />

## Result
Unencrypted login credentials were visible in captured packets.

## Learning Outcome
- Understanding packet analysis
- Importance of HTTPS encryption
- Risks of unsecured networks

## Prevention
- Use HTTPS websites
- Encrypt network traffic
- Avoid public Wi-Fi for sensitive data

⚠️ Educational use only in controlled environment.
