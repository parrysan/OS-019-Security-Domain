---
title: "OS-019 — Security Domain"
type: project-bootstrap
created: "2026-07-04"
---

# OS-019 — Security Domain

> **Bootstrap order — read these in order before doing any work in this project:**
>
> 1. `~/.claude/CLAUDE.md` → `Open-Memory-Vault/system/identity/MASTER-PROMPT.md` — Phil's identity (auto-loaded via symlink in Claude Code; other tools should mirror this).
> 2. `~/AGENT.md` → `agent-config/AGENT.md` — global operating manual (work style, skills routing, secrets policy, layering rules in §2.10).
> 3. `Open-Memory-Vault/AGENTS.md` — vault operating contract (read **only** if you will write to the vault during this session).
> 4. `Open-Memory-Vault/projects/OS-019-Security-Domain/README.md` — durable project page (status, decisions, recent activity, vault-side context).
> 5. **This file (`CLAUDE.md`)** — project-specific overrides and live operational references (below).
>
> **The project's `CLAUDE.md` is a bootstrap manifest, not a knowledge dump.** It points at everything else. Durable knowledge lives in the vault project page. Do not duplicate.

---

## At a glance

- **Code**: `OS-019`
- **Name**: Security Domain
- **Stakeholder**: Phil (self)
- **Type**: `aios`
- **Status**: `planning`
- **Priority**: `low`
- **Revenue lane**: `4-aios`
- **Autonomy mode**: `co-pilot` — security decisions stay with Phil until the charter defines safe autonomy boundaries.
- **Skill centre**: `Security`
- **Purpose** (one sentence): The **Security Skill Centre** — the AIOS centre of excellence for defensive security: site/security-header audits, secrets-policy enforcement, dependency review, and hardening standards for OG properties and client sites. First full test of the skill-centre cookie-cutter (`~/OG/ai-os/skill-centres.md`).
- **Last touched**: `2026-07-04`

---

## Where things live

| Resource | Location |
|---|---|
| **Code root** | this folder (`dev/OS-019-Security-Domain/`) |
| **Project docs** | `./docs/` (charter: `docs/security-domain-design.md` — pending, full cookie-cutter run) |
| **Vault project page** | `Open-Memory-Vault/projects/OS-019-Security-Domain/README.md` |
| **GitHub repo** | https://github.com/parrysan/OS-019-Security-Domain |
| **External systems** | none yet |

---

## Live references

- **Front door**: none yet — established during the cookie-cutter run
- **Known first engine candidates**: the `security-review` skill (already in the global library), securityheaders.com checks (pattern proven in the OS-017 oganiko.com pilot audit)
- **Credentials**: none stored here

---

## Tech stack

Markdown-first operating environment. Defined during the charter run.

---

## Project-specific rules

- **Defensive only.** Audits, hardening, policy enforcement for owned/authorized properties — nothing offensive.
- **Skills stay global** (skill-centres.md contract).

---

## Skills

- **Project-local skills**: none — uses global library
- **Most relevant global skills for this project**: `security-review`, `meta-find-skills`, `audit`

---

## Notes for the next session

Last action (2026-07-04): scaffolded as the Security Skill Centre home — placeholder pending the first full cookie-cutter run (charter, engine research, playbooks, front door). Next action: run the cookie-cutter when security work is first prioritized. Open question: none.
