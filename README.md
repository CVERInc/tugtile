**English** · [日本語](README.ja.md) · [한국어](README.ko.md) · [繁體中文](README.zh-TW.md)

# tugtile

**Markdown-backed kanban board for [Obsidian](https://obsidian.md). Tug tiles to reorder.**

tugtile turns any Markdown note into a kanban board — lanes are `## ` headings, cards
(we call them **tiles**) are `- [ ]` task-list items. Your board *is* a plain `.md` file:
drag a tile and the file updates; edit the file and the board updates. Nothing is locked
inside a database or a proprietary format.

## Coming from obsidian-kanban?

Your boards just open. tugtile reads the same frontmatter, the same `- [ ]` cards, the
same `%% kanban:settings %%` block and the same `***` archive as the (GPL,
now-unmaintained) [obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban), and
keeps the original markers in place until you choose to upgrade a board — so going back
stays possible. What you gain on top: undo / redo, an editor built for phones and iPads,
and active maintenance. Written from scratch (clean-room), **MIT**.

## Highlights

- **Your data stays Markdown** — human-readable, diff-friendly, portable. Board and
  table views over the same note, plus a raw-editor button when you want the text itself.
- **Built-in undo / redo** — board actions are reversible.
- **An editor that survives phones** — two-row toolbar, virtual-keyboard-aware layout on
  iOS/iPad; drag-reorder lanes & tiles, dates/times, tags, archive.
- **CJK-first, concretely** — re-highlighting waits while your IME is composing, so CJK
  input is never interrupted; `#tags` accept CJK; sorting is locale-aware.
- **No network, no telemetry** — your boards never leave your vault.

## Install

- **Manual:** from the [latest release](../../releases/latest), download `main.js`,
  `manifest.json`, and `styles.css` into your vault's `.obsidian/plugins/tugtile/` folder,
  then enable **tugtile** in Settings → Community plugins.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat):** add the beta plugin `CVERInc/tugtile`.

Sister plugin: **[marktile](https://github.com/CVERInc/marktile)** — the same editor as a
standalone Markdown pane.

---

Published by **CVER Inc.** · [cver.net](https://cver.net) · MIT License.
