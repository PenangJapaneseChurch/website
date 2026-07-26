# Penang Japanese Church（ペナン日本人教会）

A Japanese Christian church in Penang, Malaysia — built with [EmDash](https://github.com/emdash-cms/emdash) and deployed on Cloudflare Workers + D1 + R2.

## Site

https://penang.japanesechurch.workers.dev

## Tech Stack

- **CMS:** EmDash (MIT, open-source)
- **Runtime:** Cloudflare Workers (SSR)
- **Database:** Cloudflare D1
- **Storage:** Cloudflare R2
- **Framework:** Astro 7 with `@astrojs/cloudflare`

## Local Development

```bash
pnpm install
pnpm dev
# → http://localhost:4321
```

## Deploy

```bash
pnpm deploy
# → Cloudflare Workers
```

## License

MIT — same as EmDash.
