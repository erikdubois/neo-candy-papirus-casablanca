# CLAUDE.md — neo-candy-papirus-casablanca

## Project overview

Standalone repo for the **neo-candy-papirus-casablanca** folder-icon theme — the same folder set as
`erikdubois/surfn-papirus-casablanca` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-papirus-casablanca/` — folders only. Packaged as `neo-candy-papirus-casablanca-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-papirus-casablanca/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
