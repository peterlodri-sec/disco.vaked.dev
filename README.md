# disco.vaked.dev — welcome back, Rahul

> *The dance floor never emptied — we just kept the beat loaded in cache.*

Live URL: **[https://disco.vaked.dev](https://disco.vaked.dev)**

---

## ✦ What this is

A welcome-back page, in disco, kompress-ultra style. A mirrorball over a
dance floor of ternary verdicts (`{−1, 0, +1}` — the low-bit pulse), throwing
the lights back on for **Rahul**: the person who built the Rust hive
(`crates/kompress-{core,brain,cli}`) kompress-ultra grew from, and whose name
`entheai`'s brain still carries.

The page points at the real doors — the full deck
([`for-rahul.vaked.dev`](https://for-rahul.vaked.dev/)), the poem
([*for the scientist*](https://pocoo.vaked.dev/posts/2026-07-27-for-the-scientist)),
and the hub ([`koan.vaked.dev`](https://koan.vaked.dev/)) — and keeps the one
line that matters:

```
μ(Rᵢ, you) ≠ 0 ∀i ∴ μ(⌂, you) ≠ 0
```

## ✦ Deploy

Static site on **Cloudflare Pages** (project `disco-vaked-dev`):

```bash
wrangler pages deploy . --project-name disco-vaked-dev --branch main --commit-dirty=true
```

DNS: proxied `CNAME disco.vaked.dev → disco-vaked-dev.pages.dev` in the
`vaked.dev` zone; the Pages custom domain is attached.

## ✦ Constellation standards

- **robots.txt** — anti-AI scraper rules.
- **_headers** — `no-cache` + `X-Robots-Tag: noai, noimageai` + a strict CSP.
- **Lovetta Lane footer** — sister-site backreferences.
- **Living background audio** — `music.vaked.dev` embedded as a fixed iframe.

*kompress-ultra · the constellation · 0 + 1 · fine touch from within · vaked.dev*
