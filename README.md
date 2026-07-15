# ⚡ HARDCORE

<p align="center">
  <img src="https://img.shields.io/badge/CoreTerm-Terminal%20Anywhere-blue?style=for-the-badge&logo=linux&logoColor=white" alt="CoreTerm">
</p>

<p align="center">
  <b>🚀 Linux Terminal & Desktop - Free, Open Source, Anywhere</b>
</p>

---

## 📖 What is CoreTerm?

**CoreTerm** gives you a **free Linux terminal or desktop** that runs on GitHub Actions.  
Access it from anywhere using **SSH** or **VNC** via **Tailscale**.

---

## ✨ Features

- ⚡ **Free** - Uses GitHub Actions (360 hours/month)
- 🌍 **Access Anywhere** - Via Tailscale secure network
- 💻 **Terminal Mode** - Lightweight SSH access
- 🖥️ **Desktop Mode** - Full XFCE desktop via VNC
- 🔒 **Secure** - Password protected + encrypted tunnel
- ⏱️ **6 Hours** - Per session

---

## 🚀 Quick Start

### 1. Fork this Repository
Click the **Fork** button at the top right.

### 2. Get Tailscale Auth Key
1. Sign up at [tailscale.com](https://tailscale.com)
2. Go to [Settings → Keys](https://login.tailscale.com/admin/settings/keys)
3. Generate an auth key
4. Copy it

### 3. Add Secret to GitHub
1. Go to **Settings → Secrets and variables → Actions**
2. Add new secret: `TAILSCALE_AUTH_KEY`
3. Paste your key

### 4. Run CoreTerm
1. Go to **Actions** tab
2. Select **CoreTerm - Terminal** or **CoreTerm - Desktop**
3. Click **Run workflow**

### 5. Connect
Check the workflow logs for:
- IP address
- Username
- Password

Then connect via SSH or VNC!

---

## 📋 Requirements

- GitHub account
- Tailscale installed on your device
- SSH client or VNC viewer



## 🎯 Connection Examples

### Terminal (SSH):

ssh coreterm@100.x.x.x
 Password: admin@123

🛠️ Tech Stack

    OS: Ubuntu Latest

    Tunnel: Tailscale

    Desktop: XFCE4 + TigerVNC

    CI/CD: GitHub Actions

⚠️ Important Notes

    Sessions last 6 hours maximum

    All data is temporary (lost after session ends)

    Don't store sensitive information

    For educational purposes only

📜 License

MIT License - Free for everyone!
🌟 Credits

Created with ❤️ for the open source community.

If you like this project, give it a ⭐!
<p align="center"> <b>Made with ☕ and 💻 by the CoreTerm Community</b> </p> ```
