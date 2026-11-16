# Wireshark Troubleshooting Casebook

> A hands-on network diagnostics casebook using packet captures and repeatable tests to investigate common TCP/IP services and connectivity issues.

[![Wireshark](https://img.shields.io/badge/Analysis-Wireshark-1679A7?logo=wireshark&logoColor=white)](https://www.wireshark.org/)
[![Protocols](https://img.shields.io/badge/Protocols-DHCP%20%7C%20DNS%20%7C%20ARP%20%7C%20ICMP%20%7C%20TCP-475569)](#case-studies)

## Project at a glance

Six case studies document the test, packet-level observations, interpretation, and troubleshooting conclusions for common network scenarios.

## Contents

- [Project objectives](#project-objectives)
- [Case studies](#case-studies)
- [Tools used](#tools-used)
- [Skills demonstrated](#skills-demonstrated)
- [Repository structure](#repository-structure)

## Packet-analysis example

![DNS packet capture in Wireshark](screenshots/dns-packets.png)

---

A practical network troubleshooting portfolio built with Wireshark. This project documents real network tests, packet captures, protocol analysis, and troubleshooting procedures.

## Project Objectives

- Analyze network traffic using Wireshark.
- Understand common network protocols.
- Identify communication problems through packet inspection.
- Document technical findings and troubleshooting steps.

## Case Studies

| Case | Topic | Documentation |
|---|---|---|
| 01 | DHCP – IP address assignment | [01-dhcp.md](cases/01-dhcp.md) |
| 02 | DNS – Name resolution | [02-dns.md](cases/02-dns.md) |
| 03 | ARP – IP-to-MAC resolution | [03-arp.md](cases/03-arp.md) |
| 04 | ICMP – Connectivity testing | [04-icmp.md](cases/04-icmp.md) |
| 05 | TCP – Three-way handshake | [05-tcp-handshake.md](cases/05-tcp-handshake.md) |
| 06 | TCP – Failed connection analysis | [06-failed-connection.md](cases/06-failed-connection.md) |

## Tools Used

- **Wireshark** – Network packet capture and protocol analysis.
- **Windows Command Prompt** – Network diagnostic commands.
- **Ping** – Connectivity testing.
- **Nslookup** – DNS troubleshooting.
- **Curl** – TCP/HTTP connection testing.
- **Git and GitHub** – Version control and project documentation.

## Skills Demonstrated

- Network protocol analysis
- TCP/IP fundamentals
- DHCP and DNS troubleshooting
- ARP and MAC address resolution
- ICMP connectivity diagnostics
- TCP handshake and connection failure analysis
- Technical documentation

## Repository Structure

```text
wireshark-troubleshooting-casebook/
├── cases/
│   ├── 01-dhcp.md
│   ├── 02-dns.md
│   ├── 03-arp.md
│   ├── 04-icmp.md
│   ├── 05-tcp-handshake.md
│   └── 06-failed-connection.md
├── screenshots/
└── README.md
```

## Purpose

This casebook is a hands-on learning project demonstrating practical networking knowledge and troubleshooting methodology for IT Support and Network Technician roles.
