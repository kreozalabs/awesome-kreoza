# Awesome Kreoza 🚀

A curated list of repositories, documentation, and tools within the **Kreoza Labs** ecosystem.

## 📦 Core Repositories
- **[.github](https://github.com/kreoza-labs/.github)**: Organization metadata & templates.
- **[styles](./styles)**: The Design System (Tailwind preset & CSS variables).
- **[eslint-config](./eslint-config)**: Shared DX / Linter rules.
- **[core](./core)**: (Planned) The main monolithic application (Go 1.22 + React/Vite).

## 🛠️ Stack Decisions
- **Backend**: Go (GraphQL + sqlc + PostgreSQL).
- **Frontend**: React (Vite + TS + Tailwind).
- **Infrastructure**: Traefik + Docker Compose + GH Actions.
- **Automation**: n8n workflows.

## 🌈 Design System
We follow a **"Flow & Intelligence"** aesthetic:
- **Primary Color**: `Indigo Flow` (hsl 239 84% 67%).
- **Theme**: Dark Mode by default.
- **Components**: Based on `shadcn/ui` and `Tailwind CSS`.

---

## 📈 Roadmap (Short Term)
1. Initialize `core` monorepo.
2. Link `styles` to `core`.
3. Set up CI/CD for the backend binary.
4. Integrate basic n8n webhook triggers.
