# 📡 Network Traffic Analysis Using Wireshark: 

## 📖 Introduction:
Network traffic analysis is an essential skill in cybersecurity.  
This task involves capturing live network packets using Wireshark and analyzing different protocols involved in communication.


## 🎯 Objective:
- Capture live network packets.
- Identify commonly used protocols.
- Analyze packet-level details.
- Export captured traffic in `.pcap` format.


## 🛠 Tools & Environment:
- **Wireshark**
- **Windows Operating System**
- Web Browser (for HTTP traffic)
- Command Prompt (`ping` command for ICMP traffic)


## 🔬 Methodology:
1. Installed Wireshark with Npcap driver.
2. Selected the active Wi-Fi interface.
3. Started live packet capturing.
4. Generated traffic by:
   - Browsing websites.
   - Executing `ping google.com`.
5. Applied display filters such as:
   - `tcp`
   - `dns`
   - `http`
   - `icmp`
6. Stopped capture and saved the file as `Packet_capture.pcap`.


## 📊 Protocols Identified & Analysis:

### 🔹 DNS (Domain Name System)
- Resolves domain names into IP addresses.
- Observed DNS query and response packets.
- Uses UDP (Port 53).

### 🔹 TCP (Transmission Control Protocol):
- Reliable and connection-oriented protocol.
- Observed 3-way handshake (SYN, SYN-ACK, ACK).
- Ensures proper data delivery.

### 🔹 HTTP (HyperText Transfer Protocol):
- Used for web communication.
- Observed request and response packets.
- Operates over TCP (Port 80).

### 🔹 ICMP (Internet Control Message Protocol):
- Used for network diagnostics.
- Observed Echo Request and Echo Reply packets during ping.


## 🔍 Packet Details Observed:
- Source and Destination IP Address  
- Source and Destination Port  
- Protocol Type  
- Packet Length  
- Sequence & Acknowledgment Numbers (TCP)  


## ✅ Conclusion
This task provided practical exposure to real-time packet capturing and protocol analysis.  
Using Wireshark, we analyzed DNS, TCP, HTTP, and ICMP traffic, improving understanding of TCP/IP communication and basic network troubleshooting techniques.

## Author:
** Himanshu vats **
