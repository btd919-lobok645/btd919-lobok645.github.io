# 환진 (桓辰) 홈페이지

> 창의적인 사고와 혁신적인 기술로 새로운 세상과 연결하는 기업

주소: https://btd919-lobok645.github.io

## 파일 구조

| 파일 | 내용 |
|---|---|
| `index.html` | 홈 — 각 페이지로 안내 |
| `about.html` | 회사소개 — 사명, 슬로건 |
| `products.html` | 제품소개 — 무선제어, DIY 키트, 장애인 보조기기, 아이디어 제품 |
| `log.html` | 작업기록 — 날짜별 진행 상황 |
| `style.css` | 전체 페이지 공통 스타일 |
| `logo.svg` | 로고 (원형 + HJ + Hwan-Jin) |
| `logo-mark.svg` | 심볼만 — 파비콘용 |
| `logo-wide.svg` | 가로형 — 넓은 공간용 |

## 작업 방법

1. VS Code로 폴더 열기
2. **Sync Changes** (또는 Pull) — 다른 PC에서 바꾼 내용 받아오기
3. 우측 하단 **Go Live** — 로컬 미리보기 시작 (127.0.0.1:5500)
4. 파일 수정 후 `Ctrl + S` — 브라우저가 자동 새로고침
5. Source Control에서 메시지 입력 → **Commit**
6. **Sync Changes** — GitHub에 반영 (실제 사이트는 1~2분 뒤)

## 메모

- 페이지 추가 시 모든 파일의 `<nav>` 에 링크를 넣어야 함
- 현재 페이지 링크에는 `class="current"` 를 붙임
- 화면 폭 600px 이하는 `style.css` 맨 아래 `@media` 블록에서 처리
- 브라우저 캐시로 변경이 안 보이면 `Ctrl + Shift + R`

## 색상

- 브랜드 블루: `#1a5490`
- 로고 블루: `#1e40af`