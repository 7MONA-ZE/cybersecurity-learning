# Web Security Basics

## Why web security matters
Many cyberattacks target web applications and services. Understanding how web apps function helps you recognize common attack methods and protective controls.

## HTTP vs HTTPS
- HTTP: text-based and not encrypted
- HTTPS: encrypted using TLS/SSL

## Common Web Vulnerabilities
### SQL Injection
Attackers manipulate queries to access or alter database data.

### XSS (Cross-Site Scripting)
User input is executed in a browser in a malicious way.

### Broken Access Control
Users can access data or actions they should not be allowed to reach.

### CSRF
A user is tricked into performing an action without realizing it.

## Authentication and Session Basics
- Login systems verify identity
- Sessions keep users authenticated during a browser session
- Cookies and tokens are used to maintain state

## Security Controls
- Input validation
- Output encoding
- Secure session management
- HTTPS enforcement
- Least privilege models
- Secure configuration

## Tools
- Burp Suite
- OWASP ZAP
- `curl`
- browser developer tools

## Good Practice
- Never trust user input
- Always validate data
- Keep authentication secure
- Review logs and failed attempts

## Summary
Web security is one of the most important beginner topics because the web is a common attack surface. Learning how websites handle input, authentication, and sessions provides a solid basis for security work.
