# Project Context

React 19 + Vite 8 with flat-config ESLint. No TypeScript, no tests configured.

Jira project key: OP
Jira cloud ID: https://testingnew848.atlassian.net

# Commands

- `npm run dev` - Start dev server
- `npm run build` - Production build
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

# Lint

ESLint uses flat config with react-hooks and react-refresh plugins. Custom rule: unused vars must start with uppercase or `_` (regex: `^[A-Z_]`).

# Gotchas

- ESLint rule `no-unused-vars` ignores variables starting with `_` or uppercase - intentional for React components and constants
- No test framework installed - add one if needed (check README for TS template as reference)