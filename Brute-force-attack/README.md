# Brute Force Attack using Medusa

## Overview
Brute force attacks try multiple password combinations to gain access.

## Tools Used
- Medusa
- Kali Linux
- Metasploitable linux

## Objective
To demonstrate password cracking using dictionary attacks.

## Procedure
1. Set up test login service
2. Prepare password list
3. Run Medusa command
4. Observe login attempts

## Screenshots
<img width="1914" height="1199" alt="Medusa-command-run" src="https://github.com/user-attachments/assets/8c5817c7-4822-4dba-8cad-2efeab881baf" />
<img width="1919" height="368" alt="Password-cracking-succesful" src="https://github.com/user-attachments/assets/b611092e-13a2-4328-8581-ec98a0b5d427" />
<img width="1634" height="757" alt="Entering-through-cracked-password" src="https://github.com/user-attachments/assets/c6818a97-0d8e-4dc0-ab94-ef755c8799f1" />
<img width="1919" height="1194" alt="Accessing-datas-through-local-system" src="https://github.com/user-attachments/assets/d57a844b-f6c8-4020-a70a-827535fc4db2" />
<img width="1335" height="305" alt="Checking-whether-the-datas-are-matching" src="https://github.com/user-attachments/assets/128760b1-0e37-4ab7-83a7-0436e3ef18b6" />


## Result
Weak password was successfully cracked.

## Learning Outcome
- Importance of strong passwords
- Understanding brute-force attacks

## Detection
- High volume of failed logins
- Single IP,multiple username
- Multiple IPs,single username
- Unusual login times
- Sequential guessing
- Anamalous response sizes

## Prevention
- Strong passwords
- Account lockout policies
- Multi-factor authentication

## MITRE ATT&CK Mapping
- Brute Force → Credential Access (T1110)

⚠️ Performed in controlled lab environment.
