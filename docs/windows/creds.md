---
layout: default
title: Credential Theft Attacks
---

## Credential Theft Attacks  
Adversaries may attempt to access credential material stored in the process memory of the Local Security Authority Subsystem Service (LSASS). After a user logs on, the system generates and stores a variety of credential materials in LSASS process memory. These credential materials can be harvested by an administrative user or SYSTEM and used to conduct Lateral Movement using Use Alternate Authentication Material.
  

### Section Breakdown
  
- [In-Memory Mimikatz via Powershell](http://127.0.0.1:4000/windows/T1003.001)  T1003.001
- [Dumping Lsass via SharpDump]() 
- [PowerSploit In-Memory Minidump Attempt]()  
