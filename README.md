# Project Homepage

Static single-page site for the paper. Deploy with GitHub Pages by pointing the
repository's Pages source at `/docs` on this branch (or merge to `main` and use
`/docs` from `main`).

```
docs/
├── index.html          # the homepage
└── static/
    ├── style.css
    └── images/         # figures copied from ../figures
```

Open locally with `python3 -m http.server -d docs 8000`.
