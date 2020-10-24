# Common techniques used in human-operated ransomware attacks 

| Tactic               | ID        | Technique                                                                                         |
|----------------------|-----------|---------------------------------------------------------------------------------------------------|
| Initial Access       | T1190     | Exploit Public-Facing Application                                                                 |
| Initial Access       | T1133     | External Remote Services                                                                          |
| Initial Access       | T1566.001 | Phishing: Spearphishing Attachment                                                                |
| Initial Access       | T1566.002 | Phishing: Spearphishing Link                                                                      |
| Execution            | T1559     | Inter-Process Communication                                                                       |
| Execution            | T1055     | Process Injection                                                                                 |
| Execution            | T1059     | Command and Scripting Interpreter                                                                 |
| Execution            | T1204.002 | User Execution: Malicious File                                                                    |
| Execution            | T1204.001 | User Execution: Malicious Link                                                                    |
| Persistence          | T1543.003 | Create or Modify System Process: Windows Service                                                  |
| Persistence          | T1547.001 | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder                             |
| Privilege Escalation | T1548.002 | Abuse Elevation Control Mechanism: Bypass User Access Control                                     |
| Privilege Escalation | T1068     | Exploitation for Privilege Escalation                                                             |
| Privilege Escalation | T1134.005 | Access Token Manipulation: SID-History Injection                                                  |
| Defence Evasion      | T1027     | Obfuscated Files or Information                                                                   |
| Credential Access    | T1558.003 | Steal or Forge Kerberos Tickets: Kerberoasting                                                    |
| Credential Access    | T1552.006 | Unsecured Credentials: Group Policy Preferences                                                   |
| Credential Access    | T1552.001 | Unsecured Credentials: Credentials In Files                                                       |
| Credential Access    | T1003     | OS Credential Dumping                                                                             |
| Discovery            | T1087.002 | Account Discovery: Domain Account                                                                 |
| Lateral Movement     | T1210     | Exploitation of Remote Services                                                                   |
| Lateral Movement     | T1021.002 | Remote Services: SMB/Windows Admin Shares                                                         |
| Lateral Movement     | T1021.001 | Remote Services: Remote Desktop Protocol                                                          |
| Exfiltration         | T1048.003 | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol  |
| Impact               | T1486     | Data Encrypted for Impact                                                                         |
