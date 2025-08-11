# Wireshark-Network-Traffic-Capture-Protocol-Analysis


## Objective
Capture live network packets in Kali Linux and analyze protocols using Wireshark.

## Tools
- Kali Linux
- Wireshark

## Steps
1. Installed Wireshark on Kali VM.
2. Captured packets on the active network interface.
3. Generated traffic by browsing websites and pinging servers.
4. Filtered packets for HTTP, DNS, TCP.
5. Saved the capture file as `.pcap`.

## Protocols Identified
- **DNS** – Resolved domain names (e.g., google.com → 142.250.x.x).
- **HTTP** – Website requests and responses.
- **ICMP** – Ping requests and replies.

## Deliverables
- Packet capture file: [`network_capture.pcap`](./network_capture.pcap)
- Screenshots: see `/screenshots` folder.
