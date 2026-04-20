# Simple Folder Note

폴더와 같은 이름의 `.md` 파일을 "폴더 노트"로 취급하는 최소 기능 Obsidian 플러그인.

## 기능

- **탐색기에서 숨기기** — 폴더 노트 파일이 파일 탐색기에 중복 노출되지 않음
- **폴더 클릭 → 노트 열기** — 파일 탐색기에서 폴더명 클릭 시 해당 노트가 자동으로 열림

## 폴더 노트 인식 규칙

두 가지 구조 모두 지원합니다.

| 종류 | 경로 예시 |
|---|---|
| 안쪽 (Inside) | `Ideas/좋은 이야기/좋은 이야기.md` |
| 바깥쪽 (Outside) | `Ideas/좋은 이야기.md` |

## 설치 방법

### 수동 설치
1. [Releases](https://github.com/HEONO3H/simple-folder-note/releases/latest)에서 `main.js`, `manifest.json` 다운로드
2. 볼트의 `.obsidian/plugins/simple-folder-note/` 폴더에 복사
3. Obsidian 재시작 후 설정 → 커뮤니티 플러그인에서 활성화

### BRAT으로 설치
1. [BRAT 플러그인](https://github.com/TfTHacker/obsidian42-brat) 설치
2. BRAT 설정에서 `Add Beta Plugin` → `HEONO3H/simple-folder-note` 입력

## 라이선스

MIT
