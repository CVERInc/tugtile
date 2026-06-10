[English](README.md) · [日本語](README.ja.md) · **한국어** · [繁體中文](README.zh-TW.md)

# tugtile

**[Obsidian](https://obsidian.md)을 위한 Markdown 네이티브 칸반 보드. 타일을 끌어서 정렬.**

tugtile은 어떤 Markdown 노트든 칸반 보드로 바꿉니다. 레인은 `## ` 제목, 카드(**타일**이라고
부릅니다)는 `- [ ]` 작업 목록 항목입니다. 보드는 그 자체로 평범한 `.md` 파일입니다 —
타일을 드래그하면 파일이 갱신되고, 파일을 편집하면 보드가 갱신됩니다. 데이터베이스나
독자 포맷에 갇히는 것은 아무것도 없습니다.

## obsidian-kanban에서 옮겨오시나요?

보드가 그대로 열립니다. tugtile은 (GPL, 유지보수가 중단된)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban)과 같은 frontmatter, 같은
`- [ ]` 카드, 같은 `%% kanban:settings %%` 블록, 같은 `***` 아카이브를 읽고 쓰며,
"업그레이드"를 직접 선택하기 전까지 원래 마커를 그대로 유지합니다 — 언제든 돌아갈 수
있습니다. 옮겨오면 얻는 것: 실행 취소/다시 실행, 휴대폰과 iPad를 위해 만들어진 에디터,
그리고 활발한 유지보수. 처음부터 새로 작성된(clean-room) **MIT** 구현입니다.

## 하이라이트

- **데이터는 언제나 Markdown** — 사람이 읽을 수 있고, diff 친화적이며, 어디로든 가져갈 수
  있습니다. 같은 노트를 보드/테이블 두 가지 뷰로, 텍스트를 직접 만지고 싶을 때는 raw
  에디터 버튼도 있습니다.
- **실행 취소/다시 실행 내장** — 보드 조작은 되돌릴 수 있습니다.
- **휴대폰에서 살아남는 에디터** — 2단 툴바, iOS/iPad 가상 키보드를 따라가는 레이아웃,
  레인·타일 드래그 정렬, 날짜/시간, 태그, 아카이브.
- **CJK 우선, 구체적으로** — IME 조합 중에는 재하이라이트를 멈춰 한국어 입력이 끊기지
  않습니다. `#태그`도 CJK 지원, 정렬은 로케일 인식 비교를 사용합니다.
- **네트워크 없음, 텔레메트리 없음** — 보드는 vault 밖으로 나가지 않습니다.

## 설치

- **수동:** [최신 릴리스](../../releases/latest)에서 `main.js`, `manifest.json`,
  `styles.css`를 vault의 `.obsidian/plugins/tugtile/`에 넣고, 설정 → 커뮤니티 플러그인에서
  **tugtile**을 활성화하세요.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat):** 베타 플러그인 `CVERInc/tugtile` 추가.

자매 플러그인: **[marktile](https://github.com/CVERInc/marktile)** — 같은 에디터를 독립된
Markdown 패널로.

---

**CVER Inc.** · [cver.net](https://cver.net) · MIT License
