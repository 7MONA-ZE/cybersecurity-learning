# Networking Basics

## What is networking?
Networking is the communication between devices and systems. In cybersecurity, understanding networking helps you detect suspicious traffic and understand how attacks move across infrastructure.

## Key Concepts
### IP Addresses
- A unique identifier assigned to a device on a network
- IPv4 and IPv6 are common versions

### Ports
- Ports are communication endpoints used by services
- Common examples:
  - 80 = HTTP
  - 443 = HTTPS
  - 22 = SSH
  - 21 = FTP

### Protocols
Common protocols include:
- TCP
- UDP
- HTTP
- HTTPS
- DNS
- ICMP

### DNS
Domain Name System translates domain names like example.com into IP addresses.

### Firewalls
Firewalls filter traffic to allow or block specific connections.

## OSI Model (Beginner Overview)
1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

## TCP vs UDP
- TCP: connection-oriented and reliable
- UDP: faster, lightweight, usually used for streaming and DNS

## Why this matters in cybersecurity
Security professionals analyze network traffic to identify:
- scanning activity
- malicious connections
- suspicious ports
- unusual login attempts
- data exfiltration patterns

## Beginner Practice
- Learn how HTTP and HTTPS differ
- Check common ports with tools such as `nmap`
- Understand how DNS works
- Look at packet capture basics in Wireshark

## Questions to Ask
- What happens when a user loads a website?
- Why do we need encryption for web traffic?
- How can an attacker use open ports to gain access?

## Summary
Networking is a foundational skill in cybersecurity. If you understand how devices communicate, you can better understand how attacks happen and how to defend systems.
