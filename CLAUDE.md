# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This repo (`SwiftPush/SwiftPush`) is a GitHub profile README repository — its sole purpose is to render `README.md` on the user's GitHub profile page (https://github.com/SwiftPush). There is no application code, build system, or test suite.

The only meaningful file is `README.md`, which uses raw HTML (not Markdown) for layout: an `<h2>` intro, a shields.io badge, and a row of devicon SVGs sized via inline `width`/`height`. Edits should preserve the HTML-in-Markdown style and keep icon URLs pointing at `raw.githubusercontent.com/devicons/devicon/master/icons/...`.

## Editing notes

- Changes are visible by pushing to `main` and viewing the GitHub profile — there is nothing to build or run locally.
- When adding a tech icon, follow the existing `<img ... width="25" height="25" />` pattern and pull the SVG from the devicon repo on the `master` branch.
