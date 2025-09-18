# Contributing to front-end-store

Thank you for your interest in contributing! This document explains the preferred workflow, coding standards, and what to include in pull requests.

1. Workflow

- Fork the repository and create a branch from `develop`.
- Use descriptive branch names: `feat/<short-desc>`, `fix/<issue-number>`, or `chore/<task>`.
- Make small, focused commits with clear messages.
- Open a pull request against `develop` and include a short description of your changes.

2. Pull Request Checklist

- Title follows the change (e.g., `feat: add responsive header`).
- Description explains what, why, and any tradeoffs.
- Screenshots included for visual changes.
- No broken links or missing assets.
- Run a quick visual check: open `index.html` and affected pages.

3. HTML/CSS Guidelines

- Keep HTML semantic and accessible. Use appropriate tags (e.g., `nav`, `main`, `header`, `footer`).
- Prefer readable class names and avoid overly specific selectors.
- Keep styles in `css/styles.css` unless adding a new stylesheet is necessary.
- Normalize styling is included via `css/normalize.css`; do not remove it.

4. Coding Style

- Indent HTML with 2 spaces.
- Keep lines reasonably short (wrap where it improves readability).

5. Issues

- Open an issue for larger changes before starting work to discuss design and approach.

If something isn't covered here, open an issue or ask in the PR comments.

Thanks for helping improve the project!
