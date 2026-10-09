# lethevinh.github.io

Personal portfolio site for Vinh Le — automation systems.

Served by GitHub Pages (user site) at https://lethevinh.github.io/

## Update rule

When a new workflow lands in
[automation-workflows](https://github.com/lethevinh/automation-workflows),
add a matching card in the S-01 grid of `index.html` and bump the spec
strip totals. The site is intentionally a curated snapshot — it updates
on every new project, not on every commit, so visitors can see it's alive.

## Maintainer notes

- Testimonial slot: when a real client quote exists, add a `.quoteframe`
  block inside the S-06 hire box (markup was removed 2026-10-09 because a
  visibly empty quote slot reads as unfinished). Never publish a quote
  that was not actually given.
- Social card: `og-card.png` is generated art (1200x630) — regenerate it
  if the tagline or palette changes.
