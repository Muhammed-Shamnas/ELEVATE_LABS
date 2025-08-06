# 🔍 Elevate Labs Internship - Task 1: Network Port Scanning using Nmap

## 🎯 Objective

The goal of this task was to perform network reconnaissance on my local network using Nmap. The objective was to identify active devices, discover open ports, understand what services are running, and assess basic network exposure risks.

---

## 🛠️ Tools Used

- Nmap – A powerful open-source network scanner used for port scanning, host discovery, and service enumeration.
- Wireshark *(optional)* – Used for capturing and analyzing packets during the scanning process.
- Operating System – Kali Linux

---

## 🌐 My Network Configuration

- IP Range Scanned: 192.168.1.0/24
- Scanning Method: TCP SYN Scan
- Command Used:

```bash
sudo nmap -sS -oN scan_results.txt 192.168.1.0/24
