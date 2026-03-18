# Network-Traffic-Analysis-Wireshark-Nmap
Developed a network traffic analysis project using Wireshark and Nmap to identify active devices, analyze DNS queries, and evaluate high-traffic endpoints.
# Network Traffic Analysis using Wireshark & Nmap

## Overview

This project analyzes network traffic within a local subnet using Wireshark and Nmap. The objective is to identify active devices, analyze communication patterns, and understand protocol behavior.

## Objectives

* Discover active devices on the network
* Capture and analyze packet-level traffic
* Identify DNS queries and accessed domains
* Analyze high-traffic endpoints
* Understand network behavior patterns

## Tools Used

* Wireshark
* Nmap
* Windows Command Prompt

## Methodology

### 1. Device Discovery

Used Nmap to identify active hosts:

nmap -sn 192.168.0.0/24

### 2. Packet Capture

Captured traffic using Wireshark with filter:

ip.addr == 192.168.0.0/24

### 3. DNS Analysis

Filtered DNS traffic:

dns

### 4. Traffic Analysis

Used:

* Statistics → Conversations
* Statistics → Endpoints

## Key Findings

* Active devices: Router, Laptop, Mobile
* Highest traffic observed between laptop and Google servers
* Most traffic encrypted (HTTPS)
* DNS queries revealed domains like Google and YouTube

## Observations

* WiFi limitations restrict visibility of other device traffic
* Only broadcast and own device traffic visible without monitor mode

## Conclusion

The network shows normal behavior with no suspicious activity. Most traffic is encrypted, indicating secure communication.

## Learning Outcomes

* Network packet analysis using Wireshark
* Device discovery using Nmap
* DNS and protocol analysis
* Traffic profiling and interpretation

## Screenshots
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/fde66d2d-f1e8-4ef8-b207-5ce51e99cdaa" />
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/6b5538dd-c99e-4559-a387-15278267fd88" />




