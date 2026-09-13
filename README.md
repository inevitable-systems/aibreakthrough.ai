# aibreakthrough.ai

GitHub Pages site for **aibreakthrough.ai**.

## Layout

```
/                 site root (index.html)
/intelligence/    hosts a single-page PDF
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
| CNAME | www  | PaulCharlton.github.io |
