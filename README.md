# Task-_5-wireshark-dns-analysis
DNS packet capture and analysis using Wireshark, filtering safe packets for demonstration and upload.
# Wireshark DNS Analysis

## Overview
This repository contains the results of a Wireshark-based network analysis focused on DNS traffic.  
Captured packets have been filtered to include only **safe** DNS queries and responses, excluding any sensitive or private information.

## Contents
- `Task_5_captured_safe.pcap` — Safe DNS packet capture file.
- `screenshots/` — Screenshots showing packet capture and filtering process.
- `README.md` — Project documentation.

## Objective
To capture, analyze, and filter DNS packets using Wireshark in a controlled lab environment, then upload only the safe data to a public repository.

## Tools Used
- **Wireshark** — For packet capture and analysis.
- **Kali Linux** — Capture environment.
- **UTM** — Virtual machine hosting.
- **GitHub** — Repository hosting.

## Filtering Criteria
- Only DNS packets were included.
- No packets containing sensitive payloads or personal identifiers.
- Protocols unrelated to the task were excluded.

## How to Open
1. Download the `.pcap` file from this repository.
2. Open in Wireshark.
3. Apply display filter:  
4. Explore the safe DNS query/response transactions.

## Disclaimer
This capture was generated in a lab setting for educational purposes only.  
No real-world sensitive data is present in this repository.


