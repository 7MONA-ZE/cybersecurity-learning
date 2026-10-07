# Lab 01: Network Basics

## Objective
Understand basic networking concepts and common services.

## Tools
- `ping`
- `nslookup` or `dig`
- `curl`
- `nmap` (if available)

## Steps
1. Open a terminal.
2. Use `ping` to test connectivity to a known website.
3. Run `nslookup` for a domain name.
4. Check the IP address and note the result.
5. Use `curl` to inspect a website response.
6. Research common ports and their functions.
7. Write down what you learned.

## Example Commands
```bash
ping google.com
nslookup google.com
curl -I https://example.com
```

## Reflection
- What did the DNS lookup return?
- Why is the server reachable by name but not by IP alone?
- How does HTTPS differ from HTTP?

## Notes
- DNS converts names to IP addresses
- HTTP uses port 80; HTTPS uses port 443
- Firewalls can block or allow traffic based on port and protocol

## Outcome
You should understand the basic idea of how devices locate each other and exchange data.
