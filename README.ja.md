[English](README.md) · **日本語** · [한국어](README.ko.md) · [繁體中文](README.zh-TW.md)

# tugtile

**[Obsidian](https://obsidian.md) のための Markdown ネイティブなカンバンボード。タイルをつまんで並べ替え。**

tugtile は任意の Markdown ノートをカンバンボードに変えます。レーンは `## ` 見出し、カード
（**タイル** と呼びます）は `- [ ]` のタスクリスト項目です。ボードはそのまま素の `.md`
ファイル——タイルをドラッグすればファイルが更新され、ファイルを編集すればボードが更新されます。
データベースや独自フォーマットに閉じ込められることはありません。

## obsidian-kanban からの乗り換え

ボードはそのまま開きます。tugtile は（GPL でメンテ終了の）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) と同じ frontmatter、同じ
`- [ ]` カード、同じ `%% kanban:settings %%` ブロック、同じ `***` アーカイブを読み書きし、
あなたが「アップグレード」を選ぶまで元のマーカーをそのまま保持します——いつでも戻れます。
乗り換えで増えるもの：取り消し／やり直し、スマホと iPad のために作られたエディタ、そして
現役のメンテナンス。ゼロから書かれた（クリーンルーム）**MIT** 実装です。

## ハイライト

- **データはずっと Markdown** ——人間が読めて、diff しやすく、持ち運べます。同じノートを
  ボード／テーブルの 2 ビューで。テキストそのものを触りたいときは raw エディタボタンも。
- **取り消し／やり直しを内蔵** ——ボード操作はやり直せます。
- **スマホで生き残るエディタ** ——2 段ツールバー、iOS／iPad の仮想キーボードに追従する
  レイアウト。レーンとタイルのドラッグ並べ替え、日付／時刻、タグ、アーカイブ。
- **CJK ファースト、具体的に** ——IME の変換中は再ハイライトを待機し、日本語入力を決して
  中断しません。`#タグ` も CJK 対応、並べ替えはロケールを認識します。
- **ネットワークなし、テレメトリなし** ——ボードが vault の外に出ることはありません。

## インストール

- **手動：** [最新リリース](../../releases/latest) から `main.js`・`manifest.json`・
  `styles.css` を vault の `.obsidian/plugins/tugtile/` に置き、設定 → コミュニティプラグイン
  で **tugtile** を有効化。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)：** ベータプラグイン `CVERInc/tugtile` を追加。

姉妹プラグイン：**[marktile](https://github.com/CVERInc/marktile)** ——同じエディタを、独立した
Markdown ペインとして。

---

**CVER Inc.** · [cver.net](https://cver.net) · MIT License
