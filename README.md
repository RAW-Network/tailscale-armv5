# Tailscale for MikroTik ARMv5 Container

A lightweight, optimized Tailscale container image for legacy MikroTik routers with ARMv5 (32-bit) processors

This project provides a **specialized Docker container** optimized for running **Tailscale** on MikroTik routers with ARMv5 architecture. It's designed for older, low-end MikroTik devices that need secure tailscale connectivity.


---

## Quick Start

### Image Location
**Registry:** `https://ghcr.io`

**Pull command:**
```bash
docker pull ghcr.io/raw-network/tailscale-armv5:latest
```

### In MikroTik RouterOS
```
ghcr.io/raw-network/tailscale-armv5:latest
```

---

## ⚠️ Important: Configuration & Setup

**For complete installation and configuration instructions**, please refer to the original project documentation:

### 📌 Original Repository (Fluent Networks)
- **Repository**: [Tailscale Mikrotik](https://github.com/Fluent-networks/tailscale-mikrotik)
- **Full Setup Guide**: [github.com/Fluent-networks/tailscale-mikrotik](https://github.com/Fluent-networks/tailscale-mikrotik#readme)

**Follow the original documentation for:**
- RouterOS container commands
- Virtual ethernet (veth) & bridge configuration  
- Routing setup & networking
- Environment variables & secrets
- Volume mounts & persistence
- Troubleshooting & debugging

---

## About This Repo

This repository provides an **ARMv5-optimized build** based on the original Fluent Networks project. It includes:

- Optimized Golang build chain for ARMv5 architecture
- Automated CI/CD pipeline for regular builds
- Published on GitHub Container Registry (GHCR)
- Same configuration approach as the original project

---

## Credits

This project is an adaptation of and builds upon:
**[Fluent Networks](https://github.com/Fluent-networks/tailscale-mikrotik)**

All credit for the original design and approach goes to the Fluent Networks.

---

**🚀 Enjoy secure, lightweight networking on your ARMv5 MikroTik device!**