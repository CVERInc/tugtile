**English** · [日本語](README.ja.md) · [한국어](README.ko.md) · [繁體中文](README.zh-TW.md)

# tugtile

**A card table for your Markdown notes in [Obsidian](https://obsidian.md) — tug tiles to reorder.**

tugtile lays a Markdown note out like cards on a table — every `- [ ]` task-list item
becomes a **tile** you can pick up and tug somewhere better, and `## ` headings are the
**lanes** the tiles line up in. Your table *is* a plain `.md` file: tug a tile and the
file updates; edit the file and the board updates. Nothing is locked inside a database
or a proprietary format.

## Coming from obsidian-kanban?

tugtile also speaks fluent kanban. Boards from the (GPL, now-unmaintained)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) just open — same
frontmatter, same `- [ ]` cards, same `%% kanban:settings %%` block, same `***` archive —
and tugtile keeps the original markers in place until you choose to upgrade a board, so
going back stays possible. What you gain on top: undo / redo, an editor built for phones
and iPads, and active maintenance. Written from scratch (clean-room), **MIT**.

## Highlights

- **Your data stays Markdown** — human-readable, diff-friendly, portable. Board and
  Table views over the same note, plus a raw-editor button when you want the text itself.
- **Built-in undo / redo** — every move at the table is reversible.
- **An editor that survives phones** — two-row toolbar, virtual-keyboard-aware layout on
  iOS/iPad; tug lanes & tiles to reorder, dates/times, tags, stash (archive).
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
