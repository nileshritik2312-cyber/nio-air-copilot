# nio-air-copilo# Nio Air Copilot

**Offline-Ready Winter Smog, Indoor Air Quality (IAQ) & Community Action Hub**

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-22c55e?style=for-the-badge)](https://nileshritik2312-cyber.github.io/nio-air-copilot/)
[![PWA Ready](https://img.shields.io/badge/PWA-Offline_Capable-38bdf8?style=for-the-badge)](https://nileshritik2312-cyber.github.io/nio-air-copilot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-eab308?style=for-the-badge)](LICENSE)

**Live Application:** [https://nileshritik2312-cyber.github.io/nio-air-copilot/](https://nileshritik2312-cyber.github.io/nio-air-copilot/)

---

## Problem Statement

Severe winter smog and temperature inversion across urban and semi-urban India trap hazardous PM2.5 near ground level, disproportionately affecting low-income households, seniors, children, security guards, and unhoused citizens. Most air-quality tools only display raw numbers without actionable, zero-cost indoor protection steps, offline reliability, or community-level coordination.

**Nio Air Copilot** turns Graded Response Action Plan (GRAP) air-quality alerts into immediate, offline-capable household protocols, collective RWA/society bulk-buying, night-shelter routing, and civic pollution reporting.

---

## Key Features

1. **GRAP Stage I–IV Protocol Banner:** Dynamically adapts emergency guidance across Moderate (`AQI 110`), Poor (`AQI 245`), Severe (`AQI 385`), and Emergency (`AQI 465`) profiles.
2. **Safe Ventilation Window & 15-Minute Rapid Flush Timer:** Tracks the afternoon solar dispersion window (`1:00 PM – 4:00 PM`) with a live countdown and built-in 15-minute air-flush timer so households ventilate only when outdoor smog dips.
3. **Zero-Cost Instant IAQ Checklist:** Actionable indoor PM2.5 reduction protocols (wet-mopping instead of dry sweeping, damp towel door-gap sealing, kitchen exhaust verification, and natural bio-filter placement).
4. **Society & RWA Group-Buy Calculator:** Calculates tiered wholesale discounts (up to 30%) when apartments pool orders for True HEPA H13 purifiers, N95 family packs, and oil-free electric heaters for night security guards, alongside a Shared Senior Clean-Air Lounge blueprint.
5. **Unhoused Night Shelter & NCAP/GRAP SOS Hub:** Routes vulnerable street sleepers to verified night shelters (*Rain Baseras*), provides one-tap access to the CPCB SAMEER helpline (`1800-11-0031`), and copies ready-to-share WhatsApp community alerts.
6. **Civic Hazard Reporting & Zero-Budget Clean Points:** Lets residents log open garbage burning or uncovered construction dust, earn persistent `localStorage` Clean Points, unlock civic badges (*Air Scout* to *Clean Air Champion*), and climb a live ward leaderboard without cash payouts.

---

## Architecture & Offline PWA Design

Nio Air Copilot is built as a zero-dependency, lightweight Progressive Web App (PWA) designed to run smoothly on entry-level smartphones and older hardware even during network outages:

```text
nio-air-copilot/
├── index.html      # Complete single-file UI, responsive CSS, and offline state engine
├── manifest.json   # Web App Manifest for standalone mobile/desktop installation
├── sw.js           # Service Worker caching core assets for full offline operation
├── LICENSE         # MIT Open-Source License
└── README.md       # Project documentationt
