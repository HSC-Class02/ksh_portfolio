# Songhyun Kim — AI & Data Portfolio

김송현의 AI·데이터 포트폴리오 웹사이트입니다. 디자인 방향은 **Blue Professional**이며, 메인 페이지는 딥블루 히어로와 흰색 콘텐츠 카드, 하위 페이지는 하늘색 헤더와 밝은 배경으로 구성했습니다.

## Website pages
- `index.html` — 메인 대시보드 및 대표 프로젝트
- `about.html` — 소개, 학력·전공, 관심 분야
- `reports.html` — AI-Generated Reports 및 GitHub 프로젝트 연동
- `certifications.html` — 자격증 및 교육 수료 이력
- `activities.html` — 프로젝트 및 교내외 활동

## Featured projects
### SK hynix DART Financial Analysis
- Repository: https://github.com/HSC-Class02/SH_SKhynix
- Dashboard: https://hsc-class02.github.io/SH_SKhynix/
- DART 공시 자료를 활용한 기업 재무 데이터 수집·분석 프로젝트

### Cornerstone — 수어 의사소통 보조도구
- 수어카드와 아두이노 LED 무드등 키링을 결합한 시제품
- 거리 감지 센서에 따라 LED 색상이 순차적으로 바뀌도록 구현
- 수어를 직접 촬영한 카드를 제작해 의미를 시각적으로 전달

## GitHub integration
- GitHub 조직 및 대표 프로젝트로 연결되는 링크를 제공합니다.
- 브라우저에서 공개 GitHub REST API를 호출해 대표 저장소의 공개 메타데이터를 표시합니다.
- API 토큰이나 비밀키를 프런트엔드 코드에 저장하지 않습니다.

## Design system
- Main page: deep navy / blue hero, white cards
- Subpages: pale sky-blue headers, white and light-blue content areas
- Responsive navigation for desktop and mobile
- Shared styles: `styles.css`
- Shared navigation/footer: `layout.js`
- GitHub API integration: `app.js`

## Deploy with GitHub Pages
1. Repository Settings → Pages로 이동합니다.
2. Build and deployment의 Source를 **GitHub Actions**로 설정합니다.
3. `.github/workflows/deploy.yml`이 `main` 브랜치 업데이트 후 사이트를 배포합니다.
4. 예상 주소: https://hsc-class02.github.io/ksh_portfolio/

## Content accuracy
- 제공된 이력서에서 확인되는 학력은 2026–2029 한림성심대학교 치위생과입니다.
- 현재 확인된 자격증·교육 수료 내역은 없어 임의로 기재하지 않았습니다.
- LinkedIn 주소는 아직 제공되지 않아 연결 대기 상태로 표시합니다.
- 전화번호, 주소, 생년월일 등 공개 포트폴리오에 불필요한 개인정보는 게시하지 않습니다.
