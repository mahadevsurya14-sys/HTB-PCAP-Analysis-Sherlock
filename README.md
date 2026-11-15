# HTB Sherlock – PCAP Analysis

![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Hack_The_Box-green)
![Category](https://img.shields.io/badge/Category-Network_Analysis-blue)
![Tool](https://img.shields.io/badge/Tool-Wireshark-purple)

## 📌 Challenge Overview

**PCAP Analysis** is a Hack The Box Sherlock challenge focused on investigating network traffic using packet analysis techniques.

The objective was to analyze a network capture file (`.pcapng`) and identify communication endpoints, HTTP file uploads, web server information, upload directories, and encrypted file transfer duration.

## 🎯 Investigation Objectives

The investigation involved six tasks:

1. Identify the sender and receiver IP addresses.
2. Identify the web server IP address.
3. Determine the uploaded filename.
4. Identify the web server software.
5. Find the upload directory.
6. Calculate the encrypted file transfer duration.

## 🛠️ Tools Used

- Wireshark
- TShark
- Kali Linux
- PCAPNG Analysis

## 🔍 Investigation Methodology

### 1. Network Traffic Analysis
- Examined network communication.
- Identified source and destination IP addresses.
- Investigated relevant conversations.

### 2. HTTP Traffic Investigation
- Filtered HTTP packets.
- Inspected POST requests.
- Examined HTTP headers and server responses.

### 3. File Upload Investigation
- Identified the uploaded filename.
- Examined the upload request URI.
- Investigated the server response.

### 4. Server Fingerprinting
- Analyzed HTTP response headers.
- Identified the web server software.

### 5. Transfer Duration Analysis
- Used Wireshark Statistics → Conversations.
- Inspected TCP conversation details.
- Investigated the duration of the encrypted file transfer.

## 📚 Key Learnings

- Practical Wireshark usage.
- Network traffic investigation.
- HTTP request and response analysis.
- TCP conversation analysis.
- Web server fingerprinting.
- Network-based digital forensics.

## 🏆 Challenge Completion

| Achievement | Result |
|---|---|
| Platform | Hack The Box |
| Challenge | PCAP Analysis |
| Status | Completed |
| XP Earned | 165 |
| Sherlock Rank | #2389 |
| Completion Date | 15 November 2026 |

## 💡 Takeaway

This Sherlock challenge improved my practical understanding of network traffic analysis and demonstrated how packet captures can reveal valuable information about network communication and file transfers.

**Learning by doing. Investigating every packet. Improving every day.**

---

*Disclaimer: This repository contains independently written learning notes. Original challenge files and proprietary challenge materials are not included.*
