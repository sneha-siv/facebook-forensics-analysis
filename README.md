# 🔍 Forensic Analysis of Facebook Android App

This project documents a forensic investigation of the Facebook APK as part of my academic coursework in Forensics and eDiscovery. The objective was to analyze the structure, permissions, and behavior of the Facebook app using open-source tools in a secure sandboxed environment.

---

## 🧪 Summary

- Decompiled the Facebook APK using **Androguard** to extract Java source code and analyze `AndroidManifest.xml`
- Identified sensitive permissions and noted unprotected API access
- Used **Android Studio** emulator to test app behavior and capture logs via **logcat**
- Performed basic **malware analysis** using an online scanner
- Captured **network logs with Wireshark** during interaction with the app
- Ensured all testing occurred in an isolated **Kali Linux VM**

---

## 🔧 Tools & Environment

- 🐧 **Host OS:** macOS Sonoma 14.1 (Mac M1)
- 🧪 **Sandboxed VM:** Kali Linux (VMware Fusion)
- 📱 **Emulation:** Android Studio with AVD Manager
- 🔍 **Analysis Tools:** Androguard, Wireshark
- 🌐 **Online Scanner:** APK Malware Analysis Tool

---

## 📁 Contents

- `Facebook_Forensics_Report.pdf` — Full report with screenshots and findings
- `screenshots/` — (Optional) Visuals of tools, emulator logs, and APK structure

---

## 🔐 Key Findings

- The app requested a large number of permissions, including access to phone state and battery status
- Found a permission related to **unprotected API access**
- Identified behavioral logs that triggered during logout/login events
- Minor issues detected in malware scan

---

## 🚧 Limitations & Future Work

- Tool compatibility was limited due to macOS M1 constraints
- Future work could involve tools like **Ghidra**, **Radare2**, or a full **Cuckoo Sandbox** setup for deeper dynamic analysis

---

## 📬 Contact

- 📧 Email: snehasivaram1968@gmail.com  
- 💼 LinkedIn: [Sneha Sivaram](https://www.linkedin.com/in/sneha-sivaram-2978b61b8)
