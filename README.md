# 💻 Windows CLI – 100 Daily Life Commands

> A curated collection of **100 essential Windows command-line commands (CMD & PowerShell)** for daily life, system management, networking, and development.

[![GitHub stars](https://img.shields.io/github/stars/rajberry/windows-cli-daily-commands?style=social)](https://github.com/rajberry/windows-cli-daily-commands/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/rajberry/windows-cli-daily-commands?style=social)](https://github.com/rajberry/windows-cli-daily-commands/network/members)

---

## 🚀 About

This repository contains **daily-use Windows commands** categorized for easy reference:

- 📁 File & Folder Management  
- 🖥 System Information  
- 🌐 Networking  
- ⚙ PowerShell Essentials  
- 🔐 User & Security  
- 🛠 Developer & Utility

Perfect for beginners, students, and professionals who want to **improve workflow in Windows CLI**.

---

## 📌 Table of Contents

1. [📁 File & Folder Management (1–20)](#-file--folder-management-1-20)  
2. [🖥 System Information (21–35)](#-system-information-21-35)  
3. [🌐 Networking (36–50)](#-networking-36-50)  
4. [⚙ PowerShell Essentials (51–70)](#-powershell-essentials-51-70)  
5. [🔐 User & Security (71–85)](#-user--security-71-85)  
6. [🛠 Developer & Utility (86–100)](#-developer--utility-86-100)

---

## 📁 File & Folder Management (1–20)

| # | Command | Description |
|---|---------|-------------|
| 1 | `dir` | List files and folders |
| 2 | `dir /a` | Show hidden files |
| 3 | `cd foldername` | Enter a folder |
| 4 | `cd ..` | Go back one directory |
| 5 | `cd \` | Go to root directory |
| 6 | `mkdir foldername` | Create a folder |
| 7 | `rmdir foldername` | Remove empty folder |
| 8 | `rmdir /s foldername` | Remove folder with files |
| 9 | `del filename.txt` | Delete a file |
|10 | `copy file1.txt file2.txt` | Copy file |
|11 | `xcopy source destination /E` | Copy folder + files |
|12 | `move file.txt D:\Folder` | Move file |
|13 | `rename old.txt new.txt` | Rename file |
|14 | `tree` | Show folder structure |
|15 | `attrib` | View file attributes |
|16 | `attrib +h file.txt` | Hide a file |
|17 | `attrib -h file.txt` | Unhide a file |
|18 | `type file.txt` | Show file content |
|19 | `more file.txt` | Read text page by page |
|20 | `cls` | Clear screen |

---

## 🖥 System Information (21–35)

| # | Command | Description |
|---|---------|-------------|
|21 | `systeminfo` | Show system details |
|22 | `hostname` | Show computer name |
|23 | `ver` | Show Windows version |
|24 | `whoami` | Show current user |
|25 | `tasklist` | Show running processes |
|26 | `taskkill /IM notepad.exe` | Kill process |
|27 | `wmic cpu get name` | CPU info |
|28 | `wmic memorychip get capacity` | RAM details |
|29 | `wmic diskdrive get size` | Disk size |
|30 | `powercfg /batteryreport` | Battery report |
|31 | `time` | Show current time |
|32 | `date` | Show current date |
|33 | `set` | Show environment vars |
|34 | `echo %USERNAME%` | Show username |
|35 | `exit` | Close CMD |

---

## 🌐 Networking (36–50)

| # | Command | Description |
|---|---------|-------------|
|36 | `ipconfig` | Show IP configuration |
|37 | `ipconfig /all` | Detailed network info |
|38 | `ping google.com` | Check internet connection |
|39 | `tracert google.com` | Trace route |
|40 | `netstat` | Show network connections |
|41 | `netstat -an` | Show all connections |
|42 | `arp -a` | Show ARP table |
|43 | `nslookup google.com` | DNS lookup |
|44 | `getmac` | Show MAC address |
|45 | `netsh wlan show profiles` | List saved Wi-Fi |
|46 | `netsh wlan show profile name="WiFi" key=clear` | Show Wi-Fi password |
|47 | `route print` | Routing table |
|48 | `ftp` | FTP service |
|49 | `telnet` | Telnet |
|50 | `curl https://example.com` | Fetch web data |

---

## ⚙ PowerShell Essentials (51–70)

| # | Command | Description |
|---|---------|-------------|
|51 | `Get-Help` | PowerShell help |
|52 | `Get-Command` | List commands |
|53 | `Get-Process` | Show running processes |
|54 | `Stop-Process -Name notepad` | Stop process |
|55 | `Get-Service` | List services |
|56 | `Start-Service servicename` | Start service |
|57 | `Stop-Service servicename` | Stop service |
|58 | `Get-ChildItem` | List directory |
|59 | `Set-Location path` | Change directory |
|60 | `New-Item file.txt` | Create file |
|61 | `Remove-Item file.txt` | Delete file |
|62 | `Copy-Item a.txt b.txt` | Copy file |
|63 | `Move-Item a.txt D:\Folder` | Move file |
|64 | `Rename-Item old.txt new.txt` | Rename file |
|65 | `Get-Content file.txt` | Read file |
|66 | `Add-Content file.txt "Hello"` | Add text |
|67 | `Clear-Host` | Clear screen |
|68 | `Get-Date` | Show date |
|69 | `Get-History` | Command history |
|70 | `Invoke-WebRequest url` | Download data |

---

## 🔐 User & Security (71–85)

| # | Command | Description |
|---|---------|-------------|
|71 | `net user` | List users |
|72 | `net user username` | User info |
|73 | `net user username password /add` | Create user |
|74 | `net localgroup` | List groups |
|75 | `net localgroup administrators` | Admin users |
|76 | `runas /user:admin cmd` | Run as admin |
|77 | `cipher /e folder` | Encrypt folder |
|78 | `cipher /d folder` | Decrypt folder |
|79 | `sfc /scannow` | System file check |
|80 | `chkdsk` | Disk check |
|81 | `control` | Open Control Panel |
|82 | `gpupdate /force` | Update group policy |
|83 | `shutdown /s /t 0` | Shutdown PC |
|84 | `shutdown /r /t 0` | Restart PC |
|85 | `logoff` | Log out |

---

## 🛠 Developer & Utility (86–100)

| # | Command | Description |
|---|---------|-------------|
|86 | `code .` | Open VS Code |
|87 | `git --version` | Check Git version |
|88 | `git status` | Git status |
|89 | `git clone repo_url` | Clone repository |
|90 | `git add .` | Stage changes |
|91 | `git commit -m "msg"` | Commit |
|92 | `git push` | Push to GitHub |
|93 | `python --version` | Python version |
|94 | `node -v` | Node.js version |
|95 | `npm install` | Install packages |
|96 | `pip install package` | Install Python package |
|97 | `where python` | Show Python path |
|98 | `where git` | Show Git path |
|99 | `history` | Command history |
|100 | `doskey /history` | CMD history |

---

## 🙌 Contribution

Feel free to **fork this repo** and improve it:

- Add **examples** for commands  
- Add **shortcuts** or **tips**  
- Report **issues** or suggest **new commands**

---

⭐ Made with ❤️ by [rajberry](https://github.com/rajberry)

