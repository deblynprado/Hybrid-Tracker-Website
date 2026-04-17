# Hybrid Tracker Website

[![Deploy to Namecheap](https://github.com/deblynprado/Hybrid-Tracker-Website/actions/workflows/deploy.yml/badge.svg)](https://github.com/deblynprado/Hybrid-Tracker-Website/actions/workflows/deploy.yml)

The official landing page for **Hybrid Tracker**, the smartest way to manage fuel, charging, and costs for your Gas, Electric, and Hybrid vehicles.

## ✨ Features

- **Multi-language Support**: Fully localized in English, Portuguese (PT-BR), and Spanish (ES).
- **Responsive Design**: Optimized for all devices with a focus on "Sophisticated Clarity".
- **iCloud Sync Integration Info**: Highlights the app's seamless data synchronization.
- **Detailed Insights**: Showcases the Pro reports and efficiency trends.
- **Interactive UI**: Subtle micro-interactions and smooth transitions using Vanilla JavaScript.

## 🛠 Tech Stack

- **Core**: Pure HTML5 & CSS3 (Vanilla).
- **Logic**: Vanilla JavaScript for animations and interactions.
- **Styling**: Modern CSS with fluid glassmorphism and kinetic typography.
- **Deployment**: GitHub Actions (FTP-Deploy-Action) to Namecheap Hosting.

## 🚀 Deployment

The site is automatically deployed to the production server upon every push to the `main` branch via GitHub Actions.

**Workflow Details:**
- **Trigger**: Push to `main`.
- **Action**: `Deploy to Namecheap` ([deploy.yml](.github/workflows/deploy.yml)).
- **Target**: Namecheap shared hosting via FTP.

## 📂 Project Structure

```text
├── index.html          # English Landing Page
├── pt-br.html          # Portuguese Landing Page
├── es.html             # Spanish Landing Page
├── support.html        # English Support Page
├── pt-br-support.html  # Portuguese Support Page
├── es-support.html     # Spanish Support Page
├── privacy.html        # Privacy Policy
├── css/                # Stylesheets (Vanilla CSS)
├── js/                 # Logic and Scroll Animations
├── assets/             # Global Assets and Brand Icons
└── app-store-screenshots/ # Localized Mockups
```

---

© 2026 Hybrid Tracker. Built with focus on performance and premium aesthetics.
