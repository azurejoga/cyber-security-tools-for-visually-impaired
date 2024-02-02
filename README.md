# cyber-security-tools-for-visually-impaired
accessible cyber security tools for the visually impaired

  
# introduction!
I felt the lack of accessible tools for the visually impaired/blind in the area of ​​cyber security.

So, I created this repository to help others who are starting out in the field or are going to college or starting out on their own.

I leave below several tools for different purposes in the area of ​​cyber security! Hope you like it!

## Resources.


## Threat intelligence platforms

## What is a threat intelligence platform, TIP.

A Threat Intelligence Platform (TIP) is a technology solution that collects, aggregates, and organizes threat intelligence data from multiple sources and formats. A TIP provides security teams with information about known malware and other threats, enabling efficient and accurate threat identification, investigation, and response. It allows threat analysts to spend their time analyzing data and investigating potential security threats, rather than spending their time collecting and managing data. Additionally, a TIP allows security and threat intelligence teams to easily share threat intelligence data with other stakeholders and security systems. A TIP can be deployed as software as a service (SaaS) or as an on-premises solution.


* [AlienVault - Open Threat Exchange, OTX](https://otx.alienvault.com/)

On this platform, you can check the latest threats, pulses from other users, receive email alerts, check your agents/end points, Windows or Linux. PS: To scan your machines for threats, you have to install the client alien agent first before doing any Scans.
Additionally, you can use the OTX API to automate tasks.
The platform is very accessible, I have nothing to complain about and it works well with my screen reader.
You need to subscribe to a pulse before you can start receiving email notifications.
Create an account, it's easy and simple!
You can also submit threat samples, see the documentation for that.

* [Open CTI, opensource threat intelligence platform](https://github.com/OpenCTI-Platform/opencti?tab=readme-ov-file)
All guides on how to install, configure and much more are on github.
I had no problems using the screen reader on Windows.

* [Pulsedive, Threat intelligence](https://pulsedive.com/)
Simple, accessible threat intelligence for screen readers. Create an account for better access.

* [0 Fox, cyber threat intelligence platform](https://www.zerofox.com/daily-intelligence-brief/)
Subscribe to 0fox's daily threat report and you will receive all the information by email

* [IBM X-Force, threat intelligence platform](https://exchange.xforce.ibmcloud.com/)
You can join as a guest or create an IBM account to share your own resources or threats.

## SIEM platforms.

## What is a SIEM

The management of security information and events,SIEM for short, is a solution that helps organizations detect, analyze and respond to security threats before they harm business operations.
SIEM, pronounced “yes,” combines security information management (SIM) and security event management (SEM) into one security management system. SIEM technology collects event log data from multiple sources, identifies activities that deviate from the norm with real-time analysis, and takes appropriate action.
In short, SIEM gives organizations visibility into activity within their network so they can quickly respond to potential  cyberattacks  and meet compliance requirements.

## Free SIEM tools

* [Wazuh](https://documentation.wazuh.com/current/quickstart.html)
Wazuh is an open source SIEM that is installable through a Linux distribution and accessed through the browser, easy, scalable, and smooth to use.

If you are using kali-linux to install Wazuh, use the -i parameter to ignore your distribution, operating system and hardware requirements.

* [OSSEC, SIEM opensource](https://www.ossec.net/ossec-downloads/)
Easy to install, it has 3 versions, the first is free, the second is also free, but requires you to create an account, while the third is paid and requires payment to access.
My NVDA screen reader had no problems managing both the agent and the server.


## OSINT, open source intelligence.

## what is OSINT

Open source intelligence (OSINT) is defined as intelligence produced by collecting, evaluating, and analyzing publicly available information for the purpose of answering a specific intelligence question.
Information versus Intelligence
It is important to note that information does not equal intelligence. Without making sense of the data we collect, open source findings are considered raw data. Only when this information is observed from a critical thinking mindset and analyzed does it become intelligence.
For example, conducting OSINT is not simply saving someone's Facebook friends list. It is about finding meaningful information that is applicable to the intelligence question and being able to provide actionable information in support of an investigation. Another way to look at this is to answer “why is this data important” and provide meaningful information about the data collected.


## free OSINT tools.

* [OSINT, framework, A collection of various OSINT tools and techniques](https://osintframework.com/)
Using the screen reader in this tool is simple, by pressing space on a tool you can see the list of tools that are available in that category. Example, I want a tool to collect usernames, so I go to where it says, usernames, and click. after clicking,I press H to go to the notes and go up with the arrow key until I hear the following thing.
(T) - Indicates a link to a tool that must be installed and run locally
So now, I know I'm close to the username tools. I keep going up the up arrow and hear the name of the tools and click on one to take me to its respective website.

* [Spiderfoot, powerful and affordable OSINT tool with more than 30 modules](https://github.com/smicallef/spiderfoot)
Installing the spiderfoot is very simple.
1. in kali-linux, type sudo apt install spiderfoot
2. Agree with Y to install, and wait for the installation to finish.
3. When finished, enter,
spiderfoot -l ip: example, 192.168.0.112 and port, example, 10333
So the actual command would look like this
spiderfoot -l 172.16.12.1 10333

* [Cyber ​​security RSS feeds](https://www.cshub.com/rss-feeds)


* [top 100 cyber security RSS feeds](https://rss.feedspot.com/cyber_security_rss_feeds/)


# Operating systems for cyber security professionals

* [kali-linux](https://www.kali.org/get-kali/)
Installing kali-linux is easy, for those familiar with virtualization, it is simple.
Additionally, when starting the distribution, press s and enter to activate the accessibility installation

## Network Tools 
* [n-map](https://nmap.org/)
Nmap, or Network Mapper, stands as a pivotal tool in the realm of network security and system exploration. Developed as open-source software, Nmap is employed to map and assess the topology of networks, identifying hosts, services, and connected devices. Its primary purpose is to provide a comprehensive and detailed view of network infrastructure, enabling system administrators, security professionals, and network experts to understand and fortify the security of their digital environments.
By offering advanced features such as port scanning, remote operating system detection, identification of running services, and support for custom scripts, Nmap distinguishes itself as a versatile tool for the proactive detection of vulnerabilities and potential threats. Its ethical and legal application is paramount, underscoring the importance of obtaining proper permission before conducting any form of scanning on networks and systems not owned by the user.

## Tools to crack passwords
* [John the Ripper password cracker](https://www.openwall.com/john/)


John the Ripper is an Open Source password security auditing and password recovery tool available for many operating systems. John the Ripper jumbo supports hundreds of hash and cipher types, including for: user passwords of Unix flavors (Linux, *BSD, Solaris, AIX, QNX, etc.), macOS, Windows, "web apps" (e.g., WordPress), groupware (e.g., Notes/Domino), and database servers (SQL, LDAP, etc.); network traffic captures (Windows network authentication, WiFi WPA-PSK, etc.); encrypted private keys (SSH, GnuPG, cryptocurrency wallets, etc.), filesystems and disks (macOS .dmg files and "sparse bundles", Windows BitLocker, etc.), archives (ZIP, RAR, 7z), and document files (PDF, Microsoft Office's, etc.) These are just some of the examples - there are many more.


## Tools for encryption


## Bluetooth tools  


## Forence tools, forensic analysis and investigation
* [30+ forensic investigation tools: mx-toolbox](https://mxtoolbox.com/NetworkTools.aspx?tab=)


A complete website with more than 30 forensic tools for investigation, analysis of email headers, spf records, dns and much more!


* [cain & abel: password: danieldonda.com](https://drive.google.com/file/d/1qswyXaC0ctEAdGVJ2Z93QF6m_AH5k9kz/view?usp=sharing)


Cain & Abel is a password recovery tool for Microsoft operating systems. Enables easy recovery of various types of passwords by detecting the network, cracking encrypted passwords using Dictionary, Brute-Force and Cryptanalysis attacks, recording VoIP conversations, decoding encrypted passwords, recovering wireless network keys, revealing password boxes, discovering passwords in caching and analyzing routing protocols.
Cain & Abel allows you to apply APR (Arp Poison Routing) very easily
Cain & Abel was developed in the hope that it will be useful for network administrators, teachers, security consultants/professionals, forensic staff, security software vendors, professional penetration testers, and everyone who plans to use it for ethical reasons.


* [Google admin toolbox, a great toolbox for forensic analysis](https://toolbox.googleapps.com/apps/main/)


Yes, google has an official tool for forensic investigation/analysis!!
Although on the website it is written that it is for debugging, but it can be used as forensic!
It has similar functions to mx-toolbox, but with some additional things!


## malware samples
there are a number of malware sample sites out there, but the most common ones are as follows.
* [vx underground](https://vx-underground.org/)
* [MalwareBazaar:](https://bazaar.abuse.ch/)
* [the zoo:](https://thezoo.morirt.com/)