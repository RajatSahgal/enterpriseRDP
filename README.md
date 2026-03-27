# 🚀 Enterprise RDP Manager

Enterprise Remote Desktop Manager for Windows — designed for efficient multi-server access, monitoring, and secure credential handling.

---

## 📦 Repository Contents

* `EnterpriseRDP.exe` — Packaged Windows desktop application
* `_internal/` — Runtime dependencies required by the executable
* Source code for:

  * UI dashboard
  * RDP connection flow
  * Encryption module
  * Database management

---

## ✨ Features

* Manage multiple RDP profiles (Add, Edit, Delete)
* Import and Export server list via CSV
* Multi-select connect with intelligent per-host handling
* Live server status and latency monitoring
* Secure encrypted credential storage (local key-based)
* Modern dashboard UI with search and filtering

---

## ▶️ Run the Application

1. Download or clone this repository
2. Ensure the following are in the same directory:

   * `EnterpriseRDP.exe`
   * `_internal/` folder
3. Double-click `EnterpriseRDP.exe` to launch

---

## 📄 CSV Format for Import

Required headers:

```csv
name,ip,port,username,password
```

### Example:

```csv
name,ip,port,username,password
server-1,192.168.1.11,3389,administrator,Password@123
```

---

## 📝 Release Notes

* Includes modern UI dashboard with improved usability
* Connection logging and monitoring enhancements
* Stable RDP launch handling
* Runtime packaging improvements with icon support

---

## ⚠️ Notes

* Multiple RDP sessions to the same host depend on **Windows session policies**
* If the application icon appears outdated in Windows Explorer:

  * Rename the `.exe`, or
  * Refresh the Windows icon cache

---

## 🎯 Overview

Enterprise RDP Manager provides a **secure, scalable, and user-friendly solution** for managing multiple remote desktop connections — ideal for IT operations, infrastructure teams, and trading environments.

---

## 📌 Future Enhancements

* Session detection and active user monitoring
* Tab-based RDP interface (like mRemoteNG)
* Alerting system for connection failures
* Role-based access and multi-user support
