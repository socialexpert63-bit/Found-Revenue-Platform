# Found Revenue – Website & RevenueRecover OS Dashboard (Concept Prototype)

Two static, dependency-free pages:

| Path | What it is |
|---|---|
| `index.html` | Marketing website: animated hero, product film, five AI demos, calculator, contact form |
| `dashboard/index.html` | RevenueRecover OS dashboard: leak finder, seven-stage AI analyst, quotes, response times, workflows, action center, calculator |

> **Important:** this is a concept prototype. All businesses, people, figures and reviews are **fictional demo data**. Revenue numbers are illustrative estimates, not client results. The AI features are scripted simulations (no live AI), the contact form sends nothing, and there are no CRM or messaging integrations.

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages
1. Create a new GitHub repository and push these files to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Your site will appear at `https://<username>.github.io/<repo>/` and the dashboard at `.../dashboard/`.

## Push from the command line
```bash
git init
git add .
git commit -m "Initial commit: Found Revenue website and dashboard prototype"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

## Notes
- The website links to the dashboard with the relative path `./dashboard/`.
- Fonts load from Google Fonts; everything else is self-contained.
- The brand name, logo mark and copy are placeholders prepared for discussion; replace with approved branding before any public use.
