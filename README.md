<div align="center">

<br/>

```
  ₣  Flowly
```

### Personal Finance Tracker — PWA

**Track spending · Manage budgets · Visualize your financial health**

[![Landing Page](https://img.shields.io/badge/Landing_Page-kayo--isle69.github.io%2Fflowly-c4a365?style=flat-square&logo=github)](https://kayo-isle69.github.io/flowly)
[![Launch App](https://img.shields.io/badge/Launch_App-Open_Flowly-4eca8b?style=flat-square&logo=pwa)](https://kayo-isle69.github.io/flowly/app.html)
[![License](https://img.shields.io/badge/License-MIT-5c9be0?style=flat-square)](LICENSE)
[![Made by](https://img.shields.io/badge/Made_by-Komino__dev-c4a365?style=flat-square)](https://github.com/kayo-isle69)

<br/>

🌐 **[Landing Page](https://kayo-isle69.github.io/flowly)** &nbsp;·&nbsp; ⚡ **[Launch App](https://kayo-isle69.github.io/flowly/app.html)**

<br/>

</div>

---

## What Is Flowly?

Flowly is a lightweight, installable **Progressive Web App** for personal finance tracking. No account needed, no server, no cloud — all data lives on your device via `localStorage`. Open it in a browser, install it on your phone like a native app, and track your money anywhere — even offline.

It is the **4th app** in the open-source web app series by [Komino_dev](https://github.com/kayo-isle69).

---

## Features

| Feature | Details |
|---|---|
| 📊 **Visual Analytics** | Monthly pie chart (spending breakdown) + 6-month bar trend chart via Chart.js |
| 💸 **Transaction Management** | Add, edit, delete income & expense entries with categories and dates |
| 🔔 **Budget Alerts** | Set monthly limits per category — visual warnings at 80% and 100% |
| 🌍 **Multi-Currency** | USD, EUR, DZD, GBP, JPY, MAD — switch anytime in settings |
| 📤 **One-Click Export** | Download all transaction history as **CSV** or **JSON** |
| 📱 **PWA — Installable** | Add to home screen, loads instantly, works fully offline |
| 🌙 **Dark / Light Mode** | Toggle from nav bar or settings page |
| 🔍 **Search & Filter** | Filter by income/expense, search by name, grouped by date |
| 🗂️ **8 Categories** | Food, Housing, Transport, Shopping, Health, Travel, Salary, Other |
| 💾 **100% Local** | No backend, no account, no tracking — your data stays on your device |

---

## Pages

```
index.html         Landing page (EN / AR toggle, dark/light, hero preview)
app.html           Dashboard (balance, charts, recent transactions)
transactions.html  Full transaction list (search, filter, edit, delete)
budget.html        Budget limits with animated progress bars + alerts
settings.html      Name, currency, theme, export CSV/JSON, clear data
```

---

## File Structure

```
flowly/
├── index.html          ← Landing page
├── app.html            ← Dashboard
├── transactions.html   ← Transaction manager
├── budget.html         ← Budget tracker
├── settings.html       ← App settings & export
├── style.css           ← Shared design system (CSS variables, components)
├── app.js              ← Core logic (localStorage, categories, utilities)
├── charts.js           ← Chart.js rendering (pie + bar)
├── sw.js               ← Service Worker (offline caching)
├── manifest.json       ← PWA manifest (name, icons, theme)
└── README.md
```

---

## Tech Stack

- **Frontend** — Vanilla HTML, CSS, JavaScript (zero frameworks)
- **Charts** — [Chart.js 4.4](https://www.chartjs.org/) via CDN
- **Fonts** — Cormorant Garamond + Syne + DM Mono (Google Fonts)
- **Storage** — Browser `localStorage` (no backend required)
- **PWA** — `manifest.json` + Service Worker (`sw.js`)
- **Hosting** — GitHub Pages

---

## Roadmap

### v1.0 — Current (Prototype)
- [x] Dashboard with charts
- [x] Transaction CRUD
- [x] Budget limits & alerts
- [x] Multi-currency support
- [x] CSV / JSON export
- [x] PWA manifest + Service Worker
- [x] Dark / Light mode
- [x] EN / AR landing page

### v1.1 — Planned
- [ ] Recurring transactions (rent, salary auto-entry)
- [ ] Category customization (add/rename/color)
- [ ] Month picker on dashboard (navigate past months)
- [ ] Notes field on transactions

### v2.0 — Future (with Backend)
- [ ] FastAPI backend (user accounts, cloud sync)
- [ ] Multi-device sync
- [ ] PDF export with summary report
- [ ] Budget history across months
- [ ] Telegram bot integration for quick entries

---

## The App Series

| # | App | Repo | Status |
|---|---|---|---|
| 1 | **Brackets** — Tournament bracket manager | [bracket](https://github.com/kayo-isle69/bracket) | ✅ Live |
| 2 | *(coming soon)* | — | 🔜 |
| 3 | *(coming soon)* | — | 🔜 |
| 4 | **Flowly** — Personal finance tracker | [flowly](https://github.com/kayo-isle69/flowly) | ✅ Live |

---

## License

MIT License — free to use, modify, and distribute.  
Built with 🖤 by **[Komino_dev](https://github.com/kayo-isle69)** · Algeria · 2026
