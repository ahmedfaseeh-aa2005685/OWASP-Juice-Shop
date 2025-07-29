# 🔒 Web Application Penetration Testing Tools and Methodology

A university-level cybersecurity project conducted at Qatar University that explores core web application penetration testing methodologies using industry-standard tools such as **Burp Suite**, **Nmap**, and **Metasploit**. The project features a hands-on simulation against the vulnerable **OWASP Juice Shop** web application to demonstrate real-world exploitation techniques.

## 👨‍💻 Team Members
- Haris Khan  
- Ifran Rafi  
- Hunzalah Hassan Bhatti  
- Ahmed Faseeh Akram  

## 📌 Project Objectives
- Understand and apply the web penetration testing methodology: Reconnaissance, Scanning, Exploitation, Privilege Escalation, and Post-Exploitation.
- Gain hands-on experience using professional tools to identify and exploit common web vulnerabilities.
- Simulate ethical hacking scenarios and document the results for academic and educational purposes.

## 🧰 Tools & Technologies Used
- **Burp Suite** – Intercept and manipulate HTTP requests, automate attacks using Intruder and Repeater.
- **Nmap** – Network mapping, port scanning, service detection, OS fingerprinting.
- **Metasploit Framework** – Module-based exploitation and post-exploitation control.
- **OWASP Juice Shop** – Intentionally vulnerable web application.
- **Hashcat & jwt.io** – Token decoding and password cracking for identity exploitation.
- **VMware + Kali Linux** – Virtualized pentesting lab environment.

## 🛠️ Key Exploits Demonstrated
- **SQL Injection** to bypass login and extract database schema.
- **Authentication Bypass** using manipulated cookie tokens.
- **Sensitive Data Exposure** through JWT decoding and password hash cracking.
- **Access Control Manipulation** to alter admin credentials and access user data.

## 🧪 Lab Setup Instructions
1. Install [VMware Workstation Player](https://www.vmware.com/products/workstation-player.html)
2. Download [Kali Linux VM](https://www.kali.org/get-kali/#kali-virtual-machines)
3. Clone Juice Shop:
   ```bash
   git clone https://github.com/juice-shop/juice-shop.git
   cd juice-shop
   npm install
   npm start
