# Wireshark
1. Packet Capture
Wireshark monitors network interfaces (like Ethernet, Wi-Fi) and captures all packets passing through.
Each packet contains information like:
Source & destination IP addresses
Protocol used (TCP, UDP, HTTP, etc.)
Payload (the actual data)
It uses the network interface in promiscuous mode to capture all traffic, not just traffic destined for your computer.

2. Packet Analysis
After capturing packets, Wireshark decodes them according to protocols.
It can show each packet in layers:
Physical Layer: Ethernet or Wi-Fi headers
Network Layer: IP addresses, routing info
Transport Layer: TCP/UDP ports, sequence numbers
Application Layer: HTTP, DNS, FTP, etc.
This layered view helps understand exactly what happened in a network conversation
