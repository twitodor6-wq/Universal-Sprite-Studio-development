# Universal Sprite Studio — CROSS_PROJECT

Protocol: TWITO DEV HQ v0.2
Checked: 2026-10-22
Status: Coordination initialized; Blender add-on source not yet imported or verified. Prior reported v0.3.0 M2 PARTIAL; multi-action Batch runtime QA pending.

## Coordination account
GitHub owner: `twitodor6-wq`
Repository: https://github.com/twitodor6-wq/Universal-Sprite-Studio-development

## Shared interfaces and project links
- https://github.com/twitodor6-wq/Rephael-Bros — propose and test PNG atlas + JSON timing/anchors export interface.
- https://github.com/twitodor9-lgtm/JLM-Night-rush — investigate if 2D sprites/UI or billboards would benefit.
- https://github.com/twitodor6-wq/Avoda-Ivrit — optional graphics production pipeline.

## Required verified reports
At each meaningful milestone, update this document with version, commit or ZIP identifier, actual QA performed and environment, shared components available, dependencies, open risks, links to Issues/PRs, and next step. Never infer test success from plans. Keep `HANDOFF.md` next to actual source when imported.

## Guardrails
No cross-repository edits without approval. No unverified merge into stable branches. Keep private identifiers, keys and sensitive information out of public repositories. Use issue links for requests and PRs for reviewed code changes. Do not rebuild from scratch.

## First tasks
- Import the latest verified source + HANDOFF after reviewing provenance.
- Define the minimal cross-project interface; keep changes modular.
- Publish verified QA results and update coordinator through issues.

## HQ synchronization — 2026-10-24
- HQ registry: https://github.com/twitodor9-lgtm/JLM-Night-rush/issues/3
- USS HQ proxy: https://github.com/twitodor9-lgtm/JLM-Night-rush/issues/5
- USS source/Batch QA: https://github.com/twitodor6-wq/Universal-Sprite-Studio-development/issues/1
- Sprite-export interface proposal: https://github.com/twitodor6-wq/Universal-Sprite-Studio-development/issues/2
- Central GitHub connection has now successfully read and written project issues. Earlier 403 warning in the HQ proxy is historic, not current.
- Last **reported** version: v0.3.0 M2 PARTIAL; NOT a verified repository release. Reported Blender 5.2.2 (Windows) single-action test: 12 PNGs + atlas + JSON. Full Batch with multiple actions remains unverified.
- Source baseline: latest full ZIP/HANDOFF unavailable in this session; no add-on source present in repository; Blender executable not available in current environment. No new build/runtime QA performed.
- Handoff: retain existing source and development loop; verify provenance before import; carry out multi-action Blender Batch test; log producer/consumer evidence and avoid unapproved merges/deployments.
