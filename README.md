# DLL Activity Monitor @Sleepy 2026

> Source code is not fully public yet.

A lightweight Windows desktop application for monitoring DLL/module activity in real time.

DLL Activity Monitor allows you to attach to a running process using its PID, inspect loaded modules, track newly loaded DLLs during runtime, and maintain a persistent activity timeline — all inside a clean and responsive interface.

Designed for diagnostics, visibility, and runtime analysis using documented Windows APIs.

## Features

### Monitoring

* 🔍 Attach to any running process by PID
* 📦 View loaded DLL modules and full file paths
* 🆕 Detect newly loaded modules in real time
* ⏱️ Live **Visible For** tracking
* 📈 Activity timeline with timestamps
* 🔄 Persistent monitoring sessions
* 🎯 Optional auto attach for Minecraft

### Analysis

* 🔎 Search and filter modules
* 🧾 View module signer / digital signature
* 🔐 Generate SHA256 hashes
* ⚠️ Module risk scoring
* 🚫 Ignore Windows/System DLLs
* 📊 Activity graphs and statistics

### Export

* 📁 Export discovered DLL files from disk
* 💾 Save monitoring sessions
* 📄 Export session history and module data

### UI

* 🌙 Clean modern dark interface
* ⚡ Fast refresh without resetting data
* 📌 Persistent module timestamps
* 🧭 Organized tabs and live status indicators

## Built With

* C++17
* ImGui
* DirectX 11
* Windows ToolHelp API
* std::filesystem

## Use Cases

* Software debugging
* Module inspection
* Runtime diagnostics
* Development workflows
* Learning and experimentation

## Notes

* Uses documented Windows APIs
* Designed for monitoring and diagnostics
* No process modification
* No memory dumping

---

Built by @Sleepy
