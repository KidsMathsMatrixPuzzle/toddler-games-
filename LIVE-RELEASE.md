# SaNa Little Hands Live v1.98

Prepared from the approved Beta source at `grajapm-hue/toddler-games-`, commit `5278cc75e8cec6903bc478512a898c9bb53c6af0`, using only its maintained `docs/beta/` application files. The user-created README is preserved.

Publish this repository's `main` branch from `/(root)`. The app entry is `index.html`; the public URL is `https://kidsmathsmatrixpuzzle.github.io/toddler-games-/`. The separate Beta remains at `https://grajapm-hue.github.io/toddler-games-/beta/index.html` for future corrections.

Live uses the name **SaNa Little Hands**, its own `sana-little-hands-live-v198-r1` cache, the project-relative manifest identity/scope, and Live-only sharing and preview URLs. The existing short install/optional-scan instructions remain in the previews. The recovery entries and updater accept only SaNa's exact project registration, so an existing MathMatrix worker at the site's root is not reused as SaNa's updater.

All game engines and artwork are identical to the approved Beta. Changes are confined to Live identity, links and installation/update setup. This preserves the existing free-building Machines experience; it adds no guided assembly or new game rules. Beta installations and saved data remain in their original app; this publication creates a separate Live app.

Validation on Naren-PC: 13 actual Chromium integration checks cover all 605 precache assets, project-relative manifest identity, a first install after the real MathMatrix root worker, independent worker scopes and caches, Live-only sharing, manual update, importing and retaining a puzzle photo offline, Machines artwork offline, and MathMatrix still opening offline afterward. Browser checks do not establish a physical phone/tablet installation result.

Run the integration check with `MM_PLAYWRIGHT` pointing to an installed Playwright package. Set `MATHMATRIX_ROOT` to a local checkout of MathMatrix Main to exercise the real root-worker coexistence case:

```text
node tools/check-live-release.cjs
```

Future releases: correct and test in Beta, then promote the approved source deliberately into this Live repository. Keep the Live name, URL, cache namespace and scoped registration checks when promoting. Verify the published files, installation/update flow and offline play after every publication.
