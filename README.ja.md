[English](README.md) · **日本語** · [한국어](README.ko.md) · [繁體中文](README.zh-TW.md)

# tugtile

**[Obsidian](https://obsidian.md) の中の、Markdown ノートのためのカードテーブル。タイルをつまんで並べ替え。**

tugtile は Markdown ノートを、テーブルに広げたカードのように扱います：`- [ ]` のタスク
リスト項目が一枚一枚の**タイル**になり、つまんで好きな場所へ動かせます。`## ` 見出しは
タイルが並ぶ**列**です。テーブルはそのまま素の `.md` ファイル：タイルを動かせばファイルが
更新され、ファイルを編集すればボードが更新されます。データベースや独自フォーマットに
閉じ込められることはありません。

## obsidian-kanban からの乗り換え

tugtile は kanban も流暢に話します。（GPL でメンテ終了の）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) のボードはそのまま開きます：
同じ frontmatter、同じ `- [ ]` カード、同じ `%% kanban:settings %%` ブロック、同じ
`***` アーカイブ。そして、あなたが「アップグレード」を選ぶまで元のマーカーをそのまま
保持します。いつでも戻れます。乗り換えで増えるもの：取り消し／やり直し、スマホと iPad の
ために作られたエディタ、そして現役のメンテナンス。ゼロから書かれた（クリーンルーム）
**MIT** 実装です。

## ハイライト

- **データはずっと Markdown**：人間が読めて、diff しやすく、持ち運べます。同じノートを
  ボード／表の 2 ビューで。テキストそのものを触りたいときは raw エディタボタンも。
- **取り消し／やり直しを内蔵**：テーブルの上の一手は、いつでもやり直せます。
- **スマホで生き残るエディタ**：2 段ツールバー、iOS／iPad の仮想キーボードに追従する
  レイアウト。列もタイルもつまんで並べ替え、日付／時刻、タグ、アーカイブ。
- **CJK ファースト、具体的に**：IME の変換中は再ハイライトを待機し、日本語入力を決して
  中断しません。`#タグ` も CJK 対応、並べ替えはロケールを認識します。
- **ネットワークなし、テレメトリなし**：ボードが vault の外に出ることはありません。

## インストール

- **手動：** [最新リリース](../../releases/latest) から `main.js`・`manifest.json`・
  `styles.css` を vault の `.obsidian/plugins/tugtile/` に置き、設定 → コミュニティプラグイン
  で **tugtile** を有効化。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)：** ベータプラグイン `CVERInc/tugtile` を追加。

姉妹プラグイン：**[marktile](https://github.com/CVERInc/marktile)**：同じエディタを、独立した
Markdown ペインとして。

---

**CVER Inc.** · [cver.net](https://cver.net) · MIT License
