🧭 12-Month Cybersecurity Roadmap
Goal: Master the red team basics, build real tools, and land your first bug bounty or ethical hacking gig.
Profile: 1st-year BSIT student with C++/C# background, Python beginner, uses Kali Linux + LM Studio with Phi-2.

🔹 Phase 1: Core Foundations (Weeks 1–8)
🎯 Goal: Understand networking, OSI layers, essential tools, and write beginner recon scripts in Python.

✅ What You'll Master:
Networking: IP, TCP/UDP, DNS, MAC, Subnetting, Wireshark filters

Ports/Protocols: Common ports (21, 22, 80, 443, etc.) & service banners

Tools: nmap, wireshark, netcat, dig, whois

Python: Create CLI recon tools (port scanner, banner grabber)

⚙️ Tools Setup:
Kali Linux (✓)

Python 3, subprocess, socket, argparse

VS Code / LM Studio + Phi-2 for offline support

📅 Weekly Breakdown:
Week	Focus	Output
1	Learn IP, TCP/UDP, DNS, MAC	Wireshark practice: ip.addr, dns, http, filters
2	Understand ports & Nmap	Use -sS, -sV, -A, --script; scan localhost
3	Python Port Scanner	CLI script: scan port range 1–100, show status
4	Python Nmap Automation	Script runs Nmap, parses -oG or XML output
5	Netcat, dig, whois	Try simple reverse shell, DNS lookups
6	Bash intro + scripting	Basic loops for automation (e.g., mass pings)
7	Build mini recon toolkit	Combine ping sweep + port scanner
8	Review + TryHackMe “Intro to Cyber” room	Recap and document your toolkit

🔹 Phase 2: Red Team Foundations (Weeks 9–24)
🎯 Goal: Learn how attackers gather info and break in — then replicate legally in labs.

✅ Skills Gained:
Footprinting, enumeration, basic exploitation

Tools: Hydra, Gobuster, Nikto, searchsploit, msfconsole

Python scripting for automation

🔧 Scripting Targets:
Auto-recon (Nmap + Gobuster combo)

Ping sweeper & live-host enumerator

XML/JSON report parser for Nmap

🧪 Lab-Based Learning:
Enroll in TryHackMe Red Team Path

Focus rooms: “Simple CTF”, “Ignite”, “Blue”, “Brute It”, “Internal”

Document findings like a pentester

📅 Activities by Month:
Month	Focus	Key Outputs
3	Enumeration + Password Attacks	Hydra & Gobuster usage, bruteforce HTTP login
4	CVEs + Exploits	Searchsploit & msfconsole, exploit local VM
5	Automated Recon	Write tool to scan IP block, extract info
6	Practice + Notes	Custom bash/python script + lab reports

🔹 Phase 3: Real-World Pentesting & Bug Bounties (Weeks 25–52)
🎯 Goal: Start real-world hacking, learn web app testing, and submit your first bug.

✅ You’ll Learn:
Bug types: XSS, IDOR, SSRF, Subdomain Takeover

Tools: Burp Suite, Google Dorking, OSINT, recon-ng

Practice reporting format + ethics

📚 Resources:
Hacker101 CTF

PortSwigger Web Security Academy

Bugcrowd University

OWASP Testing Guide

🧰 Script Goals:
Subdomain Finder: Python + requests + wordlists

Form Auto-Submitter: Simulate login bypass

Directory Brute-Forcer: Build your own dirbuster clone

🗂 Practice Plan:
Month	Focus	Key Milestone
7	Learn web bugs (XSS, IDOR)	Build test lab using DVWA or Juice Shop
8	Burp Suite mastery	Intercept, modify, and test requests
9	Bug bounty tryouts	Try HackerOne or Bugcrowd reports
10–12	Build Portfolio + Hunt Bugs	Log 3+ bugs or findings (even duplicates), publish 1 tool on GitHub

📘 Weekly Sample Plan (Phase 1, Week 1)
Day	Task
Mon	Watch “Bits & Bytes of Networking” + take notes on IP/DNS
Tue	Run 3 Nmap scans (-sS, -sV, -A) — document findings
Wed	Install python3-nmap or use subprocess in Python
Thu	Write port scanner script (1–100) using socket
Fri	Use Wireshark to capture DNS/HTTP/TCP from browser
Weekend	Review + Ask Phi-2/me to optimize your script

🧠 Pro Tips:
📓 Keep a daily hacking journal (problems, solutions, insights)

💻 Create a private GitHub repo for recon tools and notes

🧪 Use VirtualBox or Proxmox to safely host vulnerable VMs

🔁 Practice weekly CTFs or challenges to stay sharp