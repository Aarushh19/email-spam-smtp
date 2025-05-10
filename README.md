# Email Spam Simulation via SMTP (CAP6135 Lab)

This project simulates a spoofed email sent manually using the Telnet protocol on port 25, interacting directly with an SMTP server. Completed as part of the Cybersecurity and Privacy program at the University of Central Florida (CAP6135).

## 🔍 Objective
To understand how SMTP allows email spoofing due to lack of built-in authentication, and explore how attackers exploit this protocol weakness.

## 🛠️ Tools & Setup
- Telnet (Linux Terminal)
- SMTP on port 25 (Eustis Server at UCF)
- Manual commands: HELO, MAIL FROM, RCPT TO, DATA

## 🧪 Steps Performed
1. Established a Telnet connection to the SMTP server.
2. Sent a `HELO` greeting and spoofed sender as `techsupport@bankofamerica.com`.
3. Used `RCPT TO` to specify recipient addresses.
4. Wrote an email body and ended it with `.` as per SMTP protocol.
5. Verified delivery acceptance by the server.

## 📸 Screenshot
![Spam Email Screenshot](https://raw.githubusercontent.com/Aarushh19/email-spam-smtp/main/Spam%20Email.png)


## ✅ Learning Outcome
- Understood SMTP protocol behavior and its vulnerabilities.
- Simulated a real-world spam scenario in a safe lab setting.
- Learned about importance of SPF, DKIM, and DMARC in modern email authentication.

## ⚠️ Disclaimer
This project was conducted in a controlled academic environment and is intended strictly for educational purposes.

---

© Aarush Gupta – MS in Cybersecurity & Privacy | University of Central Florida
