# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **configuration-only template** (Cursor + Claude AI Engineering Template, 2026 edition). It contains `.mdc` rule files and a `README.md` — there is no application code, no package manifests, no services, and no dependencies.

### Key facts

- **No build/test/lint/run commands exist.** The `.mdc` files reference `npm run build`, `npm run test`, `npm run typecheck` as conventions for *target projects* that adopt this template, not for this repo itself.
- **No dependencies to install.** There is no `package.json`, `requirements.txt`, or any other dependency manifest.
- **No services to start.** There are no servers, databases, or background processes.
- **Files are all static text.** The seven `.mdc` files and `README.md` can be validated with standard text-editing tools only.

### Development workflow

To work on this repo, simply edit the `.mdc` rule files or `README.md` with any text editor. No build or compilation step is needed.
