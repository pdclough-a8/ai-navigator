# AI Agent Instructions for a8-ai-navigator

This repository is a small static website built from a single `index.html` file.

## Key points

- The only source file is `index.html` at the repository root.
- There is no build system, package manager, or backend.
- Styling and content are embedded directly in `index.html`.
- GitHub Actions deploy the repository to GitHub Pages via `.github/workflows/static.yml`.

## Recommended behavior for AI agents

- Treat `index.html` as the application entry point.
- Avoid adding unnecessary files unless the user explicitly requests a more complex structure.
- Preserve the existing static HTML/CSS structure and inline styles when making updates.
- If new functionality is needed, implement it in `index.html` unless the user asks to add a new asset or script file.
- Do not change the deployment workflow unless asked; the current workflow uploads the repository root for Pages deployment.

## When asked to improve the project

- Focus on content, accessibility, and small UI refinements within the single-page file.
- If the user requests a more robust structure, ask whether they want a multi-file static site or a frontend framework setup.
