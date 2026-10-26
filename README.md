# SeaFlow — Evidence First

This repository publishes the official bilingual SeaFlow homepage and preserved project-control/history views. It remains a generated, read-only mirror, not the canonical source of project state or implementation contracts.

- `index.html`: Chinese homepage, six Skills, Our Reports and Our Promise.
- `en.html`: English homepage counterpart with reciprocal language links.
- `project-control.html` / `history.html` and their English counterparts: preserved supporting records.
- [Research Reports](https://github.com/HuDeyi-66/SeaFlow/tree/main/reports): RD03 working-paper original and a separately labeled aggregate V3.6 Public Edition; the detailed Chinese Run_001 source remains internal.

The canonical private formal repository maintains `scripts/build_project_control_ui.py` and the additive `scripts/build_public_showcase.py` publication pipeline, with a specifically disclosed operator catalog and homepage template. Regenerate the allowlisted static output from that source; do not hand-maintain divergent public pages. The source branch for this publication is `project-control/v1.1-pre-gray-ready`.

V3.5 remains bounded six-Skill synthetic integration acceptance. The V3.6 exploratory evaluation is sealed: its primary paired endpoint is tied across 34 currently judgeable complete pairs, while a separate owner-reported expert re-review suggests a slight edge among reviewed cases only. This does not establish third-party benchmark acceptance or production readiness. V3.6.1 PARTIAL/HOLD remains separate and is not an overall PASS. Public Skill baselines may lag accepted local contracts. WenHai remains local-only.

GitHub Actions keeps its existing eight-file Pages allowlist: six HTML files, `fonts.css` and `.nojekyll`. Only the current bilingual homepage and preserved supporting pages are deployed; candidate directories and internal revision galleries are not included. No private Core code, private assets, datasets, intake reports, source inventories or execution logs belong in this mirror.

Typography uses local Times New Roman for English display text and a Helvetica-first Swiss sans-serif stack for English body/UI text. The original Helvetica font is not bundled. TeX Gyre Heros (GUST Font License) is the explicitly identified compatible fallback; its renamed WOFF subsets and complete license notice are embedded in `fonts.css`, so no font service or external request is needed. Chinese uses the appropriate system Chinese font fallback.

Each overview, project-control and history route now has a matching Chinese/English presentation. Chinese displays 技能 and 运行核心 and localized operator labels. English displays English category labels and operator names. Native identifiers are retained in data attributes, and historical state JSON is unchanged; presentation-only localization also applies to dynamic detail panels and accessibility labels.
