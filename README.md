# Mail Server Setup

A complete mail server setup using Postfix, Dovecot, and Roundcube with SSL/TLS encryption and DNS records for SPF, DKIM, and DMARC.

## 📌 Features

- Secure Postfix SMTP server
- Dovecot IMAP/POP3 server
- Webmail access via Roundcube
- SSL/TLS encryption
- SPF, DKIM, and DMARC DNS configuration
- Email sending/receiving tests

## 🛠️ Technologies Used

- Postfix
- Dovecot
- Roundcube
- OpenSSL
- DNS (SPF, DKIM, DMARC)

## 📥 Setup

1. Install dependencies using package managers (apt/yum)
2. Configure:
   - `main.cf` (Postfix)
   - `dovecot.conf` (Dovecot)
   - Roundcube web client
3. Generate SSL certificates
4. Add DNS records
5. Test email functionality
