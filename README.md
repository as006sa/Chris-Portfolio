# Chris Portfolio

Personal portfolio site for `chris.hj-corp.cc`.

## What Is Included

- Home page with positioning, selected projects, case summaries, timeline, skills, and contact area.
- Dedicated case pages:
  - `/projects/light-show/`
  - `/projects/intranet-systems/`
- Local visual asset for the hero preview.
- SEO metadata, sitemap generation, 404 page, and Cloudflare Pages headers.
- Cloudflare Pages deployment notes.

## Commands

```powershell
npm install
npm run dev
npm run build
npm run preview
```

Local dev URL:

```txt
http://127.0.0.1:4321/
```

## Deploy

This is a static Astro site. Deploy `dist/` to Cloudflare Pages, or connect this repository and use:

```txt
Framework preset: Astro
Build command: npm run build
Output directory: dist
```

## Before Publishing

- Add LinkedIn link if available.
- Add a resume PDF download if desired.
- Review the live Cloudflare Pages URL after deployment and then bind `chris.hj-corp.cc`.
