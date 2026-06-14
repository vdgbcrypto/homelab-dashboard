# Homelab Dashboard

🌸 Anime / 📖 Manga / 🤖 AI Futuristic themed homelab dashboard.

A beautiful single-page dashboard with links to all your homelab services and VMs. Choose between three stunning layout themes.

## Themes

- **🌸 Anime** — Vibrant pink/purple theme with floating particles, glowing cards, and Japanese subtitle
- **📖 Manga** — Black & white manga-style with halftone patterns, bold borders, and comic-book feel
- **🤖 AI Futuristic** — Dark cyberpunk with neon green, glitch effects, scanlines, and grid background

## Features

- **3 layout themes** with one-click switching (saved to localStorage)
- **Service status monitoring** — auto-checks if services are online
- **Responsive design** — works on desktop and mobile
- **Zero dependencies** — pure HTML/CSS/JS, no build step
- **Click any card** to open that service in a new tab

## Services Tracked

| Service | Port | Description |
|---------|------|-------------|
| Docker Worker VM | 192.168.1.83 | 16 vCPU, 7.2GB RAM Debian 13 |
| TrueNAS SCALE | :8000 | Primary NAS & hypervisor |
| OpenLab Dashboard | :8899 | This dashboard |
| ntopng | :3002 | Network traffic analysis |
| Netdata | :19999 | Real-time system metrics |
| AdGuard Home | :8090 | Network-wide ad blocking |
| Portainer | :9443 | Docker container management |
| Vaultwarden | :8080 | Self-hosted password manager |
| Syncthing | :8384 | File synchronization |
| Crypto Trading Bot | :8001 | DOGE/USDT automated trading |

## Setup

Just open `index.html` in any browser. No server required.

To customize services, edit the `services` array and the HTML cards in `index.html`.

## License

MIT
