# tugtile

**Markdown-backed kanban board for [Obsidian](https://obsidian.md). Tug tiles to reorder.**

tugtile turns any Markdown note into a kanban board — lanes are `## ` headings, cards
(we call them **tiles**) are `- [ ]` task-list items. Your board *is* a plain `.md` file:
drag a tile and the file updates; edit the file and the board updates. Nothing is locked
inside a database or a proprietary format.

Clean-room, **MIT**, CJK-friendly. Format-compatible with the (GPL, now-unmaintained)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) — same frontmatter, same
`- [ ]` cards, same `%% kanban:settings %%` block, same `***` archive — so it reads and
writes your existing boards.

## Install

- **Manual:** from the [latest release](../../releases/latest), download `main.js`,
  `manifest.json`, and `styles.css` into your vault's `.obsidian/plugins/tugtile/` folder,
  then enable **tugtile** in Settings → Community plugins.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat):** add the beta plugin `CVERInc/tugtile`.

## Highlights

- **Your data stays Markdown** — human-readable, diff-friendly, portable.
- Built-in **undo / redo** (kanban can't).
- Drag-reorder lanes & cards, dates/times, tags, archive, board / table views.
- **CJK-first**, works on desktop and mobile / iPad.

Sister plugin: **[marktile](https://github.com/CVERInc/marktile)** — the same editor as a
standalone Markdown pane.

---

Published by **CVER Inc.** · [cver.net](https://cver.net) · MIT License.
