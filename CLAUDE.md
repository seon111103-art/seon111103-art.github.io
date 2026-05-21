# github-site 프로젝트 가이드

## 앱 목록
- `/holiday/` — 윈드홀리데이 (황금연휴 달력)
- `/coin/` — 코인 관련
- `/exchange/` — 환율
- `/game/` — 게임
- `/gift/` — 선물
- `/realestate/` — 부동산
- `/stock/` — 주식

## 디자인 시스템
모든 앱은 `design-system.css`의 변수와 패턴을 기반으로 한다.
새 앱 만들 때 head에 추가:
```html
<link rel="stylesheet" href="/design-system.css">
```

## 공통 컬러 팔레트
- 기본색: `#2196F3` (sky blue)
- 강조: `#FF9800` (gold), `#9C27B0` (purple)
- 위험: `#F44336` (red)
- 성공: `#2E7D32` (green)
- 다크모드 배경: `#0D1B2A`

## 배포
- GitHub Pages로 자동 배포
- push 전 반드시 로컬에서 브라우저 확인

## 광고
- AdSense: `ca-pub-5695400087151759`
- 광고 태그 head에 포함 필수
