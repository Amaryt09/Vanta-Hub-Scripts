# 🌿 Vanta Hub | Plants vs Brainrots 🧠  

Compact draggable GUI for Roblox with **key system authentication**, **close/minimize functionality**, and a clean, modern design.  
Created by **Vanta**.  

---

## ✨ Features
- 🔑 **Key System**  
  - Keys are validated with format + timestamp.  
  - Supports Standard, Premium (7d/30d), and Lifetime keys.  
  - Keys are auto-saved locally for convenience.  

- 📋 **User Identification**  
  - User ID and Username are displayed.  
  - Copy-to-clipboard functionality for User ID.  

- 🖥️ **GUI Features**  
  - Compact draggable frames (desktop & mobile friendly).  
  - Minimize / Expand functionality.  
  - Close button destroys the GUI.  

- 📂 **Config System**  
  - Keys saved under `VantaHub/` folder in your executor.  
  - Auto-loads valid keys on next run.  

- 🧩 **UI Components** (ready-to-use)  
  - Tabs  
  - Buttons  
  - Sliders  
  - Toggles  

---

## 🚀 How to Use
1. Load the script into your executor.  
2. Enter your **User Key** (get from Discord).  
3. If valid, the main GUI will unlock automatically.  

👉 Use the command in Discord:  
```
!getkey <YourUserID>
```

---

## 🔑 Key Types
- **STA** → Standard (12h)  
- **PRE** → Premium (7 days)  
- **PRM** → Premium (30 days)  
- **LIF** → Lifetime (365 days)  

Expired keys will require regeneration in Discord.  

---

## 📋 Example Key Format
```
VANTA_STA_<UserID>_<Timestamp>_<Hash>
```

---

## 🛠️ File Structure
- `VantaHub/` → Config folder (auto-created).  
- `VantaUserKey_<UserID>.txt` → Saved key file.  

---

## 🌐 Scirod Server
The official **Vanta Hub Server** is your place for:  
- 📢 Updates & Announcements  
- 🎟️ Key Distribution (`!getkey`)  
- 🛠️ Support for Vanta Hub  
- 💬 Community Discussions  

Join us here:  
👉 [Vanta Hub Discord](https://discord.gg/ZFfnhYA3bb)  

---

## ⚠️ Disclaimer
This script is made for **educational purposes only**.  
The creators are not responsible for misuse, bans, or violations of Roblox ToS.  
