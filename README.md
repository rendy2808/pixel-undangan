# 👾 Pixel Wedding Invitation

Undangan pernikahan digital dengan tema pixel art / retro RPG game.
Dibangun dengan pure HTML + CSS + vanilla JS. Tanpa framework, tanpa build tool.

## 🎮 Fitur

- **Loading screen** ala game loading
- **Pixel art couple** (CSS box-shadow)
- **Quest log** — detail acara kayak quest RPG
- **Player stats** — stat lucu pasangan
- **RSVP dialog box** — ala game choice
- **Floating particles** — pixel hearts + pixel lilies (canvas)
- **8-bit music** — wedding march with Web Audio API square wave
- **CRT scanline overlay** — authentic retro feel
- **Responsive** — mobile-friendly
- **Zero dependency** — cuma Google Fonts

## 🚀 Quick Start

```bash
# Buka langsung
open index.html

# Atau serve dengan Python
python3 -m http.server 8000
# Buka http://localhost:8000
```

## 🎨 Customization

Edit langsung di `index.html`:

| Variable | Lokasi |
|---|---|
| Nama couple | `<h1 class="hero-names">` |
| Tanggal | `<div class="hero-date">` |
| Detail acara | `<section class="quest-section">` |
| Player stats | `<section class="dialog-box">` angka di `.stat-value` |
| Warna tema | `:root` CSS variables di `<style>` |

## 🏗️ Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- Canvas API (floating particles)
- Web Audio API (8-bit music)

## 📄 License

MIT — bebas dipake buat undangan nikahan lo!
