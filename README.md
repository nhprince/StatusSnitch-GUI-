# 📡 StatusSnitch — Messenger Activity Tracker (EXE Version)

**StatusSnitch** is a Windows desktop application that lets you monitor the **online/offline activity status** of any Facebook Messenger user in real time. Designed for privacy-aware users, it offers a sleek interface, system tray support, and automatic log saving — all in a single executable file.

> ⚠️ This app is for personal and ethical use only. Never track someone without their knowledge or consent.

---

## 🧩 Features

- 🟢 **Live Status Detection**  
  Instantly detects whether your target is *Active now*, *Recently active*, or *Inactive*.

- 🎯 **Target Username Input**  
  Just enter their Messenger username (from profile URL) — no coding required.

- 🔐 **Secure Login**  
  Facebook credentials are entered securely at runtime and **never stored**.

- 🧾 **Log Viewer**  
  Real-time status changes are recorded and saved to local text files.

- ⚠️ **CAPTCHA/2FA Detection**  
  Notifies you if login is blocked by Facebook’s security checks.

- 🛑 **System Tray Mode**  
  Minimizes to tray to let the app run silently in the background.

- 💾 **Auto Log Saving**  
  Monitoring logs are saved with timestamps for review or export.

---

## 🖥️ How to Use

1. **Download and open** the `StatusSnitch.exe` file (no installation required).
2. On the login screen:
   - Enter your **Facebook email/phone** and password.
   - Input the **Messenger username** of the person you want to track.
3. Click **Start Monitoring**.
4. The app will:
   - Log in to Facebook Messenger
   - Open a conversation with the target
   - Begin tracking their status changes
5. Logs will appear live in the interface and be saved automatically.

---

## 📁 Log Files

- Saved in a `logs/` folder next to the EXE file.
- Format:
  ```
  logs/username_YYYYMMDD_HHMM.txt
  ```
- Each file includes:
  ```
  [15:34:02] Status changed: Active now
  [15:50:27] Status changed: Active 10 minutes ago
  ```

---

## 🔐 Notes on Privacy & Security

- Your Facebook login is used **only for local automation**. No credentials are stored.
- For safety, use a **secondary Facebook account** to avoid triggering Facebook’s security systems.
- If CAPTCHA or 2FA is detected, you’ll be notified to log in manually and re-authenticate.

---

## ⚠️ Disclaimer

> This tool is intended strictly for **educational and personal ethical use**.  
> The developer is not responsible for any misuse or policy violations.  
> Tracking someone without their consent may violate privacy laws or platform rules.

---

## 🧑‍💻 Developed By

**NH Prince Pradhan**  
🛡️ Ethical Hacker | 🐍 Python Developer | 🎓 Student  
🔐 Hacker Alias: `Nihal Cipher`  
📫 GitHub: [NH Prince Pradhan](https://github.com/nhprince)

---

Stay safe. Stay ethical.  
**— StatusSnitch Team**
