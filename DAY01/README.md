## Day 01: Cybersecurity Foundations

### What is Cybersecurity?
> Cybersecurity involves protecting systems, networks, and data from unauthorized access, breaches, and attacks.

---

### CIA Triad

- *Confidentiality* — Restrict data access to authorized users.
- *Integrity* — Ensure data remains unchanged and reliable.
- *Availability* — Keep systems accessible when needed.

---

### Security Teams

| Team Type     | Role                                             |
|---------------|--------------------------------------------------|
| Red Team      | Offensive security: Simulate attacks.            |
| Blue Team     | Defensive security: Monitor and defend systems.  |
| Purple Team   | Red + Blue collaboration for continuous learning.|

---

### Abbreviations Reference Table

| Term  | Definition                                      |
|-------|-------------------------------------------------|
| TSL   | Transport Layer Security                        |
| IDS   | Intrusion Detection System                      |
| IPS   | Intrusion Prevention System                     |
| POC   | Proof of Concept                                |
| IR    | Incident Response                               |
| SOC   | Security Operations Center                      |
| SIEM  | Security Information and Event Management       |
| SAAS  | Software as a Service                           |

---

### Top Threats Overview

- *Phishing* — Fake communications tricking users into giving sensitive data.
- *Ransomware* — Encrypts data, demands payment to restore access.
- *Malware* — Malicious software designed to damage/disable systems.
- *Social Engineering* — Human manipulation to gain confidential data.
- *MITM (Man-in-the-Middle)* — Intercepting communication between parties.
- *Zero-Day Attack* — Exploits unknown software vulnerabilities.

---

### Encryption Summary

- *Symmetric Encryption:* One key for both encryption & decryption.
- *Asymmetric Encryption:* Public & private key pair for secure exchanges.

Example (CLI using OpenSSL):

openssl enc -aes-256-cbc -in input.txt -out encrypted.txt

