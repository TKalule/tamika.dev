# tamika.dev

Personal one-page site for Tamika Kalule — Product & Engineering Lead, London.

Static HTML + CSS, no build step, no dependencies.

## Files

```
.
├── index.html          markup
├── styles.css          all styling (incl. dark/light, responsive)
├── images/
│   ├── avatar.jpg      hero portrait
│   ├── IMG_*.jpg       gallery photos
│   └── logos/          school / training logos (SVG)
└── docs/               design history (gitignored)
```

## Develop

Open `index.html` in any browser:

```sh
open index.html
```

For a real local server (recommended — keeps relative paths and mailto behaviour clean):

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Drop the three top-level assets (`index.html`, `styles.css`, `images/`) onto any static host:

- **GitHub Pages** — push to a repo, enable Pages on `main` / root.
- **Netlify / Vercel** — drag-and-drop the folder, or connect the git repo.
- **Custom host** — `rsync` or upload the files.
