# 🤖 Proto-Hub

> **A high-tech, ad-free cyberware and app portal built by a Protogen developer.**

[![Live Site](https://img.shields.io/badge/Live_Site-Proto--Hub-ff2a4b?style=for-the-badge&logo=github&logoColor=white)](https://astrodev-lab.github.io/Proto-Hub/)
[![Status](https://img.shields.io/badge/Server_Status-Active-brightgreen?style=for-the-badge)](https://astrodev-lab.github.io/Proto-Hub/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🌐 Live Website

Access the official web app directly at:  
👉 **[https://astrodev-lab.github.io/Proto-Hub/](https://astrodev-lab.github.io/Proto-Hub/)**

---

## ✨ Features

- 🚀 **Ad-Free & Direct Downloads:** No countdown timers, paywalls, or third-party redirect ads.
- ⚡ **High-Tech Aesthetic:** Cyber-red and obsidian dark-mode interface powered by modern CSS animations.
- 🃏 **Interactive 3D Cards:** Lift-and-flip information cards showcasing developer and system architecture specs.
- 🔍 **Live Search Filter:** Dynamic app searching built right into the App Store catalog.
- 📦 **GitHub Releases Infrastructure:** Fast binary distribution hosted straight from GitHub infrastructure.

---

## 📁 Repository Structure

```text
Proto-Hub/
├── index.html     # Cyberpunk Landing Page with 3D Flip Cards & CTA Button
├── apps.html      # App Store Catalog & Direct Download Page
├── avatar.png     # Protogen Avatar Icon (Squircle Header Branding)
└── README.md      # Repository Documentation
```

---

## 🚀 How to Add New Apps

1. Go to **Releases** → **Draft a new release**.
2. Tag your version (e.g., `v1.0.0`) and attach your compiled binary (`.exe`, `.zip`, `.apk`, etc.).
3. Publish the release and copy the direct download link.
4. Edit `apps.html` in this repo and paste the link into the desired app card's `href` attribute:

```html
<a href="https://github.com/astrodev-lab/Proto-Hub/releases/download/v1.0.0/your-app.zip" class="btn-download" download>
  Download (.zip)
</a>
```

---

<p align="center">
  <i>Maintained with high-tech visor energy by AstroDev • Powered by GitHub Pages</i>
</p>