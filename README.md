# Wireshark Network Investigation Lab

## Overview
This project demonstrates intermediate packet capture and analysis using Wireshark on Kali Linux.

## Objectives
- Capture and analyze live traffic.
- Inspect TCP, DNS, HTTP, and TLS activity.
- Use display filters, conversations, endpoints, and I/O graphs.
- Identify normal and unusual network behavior.

## Tools Used
- Kali Linux
- Wireshark
- Browser
- Ping
- Local network traffic

## Methodology
1. Captured baseline traffic.
2. Applied display filters to isolate protocols.
3. Followed TCP streams to reconstruct conversations.
4. Reviewed conversations, endpoints, and I/O graphs.
5. Investigated a suspicious or unusual pattern.

## Key Findings
- DNS queries showed domain resolution behavior.
- TCP analysis revealed normal handshakes and retransmissions.
- TLS inspection helped identify certificate or handshake behavior.
- I/O graphs highlighted traffic spikes.

## Evidence
- Screenshots of filters, streams, conversations, and graphs.
- Saved packet capture files.

## Lessons Learned
Wireshark can be used beyond basic packet viewing to investigate flow behavior, performance issues, and security anomalies.
