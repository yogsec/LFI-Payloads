# 🚀 LFI Payloads

Welcome to **LFI Payloads**! This repository is designed to help security researchers and penetration testers identify and exploit **Local File Inclusion (LFI)** vulnerabilities with effective payloads. 🛡️

---

## 📂 What is LFI?

**Local File Inclusion (LFI)** is a web vulnerability that allows an attacker to include files on a server through the web browser. This can potentially lead to:

- 🕵️‍♂️ Information Disclosure
- 🐍 Code Execution
- 🔥 Server Compromise

---

## 📜 Payloads

This repository contains various payloads categorized for easy access:

✅ **Basic Payloads**\
✅ **Encoding Techniques**\
✅ **Traversal Techniques**\
✅ **Wrapper Bypass**\
✅ **PHP Filters**\
✅ **Log Poisoning Payloads**

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

---

## 🧰 Examples

**Basic Payload:**

```bash
?page=../../../../etc/passwd
```

**PHP Filter Bypass:**

```bash
?page=php://filter/convert.base64-encode/resource=index.php
```

---



