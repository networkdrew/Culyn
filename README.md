# Culyn

Culyn's personal corner of the internet — a MySpace-inspired personal hub,
themed around whatever she's into (KATSEYE, Lilo & Stitch, HonestAV right
now). Deployed as a static Cloudflare Worker at **culyn.drewcassidy.dev**.

Intentionally **not** linked from the [drewcassidy.dev](https://drewcassidy.dev)
root hub — this is a personal/family page, not part of the public portfolio.
It's the first of what will be a page per family member.

Projects/apps for her live flat off the root, e.g.
`culyn.drewcassidy.dev/csread/` — no repeated prefix.

## Projects

- **`csread/`** — Culyn & Stitch's Reading Time — a Lilo & Stitch themed
  reading session timer with collectible 'Ohana treasures. Previously its
  own repo/domain (`networkdrew/culynandstitchreadingtime`,
  `csreading.drewcassidy.dev`), folded in here.

## Local dev

```
npx http-server .
```

## Deploy

```
wrangler deploy
```

## Adding something new for her

1. Create a new top-level folder, e.g. `foo/`, self-contained.
2. Add a card for it in the "My Stuff" grid on the root `index.html`.
3. Deploy.
