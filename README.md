# Pet Buys UK

The second site in the same playbook as Budget Buys UK — separate repo, separate URL, same free hosting and same already-approved Amazon Associates account.

## One-time setup (only the account owner can do these — tied to identity)

1. **Turn on GitHub Pages** for this repo once pushed: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `/(root)`.
2. **Add this site's URL to the Amazon Associates website list** — same account as Budget Buys UK, no new application needed, just add `https://richardgolding28-gif.github.io/pet-buys-uk/` alongside the existing one under "Edit Your Website, Mobile App, and Alexa Skill List".
3. That's it — the tag (`trailandtarp-21`) is already active from day one since it's the same account.

## What runs on its own

Same automation pattern as Budget Buys UK: a scheduled job works through `CONTENT_QUEUE.md`, researches real current UK products, writes a new guide, commits, and pushes. GitHub Pages rebuilds automatically. FAQPage structured data and internal linking are built in from the first post, not retrofitted.

## Why this niche

Evergreen (no seasonal dead months, unlike camping/gift content), high buyer intent, and doesn't compete with Budget Buys UK's audience or search terms at all.
