# Android APK Security Analyzer

Android APK Security Analyzer is a lightweight static analysis tool designed to detect common security vulnerabilities and insecure configurations in Android applications.

The tool performs rule-based static analysis by examining the `AndroidManifest.xml` and application code (smali, dex, and textual resources) to identify security risks.

This project is inspired by tools like QARK and MobSF and is intended for educational, research, and cybersecurity learning purposes.

---

## Features

- Debuggable app detection  
- Exported component checks  
- Dangerous permission detection  
- Weak cryptography detection (MD5, SHA1, DES, ECB)   
- Hardcoded secret detection  
- WebView security checks  
- Insecure broadcast and PendingIntent checks  

---

## Requirements

- Python 3.8+
- Androguard

Install dependency:

```bash
pip install androguard

