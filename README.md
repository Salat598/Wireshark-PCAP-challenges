
subject : Wireshark PCAP Analysis Challenge

Objective
Analyze a PCAP file and identify credentials transmitted in plaintext over HTTP.

Tools Used
- Windows 11
- Wireshark

Methodology
1. Opened the PCAP file in Wireshark.
2. Applied the filter: http
3. Located an HTTP POST request.
4. Followed the TCP Stream.
5. Identified credentials transmitted in plaintext.
Findings
This analysis demonstrated how unencrypted HTTP traffic can expose usernames and passwords to anyone able to capture network traffic.

Skills Demonstrated
- Packet Analysis
- HTTP Traffic Analysis
- Wireshark
- Cybersecurity Investigation
 Lessons Learned
Always use HTTPS to protect sensitive information during transmission.

