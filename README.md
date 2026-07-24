# Wireshark Network Analysis

## Overview

This project demonstrates network traffic analysis using Wireshark. The objective is to capture, inspect, and analyze network packets to understand communication between devices and identify common network protocols.

## Objectives

- Capture live network traffic
- Analyze common network protocols
- Understand packet flow
- Identify DNS, HTTP, HTTPS, TCP, ICMP, and ARP traffic
- Perform basic network security analysis

## Tools Used

- Wireshark
- Windows 11
- Google Chrome
- Command Prompt

## Protocols Analyzed

- ARP
- DNS
- TCP
- UDP
- HTTP
- HTTPS (TLS)
- ICMP

## Project Structure

```
Wireshark-Network-Analysis/
│
├── captures/
├── docs/
├── report/
└── README.md
```

## Methodology

1. Started packet capture using Wireshark.
2. Generated network traffic by browsing websites.
3. Executed ping and DNS lookup commands.
4. Stopped the capture after several minutes.
5. Applied protocol filters.
6. Analyzed captured packets.
7. Documented findings.

## Key Findings

- DNS queries successfully resolved domain names.
- TCP established reliable connections using the three-way handshake.
- HTTPS traffic was encrypted using TLS.
- ICMP packets were observed during ping operations.
- ARP packets resolved IP addresses to MAC addresses.

## Learning Outcomes

- Packet capture techniques
- Protocol identification
- Network troubleshooting
- Basic threat detection
- Wireshark filtering

## Future Improvements

- Analyze malware traffic
- Detect port scanning
- Analyze suspicious network behavior
- Integrate Wireshark with IDS tools

## Author

A. Venkata Vishnu Vardhan
