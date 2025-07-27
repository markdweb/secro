
# 🔐 Secro (Secure Chrome Launcher)

**Secro** is a secure and offline Chrome profile launcher with an integrated password lock, auto-lock timer, and PC hardware binding. It is designed to prevent unauthorized access to specific Chrome profiles and help users stay focused by limiting browser usage.

> **Author**: Mark Dhel “Makoy” Villarama  
> **Purpose**: Personal-use project turned powerful privacy tool


<img src="https://github.com/markdweb/secro/blob/master/src/passcode.PNG" width="100%"/>

---

## 📌 Features

### ✅ Hardware Lock
- Binds the app to a specific machine using CPU, motherboard, and disk serials.
- Unauthorized PCs are blocked from accessing the launcher.

### 🔑 Passcode Lock
- Launch Chrome only after entering the correct passcode.
- 3 wrong attempts = 1-minute lockout.

### ⏱️ Auto-Lock Timer
- Automatically closes Chrome after a set period of inactivity.
- Option to extend time via a warning popup before lock triggers.

### ⚠️ Warning Popup
- Notifies user 1 minute before auto-lock.
- User can extend session by 2 mins to 10 hours.

### 📁 Path Configuration
- Set custom Chrome executable path and user profile directory.

### 🔧 Settings
- Change passcode
- Enable/disable auto-lock
- Reset hardware lock (via ALT+P shortcut)

### 📜 Activity Monitoring
- Monitors if Chrome has been closed to return to lock screen.

---

## 📂 How to Use

1. **First Run**  
   Launch `Secro.exe`. It will automatically bind to your PC hardware. You’ll see a green `Authorized` status if successful.

2. **Set Chrome Path & Profile**  
   Go to `Menu > Configure Path`, choose your `chrome.exe`, and create or select a profile folder.

3. **Unlock and Launch Chrome**  
   Input your passcode and click unlock. If correct, Chrome will launch using the selected profile.

4. **Enable Auto-Lock** *(Optional)*  
   Set timer in `Auto-Lock Timer` settings. App will automatically close Chrome after X minutes of inactivity.

5. **Extend Session**  
   If timer hits 1 minute, a warning popup will appear. Choose an extension time to continue the session.

6. **Change Passcode or Reset Lock**  
   Accessible from the menu. To reset hardware lock, press `ALT + P`.

---

## 🛠 Developer Notes

- Language: VB.NET (WinForms)
- App stores all settings using `.NET My.Settings`
- Completely offline – no server or network interaction

---

## 📬 Contact

- GitHub: [github.com/markdweb](https://github.com/markdweb)
- Email: `markdhelvillarama1029@gmail.com`

---

> This project started as a personal tool to build discipline and privacy in browsing habits. Now it’s a complete custom security launcher made with passion and purpose.

