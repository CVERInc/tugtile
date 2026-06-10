[English](README.md) · [日本語](README.ja.md) · **한국어** · [繁體中文](README.zh-TW.md)

# tugtile

**[Obsidian](https://obsidian.md)을 위한 Markdown 기반 칸반 보드. 타일을 끌어 순서를 바꾸세요.**

tugtile은 모든 Markdown 노트를 칸반 보드로 바꿉니다. 레인은 `## ` 제목, 카드(우리는
**타일**이라 부릅니다)는 `- [ ]` 작업 목록 항목입니다. 보드가 곧 평범한 `.md` 파일입니다——
타일을 끌면 파일이 갱신되고, 파일을 편집하면 보드가 갱신됩니다. 데이터베이스나 독점 형식에
갇히지 않습니다.

클린룸 구현 · **MIT** · CJK 친화적. (GPL이며 더 이상 유지보수되지 않는)
[obsidian-kanban](https://github.com/mgmeyers/obsidian-kanban)과 형식 호환——같은
frontmatter, 같은 `- [ ]` 카드, 같은 `%% kanban:settings %%`, 같은 `***` 보관——그래서
기존 보드를 그대로 읽고 씁니다.

## 설치

- **수동:** [최신 릴리스](../../releases/latest)에서 `main.js`, `manifest.json`,
  `styles.css`를 보관함의 `.obsidian/plugins/tugtile/` 폴더에 넣고, 설정 → 커뮤니티
  플러그인에서 **tugtile**을 활성화하세요.
- **[BRAT](https://github.com/TfTHacker/obsidian42-brat):** 베타 플러그인으로
  `CVERInc/tugtile`을 추가하세요.

## 특징

- **데이터는 Markdown 그대로**——사람이 읽을 수 있고, diff에 친화적이며, 이식성이 좋습니다.
- **실행 취소 / 다시 실행** 내장(kanban은 불가).
- 레인·카드 끌어 순서 바꾸기, 날짜/시간, 태그, 보관, 보드 / 테이블 보기.
- **CJK 우선**, 데스크톱과 모바일 / iPad에서 동작.

자매 플러그인: **[marktile](https://github.com/CVERInc/marktile)**——같은 편집기를
독립 Markdown 창으로.

---

발행: **CVER Inc.** · [cver.net](https://cver.net) · MIT License
