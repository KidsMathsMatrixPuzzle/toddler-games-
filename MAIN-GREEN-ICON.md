# SaNa - Toddler Main: green puppy PWA icon

The Main launcher icon now uses the approved puppy with a thick green border. Beta retains its gold puppy icon. The separate circular welcome illustration, SaNa branding, app name, manifest identity `/toddler-games-/`, launch paths, scope, gameplay and saved-data keys are unchanged.

Files: `sana-puppy-green-v199-192.png` and `sana-puppy-green-v199-512.png`. Main's manifest, favicon, Apple touch icon and preview metadata select the new filenames. Legacy `icon.svg`, `icon-192.png` and `icon-512.png` also use the green tile. The old versioned gold assets remain available for previously cached references. No Beta or MathMatrix repository files change.

Cache: `sana-little-hands-live-v199-green-puppy-icon`. Fresh update entry after publication: https://kidsmathsmatrixpuzzle.github.io/toddler-games-/install-live-v1.99-green.html . Existing recovery entries target the same cache. Visible app version stays v1.99.

Validation on Naren-PC: 17 Chromium web/install-cache checks and ten actual previous-v1.99 upgrade checks passed. The processed Main name and identity, new icon URL, saved settings/photo, open game, unrelated caches and offline play are retained. Both PNG sizes, four visible green frame samples, opacity and legacy aliases were checked. The welcome image and all manifest fields except icon URLs are byte-for-byte/structurally unchanged. Offline digests and worker syntax pass. These checks do not establish a physical Android launcher's icon refresh.

## Android routing limitation remains

The user's screenshots show toddler content inside an Android task carrying the MathMatrix icon. The public MathMatrix manifest scope is `/`, enclosing Main's `/toddler-games-/` scope. Distinct manifest IDs and worker/cache scopes alone do not resolve Android link capture or nested-app installation promotion. The earlier web integration checks did not test installed Android WebAPK routing. This release changes the icon only; it does not claim to fix that routing issue.

[Google documents overlapping PWA scopes](https://web.dev/articles/building-multiple-pwas-on-the-same-domain), including manual browser-menu installation as a workaround and separate origins as the recommended architecture. Main's repository remains the canonical target. Do not move or narrow the publicly shared MathMatrix app as an incidental icon fix, or clear shared-origin user data.

## Artwork preparation

Mode: built-in image generation, editing the approved Main puppy tile. Master copied to ignored `artifacts/green-puppy/source.png`. Sharp prepares deployment dimensions and the legacy SVG wrapper. Final project assets are the versioned PNGs named above.

Exact generation prompt:

> Use case: precise-object-edit. Asset type: production PWA launcher icon for SaNa - Toddler MAIN only. Edit the attached approved puppy tile. Preserve the same puppy exactly: the white and brown silky fur, both full floppy ears, glossy eyes, black nose, tiny pink tongue, the pink-and-blue bow and hair tuft, and the full visible furry chest. Preserve the composition, expression, warm cream interior, square canvas, and recognizable artwork. Change only the existing thin GOLD OUTER FRAME into a clearly visible, thick EMERALD-GREEN rounded-square border, about 7 percent of the canvas width, smoothly following the existing rounded tile shape. Keep the entire puppy inside the border without cropping any hair, bow, ears, face or chest. Make the green strong and easy to distinguish at a tiny phone icon size, including when the launcher uses a circular mask. Keep the canvas fully opaque, with green reaching the outer edge and rounded corners blending into a pale green outer background. Do not change the puppy into a different animal or style. No words, letters, numbers, labels, watermarks, extra objects, duplicate tiles, size annotations, buttons, or mockup scene. Output one clean square app icon only.
