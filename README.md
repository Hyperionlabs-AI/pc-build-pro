# PC Build Pro — Realistic Builds

Small static web project that displays PC build data and custom news.

## Contents
- `index.html` — main page
- `assets/app.js` — application JavaScript
- `assets/styles.css` — styles
- `pc_build_matrix_normalized.json` — build data
- `custom_news.json` — news/announcements data

## Run locally
You can preview the site by opening `index.html` in a browser, but a simple HTTP server is recommended to avoid CORS/asset issues:

Python 3 (built-in):
```bash
python -m http.server 8000
# then open http://localhost:8000
```

Node (http-server):
```bash
npm install -g http-server
http-server -c-1
```

## Development
- Edit UI/logic in `assets/app.js` and styling in `assets/styles.css`.
- Data files are JSON at the repo root — update `pc_build_matrix_normalized.json` or `custom_news.json` as needed.

## Deployment
- This is a static site; you can host it using GitHub Pages (enable Pages from the `main` branch, `/` root), Netlify, Vercel, or any static hosting.

## Contributing
- Open issues or PRs on GitHub. Keep changes small and document data schema changes.

## License
Add a license file (e.g., `LICENSE`) if you want to make this repository explicitly reusable. MIT is a common choice.

---
Generated README for `pc-build-pro`.
