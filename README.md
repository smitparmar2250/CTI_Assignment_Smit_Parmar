# CTI_Assignment_Smit_Parmar
# Diamond Model Threat Actor Analysis  
**Author:** Smit Parmar  


## 📌 Task 3: Diamond Model Elements 


| Vertex         | Details |
|----------------|---------|
| **Adversary** | Individuals using the repository **“Subaat”** |
| **Infrastructure** | Host IPs used in activity: **5.189.157.215 (Germany)**, **115.186.136.237 (Pakistan)** |
| **Capability** | **QuasarRAT** delivered through malicious RTF files exploiting **CVE-2012-0158**; **Crimson Downloader** deployed using Excel macros |
| **Victim** | A **US-based government organization** targeted through **phishing emails** |


## 📌 Task 5: Threat Actor Profile Summary 

In July 2017, cybersecurity researchers at Palo Alto Networks Unit 42 discovered a focused phishing campaign targeting a US government agency. The attackers sent 43 emails with subjects like “Invention” and “Invention Event” each including malicious attachments designed to exploit software vulnerabilities on victims’ computers. These attachments two specially crafted RTF files and an Excel spreadsheet used tactics like obfuscation and hidden macros to install remote access tools known as QuasarRAT and Crimson Downloader. Investigation revealed that the email campaign was connected to infrastructure spread across Germany and Pakistan, including suspicious IP addresses and a domain called subaat.com. The subaat domain hosted a large number of malware varieties, and its ownership tied back, through forum activity and registration records, to an individual possibly operating from Pakistan. Researchers noted similarities between these attacks and older campaigns such as Operation Transparent Tribe, but there wasn’t enough evidence to determine if the same group was responsible. Overall, the case highlights the persistent risk of phishing against public sector targets and how attackers carefully combine social engineering, document exploitation, and international infrastructure to reach their aims. For defenders, this shows the importance of monitoring for unexpected attachments and proactively blocking known bad infrastructure.
---

## 📌 Task 6: Reflection 


1. How does the Diamond Model help?

The Diamond Model breaks down attacks into simple parts. It helps you see who is doing the attack, what tools they use, and who they are targeting. This makes it easier to understand and track bad guys.

2. What were the challenges?

It was sometimes hard to tell which servers and websites the attacker used and to know for sure who was behind the attack. Some clues matched other groups, so that got confusing.

3. How can it help stop attacks?

By knowing how attackers work and what tools or methods they use, defenders can keep watch for those threats, set up better blocks, and warn people who might get targeted next.


