# SeaFlow — Evidence First

This repository publishes the security-reviewed, read-only SeaFlow project showcase. It is a generated mirror, not the canonical source of project state or implementation contracts.

- `index.html`: default Simplified Chinese project overview, all six Skills and directly visible operator summaries.
- `en.html`: complete English overview, with reciprocal language links.
- `project-control.html`: preserved project-control view and its historical lifecycle states.
- `history.html`: preserved development-generation history.

The canonical private formal repository maintains `scripts/build_project_control_ui.py` and the additive `scripts/build_public_showcase.py` publication pipeline, with a specifically disclosed operator catalog and homepage template. Regenerate the allowlisted static output from that source; do not hand-maintain divergent public pages. The source branch for this publication is `project-control/v1.1-pre-gray-ready`.

V3.5 has bounded six-Skill synthetic integration acceptance. V3.6 external benchmarking is pending. Production readiness, independent legal correctness and real-corpus accuracy are not established. Public Skill repository baselines may lag the accepted local contracts. WenHai remains local-only.

GitHub Actions deploys exactly four HTML files, `fonts.css` and `.nojekyll` to GitHub Pages. No private Core code, private assets, datasets, intake reports, source inventories or internal execution logs belong in this mirror.

Typography uses local Times New Roman for English display text and a Helvetica-first Swiss sans-serif stack for English body/UI text. The original Helvetica font is not bundled. TeX Gyre Heros (GUST Font License) is the explicitly identified compatible fallback; its renamed WOFF subsets and complete license notice are embedded in `fonts.css`, so no font service or external request is needed. Chinese uses the appropriate system Chinese font fallback.
