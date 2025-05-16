# Forensix
A powerful and interactive Project built in Python for SOC analysts, incident responders, and threat hunters. This tool enables real-time investigation and threat response on Windows systems using a structured, menu-driven interface.

![Forensix Tool](https://github.com/user-attachments/assets/7e1bd8e6-d517-47dc-b048-31e57158897e)

---

## 🎯 Key Features

🔍 **System Investigation**
- List local user accounts and administrators
- View detailed user information and last login time
- Monitor running processes and their full command lines
- Check startup programs and scheduled tasks

📡 **Network & Connection Analysis**
- Display active TCP connections
- Analyze `netstat -anb` output
- Inspect network adapters and DNS resolution

📝 **Log Review**
- Read security event logs
- View PowerShell operational logs
- Scan for `.ps1` (PowerShell) scripts across user directories

🧠 **Malware Hunting**
- Detect suspicious or hidden processes (keyloggers/backdoors)
- Search for hidden `.exe` files
- Compute SHA256 hash of any file for further analysis

🧬 **Registry Forensics**
- Scan known suspicious registry locations
- Delete specific registry values interactively
- Backup and restore registry easily
- Check for registry-based spyware and persistence mechanisms

🛠️ **Live Threat Response**
- Kill a process by PID
- Delete a file or executable by path
- Disable/enable network adapters
- Review and investigate suspicious scheduled tasks

---

## 📦 How to Use

1. Run the compiled executable `Forensix.exe` (must running as administrator).
2. Navigate the tool using the interactive menu.
3. View results directly in the terminal.
4. Use responsibly within legal and authorized environments only.

---

## 🔧 Requirements

- OS: Windows 10/11 (Admin privileges recommended)
- PowerShell 5.1+
- Python3
---
![Untitled](https://github.com/user-attachments/assets/cdc515c5-9a60-4848-a909-aad84b25c80c)
