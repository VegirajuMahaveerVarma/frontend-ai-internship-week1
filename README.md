# CLAUDE.md

## Project Overview

This repository contains the **FlyRank Frontend** — an AI Engineering capstone project focused on building a modern, production-quality frontend application using AI-assisted development practices.

## Technology Stack

| Tool / Library | Purpose |
|---|---|
| [Next.js](https://nextjs.org/) | React framework with SSR and routing |
| [TypeScript](https://www.typescriptlang.org/) | Static typing for application code |
| [React](https://react.dev/) | UI component library |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [Git & GitHub](https://github.com/) | Version control and collaboration |
| [Claude Code](https://claude.ai/code) | AI-assisted development |

## Development Conventions

### Code Style
- Write all application code in **TypeScript**.
- Use **clear, descriptive** variable and function names.
- Avoid introducing unnecessary third-party dependencies.

### Components
- Prefer **reusable React components** over one-off implementations.
- Keep components **small and focused** — one responsibility per component.
- Separate **business logic from presentation** where practical.

### UI & Accessibility
- Use **semantic HTML** elements.
- Maintain **responsive layouts** across screen sizes.
- Follow **accessible UI practices** (ARIA roles, keyboard navigation, sufficient contrast).

## Git Conventions

This project uses [Conventional Commits](https://www.conventionalcommits.org/).

| Prefix | When to use |
|---|---|
| `feat:` | New functionality |
| `fix:` | Bug fixes |
| `docs:` | Documentation changes |
| `refactor:` | Code restructuring with no behaviour change |
| `chore:` | Configuration, tooling, or maintenance tasks |

**Examples:**
```
feat: add search results ranking component
fix: correct pagination offset on filtered views
docs: update development conventions in CLAUDE.md
refactor: extract API client into shared utility
chore: update ESLint config to flat format
```

## AI Development Rules

When using Claude Code or any AI assistant on this project:

1. **Inspect before modifying** — review existing code and context before making changes.
2. **Explain significant changes** — provide reasoning when asked or when changes are non-obvious.
3. **Preserve existing functionality** — do not break working behaviour when modifying code.
4. **Avoid unnecessary dependencies** — prefer solutions using what is already in the stack.
5. **Favour simplicity** — choose the most straightforward, maintainable solution available.
