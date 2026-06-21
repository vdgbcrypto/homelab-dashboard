# 🌸 Homelab Dashboard — Anime / Manga / Futuristic Themes

A beautifully themed homelab dashboard with three visual styles. Built as a single-page application with zero external dependencies.

![Anime Theme](https://img.shields.io/badge/theme-🌸%20Anime-pink)
![Manga Theme](https://img.shields.io/badge/theme-📖%20Manga-amber)
![Futuristic Theme](https://img.shields.io/badge/theme-🤖%20Futuristic-cyan)

## Themes

| Theme | Style | Best For |
|---|---|---|
| **Anime** 🌸 | Pink/purple gradients, floating particles, glowing effects | Dark rooms, RGB setups |
| **Manga** 📖 | Paper-like light background, halftone patterns, bold borders | Bright environments, readability |
| **Futuristic** 🤖 | Dark cyan grid, scanlines, glitch effects, monospace | Terminal lovers, cyberpunk vibes |

## Quick Start

```bash
# Python
python3 -m http.server 8000

# Docker
docker run -d --name homelab-dashboard -p 8000:8000 \
  -v $(pwd):/usr/share/nginx/html:ro \
  nginx:alpine
```

## Features

- **Zero dependencies** — pure HTML/CSS/JS in a single file
- **Theme switcher** — instant switching with localStorage persistence
- **Password gate** — client-side auth (use server-side auth for production)
- **Service cards** — quick links to all your homelab services
- **Responsive** — works on desktop and mobile

## Configuration

Edit the `SERVICES` array in the HTML to add your services:

```javascript
const SERVICES = [
  { name: 'Grafana', icon: '📊', desc: 'Metrics & dashboards', url: 'https://grafana.example.com' },
  { name: 'TrueNAS', icon: '🖥️', desc: 'Storage management', url: 'https://truenas.example.com' },
  // ... add your services
];
```

## Browser Compatibility

- Chrome / Edge / Firefox / Safari (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## License

MIT License — see [LICENSE](LICENSE) for details.
