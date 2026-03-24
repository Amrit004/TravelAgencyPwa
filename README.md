# ✈️ Wandr — AI Travel Planner PWA

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

**AI-Powered Travel Planning PWA with Offline Support**

[Live Demo](https://wandr.vercel.app) · [View Code](https://github.com/Amrit004/TravelAgencyPwa)

</div>

![Wandr Screenshot](screenshot.png)

---

An AI-powered travel planning progressive web app featuring NLP query processing, budget planning, and full offline capability using Service Workers and IndexedDB.

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **AI Matching Engine** | Client-side recommendation system |
| **NLP Query Processing** | Natural language travel queries |
| **Budget Planning** | Cost estimation and budget tracking |
| **Offline Support** | Full functionality without internet |
| **Data Persistence** | IndexedDB for local storage |
| **PWA Features** | Add to home screen, installable |

## 🧰 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| PWA | Service Workers, Workbox |
| Storage | IndexedDB |
| Offline | Cache API, Background Sync |
| NLP | Custom tokenization and parsing |

## 📱 PWA Capabilities

- Installable on iOS and Android
- Offline-first architecture
- Background data synchronization
- App-like experience

## 📂 Project Structure

```
travelai-pwa/
├── index.html           # Main application
├── sw.js               # Service Worker
├── manifest.json       # PWA manifest
├── css/
│   └── style.css      # Responsive travel theme
├── js/
│   ├── app.js         # Main application logic
│   ├── ai.js          # AI matching engine
│   ├── nlp.js         # Query processing
│   └── db.js          # IndexedDB operations
└── README.md
```

## ⚡ Quick Start

```bash
git clone https://github.com/Amrit004/TravelAgencyPwa.git
cd TravelAgencyPwa
open index.html   # No server required

# For offline/PWA features, use a local server
npx serve .
```

---

<div align="center">

**Built by Amritpal Singh Kaur**

[LinkedIn](https://linkedin.com/in/amritpal-singh-kaur-b54b9a1b1) · [GitHub](https://github.com/Amrit004) · [Portfolio](https://apsk-dev.vercel.app)

</div>
