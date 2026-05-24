# 🍏 Swift Portfolio Showcase – LocalMind & Friends

A modern, dark‑theme HTML portfolio that presents 11 cutting‑edge Swift projects from the [karkadi](https://github.com/karkadi) ecosystem.  
The page aggregates iOS, macOS, watchOS, server‑side Swift, FPGA, and AI‑driven apps – all built with **Swift 6**, **The Composable Architecture (TCA)**, **Metal**, **RealityKit**, and modern concurrency.

👉 **Live preview**: [GitHub Pages link will appear here after deployment]

![Preview](https://img.shields.io/badge/UI-Dark_Blue_Theme-0a0f1f?style=for-the-badge)  
![Swift](https://img.shields.io/badge/Swift-6.0-orange?style=for-the-badge)  
![TCA](https://img.shields.io/badge/Architecture-TCA-purple?style=for-the-badge)

---

## 📦 Projects Featured

| Project                  | Platform           | Key Technologies                                                |
| ------------------------ | ------------------ | --------------------------------------------------------------- |
| **LocalMind**            | iOS / iPad / macOS | Offline AI, Apple Intelligence, TCA, SQLite, iCloud Sync, LaTeX |
| **Tetris AI**            | iPhone             | Neural Network, Genetic Algorithm, TCA, 94% test coverage       |
| **FalloutPipBoy**        | watchOS            | HealthKit, 3 watch faces, Swift Concurrency                     |
| **StreamingAudioPlayer** | iOS                | Metal shaders, AVFoundation, SwiftData, TCA                     |
| **Marvel Dusting**       | iOS (SpriteKit)    | Particle disintegration, async/await, layer effects             |
| **TM1638 FPGA**          | FPGA / Verilog     | 8‑digit 7‑segment driver, key scanning, Quartus                 |
| **WritingPen**           | iOS / macOS        | Handwriting animation, Core Text, SVG support                   |
| **SpaceX Explorer**      | iOS + Vapor        | Full‑stack Swift, GraphQL, Fluent, Apollo iOS                   |
| **WalkingRecords**       | iOS                | GPS tracking, MapKit, Metal animation, GPX export               |
| **Abyssal‑6**            | iOS                | RealityKit 3D gallery, text adventure, i18n                     |
| **Rick and Morty**       | iOS                | REST API, SwiftData, search/filter, async image loading         |

Each card includes **screenshot references** (from the original `ScreenShoots/` folders) and a clickable GitHub link (update `href` with actual repo URLs).

---

## 🚀 Getting Started (for your own fork)

This repository contains a single static `index.html` file that presents the portfolio.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 2. Customise the links

Edit the `index.html` file: replace every `#` inside the `.repo-link` `href` attributes with the actual GitHub URLs of the corresponding repositories.

Example:

```html
<div class="card-footer">
  <a href="https://github.com/karkadi/LocalMind" class="repo-link"
    >Explore LocalMind</a
  >
</div>
```

### 3. (Optional) Add real screenshots

If you want the screenshot badges to link to actual images, you can wrap the `.screenshot-thumb` spans with `<a>` tags pointing to your assets.

### 4. View locally

Open `index.html` in any modern browser – no build step required.

### 5. Deploy to GitHub Pages

- Go to your repository **Settings → Pages**
- Set source to `main` branch, root folder (`/`)
- Your portfolio will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

---

## 🎨 Design & Theme

- **Deep navy / dark blue** colour scheme (`#0a0f1f` background, `#111827` cards)
- Responsive grid layout (auto‑fill, min‑width 360px)
- Smooth hover effects and gradient accents
- System‑adaptive reference to light/dark screenshots (icons only)
- Font Awesome 6 + Google Fonts (Inter)

---

## 📄 License

This portfolio page is provided under the **MIT License**.  
The underlying projects remain under their respective licenses (mostly MIT, educational for Abyssal‑6).

See the `LICENSE` file in this repository (if included) or refer to each original project’s license.

---

## 🙌 Credits

- All projects developed by [karkadi](https://github.com/karkadi)
- Icons by [Font Awesome](https://fontawesome.com/)
- Inspiration from Apple’s Human Interface Guidelines & Swift community

---

**Built with ❤️ to showcase the power of Swift 6 across the entire Apple ecosystem.**
