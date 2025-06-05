# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## Tools Used
- **Wireshark**: A network protocol analyzer for capturing and analyzing network traffic.

## Steps Followed
1. **Installed Wireshark** on the system.
2. **Initiated packet capture** on the active network interface.
3. **Generated network traffic** by:
   - Browsing websites (e.g., google.com, flipkart.com).
   - Using command-line tools like `ping` to send ICMP requests.
4. **Stopped the capture** after sufficient data was collected.
5. **Applied filters** in Wireshark to isolate specific protocols:
   - `http`
   - `dns`
   - `tcp`
   - `udp`
6. **Saved the capture** as `network_capture.pcap`.

## Protocols Identified
- **DNS (Domain Name System)**: Resolves domain names to IP addresses.
- **TCP (Transmission Control Protocol)**: Ensures reliable data transmission.
- **HTTP (Hypertext Transfer Protocol)**: Facilitates web page requests and responses.
- **UDP (User Datagram Protocol)**: Enables connectionless data transmission.
- **ICMP (Internet Control Message Protocol)**: Used for network diagnostics (e.g., ping).

## Summary of Packet Types
- **DNS Queries and Responses**: Observed during domain name resolutions.
- **TCP Handshakes**: Noted during the initiation of HTTP connections.
- **HTTP GET Requests**: Captured when accessing web pages.
- **UDP Packets**: Detected, possibly related to services like DNS or streaming.
- **ICMP Echo Requests/Replies**: Seen during ping operations.

## Observations
- The capture showcases a typical web browsing session, highlighting the interplay between DNS resolution, TCP connections, and HTTP requests.
- The presence of ICMP packets indicates network diagnostic activities.
- UDP packets suggest background services or applications utilizing connectionless communication.

## Note
Encrypted traffic (e.g., HTTPS) appears as TLS packets and cannot be decrypted without the appropriate encryption keys.

## Key Learnings
- Gained hands-on experience with Wireshark for capturing and analyzing network traffic.
- Developed an understanding of common network protocols and their roles in data transmission.
- Learned to apply filters in Wireshark to isolate and study specific types of network traffic.
