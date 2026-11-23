# Songhyun Kim — AI & Data Portfolio

A responsive multi-page portfolio website using the **Blue Professional** design direction.

## Pages
- `index.html` — Home
- `about.html` — About
- `reports.html` — AI-Generated Reports
- `certifications.html` — Qualifications & Certifications
- `activities.html` — Activities

## Design
- Main page: deep blue / navy hero and white content cards
- Subpages: pale sky-blue page headers and light backgrounds
- Responsive navigation for desktop and mobile
- Shared styles in `styles.css`; shared header/footer in `layout.js`

## GitHub integration
- Links to the GitHub organization and SK hynix DART project
- Links to the published SK hynix dashboard
- Uses the public GitHub REST API in the browser to display repository metadata and selected organization repositories
- No API token is stored in this static website

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. The workflow in `.github/workflows/deploy.yml` will publish the site after a push to `main`.
4. Expected URL: https://hsc-class02.github.io/ksh_portfolio/

## Content accuracy
The CV file previously supplied contained only the heading “입 사 지 원 서”. Therefore, no unverified LinkedIn URL, certificates, or education completion dates have been invented. Add confirmed information to the relevant HTML page when available.
