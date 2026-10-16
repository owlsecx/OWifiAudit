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

Wi-Fi environment & security auditor (read-only)

---

## ✨ Features

- Wireless interface discovery — iw dev, nmcli device, sysfs /sys/class/net/*/wireless, driver, MAC, state, PHY capabilities and supported bands (2.4/5/6 GHz)
- Passive network scan through the system tooling: nmcli (terse, escape-aware), iw scan, iwlist scan — automatic fallback chain, timeouts, privilege hints
- Robust parsers: SSID, BSSID, channel, frequency, signal (dBm / % / bars), RSN/WPA AKM + ciphers, WPS state, hidden SSIDs, PMF (802.11w)
- Security classifier — OPEN / OWE / WEP / WPA / WPA2 / WPA3 / WPA2-WPA3 transition / Enterprise
- Embedded OUI vendor table (~230 prefixes) with locally-administered (randomised) BSSID detection
- Assessment engine — open/WEP (critical), TKIP, WPS, hidden SSIDs, evil-twin / rogue AP heuristics, karma-style lure SSIDs, default router SSIDs
- Channel congestion analysis + recommendation for 2.4 GHz (1/6/11) and 5 GHz (non-DFS first)
- Current connection & privacy posture (MAC randomisation, PMF, link rate, gateway)
- Saved profile audit (NetworkManager / iwd) — never prints secrets, only reports presence
- ASCII spectrum view (per-channel occupancy)
- Export TXT / MD / JSON / CSV, save chooser, clipboard, full CLI with --fail-on CI gate

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OWifiAudit
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
