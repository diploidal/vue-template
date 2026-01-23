# Vue Template

A template to quickly bootstrap Vue projects with modern tooling.

## Features

- [Vue 3](https://vuejs.org/) + TypeScript + [Vite](https://vite.dev/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [Oxlint](https://github.com/oxc-project/oxc) - Fast linter
- [Oxfmt](https://github.com/aspect-build/rules_oxlint) - Fast formatter
- [Shadcn Vue](https://www.shadcn-vue.com/) - UI components

## Getting Started

### Install Dependencies

```bash
bun install
```

### Run Development Server

```bash
bun run dev
```

### Build for Production

```bash
bun run build
```

## Adding Components

To add Shadcn Vue components:

```bash
bunx --bun shadcn-vue@latest add button
```

For more information, visit the [Shadcn Vue Documentation](https://www.shadcn-vue.com/docs/installation/vite#add-components).

## Scripts

| Command              | Description                    |
| -------------------- | ------------------------------ |
| `bun run dev`        | Start development server       |
| `bun run build`      | Build for production           |
| `bun run preview`    | Preview production build       |
| `bun run lint`       | Run linter                     |
| `bun run lint:fix`   | Run linter with auto-fix       |
| `bun run format`     | Check formatting               |
| `bun run format:fix` | Fix formatting                 |

---

> I'll try to keep this template up-to-date with the latest versions of the packages.
