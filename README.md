# Task 5: Network Traffic Capture and Analysis using Wireshark

## Objective
Capture live network packets, analyze traffic, and identify protocols.

## Tools Used
- Wireshark (Latest Version)
- Windows 10
- Command Prompt / Web Browser

## Steps Performed
1. Installed Wireshark with NPcap driver.
2. Selected the active Wi-Fi interface.
3. Generated traffic by:
   - Pinging google.com
   - Browsing a few websites
4. Stopped capture after 1 minute.
5. Applied filters for protocols like `http`, `dns`, `tcp`.
6. Identified and analyzed key protocols.

## Protocols Identified
- **HTTP**: Unencrypted web traffic (port 80)
- **DNS**: Domain resolution queries (port 53)
- **TCP**: Reliable data transfer protocol
- **ICMP**: Ping traffic

## Deliverables
- `network_capture.pcap`: Packet capture file
- `report.pdf`: Summary of findings

## Outcome
Successfully captured and analyzed live packet data and became familiar with key networking protocols and packet structures.
