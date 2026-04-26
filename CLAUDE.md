# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A portfolio repository — not a software project. It holds PDFs of Ryan Cox's published work and conference presentations, surfaced via bit.ly links (see `README.md`). There is no build, lint, or test pipeline.

## Layout

- `publications/ibm-redbooks/` — historical IBM Redbooks (WebSphere, CBConnector, SOA patterns).
- `publications/salesforce/` — Salesforce conference decks, organized by venue:
  - `architect-dreamin/`, `cactusforce/`, `devops-dreamin/`
  - Loose PDFs at the `salesforce/` root (e.g. user-group talks) that don't belong to a recurring venue.
- `.sfdx/` — stray Salesforce CLI scratch metadata; unrelated to portfolio content.

Filenames encode the venue and date (e.g. `Cactusforce - Salesforce MCP and A2A Support (Jan 2026).pdf`); preserve that convention when adding new decks.

## Working in this repo

- Typical changes are adding a new PDF under the right venue folder and updating `README.md` if a new bit.ly link is needed.
- Do not attempt to parse, rewrite, or "refactor" the PDFs — treat them as opaque binary artifacts.
- Commits in history are presentation-sized units (one commit per deck or per README update); follow that pattern.
