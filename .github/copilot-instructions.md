## Repo summary

This repository is a personal GitHub profile README and image assets. There is no build system, test harness, or runtime code in the repository—the primary source of truth is `README.md` and the `img/` directory.

## High-level guidance for AI coding agents

- Primary goal: make small, well-scoped improvements to the README and image assets. Avoid creating large new application scaffolds unless the maintainer asks.
- Files of interest:
  - `README.md` — the profile content (badges, images, sections to update)
  - `img/` — banner and other image assets referenced by the README

## Allowed changes (safe, high-value)

- Edit or improve copy in `README.md` (headings, badges, links, grammar).
- Replace or optimize images in `img/` (keep filenames consistent or update `README.md` refs).
- Add small assets (icons, responsive image variants) and update README image references.
- Add metadata files that improve discoverability (e.g., `LICENSE`, small `CONTRIBUTING.md`) but only with the author's consent for licensing choices.

## What NOT to do

- Do not add large frameworks or project scaffolding (no `package.json`, no new JS/TS build setups) unless a maintainer explicitly requests it.
- Do not commit secrets, API keys, or personal data.
- Avoid changing the repository's owner/profile settings; focus on repository content only.

## Patterns & examples from this repo

- Badges and skill icons are inline Markdown image links in `README.md`. When updating icons, keep the same width/height attributes to maintain layout.
- Banner: `img/github-header-banner.png` is used at the top; if replacing the banner, either preserve the filename or update the `README.md` src accordingly.

## PR and commit guidance

- Commit message style: short imperative summary, e.g. `docs: improve README badges` or `chore: optimize banner image`.
- PR description should include what changed, why, and a before/after screenshot for visual edits.

## Debugging & verification

- Visual changes: test by opening the rendered `README.md` on GitHub or previewing Markdown locally.
- Asset changes: verify images render and paths are correct; if changing filenames, update all references in `README.md`.

## When you need more context

- If a requested change touches CI/build/test, ask for clarification—there are no build files here.
- For additions beyond README/images (websites, portfolio pages), propose a short plan and wait for maintainer approval.

If anything in this file is unclear or you need more repository context to do a task, ask and I'll provide guidance or additional files.
