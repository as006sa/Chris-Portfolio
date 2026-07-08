# Chris Portfolio

Resume-style portfolio site for `chris.hj-corp.cc`.

This site presents Chris Tsai's full-stack work around enterprise workflow systems, internal tools, and a live public product.

## Live Links

- Portfolio target domain: `https://chris.hj-corp.cc/`
- Public product: `https://lighting.hj-corp.cc/`
- GitHub profile: `https://github.com/as006sa`

## What Is Included

- Resume-style home page with positioning, target roles, selected projects, recent delivery record, ownership notes, skills, and contact area.
- Dedicated case pages:
  - `/projects/light-show/`
  - `/projects/intranet-systems/`
- Public Light Show screenshots that exclude admin/private data.
- SEO metadata, sitemap generation, 404 page, and Cloudflare Pages headers.
- Cloudflare Pages deployment notes.
- GitHub Profile README draft at `docs/github-profile-readme.md`.

## Stack

- Astro
- TypeScript
- Static output
- Cloudflare Pages target
- `@astrojs/sitemap`

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

The build produces:

- Static pages
- `sitemap-index.xml`
- `404.html`
- Cloudflare Pages `_headers`

## Before Publishing

- Add LinkedIn link if available.
- Add a resume PDF download if desired.
- Review the live Cloudflare Pages URL after deployment and then bind `chris.hj-corp.cc`.
