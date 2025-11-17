# CTI_Assignment_Smit_Parmar
# Diamond Model Threat Actor Analysis  
**Author:** Smit Parmar  


##  Task 3: Diamond Model Elements 


| Vertex         | Details |
|----------------|---------|
| **Adversary** | Individuals using the repository **“Subaat”** |
| **Infrastructure** | Host IPs used in activity: **5.189.157.215 (Germany)**, **115.186.136.237 (Pakistan)** |
| **Capability** | **QuasarRAT** delivered through malicious RTF files exploiting **CVE-2012-0158**; **Crimson Downloader** deployed using Excel macros |
| **Victim** | A **US-based government organization** targeted through **phishing emails** |


##  Task 5: Threat Actor Profile Summary 

In July 2017, researchers from Palo Alto Networks Unit 42 found a phishing attack aimed at a US government agency. The attackers sent 43 emails with subjects like “Invention” and “Invention Event.” Each email had a dangerous file attached. These files included two RTF documents and one Excel file. They were designed to trick the victim’s computer into running hidden code, turning on things like macros or using old software bugs. Once opened, the files installed malware tools called QuasarRAT and Crimson Downloader, which let the attacker take control of the device.

While investigating, the researchers found that the emails and malware were linked to servers in Germany and Pakistan. One domain, subaat.com, stood out because it hosted many types of malware. Records and online activity suggested the domain might be connected to someone living in Pakistan. Some parts of the attack looked similar to older operations like Transparent Tribe, but there wasn’t enough proof to say it was the same group.

**Overall, the case shows that phishing is still a big danger for government organizations. Attackers use simple tricks emails, fake documents, and old software bugs to get into systems. It also shows that their setup can be spread across different countries. For defenders, this is a reminder to watch for strange attachments and block known bad servers before they cause damage.


##  Task 6: Reflection 


1. How does the Diamond Model help?

The Diamond Model breaks down attacks into simple parts. It helps you see who is doing the attack, what tools they use, and who they are targeting. This makes it easier to understand and track bad guys.

2. What were the challenges?

It was sometimes hard to tell which servers and websites the attacker used and to know for sure who was behind the attack. Some clues matched other groups, so that got confusing.

3. How can it help stop attacks?

By knowing how attackers work and what tools or methods they use, defenders can keep watch for those threats, set up better blocks, and warn people who might get targeted next.


