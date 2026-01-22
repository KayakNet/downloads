# KayakNet Downloads

Official releases for KayakNet - Anonymous Encrypted Network.

## Quick Install

### Linux (Recommended)
```bash
curl -sL https://raw.githubusercontent.com/KayakNet/downloads/main/releases/linux-gui/install.sh | bash
```

### Windows
```powershell
mkdir C:\KayakNet
Invoke-WebRequest -Uri "https://github.com/KayakNet/downloads/raw/main/releases/windows/kayaknet.exe" -OutFile "C:\KayakNet\kayaknet.exe"
cd C:\KayakNet
.\kayaknet.exe -proxy -bootstrap 203.161.33.237:8080
```

---

## Downloads

### Linux GUI (Recommended)

| Format | Download | Description |
|--------|----------|-------------|
| **Universal Installer** | [install.sh](https://github.com/KayakNet/downloads/raw/main/releases/linux-gui/install.sh) | One-line install for all distros |
| **Debian/Ubuntu** | [kayaknet_1.0.0_amd64.deb](https://github.com/KayakNet/downloads/raw/main/releases/linux-gui/kayaknet_1.0.0_amd64.deb) | .deb package |
| **Script** | [kayaknet-gui](https://github.com/KayakNet/downloads/raw/main/releases/linux-gui/kayaknet-gui) | Python GTK script |

### Linux CLI (Daemon Only)

| Architecture | Download |
|--------------|----------|
| x86_64 (amd64) | [kayakd](https://github.com/KayakNet/downloads/raw/main/releases/linux/kayakd) |

### Windows

| File | Download |
|------|----------|
| Executable | [kayaknet.exe](https://github.com/KayakNet/downloads/raw/main/releases/windows/kayaknet.exe) |

### Android

| File | Download |
|------|----------|
| APK | [kayaknet-latest.apk](https://github.com/KayakNet/downloads/raw/main/releases/android/kayaknet-latest.apk) |

---

## Installation Instructions

### Linux GUI

**Option 1: One-Line Install (All Distros)**
```bash
curl -sL https://raw.githubusercontent.com/KayakNet/downloads/main/releases/linux-gui/install.sh | bash
```

**Option 2: Debian/Ubuntu**
```bash
wget https://github.com/KayakNet/downloads/raw/main/releases/linux-gui/kayaknet_1.0.0_amd64.deb
sudo dpkg -i kayaknet_1.0.0_amd64.deb
sudo apt-get install -f
```

**Option 3: Direct Script**
```bash
wget https://github.com/KayakNet/downloads/raw/main/releases/linux-gui/kayaknet-gui
chmod +x kayaknet-gui
./kayaknet-gui
```

After install, run `kayaknet-gui` or find "KayakNet" in your application menu.

### Windows

```powershell
# Download
mkdir C:\KayakNet
Invoke-WebRequest -Uri "https://github.com/KayakNet/downloads/raw/main/releases/windows/kayaknet.exe" -OutFile "C:\KayakNet\kayaknet.exe"

# Run
cd C:\KayakNet
.\kayaknet.exe -proxy -bootstrap 203.161.33.237:8080
```

Then open browser to: `http://127.0.0.1:8080`

### Android

1. Download [kayaknet-latest.apk](https://github.com/KayakNet/downloads/raw/main/releases/android/kayaknet-latest.apk)
2. Enable "Install from unknown sources" in Settings
3. Open the APK to install
4. Launch KayakNet app

---

## Bootstrap Nodes

| Location | Address |
|----------|---------|
| Primary (US) | `203.161.33.237:8080` |
| Secondary (US) | `144.172.94.195:8080` |

---

## After Installation

| Service | URL |
|---------|-----|
| Web UI | http://127.0.0.1:8080 |
| Chat | http://127.0.0.1:8080/chat |
| Marketplace | http://127.0.0.1:8080/market |
| Domains | http://127.0.0.1:8080/domains |
| HTTP Proxy | 127.0.0.1:8888 |

To access `.kyk` domains, configure your browser to use the proxy at `127.0.0.1:8888`.

---

## Features

- Anonymous P2P network with 3-hop onion routing
- End-to-end encrypted messaging
- Marketplace with Monero/Zcash escrow
- .kyk domain registration
- Traffic analysis resistance
- No servers, no logs

---

## System Requirements

- **Linux**: Ubuntu 20.04+, Debian 11+, Fedora 35+, Arch
- **Windows**: Windows 10/11
- **Android**: Android 8.0+
- **RAM**: 256MB minimum
- **Network**: Any internet connection

---

## Support

- GitHub: https://github.com/KayakNet/KayakNet
- Documentation: https://docs.kayaknet.io

---

**KayakNet** - Anonymous // Encrypted // Unstoppable
