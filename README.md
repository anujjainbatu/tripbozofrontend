

```markdown
# tripbozo Frontend



## Overview

The TripBozo Frontend provides:

- A dynamic, country-selector UI for browsing curated app bundles.
- QR code preview and sharing interface.
- Responsive layouts for desktop and mobile.
- Integration with the Django REST API (CORS-enabled).
- Real-time bundle updates via SWR caching.

---

## Key Folders

| Folder              | Purpose                                                  |
| ------------------- | -------------------------------------------------------- |
| `pages/`            | Next.js routes (SSR & SSG for SEO)                      |
| `components/`       | Reusable UI elements (cards, modals, buttons)           |
| `lib/api.js`        | Fetch wrappers (using `fetch` + SWR)                    |
| `styles/`           | TailwindCSS `globals.css` & theme overrides             |
| `public/`           | Static assets (logos, icons)                            |

---

## Getting Started

```bash
git clone https://github.com/suryansh-it/tripbozofrontend.git
cd tripbozofrontend

npm install
cp .env.local.example .env.local
