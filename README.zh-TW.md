[English](README.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **繁體中文**

# tugtile

**在 [Obsidian](https://obsidian.md) 裡為你的 Markdown 筆記開一張牌桌——拖一下牌，就排好。**

tugtile 把一份 Markdown 筆記攤成一桌牌——每個 `- [ ]` 任務項目是一張**牌**，拿起來就能
拖到更好的位置；`## ` 標題是牌排成的**牌列**。你的牌桌**就是**一個素的 `.md` 檔：拖牌，
檔案就更新；改檔案，牌桌就更新。沒有任何東西被鎖進資料庫或私有格式。

## 從 obsidian-kanban 搬過來？

tugtile 也說流利的看板語。（GPL、已停止維護的）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) 的看板直接打開就能用——
相同的 frontmatter、相同的 `- [ ]` 卡片、相同的 `%% kanban:settings %%` 區塊與相同的
`***` 封存——而且在你主動選擇「升級」之前，tugtile 原樣保留原本的標記，隨時可以回頭。
搬過來多得到的：復原／重做、為手機與 iPad 打造的編輯器，以及仍在活躍的維護。從零寫起
（clean-room）、**MIT** 授權。

## 亮點

- **資料永遠是 Markdown**——人類可讀、好 diff、帶得走。同一份筆記有牌桌／牌表兩種檢視，
  想直接碰文字時還有 raw 編輯器按鈕。
- **內建復原／重做**——桌上每一手都可以反悔。
- **在手機上活得下來的編輯器**——雙排工具列、iOS／iPad 虛擬鍵盤自動避讓；牌列與牌都能
  拖曳排序，加上日期／時間、標籤、收牌（牌庫）。
- **CJK 優先，而且講得出細節**——IME 組字期間暫停重新上色，中文輸入絕不被打斷；`#標籤`
  支援 CJK；排序使用 locale 感知比較。
- **不連網、零遙測**——你的牌桌永遠不會離開 vault。

## 安裝

- **手動：** 從[最新 release](../../releases/latest) 下載 `main.js`、`manifest.json`、
  `styles.css` 放進 vault 的 `.obsidian/plugins/tugtile/`，然後在 設定 → 社群外掛 啟用
  **tugtile**。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)：** 加入 beta 外掛 `CVERInc/tugtile`。

姊妹外掛：**[marktile](https://github.com/CVERInc/marktile)**——同一顆編輯器，作為獨立的
Markdown 分頁。

---

**CVER Inc.** 出品 · [cver.net](https://cver.net) · MIT License
