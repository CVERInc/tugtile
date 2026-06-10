[English](README.md) · **日本語** · [한국어](README.ko.md) · [繁體中文](README.zh-TW.md)

# tugtile

**[Obsidian](https://obsidian.md) のための Markdown ネイティブなカンバンボード。タイルをつまんで並べ替え。**

tugtile は任意の Markdown ノートをカンバンボードに変えます。レーンは `## ` 見出し、カード
（**タイル** と呼びます）は `- [ ]` のタスクリスト項目です。ボードはそのまま素の `.md`
ファイル——タイルをドラッグすればファイルが更新され、ファイルを編集すればボードが更新されます。
データベースや独自フォーマットに閉じ込められることはありません。

クリーンルーム実装・**MIT**・CJK フレンドリー。（GPL でメンテ終了の）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) とフォーマット互換——
同じ frontmatter、同じ `- [ ]` カード、同じ `%% kanban:settings %%`、同じ `***` アーカイブ
——なので既存のボードをそのまま読み書きできます。

## インストール

- **手動：** [最新リリース](../../releases/latest) から `main.js`・`manifest.json`・
  `styles.css` を vault の `.obsidian/plugins/tugtile/` に置き、設定 → コミュニティプラグイン
  で **tugtile** を有効化します。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)：** ベータプラグインに
  `CVERInc/tugtile` を追加します。

## 特長

- **データは Markdown のまま**——人が読めて、差分が取りやすく、可搬。
- **元に戻す / やり直し** を内蔵（kanban にはできません）。
- レーン・カードのドラッグ並べ替え、日付/時刻、タグ、アーカイブ、ボード / テーブル表示。
- **CJK ファースト**、デスクトップとモバイル / iPad で動作。

姉妹プラグイン：**[marktile](https://github.com/CVERInc/marktile)**——同じエディタを
単体の Markdown ペインとして。

---

提供：**CVER Inc.** · [cver.net](https://cver.net) · MIT License
