# Awesome Kreoza 🚀

A curated list of repositories, documentation, and tools within the **Kreoza Labs** ecosystem.

## 📦 Package Architecture
To ensure code can be shared cleanly across Web, Desktop, and Mobile, each package has a strict, single responsibility. What goes where:

- **[brand](../brand)**
  - **Includes**: SVG logos, raw font files (.ttf, .woff2), PDF/Markdown design guidelines.
  - **Excludes**: Code, CSS, or React components.

- **[styles](../styles)**
  - **Includes**: Tailwind preset config (`tailwind-preset.js`), CSS variables (`tokens.css`), font `@import` rules.
  - **Excludes**: React components.

- **[ui](../ui)**
  - **Includes**: React component files (e.g., `Button.tsx`, `Tabs.tsx`).
  - **Excludes**: Config base files or raw SVG assets.

- **[icons](../icons)**
  - **Includes**: Custom SVGs compiled into React components (e.g., `<IconHome />`).
  - **Excludes**: Non-icon illustrations or standard UI components.

## 📦 Core Repositories
- **[.github](https://github.com/kreoza-labs/.github)**: Organization metadata & templates.
- **[eslint-config](../eslint-config)**: Shared DX / Linter rules.
- **[tooling](../tooling)**: Shared developer tooling and configurations (e.g., stylelint-config, prettier-config, configs for Python, and non-TypeScript specific setups).
