# Woodz Witch Fashion — Public Preview

[Open the live runway](https://tonidondoni.github.io/woodz-witch-fashion-preview/) · [Infinite Single-Event Black Runway](https://tonidondoni.github.io/woodz-witch-fashion-preview/infinite-single-event-rc/) · [Release Candidate GPT — Moonlight and Fog](https://tonidondoni.github.io/woodz-witch-fashion-preview/release-candidate-gpt/) · [View the creature gallery](https://tonidondoni.github.io/woodz-witch-fashion-preview/studies/neon-creatures/) · [Living Acts](https://tonidondoni.github.io/woodz-witch-fashion-preview/living-acts/) · [Scenes in the wood](https://tonidondoni.github.io/woodz-witch-fashion-preview/scenes/) · [Release history and exact source revisions](changelog.md)

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

## Infinite Single-Event Black Runway — Experimental candidate

[Open the new black-stage experiment](https://tonidondoni.github.io/woodz-witch-fashion-preview/infinite-single-event-rc/). The woman walks on black with exactly one transient procedural neon-chalk entity at a time and silent gaps between events. Events are generated from independently indexed seeds, not a fixed list of pre-rendered animations. The original root preview and previous release candidates remain unchanged.

[Source and implementation PR #11](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/11) — folder `out/infinite-single-event/`, rebuildable standalone page at `site/infinite-single-event-rc/index.html`. The source PR's headless offline browser verification passed; real phone performance and artistic acceptance remain pending.

## Living Acts — experimental candidate

[Open the living acts runway](https://tonidondoni.github.io/woodz-witch-fashion-preview/living-acts/). The forest is staged as a sequence of seeded acts: every act has its own length, announces itself with a title card, sets the weather of the woodland, and sends one signature set piece across the stage (a constellation stag, a lantern procession, a moth wake, a fairy ring, a leshy choir, a wisp fountain, a moonflower). Rare unannounced cameos add a star fall and an owl. A fourth, faster foreground row is drawn after the walker, so foreground vegetation really passes in front of her sneakers, and `NEW DREAM` reshuffles the act programme, the woodland layout and the colour mood instead of redrawing the same world.

Source and implementation PR: [woodz_witch_fashion #12](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/12) — folder `out/runway-acts/`, rebuildable standalone page at `out/runway-acts/index.html`. The original root preview and the other candidates remain unchanged. Headless offline verification passed in the source PR; real phone performance and artistic acceptance remain pending.

## Scenes in the wood — experimental candidate

[Open the scene-staged runway](https://tonidondoni.github.io/woodz-witch-fashion-preview/scenes/). Each act of the runway is now a small scene: three overlapping beats tile its whole length, so something is on the stage for essentially the entire act (96-100% of each measured act, mean 98%, against 16% for the single-fly-past version in `/living-acts/`). Exactly one beat per act is the act's headline set piece and the other two are quieter pieces from the same cast. A piece can enter from the left, enter from the right and face the way it travels, arrive and hold beside her, or rise out of the ground and drift, so the show no longer reads as one conveyor belt. The act title card now stays up for the whole act instead of vanishing after four seconds.

Source and implementation PR: [woodz_witch_fashion #13](https://github.com/ToniDonDoni/woodz_witch_fashion/pull/13) (stacked on #12) — folder `out/runway-scenes/`. The root preview and the other candidates remain unchanged.
