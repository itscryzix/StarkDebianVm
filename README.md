# Stark Coder - Debian VM Setup & VPS Manager

<div align="center">

![Version](https://img.shields.io/badge/version-2.5-blue)
![License](https://img.shields.io/badge/license-Copyright-StarkCoder)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20WSL2-green)

</div>

## 📌 About

**Stark Coder** ek automated server management toolkit hai jo VPS setup, Ubuntu/Debian VMs, aur dashboard installation ko streamline karta hai. Yeh scripts Linux servers ya WSL2 environment mein run hoti hain.

---

## 🚀 Features

- ✅ **IDX VM Setup** — dev.nix + script.sh auto-configuration
- ✅ **Ubuntu VNC Docker** — Web-accessible Ubuntu VM with VNC
- ✅ **Pterodactyl Panel** — Game server panel installer
- ✅ **Playit Tunnel** — Secure tunnel service
- ✅ **ChunkDash** — Stark Coder's custom Feastic hosting dashboard

---

## 📁 Files

| File | Description |
|------|-------------|
| `install.sh` | Main menu — Install all tools |
| `ubuntu.sh` | Ubuntu VNC Docker runner |
| `script.sh` | Debian 11 VM configuration |
| `dev.nix` | Nix-based IDX environment config |
| `installer.sh` | Full VPS manager (advanced) |

---

## ⚙️ Requirements

- Linux OS (Ubuntu 20.04+, Debian 11+)
- Bash 5.0+
- Root / Sudo access
- WSL2 supported (Windows users ke liye)

---

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/itscryzix/StarkDebianVm.git
cd StarkDebianVm

# Make executable
chmod +x *.sh

# Run the installer
./install.sh
```

Ya direct run karein:

```bash
bash install.sh
```

---

## 🎯 Menu Options

```
================================================
    WELCOME TO Stark Coder Auto Setup
================================================

Choose an option:
  1) Setup IDX VM (dev.nix + script.sh)
  2) Run Ubuntu VNC Docker
  3) Install Pterodactyl Panel + Node
  4) Install Playit
  5) Stark Coder's Custom Dash ChunkDash
  0) Exit
```

---

## 📄 Copyright

> **Copyright © 2026 Stark Coder.** All Rights Reserved.
>
> This software is proprietary and confidential. Unauthorized copying, distribution, or modification is strictly prohibited.
>
> Developed & maintained by **Stark Coder**.

---

## 🤝 Contributing

Contributions welcome! Please read CONTRIBUTING.md before submitting PRs.

---

## 📞 Support

For issues or questions:
- Open a GitHub Issue
- Contact: [Your Email/Discord]

---

<div align="center">

Made with ❤️ by **Stark Coder**

</div>
