# rae-dojo — one router skill for your whole panel of experts

A private Claude **plugin marketplace** containing a single skill, **`dojo`**, that routes any
question to the right expert advisor (or convenes a small panel) and reads that expert's persona
and topic files on demand. Install it once and it works in **Cowork and in every chat and
Project** on your account.

This replaces ~120 separate expert skills cluttering the `/` picker with **one clean entry**
that (a) routes reliably from a categorised index, (b) can convene multi-expert panels, and
(c) keeps your context light — only the small router loads up front; full persona content is
pulled only for the expert(s) actually needed.

## Roster — complete

- **120** experts, **every one with a full persona library** (persona + topic files).
- Recovered directly from your synced Claude account after the original laptop was lost, so
  nothing is missing — including the experts that weren't in your last export (Sen, Ostrom,
  Alan Watts, Cal Newport, Peter Attia, Timothy Snyder, Vaclav Smil, and the rest), plus
  John Rawls.

## What's in here

```
rae-dojo-marketplace/
├── .claude-plugin/marketplace.json
├── README.md
├── LICENSE
└── plugins/
    └── dojo/
        ├── .claude-plugin/plugin.json
        └── skills/
            └── dojo/
                ├── SKILL.md            # the router + full categorised expert index
                ├── _INDEX_SNAPSHOT.md  # standalone copy of the index
                └── experts/
                    ├── dojo-brene-brown/
                    │   ├── persona.md
                    │   ├── _expert.md   # the expert's original routing/topic map
                    │   └── <topic>.md …
                    └── …                # 120 expert folders
```

There is exactly **one** `SKILL.md` in the plugin, so it loads as a single skill named `dojo`
(invoked as `dojo:dojo`). The `experts/` folders are reference material, not separate skills.

## Publish it (one-time)

```bash
cd rae-dojo-marketplace
git init
git add .
git commit -m "Rae's dojo router skill — 120 experts"
git branch -M main
git remote add origin https://github.com/<your-username>/rae-dojo-marketplace.git
git push -u origin main
```

## Install it in Claude (one-time)

1. **Customize** (left sidebar) → **Plugins** tab.
2. Under **Personal plugins**, click **“+”** → **Add marketplace** → **Add from a repository**,
   and paste your repo URL (or `your-username/rae-dojo-marketplace`).
3. The **dojo** plugin appears — click **Install**.

Then, in any chat or in Cowork: say **"ask dojo …"**, name a thinker, or ask "what would Patton
say about this evaluation design?" — the router loads, picks the expert(s), reads their persona,
and answers in voice.

## Back up your library (do this now)

Because the whole set is here in one place, this repo doubles as your **backup**. Once it's on
GitHub, your 120 personas are safe from any single machine failing again. Keep the repo private.

## Retire the old individual skills

Once you've confirmed the router works, remove the ~119 individual dojo skills under **Customize
→ Skills** so you don't see both `dojo-brene-brown` (old upload) and the router. Do this only
after testing.

## Update it later

Edit files, then `git add . && git commit -m "…" && git push`. In Claude, **Customize → Plugins
→ update the marketplace**. Because `plugin.json` has no pinned `version`, every push is treated
as a new version, so it refreshes automatically.
