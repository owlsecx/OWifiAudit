# 🦉 OWifiAudit

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OWifiAudit** — Wi-Fi Security Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OWifiAudit is a wireless-network security auditing tool that surveys nearby Wi-Fi networks and assesses their encryption and configuration posture. It enumerates access points, identifies weak or open security (WEP/WPA/WPS), and reports signal, channel and vendor details. It is intended strictly for authorized wireless assessments.

---

## ✨ Features


- Access-point discovery with SSID, BSSID, channel and signal strength
- Encryption posture assessment (open, WEP, WPA/WPA2/WPA3, WPS exposure)
- OUI vendor identification for discovered access points
- Rogue/weak-network flagging for defensive review
- Structured export of survey results for reporting
- Offline --self-test for safe verification

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OWifiAudit
./OWifiAudit --self-test
./OWifiAudit --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
