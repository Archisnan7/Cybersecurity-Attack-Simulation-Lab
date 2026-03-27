# SQL Injection Testing

## Overview
SQL Injection is a vulnerability that allows attackers to manipulate database queries.

## Tools Used
- Vulnerable test website
- Browser

## Objective
To test web application vulnerability using SQL payloads.

## Procedure
1. Open vulnerable login page
2. Enter SQL payload (e.g., ' OR '1'='1)
3. Observe system response

## Screenshots
<img width="1919" height="646" alt="Using-OR 1=1 -payload" src="https://github.com/user-attachments/assets/612d1720-89e7-4122-bb5f-5994c747c719" />
<img width="1887" height="642" alt="Using-OR 1=1-- payload" src="https://github.com/user-attachments/assets/7eb4af37-aad5-4351-9943-cc41234cbaf1" />
<img width="1911" height="683" alt="using-OR 1=1# -payload" src="https://github.com/user-attachments/assets/6b8ff937-53e2-4c52-936e-4c04462ff587" />
<img width="1919" height="593" alt="Using-Admin#-payload" src="https://github.com/user-attachments/assets/9c51175f-973a-4208-ab68-ef415d86a939" />
<img width="1905" height="561" alt="Using-admin-- payload" src="https://github.com/user-attachments/assets/45a86206-b570-477c-b441-0f2465e03226" />
<img width="1880" height="829" alt="Using-admin-payload" src="https://github.com/user-attachments/assets/db4121d6-91eb-468c-96ce-28507bbbcd26" />
<img width="1905" height="645" alt="Login-successful-using-admin-payload" src="https://github.com/user-attachments/assets/97d57df2-11b7-4a24-af18-192dba8d98fb" />


## Result
Authentication bypass was achieved.

## Learning Outcome
- Understanding database vulnerabilities
- Importance of input validation

## Prevention
- Use prepared statements
- Input sanitization
- Use ORM frameworks

## MITRE ATT&CK Mapping
- SQL Injection → Exploitation (T1190)

⚠️ Tested only on safe/vulnerable lab websites.
