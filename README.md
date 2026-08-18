# SOC Lab 1 – Network Scanning & Traffic Analysis

A hands-on network security lab focused on network reconnaissance, open-port identification, and packet analysis using Nmap, Wireshark, and Kali Linux.

> **Project Type:** Cybersecurity / SOC / Network Security  
> **Status:** Hands-on Lab Project

---

## Objective

The objective of this lab was to understand how security analysts perform basic network reconnaissance and analyze the resulting network traffic.

The lab followed a simple investigation workflow:

**Network Scan → Identify Services → Capture Traffic → Analyze Packets → Document Findings**

---

## Tools Used

- **Kali Linux** — Security testing and analysis environment
- **Nmap** — Network discovery and port scanning
- **Wireshark** — Packet capture and network traffic analysis

---

## Lab Activities

### 1. Network Scanning

Used Nmap to perform network reconnaissance and identify accessible ports and services.

### 2. Service Identification

Reviewed discovered ports and identified the services associated with the scan results.

### 3. Packet Capture

Used Wireshark to capture network traffic generated during the lab.

### 4. Traffic Analysis

Analyzed captured packets to understand:

- Source and destination communication
- TCP connections
- Port activity
- TLS/HTTPS traffic
- Network communication patterns

---

## Key Findings

The investigation identified:

- An open port associated with the lab environment
- TCP communication between systems
- TLS/HTTPS traffic over port 443
- Network activity generated during reconnaissance

> Findings are specific to the controlled lab environment and should not be interpreted as a general security assessment.

---

## Investigation Workflow

```text
        Target System
              │
              ▼
          Nmap Scan
              │
              ▼
      Open Port Discovery
              │
              ▼
       Service Analysis
              │
              ▼
      Wireshark Capture
              │
              ▼
       Packet Analysis
              │
              ▼
       Security Findings
