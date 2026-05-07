# Sunflower 🌻

**A mobile app that turns open data into accessible, actionable insights — built to improve data literacy for everyone.**

*Benedetta Marchesin, Gabriel Vincenzi, Natasha Litherland*
*[sunflower-data.com](https://sunflower-data.com)*

---

## What is Sunflower?

Open data is everywhere — but it's largely inaccessible to anyone without a technical background. Government statistics, economic indicators, and public datasets sit in formats and portals that most people can't navigate, let alone act on.

Sunflower bridges that gap. It's a mobile-first platform that takes curated datasets from trusted institutional sources and presents them through an intuitive interface designed for exploration, learning, and discussion — no data science background required.

The goal is not just to display data, but to build genuine data literacy: the ability to understand what numbers mean, interrogate where they come from, and use them to form better-informed views.

---

## Background

Sunflower started in May 2025 as an international university initiative. In June 2025, the project placed at the podium of the Council of Europe's *Democracy's Firewall* hackathon, competing against over 250 teams. In February 2026, the team was accepted into the spring cohort of People Powered and Coglobal's Democratic Innovations Accelerator. As of May 2026, the team is seeking funding and conducting a pilot phase of user testing ahead of launch.

---

## Features

**Go Deep** — Explore datasets in detail with intuitive analysis tools. Drill into the numbers, compare across time and geography, and surface insights that aren't obvious from headlines.

**Learn** — Build lasting knowledge through gamified, educational interactions with data. The platform guides users toward critical thinking rather than passive consumption.

**Engage** — Participate in a community layer where users can request new datasets, discuss findings, and share interpretations — making the platform collectively more relevant over time.

**Curated Content** — Data is sourced from established, reliable institutions (see below), not scraped or unverified. Curation decisions prioritize clarity and relevance.

**User-Friendly Interface** — Designed for general audiences. No prior knowledge of statistics or data science is assumed.

---

## Data Sources

| Source | Description |
|---|---|
| [ISTAT](https://www.istat.it) | Italian national statistical office |
| [Eurostat](https://ec.europa.eu/eurostat) | European Union statistical data |
| [OECD](https://data.oecd.org) | Global economic and social data |
| [World Bank](https://data.worldbank.org) | International development data |
| Community Requests | User-suggested datasets, reviewed before inclusion |

---

## Tech Stack

Built with **React Native** via **Expo**, styled with **NativeWind** (Tailwind CSS for React Native), and written in **TypeScript**.

```
├── app/               # Expo Router screens and navigation
├── components/        # Reusable UI components
├── services/          # Data fetching and API logic
├── interfaces/        # TypeScript interfaces
├── types/             # Shared type definitions
├── constants/         # App-wide constants
├── hooks/             # Custom React hooks
├── assets/            # Images, fonts, icons
├── istatTools.py      # Python utility for ISTAT data processing
├── test.ipynb         # Data exploration notebook
├── app.json           # Expo configuration
├── tailwind.config.js # NativeWind / Tailwind configuration
└── tsconfig.json      # TypeScript configuration
```

---

## Getting Started

**Prerequisites**
- Node.js (LTS recommended)
- npm or yarn
- Expo CLI: `npm install -g expo-cli`
- For iOS: Xcode (macOS only) or the Expo Go app
- For Android: Android Studio or the Expo Go app

**Install dependencies**
```bash
npm install
```

**Start the development server**
```bash
npx expo start
```

Then scan the QR code with the Expo Go app on your device, or press `i` for iOS simulator / `a` for Android emulator.

**Data tools (Python)**

The `istatTools.py` script and `test.ipynb` notebook are used for processing and exploring ISTAT datasets before they are integrated into the app. They require Python 3 with standard data libraries (`pandas`, `requests`).

---

## Philosophy

Sunflower is built around the belief that data literacy is a civic skill — not just a technical one. As open data becomes more available, the gap between what institutions publish and what citizens can actually use grows wider. Sunflower is designed to close that gap, not by simplifying data, but by making the tools to understand it genuinely accessible.

The platform is deliberately non-partisan. It presents data from institutional sources with full attribution and does not editorialize beyond facilitating exploration and discussion.

---

## Status

The app is currently in a **pilot phase** of user testing. The team is actively seeking funding and partnerships to support launch.

If you're interested in collaborating, contributing datasets, or supporting the project, get in touch:

- natasha@sunflower-data.com
- benedetta@sunflower-data.com
- gabriel@sunflower-data.com
- [sunflower-data.com](https://sunflower-data.com)

---

## License

© 2025–2026 Sunflower. All rights reserved. Contact the team for licensing inquiries.
