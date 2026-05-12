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

- **Frontend:** Next.js 14 (App Router) + TypeScript + TailwindCSS + shadcn/ui
- **Backend:** Supabase (PostgreSQL + Auth + Storage + Realtime + Edge Functions)
- **State:** Zustand + TanStack Query
- **Forms:** React Hook Form + Zod
- **State Machines:** XState
- **PDF:** Puppeteer + HTML templates
- **Testing:** Vitest + Playwright
- **Hosting:** Vercel + Supabase Cloud
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
- **Syntax highlighting** (TypeScript, SQL, JSON, YAML, Bash)
- **Print-friendly** — export to PDF via Ctrl+P
- **Full RTL** Arabic support
- **Self-contained** — no internet required after first load (CDN-cached)

## 📜 License

Proprietary — All rights reserved.
