# aibreakthrough.ai

GitHub Pages site for **aibreakthrough.ai**.

## Layout

```
/                 site root (index.html)
/intelligence/    redirects to the one-page brief PDF
/explainers/      SAGE explainer videos (mp4 + poster frames)
/investors/       redirects to the seed/angel investor brief PDF
CNAME             custom domain: aibreakthrough.ai
.nojekyll         serve files as-is (no Jekyll processing)
```

## Publishing

Pages is served from the `main` branch, root (`/`). Push to `main` to deploy.

## DNS

Point the apex domain at GitHub Pages:

| Type  | Name | Value |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | inevitable-systems.github.io |
