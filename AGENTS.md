# Agent Skills

This repo is configured for engineering agent workflows. The skills below manage its issue tracker, triage labels, and domain documentation. See `docs/agents/*.md` for their configuration.

## Agent skills

### Issue tracker

Issues and PRs live as GitHub issues in the repository. The `gh` CLI handles all operations (create, view, comment, label, close). See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage roles categorise every issue or PR: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context layout with one `CONTEXT.md` at the repo root and ADRs in `docs/adr/`. Agents read these before exploring code. See `docs/agents/domain.md`.
