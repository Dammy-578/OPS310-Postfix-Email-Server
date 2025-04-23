# OPS310-Postfix-Email-Server
Postfix email server deployment with TLS encryption and mail delivery testing using swaks, telnet, and mailx. Completed for OPS310 at Seneca Polytechnic.
# Postfix Email Server Deployment & TLS Security – OPS310 Lab 4 & Assignment 1

**Course:** OPS310 – Cloud Platform Management  
**Date:** March 2025  
**Institution:** Seneca Polytechnic

---

## 🧠 Overview
This lab-based assignment focused on building a secure email system using Postfix on a Linux VM. The goal was to send and receive mail locally, configure secure communication with TLS, and validate delivery using testing tools and log analysis — without relying on external services.

---

## 🛠️ Configuration Tasks
- Installed Postfix and configured domain-based mail routing
- Updated `/etc/postfix/main.cf` with custom hostname and domain settings
- Configured `/etc/aliases` and ran `newaliases` to route mail to users
- Used tools like `mailx`, `swaks`, and `telnet` to test message delivery
- Enabled TLS (`smtpd_tls_security_level = may`) for encrypted sessions
- Analyzed logs from `/var/log/mail.log` to verify message headers and delivery success

---

## 🔐 Security Focus
- Implemented **TLS encryption** to protect SMTP sessions  
- Verified encryption using `swaks` with custom headers  
- Ensured hostname resolution and static IP configuration for VM

---

## ✅ Tools Used
- **Postfix**  
- **swaks**  
- **mailx**  
- **telnet**  
- **Ubuntu (Linux)**

---

## 🧠 Skills Demonstrated
- Postfix configuration  
- Linux system administration  
- TLS-secured SMTP email delivery  
- Email client and mail log troubleshooting

---

## 📂 Notes
No files or screenshots are uploaded in this repository, but all testing, configuration, and validation were completed in a live Linux environment and submitted separately for grading.

---

## ✅ Project Status
- ✔️ Postfix SMTP server configured and tested  
- ✔️ TLS encryption confirmed  
- ✔️ Delivery validated using log output and command-line tools
