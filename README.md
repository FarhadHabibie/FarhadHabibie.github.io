# Portfolio — Ananda Farhad Habibie

Data Analyst / AI Agent Builder. Dark technical theme.

## Structure
```
portfolio/
├── index.html    # single-page portfolio (self-contained)
├── README.md     # this file
└── robots.txt    # crawler permission
```

## Run locally
Open index.html directly, or:
```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Edit content
All content lives in index.html:
- Projects → `<article class="card" data-cat="...">` blocks
- Email/social links → search `habibiefarhad@gmail.com`, `github.com/FarhadHabibie`, `linkedin.com/in/farhad-habibie`, `medium.com/@awesomefarhad6`
- Stats → hero `.meta-row` and terminal `.stats`
- Colors → `:root` CSS variables

Report card links currently point at Medium — replace each with the real
report/repo URL when published.

## Deploy (pick one)
- **GitHub Pages**: push folder to repo `username.github.io`, or repo + Settings→Pages
- **Netlify / Vercel**: drag-drop the folder
- **Any host**: upload via FTP — no build step needed
