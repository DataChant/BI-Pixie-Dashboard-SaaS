# BI Pixie Dashboard (SaaS) — ARCHIVED

This repository is **archived and read-only**. The SaaS sample-data dashboard it held was
salvaged into the BI Pixie monorepo and is no longer maintained here.

## Where it lives now

**Repo:** `bi-pixie/BI-Pixie-Azure-Deployment`
**Path:** [`dashboard/saas/`](https://github.com/bi-pixie/BI-Pixie-Azure-Deployment/tree/main/dashboard/saas)

What was preserved (2026-06-15): the complete openable dashboard (`BI Pixie.pbip`, report,
semantic model) **including the cached sample data** `BI Pixie.SemanticModel/.pbi/cache.abf`
that the SaaS Template App publishes via install ticket, plus the Copilot grounding docs
(`AI Instructions`, `Q&A Trigger Prompts`) and a publish runbook. See
`dashboard/saas/README.md` in the monorepo for the publish flow.

The canonical, maintained model and report live at `dashboard/BI Pixie.SemanticModel` and
`dashboard/BI Pixie.Report` in the monorepo (strictly ahead of this snapshot). The Fabric
Workload cannot carry sample data, so the snapshot here is SaaS-only.

## Note

This repository's git history is retained read-only. Do not reuse any credentials that ever
appeared here.
