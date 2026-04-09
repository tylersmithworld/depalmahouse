# Outreacher — verification continuation

## What this is
`index.html` is a flat-by-instrument IG outreach list for Simen (Creative Director, Depalma House). 329 entries at start; many handles were best-guesses and are wrong or dead. Tyler is cleaning it section-by-section.

URL (live): https://depalma.house/s/outreacher/ — private, noindex, DM-only link.

## The task
For every entry in `index.html` that is **not** already marked with `<span class="m">✓</span>`:

1. Web-search the person's name + "instagram" (add a credit/city qualifier if the name is common).
2. **Loose verification:** accept if a profile exists AND the bio/content clearly matches the person (instrument, credit, city). Don't accept random accounts that just share the name.
3. **If correct handle found:** edit the `<li>` to use the correct handle in all three places (`data-k="..."`, `href="https://instagram.com/..."`, and the visible `@handle` text). Add `<span class="m">✓</span>` right after the `</a>`.
4. **If no matching profile found OR the person turns out to be the wrong instrument:** delete the `<li>` entirely.
5. **Do not add new entries.** Pure verify/prune only. Tyler accepts up to ~10% shrinkage as long as survivors are all real.

After each section, update the counter at the bottom (`<span id="cnt">0</span> / N`) to reflect the new total.

## Progress
- [x] **Bass** — done. 32 → 28. All ✓. (Removed: henrywas__, sebsteinberg, shamarallen, danhorne. Many wrong handles corrected.)
- [ ] Guitar (51 entries)
- [ ] Keys (48)
- [ ] Drums (42)
- [ ] Horns (25)
- [ ] Strings (12)
- [ ] Vocalists (58)
- [ ] Producers / Composers (30)
- [ ] Multi-Instrumentalists (19)
- [ ] Bands / Collectives (12)

Sections live in this order in `index.html`, each as a single long line right after its `<h2 id="...">` header.

## Known broken patterns to watch for
- Handles built from `firstnamelastname` or `firstnamelastnamebass` when the actual account uses an underscore, a suffix like `music` / `official`, or something totally different (e.g. `endea_owens` → `endeatheebassbae`, `tim_lefebvre` → `timlefev`, `pinopalladinoofficial` → `pino_palladino_official_`).
- Wrong-instrument collisions: e.g. `shamarallen` was in Bass but Shamarr Allen is a New Orleans trumpet player — remove, don't relocate.
- Someone's website/brand used as IG handle (e.g. `pedalsandeffects` is Juan Alderete's website; his IG is `j_alderete`).
- Common first-name accounts that are fan pages, not the artist.

## Verification format
Parallelize web searches in batches of ~20 when possible. For each entry do 1–2 searches max; don't go down rabbit holes. If uncertain after 2 searches, remove the entry.

## Files
- `index.html` — the page itself. Self-contained HTML + inline CSS + inline JS. localStorage key: `depalma-outreach-done`.
- Data model: each entry is an `<li>` with `data-k` (storage key), handle link, optional `<span class="m">✓</span>`, and `<span class="d">Name — credit</span>`.

## Deployment
Static site at `depalma.house` via GitHub Pages. After edits:
```
cd /path/to/depalmahouse
rm -f .git/HEAD.lock .git/index.lock
git add s/outreacher/index.html
git commit -m "Outreacher: verify [section]"
git push
```

## Sibling context
- Sessions booking page: `../private/x7f3/Artist_Invite.html` (the obscure URL Simen DMs to artists). Has a gear-list toggle. Don't touch unless asked.
- Auto-memory about this project: `/sessions/.../.auto-memory/project_catalog_page.md` etc. — not needed for the outreacher task.
