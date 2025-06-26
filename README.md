# TripBozo Frontend

> This repo delivers tripbozo’s user interface, built in Next.js (App Router) and React, with server-side rendering and incremental static regeneration for blazing-fast performance.

## Overview

The TripBozo Frontend provides:

- A dynamic, country-selector UI for browsing curated app bundles.
- QR-code preview and sharing interface.
- Responsive layouts for desktop and mobile.
- Integration with the Django REST API (CORS-enabled).
- Real-time bundle updates via SWR caching.

---

## 🔑 Key Folders

| Folder             | Purpose                                                           |
| ------------------ | ----------------------------------------------------------------- |
| `app/`             | Next.js App Router entrypoints and layouts (SSR, SSG, ISR)        |
| `components/`      | Reusable UI elements (cards, modals, buttons)                    |
| `lib/api.ts`       | Fetch wrappers (using `fetch` + SWR)                             |
| `styles/`          | TailwindCSS `globals.css` & theme overrides                      |
| `public/`          | Static assets (logos, icons)                                     |

---

## 🚀 Running Locally

```bash
git clone https://github.com/suryansh-it/tripbozofrontend.git
cd tripbozofrontend

npm install
cp .env.local.example .env.local
npm run dev
# Visit http://localhost:3000
