# Common techniques used in human-operated ransomware attacks 

| Tactic               | Technique                                                                                                    |
|----------------------|--------------------------------------------------------------------------------------------------------------|
| Initial Access       | Exploit Public-Facing Application (T1190)                                                                    |
| Initial Access       | External Remote Services (T1133)                                                                             |
| Initial Access       | Phishing: Spearphishing Attachment (T1566.001)                                                               |
| Initial Access       | Phishing: Spearphishing Link (T1566.002)                                                                     |
| Execution            | Inter-Process Communication (T1559)                                                                          |
| Execution            | Process Injection (T1055)                                                                                    |
| Execution            | Command and Scripting Interpreter (T1059)                                                                    |
| Execution            | User Execution: Malicious File (T1204.002)                                                                   |
| Execution            | User Execution: Malicious Link (T1204.001)                                                                   |
| Persistence          | Create or Modify System Process: Windows Service (T1543.003)                                                 |
| Persistence          | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder (T1547.001)                            |
| Privilege Escalation | Abuse Elevation Control Mechanism: Bypass User Access Control (T1548.002)                                    |
| Privilege Escalation | Exploitation for Privilege Escalation (T1068)                                                                |
| Privilege Escalation | Access Token Manipulation: SID-History Injection (T1134.005)                                                 |
| Defence Evasion      | Obfuscated Files or Information (T1027)                                                                      |
| Credential Access    | Steal or Forge Kerberos Tickets: Kerberoasting (T1558.003)                                                   |
| Credential Access    | Unsecured Credentials: Group Policy Preferences (T1552.006)                                                  |
| Credential Access    | Unsecured Credentials: Credentials In Files (T1552.001)                                                      |
| Credential Access    | OS Credential Dumping (T1003)                                                                                |
| Discovery            | Account Discovery: Domain Account (T1087.002)                                                                |
| Lateral Movement     | Exploitation of Remote Services (T1210)                                                                      |
| Lateral Movement     | Remote Services: SMB/Windows Admin Shares (T1021.002)                                                        |
| Lateral Movement     | Remote Services: Remote Desktop Protocol (T1021.001)                                                         |
| Exfiltration         | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol (T1048.003) |
| Impact               | Data Encrypted for Impact (T1486)                                                                            |
