# HARDCORE

<p align="center">
  <img src="https://img.shields.io/badge/Linux-Terminal%20Only-green?style=for-the-badge&logo=linux&logoColor=white" alt="Linux Terminal Only">
</p>

<p align="center">
  <b>⚡ Linux Terminal - SSH Access from Anywhere via Tailscale</b>
</p>

---

## 📖 What is this?

A **lightweight Linux terminal** running on **GitHub Actions**, accessible via **SSH** through **Tailscale** secure network.

No desktop, no VNC, no bloat. Just pure terminal power.

---

## ✨ Features

- 💻 **Pure Terminal** - SSH access only
- 🔒 **Secure** - Tailscale encrypted tunnel
- 🔗 **No Secrets Needed** - Login via browser link
- ⚡ **Free** - Uses GitHub Actions free tier
- ⏱️ **6 Hours** - Per session
- 🛠️ **Root Access** - Full sudo privileges

---

## 🚀 Quick Start

### Step 1: Fork this Repository
Click the **Fork** button at the top right.

### Step 2: Install Tailscale on Your Device
Download from [tailscale.com/download](https://tailscale.com/download)
- Windows / macOS / Linux / iOS / Android

### Step 3: Run the Workflow
1. Go to **Actions** tab
2. Select **Linux Terminal Only**
3. Click **Run workflow**

### Step 4: Authenticate
1. A login link will appear in the workflow logs:

To authenticate, visit:
https://login.tailscale.com/a/xxxxx
text

2. Open the link in your browser
3. Log in with your Tailscale account

### Step 5: Connect via SSH
Once authenticated, the IP will appear:
```bash
ssh toolboxlap@[TAILSCALE_IP]

Password: admin@123
📋 Default Credentials
Field	Value
Username	toolboxlap
Password	admin@123
Port	22
🔌 Connection Guide
Windows
bash

ssh toolboxlap@100.x.x.x

Or use Putty: Enter IP, port 22, click Open
macOS / Linux
bash

ssh toolboxlap@100.x.x.x

Android / iOS

Use Termius app:

    Host: TAILSCALE_IP

    Port: 22

    User: toolboxlap

    Password: admin@123

💡 What Can You Do?
bash

# Update system
sudo apt-get update && sudo apt-get upgrade -y

# Install tools
sudo apt-get install -y vim htop neofetch git curl

# Check system info
neofetch
htop

# Clone repositories
git clone https://github.com/user/repo.git

# Run scripts
bash script.sh

⚠️ Important Notes

    ⏱️ Session ends after 6 hours maximum

    💾 All data is temporary (lost when session ends)

    🔄 Run the workflow again for a new session

    📁 Save important files before session ends

    🎓 For educational and development purposes

❓ Troubleshooting
"Connection refused"

    Make sure Tailscale is running on your device

    Wait for the IP to appear in logs

    Check if you opened the authentication link

"Permission denied"

    Use correct password: admin@123

    Make sure Caps Lock is off

"Session expired"

    Maximum 6 hours per session

    Run the workflow again

No IP shown

    Did you open the authentication link?

    Check the workflow logs for the login URL

📜 License

MIT License - Free for everyone!
🌟 Credits

Created with ❤️ for the open source community.

If this helped you, give it a ⭐!
<p align="center"> <b>💻 Terminal Anywhere, Anytime!</b> </p> ```

هذا كل شيء! جاهز للنشر. هل تريد تعديل أي جزء؟
