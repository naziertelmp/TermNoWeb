# 💻 WebTerm - Linux Terminal in Your Browser

<p align="center">
  <img src="https://img.shields.io/badge/WebTerm-Browser%20Terminal-blue?style=for-the-badge&logo=linux&logoColor=white" alt="WebTerm">
</p>

<p align="center">
  <b>⚡ Free Linux Terminal - Access from Any Browser, No VPN Required</b>
</p>

---

## 📖 What is WebTerm?

**WebTerm** gives you a **free Linux terminal** running on GitHub Actions, accessible directly from your **phone or desktop browser** - no VPN, no apps, no registration required.

---

## ✨ Features

- 🌐 **Browser Only** - No apps, no VPN
- 📱 **Mobile Friendly** - Works on phone browsers
- 🔒 **Secure** - Cloudflare encrypted tunnel
- ⚡ **Free** - GitHub Actions free tier
- ⏱️ **6 Hours** - Per session
- 🛠️ **Root Access** - Full sudo privileges
- 🔗 **Instant Link** - Get a URL and connect

---

## 🚀 Quick Start

### Step 1: Fork this Repository
Click the **Fork** button.

### Step 2: Run the Workflow
1. Go to **Actions** → **WebTerm**
2. Click **Run workflow**

### Step 3: Get Your Link
Wait ~30 seconds, then check the logs for:
```
https://xxxxx.trycloudflare.com
```

### Step 4: Open in Browser
Open the link on **any device** - phone, tablet, or computer.

---

## 📱 Mobile Usage

1. Open the link in your phone browser
2. Terminal appears instantly
3. Use on-screen keyboard
4. Full Linux experience

---

## 💻 What You Can Do

```bash
# System info
neofetch
htop

# Install tools
sudo apt-get install -y vim git python3

# Code
vim hello.c
gcc hello.c -o hello
./hello

# Browse files
ls -la
cd /home
```

---

## 🎯 How It Works

```
┌─────────────────────────────────┐
│         GitHub Actions          │
│  ┌───────────────────────────┐  │
│  │     Ubuntu + ttyd         │  │
│  │     Terminal on :3000     │  │
│  └───────────────────────────┘  │
│              │                  │
│         Cloudflare              │
│         Tunnel                  │
│              │                  │
└──────────────┼──────────────────┘
               │
      ┌────────┴────────┐
      │   Your Browser   │
      │   Phone / PC     │
      └─────────────────┘
```

---

## ⚠️ Important Notes

- ⏱️ Session ends after **6 hours**
- 💾 All data is **temporary**
- 🔗 Link changes each session
- 🎓 For educational purposes
- 📵 Don't abuse - respect GitHub's limits

---

## 🛠️ Tech Stack

- **OS**: Ubuntu
- **Terminal**: ttyd
- **Tunnel**: Cloudflare Tunnel
- **CI/CD**: GitHub Actions

---

## 🔒 Security

- End-to-end encrypted via Cloudflare
- One-time links per session
- No ports exposed
- No passwords transmitted

---

## 📱 Tested On

- ✅ Chrome Android
- ✅ Safari iOS
- ✅ Chrome Desktop
- ✅ Firefox
- ✅ Edge

---

## 📜 License

MIT License - Free for everyone!

---

<p align="center">
  <b>🌐 Terminal Anywhere, No Apps Needed!</b>
</p>
