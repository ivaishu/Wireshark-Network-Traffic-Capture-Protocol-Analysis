# Wireshark-Network-Traffic-Capture-Protocol-Analysis


## 📖 Project Overview
This project demonstrates hands-on **packet capture** and **protocol analysis** using [Wireshark](https://www.wireshark.org/) on Windows.  
The goal was to capture live network traffic, identify different protocols, and analyze their behavior.

---

## 🛠 Tools & Environment
- **Operating System**: Windows 10/11
- **Software**: Wireshark (latest version)
- **Additional Component**: Npcap (installed with Wireshark)
- **Command Line Tools**: `ping`, `nslookup`

---

## 🎯 Objectives
1. Capture live network packets using Wireshark.
2. Identify at least **3 different protocols** in the captured data.
3. Export the capture as a `.pcap` file.
4. Summarize key findings and insights.

---

## 📌 Steps Performed
1. **Installed Wireshark** with Npcap for packet capturing.
2. **Selected active network interface** (Wi-Fi) and started capture.
3. **Generated traffic** by:
   - Browsing multiple websites.
   - Running `ping google.com` in Command Prompt.
   - Using `nslookup example.com` for DNS queries.
4. **Stopped the capture** after ~2 minutes.
5. **Filtered traffic** by protocol:
   - `http` → View HTTP requests and responses.
   - `dns` → Inspect DNS queries and replies.
   - `tcp` → Observe TCP handshakes and connections.
6. **Saved capture** as `capture.pcap`.
7. **Took screenshots** of filtered protocol views.
8. **Prepared analysis report** summarizing findings.

---

## 📊 Protocols Identified
| Protocol | Description | Example Observation |
|----------|-------------|---------------------|
| **HTTP** | Transfers web page data between client and server. | Observed `GET` requests to multiple domains. |
| **DNS**  | Resolves domain names to IP addresses. | DNS query for `example.com` returning IPv4 address. |
| **TCP**  | Reliable transport protocol for data transfer. | 3-way handshake between local and remote hosts. |

---

## 📂 Project Structure

📁 wireshark-packet-analysis-windows
├── 📄 README.md
├── 📂 captures
│ └── capture.pcap
├── 📂 screenshots
│ ├── http-filter.png
│ ├── dns-filter.png
│ └── tcp-filter.png
└── 📄 analysis-report.pdf

---

## 📸 Screenshots
### HTTP Traffic
![HTTP Filter Screenshot](screenshots/http-filter.png)

### DNS Traffic
![DNS Filter Screenshot](screenshots/dns-filter.png)

### TCP Traffic
![TCP Filter Screenshot](screenshots/tcp-filter.png)

---

## 📑 Key Learnings
- How to **capture and filter** specific network protocols in Wireshark.
- Recognized differences between **TCP**, **UDP**, and **application-layer protocols** like HTTP/DNS.
- Understood packet structure and how it can be used in **SOC investigations** or **network troubleshooting**.

---

## 📜 References
- [Wireshark Official Documentation](https://www.wireshark.org/docs/)
- [Packet Life Wireshark Cheatsheet](https://packetlife.net/media/library/13/Wireshark_Display_Filters.pdf)

---
