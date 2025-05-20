## 🛡️ Networking Core Protocols

**Room:** [Networking Core Protocols — TryHackMe](https://tryhackme.com/room/networkingcoreprotocols)  
**Status:** ✅ Completed  
**Date:** *20 May 2025*  

### 🎯 Objective
This room focused on core TCP/IP protocols used in networking, including DNS, HTTP, FTP, SMTP, POP3, and IMAP. The goal was to understand how these protocols function behind the scenes and their roles in various network communications.

---

### 🗝️ Key Concepts  
- **DNS Resolution** — How domain names are mapped to IP addresses using A, AAAA, CNAME, and MX records  
- **WHOIS Protocol** — Querying domain registration information and ownership details  
- **HTTP Methods** — Core web commands (GET, POST, PUT, DELETE) and their functions  
- **FTP Operations** — File transfer mechanisms (RETR, STOR) and authentication flow  
- **Email Protocols** — SMTP for sending vs POP3/IMAP for receiving emails  
- **Protocol Ports** — Default TCP/UDP ports for services (DNS:53, HTTP:80, SMTP:25, etc.)  
- **Raw Protocol Interaction** — Using `telnet` to manually communicate with services  
- **Packet Analysis** — Inspecting protocol exchanges with tools like Wireshark  

---

### 🛠️ Tools Used
- `nslookup` — For DNS record queries
- `whois` — For looking up domain registration information
- `telnet` — For raw protocol interaction (HTTP, SMTP, POP3, IMAP)
- `ftp` client — For file transfers using FTP protocol

---

### ⚠️ Challenges Faced
- Understanding the different DNS record types and their purposes was initially confusing.
- Remembering all the various protocol commands and their syntax was challenging.
- The difference between POP3 and IMAP synchronization approaches required some research to fully grasp.

---

### 🧠 What I Learned
- How DNS resolution works behind the scenes when browsing the web
- The actual commands exchanged when sending emails via SMTP
- The difference between retrieving (POP3) and synchronizing (IMAP) emails
- How to interact directly with servers using raw protocol commands
- The importance of protocol analysis for troubleshooting and security

---

### 🌐 Real-World Application:
> Understanding these core protocols is fundamental for network troubleshooting, security analysis, and penetration testing. For example, knowing SMTP commands helps identify misconfigured mail servers that could be abused for spam, while DNS knowledge is crucial for investigating phishing domains or setting up proper network infrastructure.

---

### 💭 Reflections:
- **Interesting:** Seeing how much complexity is hidden behind simple actions like loading a webpage or sending an email.
- **Hardest part:** Remembering all the different port numbers and which protocol uses which transport layer.
- **Unforgettable takeaway:** That you can send an email using just telnet and proper SMTP commands!
