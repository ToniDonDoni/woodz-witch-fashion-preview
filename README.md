# Woodz Witch Fashion — Public Preview

[Open the live runway](https://tonidondoni.github.io/woodz-witch-fashion-preview/) · [Release Candidate GPT — Moonlight and Fog](https://tonidondoni.github.io/woodz-witch-fashion-preview/release-candidate-gpt/) · [View the creature gallery](https://tonidondoni.github.io/woodz-witch-fashion-preview/studies/neon-creatures/) · [Release history and exact source revisions](changelog.md)

## Source and publication

The primary project is [woodz_witch_fashion](https://github.com/ToniDonDoni/woodz_witch_fashion), a private repository containing the walking assets and editable drawing code. This public repository distributes the browser previews through GitHub Pages.

**Current runway source revision:** [`0e6cf29d4059e305a975a77fade10cb3f7a1ecb2`](https://github.com/ToniDonDoni/woodz_witch_fashion/commit/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2).
Its reproducible source and the exact published HTML are in [`out/forest-spectators/`](https://github.com/ToniDonDoni/woodz_witch_fashion/tree/0e6cf29d4059e305a975a77fade10cb3f7a1ecb2/out/forest-spectators).

See [changelog.md](changelog.md) for each published version's source revision, build location, publication commit and changes. [deployment.json](deployment.json) records the same mapping in machine-readable form. Private source links require permission to access the main project.

## Current preview

The existing walking sprites stay centered while layered trees, moss, ferns, mushrooms, stumps and eight neon chalk spectators move right. Spectators glance toward the walker. Contours boil at 12 Hz; new forest content is drawn at runtime. All sprite data and code are embedded in `index.html`.

The gallery is a separate standalone page for comparing the eight creature designs. Both pages work without runtime network requests. GitHub Pages publishes the `main` branch root.

The existing walk-loop seam is unchanged; physical-phone performance has not been verified.

## Future releases

Before publishing a new page, save its editable sources and exact deliverable in the private repository. Update `changelog.md` and `deployment.json` with an immutable source commit, artifact path and publication commit or PR. Use commit links rather than moving branch links. If several pages come from different revisions, record each separately.

## Release Candidate GPT (separate preview)

A self-contained experimental variant at [`release-candidate-gpt/`](release-candidate-gpt/), with the current forest spectators plus the moon and stars from the source project, restrained procedural moonbeams and a drifting fog band. It features a LIGHT ON/OFF switch for visual A/B testing. The original root runway remains untouched. Physical phone performance testing and art direction review are pending; do not consider the release candidate production-accepted.

Source and implementation PR: [woodz_witch_fashion #10](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/10). The builder and renderer sources are in `out/release-candidate-gpt/` on that branch.
