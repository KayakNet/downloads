# KayakNet Downloads

Official releases for KayakNet - a privacy-first anonymous P2P network.

## Latest Release: v0.1.0

| Platform | Architecture | Download |
|----------|--------------|----------|
| Linux | x86_64 (amd64) | [kayakd-v0.1.0-linux-amd64.tar.gz](https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-linux-amd64.tar.gz) |
| Linux | ARM64 | [kayakd-v0.1.0-linux-arm64.tar.gz](https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-linux-arm64.tar.gz) |
| macOS | x86_64 (Intel) | [kayakd-v0.1.0-darwin-amd64.tar.gz](https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-darwin-amd64.tar.gz) |
| macOS | ARM64 (Apple Silicon) | [kayakd-v0.1.0-darwin-arm64.tar.gz](https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-darwin-arm64.tar.gz) |
| Windows | x86_64 | [kayakd-v0.1.0-windows-amd64.zip](https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-windows-amd64.zip) |

## Quick Start

### Linux/macOS

```bash
# Download
wget https://github.com/KayakNet/downloads/releases/download/v0.1.0/kayakd-v0.1.0-linux-amd64.tar.gz

# Extract
tar -xzf kayakd-v0.1.0-linux-amd64.tar.gz

# Run
./kayakd --bootstrap 203.161.33.237:4242 --proxy --name my-node -i
```

### Windows

1. Download the Windows zip file
2. Extract to a folder
3. Open Command Prompt in that folder
4. Run: `kayakd.exe --bootstrap 203.161.33.237:4242 --proxy --name my-node -i`

## After Starting

1. Configure your browser proxy to `127.0.0.1:8118`
2. Navigate to `http://home.kyk` in your browser
3. You're now on KayakNet!

## Features

- Anonymous P2P network with 3-hop onion routing
- Built-in marketplace (escrow with Monero/Zcash)
- Encrypted chat rooms
- .kyk domain system
- Traffic analysis resistance

## Verify Downloads

Checksums for v0.1.0:

```
SHA256 checksums in checksums.txt included with each release
```

## System Requirements

- **OS**: Linux, macOS, or Windows
- **RAM**: 512MB minimum
- **Network**: Any internet connection
- **Ports**: UDP 4242 (outbound)

## Support

For issues and questions, visit the KayakNet community.

---

KayakNet - Privacy First


