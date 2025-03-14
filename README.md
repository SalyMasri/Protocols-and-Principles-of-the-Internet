#  Protocols and Principles of the Internet – DNS & TCP Analysis

## Overview
This repository contains completed assignments from the **IK2218 – Protocols and Principles of the Internet** course, focusing on **DNS Configuration & Replication** and **TCP Protocol Analysis**.

## 🛠️ Technologies & Tools Used
- **Networking Protocols**: DNS, ARP, IP, UDP, TCP
- **Software & Tools**: BIND, Wireshark, VirtualBox, `dig`
- **Command-Line Utilities**: `named-checkconf`, `tcpdump`, `rndc reload`
- **Git Workflow**: Version-controlled configuration files and reports

---

## 🌍 **1. DNS Configuration & Management**
Configured and tested a **DNS zone (`groupX.ik2218.ssvl.kth.se`)**, created **subzones**, and implemented **delegations**.

✔️ **Set up zone files** with **SOA, NS, A, and TXT records**  
✔️ **Delegated "america.groupX" to an external nameserver**  
✔️ **Configured master-slave DNS replication** for redundancy  
✔️ **Validated setup with `dig +trace` and `Zonemaster`**  

---

## 📡 **2. TCP Protocol Analysis**
Captured and analyzed **TCP traffic** using **Wireshark** to understand **connection management, data transfer, retransmissions, and congestion control**.

✔️ **Captured TCP handshake (`SYN`, `SYN-ACK`, `ACK`)**  
✔️ **Compared TCP & UDP efficiency (87.43% vs. 92.94%)**  
✔️ **Observed retransmissions & fast recovery mechanisms**  
✔️ **Measured delayed ACKs (150ms) and congestion window behavior**  

---

## ✅ **Final Results**
- **DNS configurations verified**, including **zone delegation & replication**
- **TCP behavior analyzed**, confirming **protocol efficiency & congestion control**
- **All tests passed successfully** with validated configurations  

