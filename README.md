# AI Harms Monitor — GitHub Pages working version

Auto-updating GitHub Pages app.

## Upload structure

Upload the repo with this structure:

```text
.github/workflows/pages.yml
public/harm_categories.json
public/news_data.json
public/sources.json
public/trusted_domains.json
scripts/update_news.py
src/main.jsx
src/style.css
index.html
package.json
vite.config.js
```

## GitHub Pages

Settings → Pages → Source: GitHub Actions.

Then Actions → Update and publish AI Harms Monitor → Run workflow.
