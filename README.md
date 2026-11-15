# Week2-Networkwalks-intership-footprint-and-Network-scanning-
🔐 Cybersecurity Lab: Information Gathering and Network Discovery

📌 Project Overview

This project documents my hands-on cybersecurity lab exercises focused on information gathering, reconnaissance, DNS enumeration, web technology fingerprinting, and internal network discovery.

I used Kali Linux reconnaissance tools and Zenmap (Nmap GUI) on Windows to investigate an authorized target and discover devices within a local lab network.

The objective was to understand how cybersecurity professionals gather information, identify exposed technologies, analyze network services, and map network infrastructure during the early stages of a penetration test.

🎯 Project Objectives

* Understand information gathering and reconnaissance techniques.
* Retrieve domain registration and DNS information.
* Identify website technologies and CMS platforms.
* Analyze HTTP response headers.
* Detect Web Application Firewall technologies.
* Enumerate DNS records.
* Discover active hosts on a local network.
* Identify IP and MAC addresses.
* Generate a visual network topology.

🛠️ Tools and Technologies

Tool	Purpose
Kali Linux	Security testing environment
WHOIS	Domain registration information
WhatWeb	Website technology fingerprinting
Nslookup	DNS-to-IP resolution
cURL	HTTP response header analysis
Wafw00f	Web Application Firewall detection
DNSRecon	DNS enumeration
Zenmap	Graphical network scanning
Nmap	Network discovery and host scanning
Windows	Network discovery environment

🔍 Practical Tasks Performed

1. WHOIS Enumeration

* Retrieved domain registration information.
* Identified name servers.
* Examined domain ownership and registration details.

2. Website Technology Fingerprinting – WhatWeb

* Identified website technologies and CMS platforms.
* Detected WordPress.
* Examined identifiable plugin versions and server technologies.

3. DNS Lookup – Nslookup

* Resolved domain names into IP addresses.
* Examined DNS query results.

4. HTTP Header Analysis – cURL

* Used curl -I to inspect HTTP response headers.
* Examined server response information.
* Investigated potentially exposed endpoint information.

5. WAF Detection – Wafw00f

* Checked whether the target website was protected by a Web Application Firewall.
* Identified ModSecurity as the detected WAF technology.

6. DNS Enumeration – DNSRecon

* Enumerated available DNS records.
* Investigated domain DNS configurations.
* Examined DNS infrastructure.

7. Internal Network Discovery – Zenmap

* Installed and used Zenmap on Windows.
* Scanned an authorized local network.
* Identified active devices and IP addresses.
* Examined MAC addresses.
* Generated a visual network topology.

💻 Commands Practiced

# WHOIS lookup
whois example.com
# Website technology fingerprinting
whatweb example.com
# DNS lookup
nslookup example.com
# Inspect HTTP response headers
curl -I https://example.com
# Detect Web Application Firewall
wafw00f https://example.com
# DNS enumeration
dnsrecon -d example.com

Replace example.com with a domain you own or are explicitly authorized to assess.

🧠 Skills Developed

* Information Gathering (OSINT)
* Passive and Active Reconnaissance
* DNS Enumeration
* Web Technology Fingerprinting
* HTTP Header Analysis
* WAF Detection
* Network Scanning
* IP and MAC Address Identification
* Network Topology Mapping
* Kali Linux Command-Line Skills
* Zenmap and Nmap Usage





Suggested folder structure:

cybersecurity-reconnaissance-lab/
│
├── README.md
│
├── screenshots/
│   ├── whois-results.png
│   ├── whatweb-results.png
│   ├── nslookup-results.png
│   ├── curl-headers.png
│   ├── waf-detection.png
│   ├── dnsrecon-results.png
│   └── zenmap-network-topology.png
│
└── notes/
    └── lab-findings.md

📚 Key Learning Outcomes

Through this practical lab, I gained experience using reconnaissance tools to collect domain information, identify website technologies, inspect HTTP responses, detect WAF technologies, and investigate DNS records.

I also gained practical experience using Zenmap to discover active devices, examine network addresses, and visualize local network infrastructure.

This project improved my understanding of the information-gathering phase of ethical hacking and penetration testing.

⚖️ Disclaimer

This project was conducted for educational purposes in an authorized cybersecurity learning environment.

All scanning and enumeration activities should only be performed against systems, domains, and networks that you own or have explicit permission to assess.

👩‍💻 Author

Cybersecurity Student | Ethical Hacking & Penetration Testing Learner

Focus Areas: Cybersecurity, Network Security, Ethical Hacking, Reconnaissance, and Penetration Testing.
