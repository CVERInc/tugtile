[English](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **繁體中文**

# tugtile

**給 [Obsidian](https://obsidian.md) 的 Markdown 原生看板。拖一張牌就重新排序。**

tugtile 把任何一份 Markdown 筆記變成看板——欄是 `## ` 標題,卡片(我們叫它**牌／tile**)是
`- [ ]` 任務清單項目。你的看板**就是**一份純 `.md` 檔:拖一張牌,檔案就更新;改檔案,看板就更新。
沒有任何東西被鎖進資料庫或專有格式裡。

淨室自寫、**MIT**、CJK 友善。與(GPL、已停止維護的)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) **格式相容**——同一套 frontmatter、
同一種 `- [ ]` 卡片、同一個 `%% kanban:settings %%`、同一種 `***` 封存——所以能直接讀寫你既有的看板。

## 安裝

- **手動:** 從[最新 Release](../../releases/latest) 下載 `main.js`、`manifest.json`、
  `styles.css` 放進你 vault 的 `.obsidian/plugins/tugtile/` 資料夾,再到 設定 → 社群外掛
  啟用 **tugtile**。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat):** 加入測試版外掛 `CVERInc/tugtile`。

## 特色

- **你的資料維持 Markdown**——人類可讀、好做 diff、可攜。
- 內建**復原／重做**(kanban 做不到)。
- 拖拉重排欄與卡、日期/時間、標籤、封存、看板／表格檢視。
- **CJK 優先**,桌面與行動裝置／iPad 都能用。

姊妹外掛:**[marktile](https://github.com/CVERInc/marktile)**——同一個編輯器,獨立的 Markdown 分頁。

---

由 **CVER Inc.** 發佈 · [cver.net](https://cver.net) · MIT License
