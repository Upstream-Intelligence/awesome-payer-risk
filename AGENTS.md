# Awesome Payer Risk — Agent Instructions

## Ecosystem Context

This repo is part of the **Upstream Intelligence** family of repos. Before working here, read the
workspace graph for cross-repo relationships:

- `/Users/kevinrichards/workspace-graph/WORKSPACE_CONTEXT.md` — low-token entrypoint
- `/Users/kevinrichards/workspace-graph/REPO_INDEX.json` — machine-readable repo index

### Sister repos

| Repo | Role |
|---|---|
| `upstream-v2` | Production healthcare AI SaaS (Django + React + Cloud Run + Vercel) |
| `upstream-data` | Public payer policy data API and CMS ingestion pipeline |
| `upstream-mcp` | Model Context Protocol server for Upstream data access |
| `upstream-skills` | Claude Code skills for Upstream workflows |
| `upstream-community` | Community docs and contributor resources |
| `awesome-payer-risk` | **This repo** — Curated payer risk resources (public) |
| `upstream-intelligence-github` | GitHub org profile (.github) |
| `upstream-intelligence-dotgithub` | Default org-level GitHub config |

### Production system

`upstream-v2` is the live production system. This is a public curated-resources repo that
supports the Upstream ecosystem's thought leadership and SEO strategy. Keep resource links
current and aligned with the production system's payer coverage.

## Code Graph

This repo uses `code-review-graph` for structural code context. Before exploring code with raw
file scans, use the graph MCP tools (`semantic_search_nodes`, `query_graph`, `detect_changes`).
If the graph is stale or empty, refresh it:

```bash
code-review-graph build --repo .
```

The graph database is local-only under `.code-review-graph/` and must not be committed.
