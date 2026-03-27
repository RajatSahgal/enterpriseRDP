# enterpriseRDP

Enterprise Remote Desktop Manager for Windows.

## What this repository contains

- `EnterpriseRDP.exe` - packaged desktop application
- `_internal/` - runtime dependencies required by the exe
- source files for UI, RDP connection flow, encryption, and database

## Features

- Manage multiple RDP profiles (Add, Edit, Delete)
- Import and Export server list via CSV
- Multi-select connect with per-host launch handling
- Live status and latency checks
- Encrypted credential storage
- Smart dashboard UI with search and filtering

## Run the application

1. Download the repository contents.
2. Keep `EnterpriseRDP.exe` and `_internal/` in the same folder.
3. Double-click `EnterpriseRDP.exe`.

## CSV format for Import

Required headers:

`name,ip,port,username,password`

Example:

```csv
name,ip,port,username,password
server-1,192.168.1.11,3389,username,password
```

## Release notes

- Current packaged build includes custom UI, connection logging, and runtime icon fixes.
- If Windows Explorer still shows a cached icon, use a newly built exe name and refresh icon cache.
