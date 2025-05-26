# cb-tasks
cyber security taks 1
# 🔍 Network Port Scan and Security Analysis

This project demonstrates a basic **TCP SYN scan** using [Nmap](https://nmap.org/), along with a follow-up **security analysis** based on the results. It helps identify active hosts in a local network, their open ports, and potential vulnerabilities.

---

## 🛠️ Tools Used

- **Nmap** (v7.97) - for network scanning
- **Wireshark** (optional) - for packet capture and deep traffic analysis
- **XML** - to store and parse Nmap results
- **Manual Research** - for understanding services and risks

---

## 📋 Steps Performed

1. Installed Nmap from [official site](https://nmap.org/download.html).
2. Identified local IP range: `192.168.1.0/24`.
3. Performed a TCP SYN scan:
   ```bash
   nmap -sS 192.168.1.0/24

