# 🟣 Anti-AFK Ultimate

Anti-AFK Ultimate is a modern, auto-updating Anti-AFK tool for Roblox.  
It features a Windows 11–style UI with purple accents, animated background, system tray mode, and multiple Anti-AFK methods.

---

## ✨ Features

### 🔧 Anti-AFK Modes
- Jump (Spacebar)
- Mouse micro-movement
- Custom key press

### 🎨 Modern Dark Purple UI
- Animated gradient background  
- Smooth fade-in  
- Clean, centered layout  

### 🖥 System Tray Support
- Minimize to tray  
- Restore from tray  
- Exit from tray  

### 🔄 Auto-Update Engine
- Auto checks GitHub Releases  
- Downloads new EXE versions  
- Replaces old version automatically  

### 🧰 Settings
- Always on Top  
- Auto-start with Windows  
- Saves configuration in `config.json`

---

## 📦 Installation

### 👍 Recommended  
Download **Anti-AFK-Ultimate-Installer.exe** from the Releases tab.

The installer creates:
- Desktop shortcut  
- Start Menu folder  
- Program directory in `Program Files`  

---

## 🔧 Build From Source

### Requirements

pip install pynput
pip install pillow
pip install pystray
pip install screeninfo
pip install pyinstaller


### Build EXE
pyinstaller --onefile --windowed --icon icon.ico "anti_afk_ultimate.py"


The EXE will appear inside `/dist/`.

---

🛡 Disclaimer

Anti-AFK Ultimate is a utility tool intended for harmless automations.
Use responsibly and avoid violating Roblox Terms of Service.

---

## 🔄 Auto-Update Format

Your GitHub `update.json` must contain:

```json
{
  "version": "1.0.0",
  "file": "Anti-AFK Ultimate.exe"
}

