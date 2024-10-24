# 📶 What is a Network Packet Sniffer?

A network packet sniffer is a software tool or hardware device used to intercept, capture, and analyze network traffic passing through a communication channel. It works by monitoring data packets at a low level, often at the network or data link layer of the OSI model. This tool allows users to examine the contents of individual packets to diagnose issues, analyze performance, or detect potential security vulnerabilities.

When a packet sniffer is deployed, it places the network interface card (NIC) in promiscuous mode, allowing the NIC to capture all packets within the network segment, even those not addressed to it.

# 💻 Uses of a Network Packet Sniffer

- Network Diagnostics and Troubleshooting
- Performance Monitoring
- Security Auditing and Intrusion Detection
- Protocol Analysis
- Application Development and Testing
- Network Forensics

# 🔧 Network Packet Sniffer using Java and Jpcap
## 📖 Description
This project is a Network Packet Sniffer built using Java and the Jpcap library. A packet sniffer is a powerful tool that captures, monitors, and analyzes network traffic in real-time. It allows users to inspect the contents of individual packets for diagnostic, performance analysis, and security purposes.

By utilizing Jpcap, this tool enables deep insights into network communication, such as analyzing headers, filtering specific protocols, and identifying network anomalies. This project demonstrates both networking concepts and Java programming skills.

# 🚀 Features
- Real-time packet capturing from network interfaces.
- Protocol-based filtering (e.g., TCP, UDP, ICMP, ARP).
- Promiscuous mode support to capture all packets within a network segment.
- Packet analysis to view source/destination IP, ports, payload, and headers.
