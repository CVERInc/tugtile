# tugtile

[English](#english) · [日本語](#日本語) · [한국어](#한국어) · [繁體中文](#繁體中文)

---

## English

**A card table for your Markdown notes in [Obsidian](https://obsidian.md) — tug tiles to reorder.**

tugtile lays a Markdown note out like cards on a table — every `- [ ]` task-list item
becomes a **tile** you can pick up and tug somewhere better, and `## ` headings are the
**lanes** the tiles line up in. Your table *is* a plain `.md` file: tug a tile and the
file updates; edit the file and the board updates. Nothing is locked inside a database
or a proprietary format.

### Coming from obsidian-kanban?

tugtile's native tongue is tiles — but it also speaks fluent kanban. Boards from the (GPL, now-unmaintained)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) just open — same
frontmatter, same `- [ ]` cards, same `%% kanban:settings %%` block, same `***` archive —
and tugtile keeps the original markers in place until you choose to upgrade a board, so
going back stays possible. What you gain on top: undo / redo, an editor built for phones
and iPads, and active maintenance.

tugtile started life as plugins *for* obsidian-kanban — until rebuilding the
whole table was easier than patching someone else's. Written from scratch (clean-room),
**MIT**.

### Highlights

- **Never lose a card** — built-in undo / redo, a backup before the first write, and
  overwrite protection: if the file changes elsewhere, tugtile reloads instead of
  clobbering it. (Backed by a data-safety test suite.)
- **Hands never leave the keyboard** — arrow keys tug a tile within or across lanes;
  Space / A / D check, archive, or delete it; Tab to a lane header and arrow-reorder the
  whole lane; new / rename lane are rebindable commands. Sort a whole board without
  reaching for the mouse.
- **An editor that survives phones** — two-row toolbar, virtual-keyboard-aware layout on
  iOS/iPad; tug lanes & tiles to reorder, dates/times, tags, stash (archive).
- **Your data stays Markdown** — human-readable, diff-friendly, portable. Board and
  Table views over the same note, plus a raw-editor button when you want the text itself.
- **Your language isn't an edge case** — every keyboard surface (the editor, card submit,
  *and* the board's move keys) pauses while your IME is composing, so a Chinese / Japanese
  / Korean candidate-confirm is never mistaken for a shortcut; card collapse is
  width-aware; `#tags` accept CJK. The six CJK guarantees — and how each is verified —
  live in [CJK.md](./CJK.md).
- **No network, no telemetry** — your boards never leave your vault.

### Install

- **Community plugins (recommended):** in Obsidian, open Settings → Community plugins →
  Browse, search for **tugtile**, then Install and Enable.
- **Manual:** from the [latest release](../../releases/latest), download `main.js`,
  `manifest.json`, and `styles.css` into your vault's `.obsidian/plugins/tugtile/` folder,
  then enable **tugtile** in Settings → Community plugins.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat) (beta builds):** add `CVERInc/tugtile`.

Sister plugin: **[marktile](https://github.com/CVERInc/marktile)** — the same editor as a
standalone Markdown pane.

**[Read more on cver.net →](https://cver.net/oss/tugtile)**

---

## 日本語

**[Obsidian](https://obsidian.md) の中の、Markdown ノートのためのカードテーブル。タイルをつまんで並べ替え。**

tugtile は Markdown ノートを、テーブルに広げたカードのように扱います：`- [ ]` のタスク
リスト項目が一枚一枚の**タイル**になり、つまんで好きな場所へ動かせます。`## ` 見出しは
タイルが並ぶ**列**です。テーブルはそのまま素の `.md` ファイル：タイルを動かせばファイルが
更新され、ファイルを編集すればボードが更新されます。データベースや独自フォーマットに
閉じ込められることはありません。

### obsidian-kanban からの乗り換え

tugtile の母語はタイル。でも kanban 語もペラペラです。（GPL でメンテ終了の）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) のボードはそのまま開きます：
同じ frontmatter、同じ `- [ ]` カード、同じ `%% kanban:settings %%` ブロック、同じ
`***` アーカイブ。そして、あなたが「アップグレード」を選ぶまで元のマーカーをそのまま
保持します。いつでも戻れます。乗り換えで増えるもの：取り消し／やり直し、スマホと iPad の
ために作られたエディタ、そして現役のメンテナンス。

tugtile の前身は、obsidian-kanban のために書いた plugin の山（plugin の plugin）でした。
他人のテーブルを直し続けるより、テーブルごと作り直すほうが早かった。ゼロから書かれた
（クリーンルーム）**MIT** 実装です。

### ハイライト

- **カードを失わない**：取り消し／やり直しを内蔵、最初の書き込み前にバックアップ、
  ファイルが外部で変わったら上書きせず再読み込み。（データ安全テストで保証）
- **手はキーボードから離れない**：矢印キーでタイルを同じ列／隣の列へ動かし、Space／A／D
  で完了・アーカイブ・削除、Tab で列見出しへ移って矢印キーで列ごと並べ替え。列の新規作成
  ／名前変更は割り当て可能なコマンド。ボード一枚、マウスに触れずに片づきます。
- **スマホで生き残るエディタ**：2 段ツールバー、iOS／iPad の仮想キーボードに追従する
  レイアウト。列もタイルもつまんで並べ替え、日付／時刻、タグ、アーカイブ。
- **データはずっと Markdown**：人間が読めて、diff しやすく、持ち運べます。同じノートを
  ボード／表の 2 ビューで。テキストそのものを触りたいときは raw エディタボタンも。
- **あなたの言語は、例外じゃない**：すべてのキーボード操作（エディタ、カード送信、そして
  ボードの移動キー）は IME の変換中は待機するので、日本語・中国語・韓国語の変換確定が
  ショートカットと取り違えられることはありません。長いカードの折りたたみは文字幅を考慮し、
  `#タグ` も CJK 対応。6 つの CJK 保証と、その検証方法は [CJK.md](./CJK.md) に。
- **ネットワークなし、テレメトリなし**：ボードが vault の外に出ることはありません。

### インストール

- **コミュニティプラグイン（推奨）：** 設定 → コミュニティプラグイン → 「閲覧」で
  **tugtile** を検索し、インストールして有効化。
- **手動：** [最新リリース](../../releases/latest) から `main.js`・`manifest.json`・
  `styles.css` を vault の `.obsidian/plugins/tugtile/` に置き、設定 → コミュニティプラグイン
  で **tugtile** を有効化。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)（ベータ版）：** `CVERInc/tugtile` を追加。

姉妹プラグイン：**[marktile](https://github.com/CVERInc/marktile)**：同じエディタを、独立した
Markdown ペインとして。

**[詳しくは cver.net で →](https://cver.net/ja-jp/oss/tugtile)**

---

## 한국어

**[Obsidian](https://obsidian.md) 안의 Markdown 노트를 위한 카드 테이블: 타일을 끌어서 정렬.**

tugtile은 Markdown 노트를 테이블 위에 펼친 카드처럼 다룹니다: `- [ ]` 작업 목록 항목
하나하나가 집어서 더 좋은 자리로 옮길 수 있는 **타일**이 되고, `## ` 제목은 타일이
늘어서는 **열**이 됩니다. 테이블은 그 자체로 평범한 `.md` 파일입니다: 타일을 옮기면
파일이 갱신되고, 파일을 편집하면 보드가 갱신됩니다. 데이터베이스나 독자 포맷에 갇히는
것은 아무것도 없습니다.

### obsidian-kanban에서 옮겨오시나요?

tugtile의 모국어는 타일이지만, kanban도 유창하게 구사합니다. (GPL, 유지보수가 중단된)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban)의 보드가 그대로 열립니다:
같은 frontmatter, 같은 `- [ ]` 카드, 같은 `%% kanban:settings %%` 블록, 같은 `***`
아카이브. 그리고 "업그레이드"를 직접 선택하기 전까지 원래 마커를 그대로 유지합니다.
언제든 돌아갈 수 있습니다. 옮겨오면 얻는 것: 실행 취소/다시 실행, 휴대폰과 iPad를 위해
만들어진 에디터, 그리고 활발한 유지보수.

tugtile은 원래 obsidian-kanban을 위해 쓴 플러그인들(플러그인의 플러그인)에서
시작했습니다. 남의 테이블을 계속 고치는 것보다 테이블째 새로 만드는 편이 빨랐습니다.
처음부터 새로 작성된(clean-room) **MIT** 구현입니다.

### 하이라이트

- **카드를 잃지 않습니다**: 실행 취소/다시 실행 내장, 첫 쓰기 전 백업, 파일이 외부에서
  바뀌면 덮어쓰지 않고 다시 읽기.（데이터 안전 테스트로 보장）
- **손이 키보드를 떠나지 않습니다**: 화살표 키로 타일을 같은 열이나 옆 열로 옮기고,
  Space／A／D로 완료・보관・삭제, Tab으로 열 머리글로 이동해 화살표 키로 열 전체를 재정렬.
  열 추가／이름 변경은 단축키를 지정할 수 있는 명령입니다. 보드 하나를 마우스 없이 정리합니다.
- **휴대폰에서 살아남는 에디터**: 2단 툴바, iOS/iPad 가상 키보드를 따라가는 레이아웃,
  열과 타일을 집어서 정렬, 날짜/시간, 태그, 보관함.
- **데이터는 언제나 Markdown**: 사람이 읽을 수 있고, diff 친화적이며, 어디로든 가져갈 수
  있습니다. 같은 노트를 보드/표 두 가지 뷰로, 텍스트를 직접 만지고 싶을 때는 raw 에디터
  버튼도 있습니다.
- **여러분의 언어는 예외가 아닙니다**: 모든 키보드 입력(에디터, 카드 전송, 그리고 보드의
  이동 키)이 IME 조합 중에는 대기하므로, 한국어・중국어・일본어의 변환 확정이 단축키로
  잘못 인식되지 않습니다. 긴 카드 접기는 글자 너비를 고려하고, `#태그`도 CJK 지원. 여섯
  가지 CJK 보증과 각각의 검증 방법은 [CJK.md](./CJK.md)에 있습니다.
- **네트워크 없음, 텔레메트리 없음**: 보드는 vault 밖으로 나가지 않습니다.

### 설치

- **커뮤니티 플러그인(권장):** 설정 → 커뮤니티 플러그인 → 「탐색」에서 **tugtile**을
  검색해 설치하고 활성화하세요.
- **수동:** [최신 릴리스](../../releases/latest)에서 `main.js`, `manifest.json`,
  `styles.css`를 vault의 `.obsidian/plugins/tugtile/`에 넣고, 설정 → 커뮤니티 플러그인에서
  **tugtile**을 활성화하세요.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)(베타 빌드):** `CVERInc/tugtile` 추가.

자매 플러그인: **[marktile](https://github.com/CVERInc/marktile)**: 같은 에디터를 독립된
Markdown 패널로.

**[cver.net에서 더 보기 →](https://cver.net/ko-kr/oss/tugtile)**

---

## 繁體中文

**在 [Obsidian](https://obsidian.md) 裡為你的 Markdown 筆記開一張牌桌：拖一下牌，就排好。**

tugtile 把一份 Markdown 筆記攤成一桌牌：每個 `- [ ]` 任務項目是一張**牌**，拿起來就能
拖到更好的位置；`## ` 標題是牌排成的**牌列**。你的牌桌**就是**一個素的 `.md` 檔：拖牌，
檔案就更新；改檔案，牌桌就更新。沒有任何東西被鎖進資料庫或私有格式。

### 從 obsidian-kanban 搬過來？

tugtile 的母語是牌，但 kanban 也說得一口流利。（GPL、已停止維護的）
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban) 的檔案直接打開就能用：
相同的 frontmatter、相同的 `- [ ]` 卡片、相同的 `%% kanban:settings %%` 區塊與相同的
`***` 封存：而且在你主動選擇「升級」之前，tugtile 原樣保留原本的標記，隨時可以回頭。
搬過來多得到的：復原／重做、為手機與 iPad 打造的編輯器，以及仍在活躍的維護。

tugtile 的前身正是幫 obsidian-kanban 寫的一堆 plugin（plugin 的 plugin），直到重做一整張
牌桌比繼續打補丁更快。從零寫起（clean-room）、**MIT** 授權。

### 亮點

- **絕不掉牌**：內建復原／重做、首次寫入前先備份、外部改檔時自動重載而非覆寫
  （由資料安全測試套件守護）。
- **雙手永遠在鍵盤上**：方向鍵把一張牌拖到同列或隔壁列，`Space`／`A`／`D` 勾選／封存／
  刪牌，`Tab` 到牌列標題再用方向鍵搬整條牌列；新增／改名牌列是可自綁熱鍵的指令。整桌牌
  理完，不用碰滑鼠。
- **在手機上活得下來的編輯器**：雙排工具列、iOS／iPad 虛擬鍵盤自動避讓；牌列與牌都能
  拖曳排序，加上日期／時間、標籤、收牌（牌庫）。
- **資料永遠是 Markdown**：人類可讀、好 diff、帶得走。同一份筆記有牌桌／牌表兩種檢視，
  想直接碰文字時還有 raw 編輯器按鈕。
- **你的語言，不是 edge case**：每一個鍵盤入口（編輯器、送出、連同牌桌的搬牌鍵）都在
  IME 組字期間讓位，中日韓的選字確認絕不被誤判成快捷鍵；長牌收合是寬度感知的；`#標籤`
  支援 CJK。六項 CJK 保證與各自的驗證方式都寫在 [CJK.md](./CJK.md)。
- **不連網、零遙測**：你的牌桌永遠不會離開 vault。

### 安裝

- **社群外掛（推薦）：** 在 Obsidian 開 設定 → 社群外掛 → 瀏覽，搜尋 **tugtile**，
  安裝後啟用。
- **手動：** 從[最新 release](../../releases/latest) 下載 `main.js`、`manifest.json`、
  `styles.css` 放進 vault 的 `.obsidian/plugins/tugtile/`，然後在 設定 → 社群外掛 啟用
  **tugtile**。
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat)（beta 版）：** 加入 `CVERInc/tugtile`。

姊妹外掛：**[marktile](https://github.com/CVERInc/marktile)**：同一顆編輯器，作為獨立的
Markdown 分頁。

**[在 cver.net 了解詳情 →](https://cver.net/zh-tw/oss/tugtile)**

---

Published by **CVER Inc.** · [cver.net](https://cver.net) · MIT License.
