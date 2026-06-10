[English](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **繁體中文**

# tugtile

**[Obsidian](https://obsidian.md) 的 Markdown 原生看板。拖一下 tile，就排好牌。**

tugtile 把任何 Markdown 筆記變成看板——lane 是 `## ` 標題，卡片（我們叫它 **tile**）是
`- [ ]` 任務清單項目。你的看板**就是**一個素的 `.md` 檔：拖動 tile，檔案就更新；編輯檔案，
看板就更新。沒有任何東西被鎖進資料庫或私有格式。

## 從 obsidian-kanban 搬過來？

你的看板直接打開就能用。tugtile 讀寫與（GPL、已停止維護的）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) 相同的 frontmatter、相同的
`- [ ]` 卡片、相同的 `%% kanban:settings %%` 區塊與相同的 `***` 封存——並且在你主動選擇
「升級」之前，原樣保留原本的標記，隨時可以回頭。搬過來多得到的：復原／重做、為手機與
iPad 打造的編輯器，以及仍在活躍的維護。從零寫起（clean-room）、**MIT** 授權。

## 亮點

- **資料永遠是 Markdown**——人類可讀、好 diff、帶得走。同一份筆記有看板／表格兩種檢視，
  想直接碰文字時還有 raw 編輯器按鈕。
- **內建復原／重做**——看板操作都可以反悔。
- **在手機上活得下來的編輯器**——雙排工具列、iOS／iPad 虛擬鍵盤自動避讓；lane 與 tile
  拖曳排序、日期／時間、標籤、封存。
- **CJK 優先，而且講得出細節**——IME 組字期間暫停重新上色，中文輸入絕不被打斷；`#標籤`
  支援 CJK；排序使用 locale 感知比較。
- **不連網、零遙測**——你的看板永遠不會離開 vault。

## 安裝

- **手動：** 從[最新 release](../../releases/latest) 下載 `main.js`、`manifest.json`、
  `styles.css` 放進 vault 的 `.obsidian/plugins/tugtile/`，然後在 設定 → 社群外掛 啟用
  **tugtile**。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)：** 加入 beta 外掛 `CVERInc/tugtile`。

姊妹外掛：**[marktile](https://github.com/CVERInc/marktile)**——同一顆編輯器，作為獨立的
Markdown 分頁。

---

**CVER Inc.** 出品 · [cver.net](https://cver.net) · MIT License
