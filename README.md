# Simple Folder Note

A minimal Obsidian plugin that treats a `.md` file with the same name as its folder as a "folder note."

## Features

- **Hide from file explorer** — the folder note file is not shown duplicated alongside its folder
- **Click folder → open note** — clicking the folder name in the file explorer opens its folder note in the current tab

## Folder note conventions

Both layouts are supported (priority: **inside → outside**):

| Type | Example path |
|---|---|
| Inside | `Ideas/Good Story/Good Story.md` |
| Outside | `Ideas/Good Story.md` (next to the folder) |

## Installation

### Manual

1. Download `main.js` and `manifest.json` from the [latest release](https://github.com/HEONO3H/simple-folder-note/releases/latest)
2. Copy them to your vault's `.obsidian/plugins/simple-folder-note/` folder
3. Reload Obsidian → Settings → Community plugins → Enable

### BRAT (beta)

1. Install the [BRAT plugin](https://github.com/TfTHacker/obsidian42-brat)
2. BRAT settings → `Add Beta Plugin` → enter `HEONO3H/simple-folder-note`

## License

MIT

---

## 한국어 (Korean)

폴더와 같은 이름의 `.md` 파일을 "폴더 노트"로 취급하는 최소 기능 Obsidian 플러그인.

### 기능
- **탐색기에서 숨기기** — 폴더 노트 파일이 파일 탐색기에 중복 노출되지 않음
- **폴더 클릭 → 노트 열기** — 파일 탐색기에서 폴더명 클릭 시 해당 노트가 현재 탭에 열림

### 폴더 노트 인식 규칙
두 가지 구조 모두 지원 (우선순위: **안쪽 → 바깥쪽**).

| 종류 | 경로 예시 |
|---|---|
| 안쪽 | `Ideas/좋은 이야기/좋은 이야기.md` |
| 바깥쪽 | `Ideas/좋은 이야기.md` (폴더와 같은 레벨) |

### 설치
수동 설치: [최신 릴리스](https://github.com/HEONO3H/simple-folder-note/releases/latest)에서 `main.js`, `manifest.json`을 볼트의 `.obsidian/plugins/simple-folder-note/`에 복사 후 재시작.

BRAT: `Add Beta Plugin` → `HEONO3H/simple-folder-note` 입력.
