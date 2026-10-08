# Published preview changelog

Each entry links a public preview to its exact source revision in the private [woodz_witch_fashion](https://github.com/ToniDonDoni/woodz_witch_fashion) project. Access to private links requires repository permission. Source snapshots for the gallery and audience runway were archived after publication from the exact local source files; they are not retrospective claims of a commit-driven build pipeline.

## Living acts — experimental candidate

- **Preview:** [Into the woods, staged in acts](https://tonidondoni.github.io/woodz-witch-fashion-preview/living-acts/).
- **Public path:** `living-acts/index.html`.
- **Primary source PR:** [#12](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/12), source revision [`70ad1ad`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/70ad1ad1550f57faaaef8ce4432cc01a62b4903d).
- **Editable sources:** `out/runway-acts/` and the built `out/runway-acts/index.html` at that revision.
- **Build:** `python out/runway-acts/build.py` with Pillow, using the 33 PNG frames in `assets/walk/`.
- **Published HTML Git blob:** `fc36d41c0f7c0d696b5e0d1964b8583c30c1c993`.
- **Published HTML SHA-256:** `355e04ab7629f97fe32b6d9377137bab34242d30a02e1ef0c7d88ecc5ee6ab4c`.
- **Changes:** seeded act director with per-act lengths (30-62 s), title cards, per-act weather, seven signature set pieces and two rare cameos; a per-dream colour grade that leaves the walker's own colours untouched; a faster foreground row composited after the walker so it occludes her sneakers; seed-derived woodland layout so `NEW DREAM` reshuffles the world.
- **Verification:** offline headless Chromium at four viewport sizes with no runtime errors and no network requests; every act theme and signature event reaches the stage over 40 acts; act starts are contiguous and act lengths vary; deterministic rendering of identical simulated times; bounded caches and object counts over ten sampled minutes plus a one-hour seek; pixel differencing proves the foreground row changes the walker's legs by 34.6 grey levels and nothing above them; the embedded walk frames are byte-identical to the previous build.
- **Limitations:** the inherited 32-to-0 gait seam is unchanged; physical-phone performance is unmeasured.

## Release Candidate GPT — moonlight and fog

- **Preview:** [Release Candidate GPT](https://tonidondoni.github.io/woodz-witch-fashion-preview/release-candidate-gpt/).
- **Public candidate PR:** [#5](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/pull/5), artifact commit [`8df86b9`](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/commit/8df86b91b2b15db0e7f2456301f0736b41aefc74).
- **Primary source PR:** [#10](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/10), source revision [`441cf8e`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/441cf8e39532ede2da156b5f3ac2f65d1ef972d2).
- **Editable sources:** `out/release-candidate-gpt/` and built `site/release-candidate-gpt/index.html` in that source revision.
- **Artifact Git blob:** `c73149f2142f99a5cac7d9ef1fbbc9855849b250` (identical in both repositories).
- **Build:** `python out/release-candidate-gpt/build.py`; combines the 33 unchanged source sprites, published spectators, current moonlit sky, and the added Canvas 2D atmosphere.
- **Effects:** stable tree-ID canopy-linked silver moonbeams, one smooth scrolling, precomputed periodic-noise fog band, and a LIGHT ON/OFF comparison switch. The existing public root runway is unchanged.
- **Verification:** JavaScript compiled and exercised with browser-API stubs (initialization, seek determinism, toggle identities, bounded caches). A real offline browser CI run is linked from primary PR #10. Phone performance acceptance and final visual review remain pending.

## Forest audience — current runway

- **Preview:** [The forest is watching](https://tonidondoni.github.io/woodz-witch-fashion-preview/).
- **Public artifact commit:** [`f317769`](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/commit/f317769d79449ac4c39a5655c3fc07c8854f72ea), [publication PR #3](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/pull/3).
- **Exact archived source revision:** [`0e6cf29d4059e305a975a77fade10cb3f7a1ecb2`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2).
- **Sources and built artifact:** [`out/forest-spectators/`](https://github.com/ToniDonDoni/woodz_witch_fashion/tree/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2/out/forest-spectators).
- **Build:** `python out/forest-spectators/build.py` with Pillow, using the 33 PNG frames in `assets/walk/` at the same source revision.
- **Published HTML Git blob:** `434db5a823e39df15507a87c90a73a3924c36c32`.
- **Published HTML SHA-256:** `1a2090d89cb067af41536710b3b5242b85842e34c00d060be91842150fedf7cc`.
- **Changes:** add eight neon chalk character studies as persistent forest spectators behind the walker; smooth travel right, pupils tracking her, 12 Hz contour redraws, bounded caches and deterministic phase-time art.
- **Verification:** the archived HTML blob matches the public root artifact exactly. All 33 inherited sprite blobs match the local build inputs. Offline rendering, two-minute identity/cache checks and four viewport layouts passed.
- **Limitations:** the existing source gait seam is unchanged; physical-phone performance remains unmeasured.

## Neon creature studies — separate gallery

- **Preview:** [Forest oddities](https://tonidondoni.github.io/woodz-witch-fashion-preview/studies/neon-creatures/).
- **Public artifact commit:** [`fb67ea7`](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/commit/fb67ea78f32ef373b688048eb167619754c2608b), [publication PR #2](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/pull/2).
- **Exact archived source revision:** [`0e6cf29d4059e305a975a77fade10cb3f7a1ecb2`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2).
- **Source and standalone page:** [`out/neon-creature-studies/`](https://github.com/ToniDonDoni/woodz_witch_fashion/tree/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2/out/neon-creature-studies).
- **Public path:** `studies/neon-creatures/index.html`.
- **HTML Git blob:** `6ef22245e880482ca920bb868386cbc315839abe`.
- **Changes:** two leshies, two mushroom options, a hare, wolf, stag and owl; animated neon chalk contours; enlargement, pause, reseeding and line-energy controls.
- **Build:** the gallery HTML is its editable standalone source; copy it directly to the public path.

## Enchanted forest — previous runway

- **Public artifact commit:** [`94293f2`](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/commit/94293f2524c78d5ee08b9eff15d3d7f4c8aa1ffd), [publication PR #1](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/pull/1).
- **Source revision:** [`7a8f357bd8974a8a3ae260f065a41b7ad6cacad4`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/7a8f357bd8974a8a3ae260f065a41b7ad6cacad4).
- **Sources:** [`out/enchanted-forest/`](https://github.com/ToniDonDoni/woodz_witch_fashion/tree/7a8f357bd8974a8a3ae260f065a41b7ad6cacad4/out/enchanted-forest).
- **Build:** `python out/enchanted-forest/build.py` with Pillow.
- **Changes:** runtime-drawn tree layers, moss, ferns, mushrooms, stumps and woodland spirits around the moving runway.

## Earlier butterfly-only preview

[Public artifact commit `5e39c1d`](https://github.com/ToniDonDoni/woodz-witch-fashion-preview/commit/5e39c1d43c005eebe10fefded153ac0593e0af9f) predates these release records. An exact source-to-artifact mapping has not been verified here; no source revision is asserted for it.
