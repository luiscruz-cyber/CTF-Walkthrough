# Capture the Flag Walkthrough – Root-Me Challenges

This project documents a multi-stage Capture the Flag (CTF) exercise completed on [Root-Me.org](https://www.root-me.org). Each challenge targeted a unique technical concept across network protocols, web exploitation, DNS misconfigurations, and client-side vulnerabilities.

---

## 🧠 Challenge Breakdown

### 1. 📧 POP – APOP (Network Protocol Analysis)
- Analyzed captured network traffic for APOP authentication
- Extracted and cracked MD5 hash using Hashcat
- Demonstrated replay attack principles and password retrieval

### 2. 🔌 TCP – Back to College (Socket Programming)
- Connected to a remote TCP service requiring a structured input
- Recreated protocol logic in Python
- Successfully interacted with the service to extract the flag

### 3. 🌐 DNS – Zone Transfer
- Identified a misconfigured DNS server via dig/nslookup
- Performed a zone transfer to obtain sensitive internal records
- Extracted the final flag from leaked DNS info

### 4. 🧩 JavaScript – Webpack (Client-side Mapping)
- Examined exposed Webpack source maps
- Reversed JavaScript logic using browser dev tools
- Found hidden functionality and extracted credentials

### 5. 💉 XSS – Server-Side
- Injected an iframe-based XSS payload
- Abused local file access via LFI-style input
- Read `flag.txt` directly from the server root

---

## 🔧 Tools & Techniques

- Wireshark  
- Hashcat  
- Python 3  
- dig / nslookup  
- Browser Dev Tools (Chrome/Firefox)  
- XSS payload crafting  
- Basic privilege escalation and info gathering  

---

## ✅ Outcome

Successfully completed all 5 challenges and documented:
- Steps taken  
- Tools used  
- Vulnerabilities exploited  
- Remediation ideas (where relevant)

---

> This CTF walkthrough demonstrates offensive security fundamentals and a systematic approach to solving multi-domain challenges.


