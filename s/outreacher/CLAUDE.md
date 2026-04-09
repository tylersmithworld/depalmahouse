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
- [x] **Guitar** — done. 51 → 49. All ✓. (Removed: gregleisz, smokeyhormel. Major handle corrections: adambrisbin→young_gumby, buck_meek→buckmeek, corywong→coryjwong, giladhekselman→ghex, harrisonwhitford→scarrisonwhitford, ichika_nito→ichika_mo, indigodesouza→indigofaraway, isaiahsharkey→sharkey335, jairusmozee→jmothegreat, jonathanwilsonmusic→nongmopaleovapedaddy420, julianlageguitar→jlage, madeline_kenney→mkenneymusic, mayadelilah→mayadelilahh, megbaird→meglingbaird, morganburrs→steelstring_player, nickhakim→en_hakim, niluferyanya→niluferyanyaaaaaa, pedromartinsmusic→pedromartins93, porridgeradio→danamargolin, samevian→sam.evian, scotte_lepage→scottielepage, thiagonassif→thiagonassifs, timhenson→thew6rst, yvettecy→yvetteyoung.)
- [x] **Keys** — done. 48 → 48. All ✓. (No removals. Handle corrections: adammacdougall→macdougallkeys, alfa_mist→alfamist, benmont_tench→benmonttench, bennysings→bennysingsmusic, bigyukimusic→bigyuki, charlieburg→burgchar, domi_louna→domi_keys, drewerickson→red_erickson, emmetcohen→heyemmet, jaharistampley→jaharistampleymusic, jamesfrancies→jamesfrancies88, jeremiah_chiu→jeremiahchiu, jordanrakei→jrakz, juliusrodriguez→orangejuliusmusic, kiefer→kiefdaddysupreme, mathispicard→oui_mathispicard, nicksemrad→nicholastsemrad, nicolezpiano→nicolezmusic, patrickbartleyjr→patbartmusic, patrickwarrenmusic→patrickwarren1, scottkinseymusic→scottkinsey1, simonmavin→mmsimonmm, spelllinglive→spellling, taylor.eigsti→tayloreigsti.)
- [x] **Drums** — done. 42 → 42. All ✓. (No removals. Handle corrections: adamrudolph→rudolphpercussion, ajspears→aspears, andresrenteria→dopolous, blaqklist→blaquedynamite, calvinrodgersdrums→calvinr_rodgers, carlosninomusic→carlosninoxperience, chrisdaveoffl→chrisdaddydave, christophersmithiii→chrissmithjazzdrums, ericmooremusic→ericmoore_ii, genecoye→genecoyedrums, jdbeck__→jdbeckmusic, jonathanbarbermusic→jonathanb_live, justincbrown→drumbrownie, kushabadey→kushthedrummer, marcusgilmore1→drummerslams, mattchamberlaindrums→mattdrumsboom, perrinmoss→perrinpezza, philippe.melanson→philippemelanson, savannahharris_→savvyknows, sputnificent→sputacular, tonyaustinmusic→tonyaustindrums, toshpeterson→tosh_thedrummer, tpridgen→thomaspridgen.)
- [x] **Horns** — done. 25 → 24. All ✓. (Removed: jazzmeiahorn — vocalist, not horn player, last name is "Horn". Handle corrections: aaronshawmusic→sheets0fsound, alex_hahn_sax→realalexhahn, braxtoncook→braxton_cook, cautiousclay→cautiousxclay, emmajeanthackray→ejthackray, givetongelin→giveton, immanuel_wilkins→immanuel.wilkins, isaiahcollier_→colliersworld, luckychopsofficial→theluckychops, melissaaldana→melissaaldanasax, rudreshmahanthappa→rudreshkm, tennishu→tenn1sh2, tivonpennicott→tivon_bzz.)
- [x] **Strings** — done. 12 → 11. All ✓. (Removed: hanskjorstad — no Instagram found. Handle corrections: brandeeyounger→harpista, carolinehshaw→carolineadelaideshaw, miguelaf→miguelatwoodferguson, robmoose→mooserob, saracaswellviolin→saracaswellvln, zachbrock→zachdbrock.)
- [x] **Vocalists** — done. 58 → 57. All ✓. (Removed: antoniacytrynowicz — no Instagram found. Handle corrections: _jordanward→jordanward, akaisolo→shinlonered, ambermarkmusic→instagramber, anna_wise→annathewise, budddy→buddy, casscombs→cassmccombs, cleosol→gyallikeclee, devinmorrisonmusic→devinjmorrison, georgiaannemuldrow→georgia.muldrow, hannahcohenmusic→misshannahcohen, ilevitable→cabralu, jonwayne→jwayniac, kenyondixon→kennygotsoul, lailaloveless→prodlaila, liv.e→_osun, lrainofficial→turrelljames, luckydaye→iamluckydaye, maassai→maassai_, navy.blue→sageelsesser, nourishedbytime→nourishedbytime_, oliviadean→oliviadeano, samarajoy99→samarajoysings, silvanaestrada→silvanaestradab, yayabey_→yayabeybay, yunamusic→yuna.)
- [x] **Producers / Composers** — done. 30 → 30. All ✓. (No removals. Handle corrections: 0pn→eccopn, dibiase→darealdibiase, dmileofficial→dmile85, dntel→jimmytamborello, estasoulection→esta, evilneedle→itsmeneedle, jameszoo→jameszoooo, mattmartians→matt_martians, micachu→goodsadhappybad, monsterrally→monster_rally, mrcarmack→mr_carmack, nathanbarr→composerbarr, pinknavel→dotdev_, takumusic→takubeats.)
- [x] **Multi-Instrumentalists** — done. 19 → 18. All ✓. (Removed: jackstrattonmusic — Jack Stratton has no personal Instagram. Handle corrections: antonioloureiro→antonioloureiromusic, cliffbeach→cliffbeachmusic, francesca.heart→serpentinedance, gingerrootband→gingerrootmusic, hethermusic→hether, joelrossvibes→imjoelmross, jonbrion→jonbrion2022, lutalo.mp3→lutalojones, ohno→ohnothedisrupt, senmorimoto→sen_morimoto, thekoreatownoddity→ktownodd, twainmusic→twainband.)
- [x] **Bands / Collectives** — done. 12 → 12. All ✓. (No removals. Handle corrections: butcherbrownmusic→butcherbrown, drugdealerzone→drugdealer, inc.noworld→inc_no_world, michelletheband→wearemichelle, moonchildmusic→thisismoonchild, okeydokeyband→okeydokey, orgoneband→orgonemusic, vansire→vansiretheband.)

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
