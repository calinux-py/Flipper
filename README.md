# Flipper - Automation & Security Scripts
**Creator**: CaliNux  
**Date**: 6/5/2023-Present

**Programming Language**: Ducky Script  
**Operating System**: Windows

## 📌 Table of Contents
- [Introduction](#introduction)
- [Scripts](#scripts)
    - [Security Scanners](#security-scanners)
    - [System Manipulation](#system-manipulation)
    - [Information Retrieval](#information-retrieval)
    - [Social Engineering](#social-engineering)
- [Disclaimer](#disclaimer)
- [Contribution](#contribution)

## 📜 Introduction

Flipper is a collection of Ducky scripts tailored for automating a myriad of tasks on Windows operating systems. Each script has a distinct function and purpose. Some scripts utilize `Invoke-RestMethod` (irm) to fetch raw PowerShell scripts directly from GitHub. Others employ Memory Execution techniques, allowing for direct execution without downloading a physical file—instead, they run based on a string within a PowerShell script. Additionally, certain scripts are encoded in base64 for enhanced functionality or security.

---

## 📜 Scripts

### Security Scanners
- **GoodUSB**: Performs vulnerability scans and prints results to the user's desktop before running the Windows MRT feature.
- **Scan-Ports**: Scans all open remote ports and saves them in a .txt file. The script then sends this .txt file to a Discord webhook.
  
### System Manipulation
- **WiltSys**: Disables key Windows protection features, such as the firewall.
- **New Admin**: Creates a new admin account with a username and password of your choice.
- **OverlayAttack**: The script downloads a PowerShell script, which, when executed, retrieves and installs Python, pip, and the PIL module. Additionally, it displays an image overlay on the user's computer and disables specific key commands. Default Password is 'pass'.
- **[Base64]Overlay Attack**: Similar to OverlayAttack but downloads a base64-encoded PowerShell script.
- **[M.E. Base64]Overlay Attack**: Fileless Memory Execution: Base64-Encoded Version of the "Overlay Attack" Ducky Script.
- **Inject-EvilTwin**: Creates a new network profile with your preferred SSID, password, and encryption type.
- **[M.E. Base64]DisableUAC**: Remote fileless memory execution script which disables Windows UAC.
- **MemeDecryption**: Uses custom decryption algo to decrypt file encrypted with "meme" encryption
- **[M.E. Base64]Ace-Ventura-Overlay-Ransom**: Forces the target to watch Ace Ventura When Nature Calls while it trolls them with messages.

### Information Retrieval
- **Get-ProductKey**: Retrieves the Windows Product Key from the system on which the script is executed.
- **SysGrab-Win**: Grabs basic system information from Windows and uploads it to Discord using a webhook.
- **BasicRecon**: Retrieves extensive system information including geolocation, public/private IP address, and more.
- **Get-Geo**: Grabs geolocation, hostname, and ISP information from the user and uploads it to a Discord webhook.
- **Get-Pic**: Takes a picture using the integrated webcam and uploads pics to Discord webhook along with private/public/gateway IP and hostname.
- **[M.E. Base64]Get-Pic**: Fileless Memory Execution: Base64-Encoded Version of the "Get-Pic" Ducky Script.
- **[M.E. Base64]Get-PublicIP**: Fileless Memory Execution: Base64-Encoded script which fetches users public IP address.
- **[M.E. Base64]Mother Of All Recons**: Fileless Memory Execution: Base64-Encoded: MOAR is a PowerShell script built to gather an extensive amount of information about a Windows system. This includes but is not limited to, system configurations, network details, browsing history, recently accessed files, and much more. It will then upload this information to a Discord Webhook passed to it.
  
### Social Engineering
- **SmashMouthTroll**: Creates unclosable Smash Mouth troll popup windows.
- **WifiBruteforcePY**: Attempts to bruteforce SSID passed by user using Python.
- **DrivePwn**: Grants access to a user's default Google Drive by passing email as an argument.
- **[Base64]YouTubeTroll**: Downloads Base64 encoded PowerShell script, decodes, and executes it. The script opens the user's default browser and executes a Troll YouTube video.
- **[M.E. Base64]YouTubeTroll**: Fileless Memory Execution: Base64-Encoded Version of the "YouTubeTroll" Ducky Script.
- **Email-Info-Grab**: Navigates to the personal info page of the user's Gmail account, takes a screenshot, and uploads it to a Discord webhook.
- **AdvEmailGrab**: Captures sensitive Gmail information and uploads it to Discord via a webhook.
- **Discord DM&Channel Cap**: Captures screenshots of a user's Discord DMs and channels, then uploads them via a webhook.
- **Encrypt/Decrypt Discord**: Encrypts or Decrypts an entire directory and sends the decryption key to a Discord webhook.

---

## ⚠️ Disclaimer

These scripts are intended for educational and ethical use only. Unauthorized access to computer systems is illegal and punishable by law.
