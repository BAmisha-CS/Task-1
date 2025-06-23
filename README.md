# Task-1
Nmap TCP SYN scan of a local VMware network (192.168.234.0/24) to identify live hosts and open/filtered ports.
Nmap TCP SYN Scan Project

This project demonstrates a basic TCP SYN scan using **Nmap** on a local virtual network (VMware).

🔧 Tools Used
- **Nmap 7.94SVN** (installed from [https://nmap.org](https://nmap.org))
- **Linux terminal** in a **VMware virtual machine**
- Optional: **Wireshark** for packet inspection (not shown in this repo)

📍 Target
- Local subnet: `192.168.234.0/24`
- Goal: Discover live hosts and identify any open or filtered TCP ports.

📤 Command Used

```bash
nmap -sS 192.168.234.0/24
192.168.234.2
- Port 53/tcp: filtered (possible DNS service)
