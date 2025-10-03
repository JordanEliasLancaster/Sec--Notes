# Domain 1: Threats, Attacks, and Vulnerabilities 

## Malware Types
- **Virus** --> needs user action (e.g., open file).
- **Worm** --> spreads automatically without the user's action.
- **Trojan** --> disguised legit software, installs malicious code
- **Rootkit** --> hides presence by altering system files/processes.
- **Ransomware** --> encrypts files, demands payment.
- **Spyware/keylogger** --> secretly collects info
- **Botnet / Bot** --> infected hosts that are being controlled to DDoS 

## Attack Types
- **Phishing** --> fake emails to trick users into giving info
- **Spear Phishing** --> targeted phishing (specific person/org)
- **Whaling** --> phishing aimed at executives.
- **Pharming** --> DNS manipulation redirects users to fake sites
- **Vishing/Smishing** --> voice (phone) /SMS phishing. 

## Web application attacks
**SQL Injection (SQLi)** --> Injects SQL to manipulate Databases 
**Cross-Site Scripting (XSS)** --> Injects client-side script that runs in the user's browser
**Cross-Site Request Forgery (CSRF)** --> Tricks a user's browser into making authenticated requests.
**Directory traversal** - Acess files outside webroot ('..\').
**Command Injection / RCE** - Run shell commands via insecure input.

## Network attacks 
**Man-in-middle (MitM)** - intercept and possible alter traffic.
**Eavesdropping** - passive sniffing of network traffic
**Evil twin** - Fake Wi-Fi AP to intercept credentials.
**Replay Attack** - Capture and resend valid data to bypass authentication.
**ARP Spoofing / Poisoning** - Redirect LAN traffic to attacker.

## DOS / DDoS
**DoS** --> Overloading a target, requests coming from a single source
**DDos** --> Distributed botnet floods the target 

## Vulnerablities 
**Zero-day** --> Unknown to Vendor, no patch available or mandated as the threat scope is unknown
**Buffer Overflow** --> Overflow memory to crash or run code
**Misconfiguration** --> Weak permissions, default creds, open ports
**Weak passwords** --> Easy Brute force attempts successful

## Insider threats
**Malicious insider** --> Intentional harm to systems
**Nefligent insider** --> Careless mistakes that lead to vulnerabilities 
**Compromised insider** --> Account hacked by attacker

