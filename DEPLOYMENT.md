# Deployment Notes

Recommended target: Cloudflare Pages.

## Cloudflare Pages

```txt
Framework preset: Astro
Build command: npm run build
Build output directory: dist
Root directory: /
Node version: 24
```

## DNS

Suggested public hostname:

```txt
chris.hj-corp.cc
```

Create a CNAME from `chris` to the Cloudflare Pages target assigned during setup.

## Before Publishing

- Add LinkedIn or resume PDF links when available.
- Confirm whether the site should remain English-only or become bilingual.
- Add real screenshots only if they do not expose private company data.
