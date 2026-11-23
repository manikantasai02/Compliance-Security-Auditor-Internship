# Compliance-Security-Auditor-Internship
# Network Traffic Analysis – Hands-On Cybersecurity Lab

## 📌 Project Overview

This project focuses on understanding and analyzing network traffic using **Wireshark**, a network protocol analyzer. The main goal is to gain practical knowledge of how data travels across a network, understand communication protocols, and identify potentially suspicious network activities.

Through this hands-on learning activity, I explore packet inspection, IP address analysis, port identification, protocol analysis, and basic network security monitoring techniques.

## 🎯 Objectives

- Understand how network communication works.
- Learn packet capture and network traffic analysis.
- Identify source and destination IP addresses.
- Analyze commonly used network protocols.
- Understand TCP, UDP, DNS, HTTP, and HTTPS traffic.
- Identify unusual or potentially suspicious network behaviour.
- Develop basic network monitoring and troubleshooting skills.

## 🛠️ Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Wireshark | Network packet capture and analysis |
| TCP/IP | Understanding network communication |
| DNS | Domain name resolution analysis |
| HTTP/HTTPS | Web communication analysis |
| Windows / Linux | Lab environment |

## 📚 Topics Covered

### 1. Network Traffic Monitoring
- Introduction to network traffic.
- Packet capture and inspection.
- Understanding packet details.

### 2. IP Address Analysis
- Source IP address.
- Destination IP address.
- Private and public IP addresses.

### 3. Protocol Analysis
- TCP – Transmission Control Protocol
- UDP – User Datagram Protocol
- DNS – Domain Name System
- HTTP – Hypertext Transfer Protocol
- HTTPS – Secure Hypertext Transfer Protocol

### 4. Wireshark Display Filters

Some useful filters explored during the lab:

```text
ip
tcp
udp
dns
http
tls
icmp
```

Additional filters:

```text
tcp.port == 80
tcp.port == 443
dns.qry.name
ip.addr == 192.168.1.1
```

### 5. Suspicious Traffic Identification

The lab introduces indicators that may require further investigation:

- Repeated connection attempts.
- Unexpected external connections.
- Unusual DNS requests.
- Unusual data transfer patterns.
- Unexpected communication with unknown hosts.

These indicators are not proof of an attack and should be investigated in context.

## 🔬 Practical Activities

1. Set up Wireshark in the lab environment.
2. Capture authorized network traffic.
3. Apply display filters to identify specific protocols.
4. Examine packet headers and communication details.
5. Identify source and destination addresses.
6. Observe network communication patterns.
7. Document findings and potential security concerns.

## 📂 Repository Structure

```text
Network-Traffic-Analysis/
│
├── README.md
│
├── Report/
│   └── Network_Traffic_Analysis_Lab_Report.docx
│
├── Screenshots/
│   └── (Add Wireshark screenshots here)
│
└── PCAP-Files/
    └── (Add authorized sample captures here)
```

## 🎓 Learning Outcomes

By completing this activity, I aim to develop practical skills in:

- Network packet inspection.
- Protocol identification and analysis.
- IP address and port analysis.
- Wireshark usage.
- Network monitoring and troubleshooting.
- Recognizing potentially suspicious network behaviour.

## 🔐 Ethical Considerations

- Analyze only networks and traffic that I own or have explicit permission to inspect.
- Do not capture private communications without authorization.
- Use sample PCAP files or controlled lab environments for practice.
- Handle captured network data responsibly.

## 📌 Project Status

**Status:** Learning Activity / Hands-On Lab

This repository documents the methodology, concepts, and practical learning process. Actual packet-analysis findings and screenshots can be added after completing an authorized traffic capture.

## 👨‍💻 Author

**Manikanta Sai**

Cybersecurity Learner | Network Security | Hands-On Labs

---

⭐ This project is part of my journey toward learning practical cybersecurity and network security concepts.
