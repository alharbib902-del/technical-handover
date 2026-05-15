# Technical Handover Document

> **Integrated Institutional Management System (IIMS)** — Technical specification for a training institute management platform.

## 🚀 Quick Start

Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

```bash
# Or serve locally
npx serve .
# Then visit http://localhost:3000
```

## 📋 Document Contents

| Tab | Sections | Topic |
|-----|----------|-------|
| **1** | 1-4 | Context, stakeholders, scope |
| **2** | 5-8 | Architecture, tech stack, data model |
| **3** | 9-12 | Functional modules, business rules, state machines, workflows |
| **4** | 13-15 | Integrations, security, performance |
| **5** | 16-20 | Coding standards, Git, testing, DevOps, API design |
| **6** | 21-22 | Open questions, roadmap, glossary |

## 🛠 Tech Stack

- **Backend:** Laravel 11 (PHP 8.3) + Eloquent ORM
- **Admin Panel:** Filament 3 (Resources, Forms, Tables, Actions, Widgets)
- **UI Reactivity:** Livewire 3 + Blade + Alpine.js + TailwindCSS
- **Database:** PostgreSQL 15 + Redis (cache + queues)
- **Auth & RBAC:** Laravel Auth + Sanctum + Spatie Permission + Filament Shield + spatie/laravel-google2fa
- **Storage:** Spatie Media Library
- **Realtime:** Laravel Reverb (WebSockets)
- **State Machines:** Spatie Laravel Model States
- **Queues & Schedules:** Laravel Horizon + Laravel Scheduler
- **PDF:** Browsershot (spatie/browsershot) + Blade RTL templates
- **Forms & Validation:** Filament Forms + Form Requests
- **Testing:** Pest + Laravel Dusk
- **Quality:** Laravel Pint + PHPStan/Larastan
- **Hosting:** Saudi VPS (Hostinger KSA / Contabo KSA / Aramco Cloud) via Laravel Forge
- **CDN/Security:** Cloudflare

## 📂 Structure

```
.
├── index.html                  # Main handover document
├── README.md                   # This file
├── .gitignore
└── مسودات-الوكلاء/             # Source markdown drafts
    ├── الجزء-01-السياق-والمعمارية.md
    ├── الجزء-02-الموديولات-والمنطق-التجاري.md
    ├── الجزء-03-التكاملات-والأمان-والأداء.md
    ├── الجزء-04-معايير-التطوير.md
    └── الجزء-05-المراجع-والملحقات.md
```

## 🔍 Features

- **Tabbed navigation** — 6 sections, 22 chapters
- **Live search** (Ctrl+K) within the document
- **Sidebar TOC** auto-generated per tab
- **Mermaid diagrams** (ERD, sequence, flowchart, state machine, git graph)
- **Syntax highlighting** (PHP, Blade, SQL, JSON, YAML, Bash)
- **Print-friendly** — export to PDF via Ctrl+P
- **Full RTL** Arabic support
- **Self-contained** — no internet required after first load (CDN-cached)

## 📜 License

Proprietary — All rights reserved.
