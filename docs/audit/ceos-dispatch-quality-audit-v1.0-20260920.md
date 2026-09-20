# CEOS dispatch-quality audit

- **Date:** 2026-09-20
- **Board:** Jira project CEOS (`cloudId` 78ab1a97-f6aa-45c6-8e1f-3255e2091f28)
- **Live board:** https://rltsolv.atlassian.net/jira/software/projects/CEOS/issues
- **Pass/fail:** PASS. A–G complete. 92 rows from live bodies. No Jira writes, no Notion, no git of issue bodies, no rewritten issue bodies.

Hygiene already passed. That is not this job. Claude memos are hypotheses only and were not used for scores.

## Dispatch bar

Fail any one and the issue is not DISPATCH:

1. Opening line states the defect.
2. Visual inspection names the failure artifact, not the success artifact.
3. Done closes only on this issue's evidence.
4. No hidden ruling. If the body still asks "rule whether," it is DECISION.
5. Non-goal or explicit out-of-scope sentence exists.
6. Evidence path is a command, path, or query a builder can run on TK421 or undercity.
7. If points = 5, Why-5 names a property of the work.

Labels, used only these:

- DISPATCH
- DECISION
- PACKET-THIN
- EPIC-PROSE
- BLOCKED (named key or named person required)

## Known live facts (not re-litigated)

- 92 issues. Re-counted from Jira. Count is 92.
- CEOS-3 declines a visual inspection on purpose.
- CEOS-2 objective 4 still has no issue.
- CEOS-8 two-line log `hourly-20260918-221951.log` still needs an owner.
- CEOS-64 is a Chore wearing a ruling.
- CEOS-8, 55, 12, 78 are Decisions. Randy rules them 2026-09-20 morning. Scored as DECISION; not rewritten.
- CEOS-27 live probe 2026-09-19T23:18Z/23:19Z TK421: Machine `CAM_LAN_TRUSTED_CIDRS` deleted; loopback `/api/health` 200; LAN no-bearer 401; LAN wrong-bearer 401; LAN Machine `CAM_API_TOKEN` 200. Remainder: `LAN-ACCESS.md` / `lan-enable.ps1` / `lan-expose.ps1` still instruct putting the CIDR back. CEOS-25 stays open. Do not close 27.

Points field used: `customfield_10016`. Every issue is **To Do**. Comments on all Decision issues and on CEOS-44, 49, 53, 62, 64, 66, 67, 68: empty.

---

## A. Live count

**92** (`project = CEOS`, JQL count + 92 keys CEOS-1…CEOS-92, `isLast: true`). Matches the known live fact.

---

## B. Coverage table

| key | type | parent | points | status | label | failed bars | worst fail quote | missing fact if PACKET-THIN |
|---|---|---|---|---|---|---|---|---|
| CEOS-1 | Epic | — | — | To Do | EPIC-PROSE | 1,2,3 | CEOS runs on a host that is always on, on UPS | |
| CEOS-2 | Epic | — | — | To Do | EPIC-PROSE | 1,2,3 | The board tells the truth about itself without a human noticing first | |
| CEOS-3 | Epic | — | — | To Do | EPIC-PROSE | 1,3 | All three objectives closed on their own issues' evidence | |
| CEOS-4 | Epic | — | — | To Do | EPIC-PROSE | 1,3 | What DTG reports to H&P is defensible when the customer reads | |
| CEOS-5 | Epic | — | — | To Do | EPIC-PROSE | 1,2,3,6 | a call-site audit of the query verb showing zero paths | |
| CEOS-6 | Epic | — | — | To Do | EPIC-PROSE | 1,3 | The estate produces artifacts whose provenance, version and supersession | |
| CEOS-7 | Decision | CEOS-4 | 1 | To Do | DECISION | 1,4,5,6 | Filed 2026-09-18, unruled | |
| CEOS-8 | Decision | CEOS-3 | 1 | To Do | DECISION | 1,2,4,5 | Row 59 ruled and recorded in CAM, naming the option | |
| CEOS-9 | Decision | CEOS-2 | 1 | To Do | DECISION | 1,2,4,5,6 | VISUAL INSPECTION: the ruled row on the CAM board | |
| CEOS-10 | Decision | CEOS-3 | 1 | To Do | DECISION | 1,2,4,5 | The row stays open for option 3 | |
| CEOS-11 | Decision | CEOS-2 | 1 | To Do | DECISION | 1,4,5 | Row 56 ruled and recorded in CAM, naming the option | |
| CEOS-12 | Decision | CEOS-6 | 2 | To Do | DECISION | 1,4,5,6 | Randy ruled "converge them" on 2026-09-18 and the convergence never ran | |
| CEOS-13 | Decision | CEOS-4 | 1 | To Do | DECISION | 1,2,4,5,6 | This is a CONTRACT decision, not an engineering one | |
| CEOS-14 | Decision | CEOS-4 | 1 | To Do | DECISION | 1,4,5,6 | CL-8 ruled and recorded in CAM, naming the option | |
| CEOS-15 | Decision | CEOS-6 | 2 | To Do | DECISION | 1,4,5 | This is Fable's single overturn request | |
| CEOS-16 | Decision | CEOS-2 | 1 | To Do | DECISION | 1,4,5,6 | Choosing which task keeps AI-41 belongs to the owner | |
| CEOS-17 | Story | CEOS-2 | 2 | To Do | PACKET-THIN | 1 | It exempts a package when a session summary cites a commit sha | Opening states how check D works, not that an invented sha exempts. |
| CEOS-18 | Chore | CEOS-2 | 2 | To Do | PACKET-THIN | 6 | The suite runs to a reported result against a restored real database | No command to run that restored-database suite. |
| CEOS-19 | Bug | CEOS-2 | 3 | To Do | PACKET-THIN | 5 | The asymmetry is the real work in this issue | No non-goal or out-of-scope sentence. |
| CEOS-20 | Chore | CEOS-1 | 1 | To Do | BLOCKED (uc; after 2026-09-21 07:20) | 1 | this is only correct AFTER Monday 2026-09-21 07:20 | |
| CEOS-21 | Chore | CEOS-2 | 1 | To Do | PACKET-THIN | 6 | the closed session row showing status done | No command or query to fetch session 120. |
| CEOS-22 | Decision | CEOS-6 | 1 | To Do | DECISION | 1,4,5 | Rule whether the 2026-09-16/17 run owes a Notion record | |
| CEOS-23 | Chore | CEOS-6 | 1 | To Do | PACKET-THIN | 5 | One British spelling, "behaviour", in a comment | No non-goal sentence. |
| CEOS-24 | Story | CEOS-2 | 2 | To Do | PACKET-THIN | 6 | the tool list served by the running bridge | No command that lists tools on the running bridge. |
| CEOS-25 | Story | CEOS-1 | 1 | To Do | PACKET-THIN | 1,3,6 | The blast radius is re-measured after CEOS-27 lands | Done waits on CEOS-27; no independent probe command. |
| CEOS-26 | Story | CEOS-1 | 3 | To Do | PACKET-THIN | 5,6 | a read attempt for the token from an unprivileged process | No non-goal; no command for that unprivileged read. |
| CEOS-27 | Story | CEOS-1 | 5 | To Do | PACKET-THIN | 6 | CAM_LAN_TRUSTED_CIDRS is 192.168.50.0/24 | Body still treats the CIDR as live; no curl; LAN-ACCESS.md / lan-enable.ps1 / lan-expose.ps1 unnamed. |
| CEOS-28 | Chore | CEOS-2 | 1 | To Do | PACKET-THIN | 3,5 | the closed session row beside CEOS-21's | Close evidence includes CEOS-21; no non-goal. |
| CEOS-29 | Chore | CEOS-2 | 2 | To Do | DISPATCH | — | — | |
| CEOS-30 | Chore | CEOS-6 | 3 | To Do | PACKET-THIN | 5 | So this is partly blocked on a ruling | No non-goal; gate fate left hanging on CEOS-12. |
| CEOS-31 | Epic | — | — | To Do | EPIC-PROSE | 1,3,6 | All seven objectives closed on their own issues' evidence | |
| CEOS-32 | Epic | — | — | To Do | EPIC-PROSE | 1,3,5,6 | The doctrine a customer buys exists in shippable form | |
| CEOS-33 | Story | CEOS-31 | 5 | To Do | BLOCKED (CEOS-78, CEOS-41) | 1 | What this issue now covers | |
| CEOS-34 | Story | CEOS-31 | 5 | To Do | PACKET-THIN | 5 | Do not design a second mechanism | No non-goal or out-of-scope sentence. |
| CEOS-35 | Bug | CEOS-31 | 5 | To Do | PACKET-THIN | 1,6 | Why defect 2 keeps the original issue | Opens on rescope history; no command to run the two-instance audit. |
| CEOS-36 | Spike | CEOS-32 | 3 | To Do | PACKET-THIN | 1,5,6 | What this spike must produce | Opens as a work list; no TK421/undercity evidence path. |
| CEOS-37 | Story | CEOS-32 | 3 | To Do | PACKET-THIN | 1,5,6 | Author POL-17, the Deliverable Standard | Opens as authoring work; evidence is Notion-only. |
| CEOS-38 | Epic | — | — | To Do | EPIC-PROSE | 1,3,6 | the single command's output across the whole repository set | |
| CEOS-39 | Spike | CEOS-31 | 3 | To Do | BLOCKED (CEOS-78, CEOS-34) | 1,3,5,6 | DEFERRED behind CEOS-78, which rules the provenance grain | |
| CEOS-40 | Story | CEOS-32 | 3 | To Do | BLOCKED (CEOS-78) | 1,5,6 | BLOCKED on CEOS-78 | |
| CEOS-41 | Story | CEOS-31 | 3 | To Do | PACKET-THIN | 1,5,6 | Build one, or state with evidence the conditions | Opens as the task; no file-referenced command yet. |
| CEOS-42 | Story | CEOS-32 | 5 | To Do | PACKET-THIN | 1,5,6 | The register itself. A flat identifier space | Opens as register work; evidence is Notion-only. |
| CEOS-43 | Spike | CEOS-2 | 3 | To Do | PACKET-THIN | 1,5,6 | The boundary half is done and verified | Opens on boundary history; no board query. |
| CEOS-44 | Spike | CEOS-4 | 1 | To Do | DECISION | 1,4,5 | The OneDrive tree is either retired or explicitly kept | |
| CEOS-45 | Story | CEOS-32 | 5 | To Do | BLOCKED (CEOS-46) | 1,5,6 | Fill the remaining 35 rows of the Exercise Program | |
| CEOS-46 | Story | CEOS-32 | 3 | To Do | PACKET-THIN | 1,5 | The Exercise Program schema changed | Opens as the task; no non-goal. |
| CEOS-47 | Chore | CEOS-32 | 3 | To Do | PACKET-THIN | 1,6 | Sweep roughly 150 MET-51 property cells | Opens as the task; cells are not a TK421/undercity path. |
| CEOS-48 | Chore | CEOS-32 | 2 | To Do | PACKET-THIN | 1,5,6 | Brand sweep, "Cybermind" to "CyberMind" | Opens as the task; no non-goal; Notion evidence. |
| CEOS-49 | Spike | CEOS-32 | 3 | To Do | DECISION | 1,4,6 | Decide whether Threat Actor Prioritization should be named | |
| CEOS-50 | Chore | CEOS-2 | 2 | To Do | PACKET-THIN | 1,6 | a Notion workspace search for "CAM" | Opens as the task; search is not TK421/undercity. |
| CEOS-51 | Chore | CEOS-32 | 1 | To Do | PACKET-THIN | 1,5,6 | Record the Baseline Engine in Notion | Opens as the task; Notion-only evidence. |
| CEOS-52 | Spike | CEOS-32 | 2 | To Do | PACKET-THIN | 1,6 | Not delegated CyberMind work | Opens as what it is; evidence is the Notion CTI register. |
| CEOS-53 | Chore | CEOS-2 | 1 | To Do | DECISION | 1,4 | Project 5's disposition ruled and recorded | |
| CEOS-54 | Story | CEOS-1 | 5 | To Do | BLOCKED (CEOS-55) | 1,5 | Blocked on CEOS-55, the repo_path decision | |
| CEOS-55 | Decision | CEOS-1 | 3 | To Do | DECISION | 1,4,5 | Why it is a decision rather than a fix | |
| CEOS-56 | Spike | CEOS-2 | 3 | To Do | PACKET-THIN | 5 | A recommendation on whether to build it, which may be no | No non-goal sentence. |
| CEOS-57 | Bug | CEOS-5 | 3 | To Do | PACKET-THIN | 5 | That is why this is a 3 rather than a 1 | No non-goal sentence. |
| CEOS-58 | Decision | CEOS-5 | 1 | To Do | DECISION | 1,4,5,6 | Whether this is acceptable on an H&P host is a policy call | |
| CEOS-59 | Decision | CEOS-4 | 1 | To Do | DECISION | 1,4,5 | The xsiam-ops pre-push hook ruled and recorded | |
| CEOS-60 | Decision | CEOS-38 | 2 | To Do | DECISION | 1,4,5 | A posture ruled and recorded | |
| CEOS-61 | Bug | CEOS-38 | 2 | To Do | PACKET-THIN | 5 | Before CEOS-54, the Wave 3a move | No non-goal sentence. |
| CEOS-62 | Story | CEOS-38 | 3 | To Do | DECISION | 4 | A ruling on the other 25: which need one | |
| CEOS-63 | Spike | CEOS-38 | 3 | To Do | DISPATCH | — | — | |
| CEOS-64 | Chore | CEOS-38 | 2 | To Do | DECISION | 4 | or are ruled dormant with the ruling recorded on the row | |
| CEOS-65 | Story | CEOS-6 | 1 | To Do | PACKET-THIN | 1,5 | cd-renderer-injection-ab-v1.0-20260916.ps1 at the root | Opens as what the file is; no non-goal. |
| CEOS-66 | Story | CEOS-2 | 1 | To Do | DECISION | 1,4 | Whether hold/ becomes a real queue state, or the packet is a stray | |
| CEOS-67 | Story | CEOS-6 | 1 | To Do | DECISION | 1,4 | The not-committed line is ruled as instruction or description | |
| CEOS-68 | Story | CEOS-4 | 1 | To Do | DECISION | 1,4 | is slo-engine-internals a tracked repo doc or a personal artifact | |
| CEOS-69 | Story | CEOS-31 | 3 | To Do | BLOCKED (CEOS-34) | 1,5 | Until draft binding holds, splitting publish buys nothing | |
| CEOS-70 | Story | CEOS-5 | 5 | To Do | BLOCKED (CEOS-88) | 6 | Every read CEOS-88 identified has been re-run | |
| CEOS-71 | Story | CEOS-1 | 3 | To Do | PACKET-THIN | 1,5 | Desktop currently spawns node C:/dev/cam-mcp/server.js | Opens as the change; no non-goal. |
| CEOS-72 | Story | CEOS-3 | 2 | To Do | DISPATCH | — | — | |
| CEOS-73 | Spike | CEOS-3 | 1 | To Do | PACKET-THIN | 1 | What this spike must answer | Opens as questions, not the unmeasured cost. |
| CEOS-74 | Story | CEOS-3 | 3 | To Do | BLOCKED (CEOS-8) | 1 | Blocked on CEOS-8, which decides the channel | |
| CEOS-75 | Story | CEOS-3 | 3 | To Do | BLOCKED (CEOS-73, CEOS-10) | 1 | Blocked on CEOS-73 for the cost and on CEOS-10 | |
| CEOS-76 | Story | CEOS-1 | 3 | To Do | PACKET-THIN | 1,6 | The scheduled checks: cam-backup-age-check and cam-notion-reach-audit | Opens as the caller; no live curl commands. |
| CEOS-77 | Story | CEOS-1 | 3 | To Do | PACKET-THIN | 1,5 | cam-mcp-http on 192.168.50.11:3101 | Opens as the callers; no non-goal. |
| CEOS-78 | Decision | CEOS-31 | 3 | To Do | DECISION | 1,4,5 | What has to be ruled | |
| CEOS-79 | Story | CEOS-31 | 3 | To Do | BLOCKED (CEOS-78) | 5,6 | CEOS-78 rules the grain, CEOS-33 carries the actor | |
| CEOS-80 | Spike | CEOS-31 | 2 | To Do | PACKET-THIN | 1,3,5,6 | the strike recorded on CEOS-31 rather than here | Opens as questions; done edits CEOS-31; Notion evidence. |
| CEOS-81 | Bug | CEOS-31 | 5 | To Do | BLOCKED (CEOS-41) | 5 | That makes CEOS-41 a hard dependency | |
| CEOS-82 | Bug | CEOS-31 | 3 | To Do | DISPATCH | — | — | |
| CEOS-83 | Bug | CEOS-31 | 3 | To Do | DISPATCH | — | — | |
| CEOS-84 | Story | CEOS-32 | 5 | To Do | BLOCKED (CEOS-78, CEOS-36) | 1,5,6 | Blocked on CEOS-78, the provenance grain ruling | |
| CEOS-85 | Story | CEOS-32 | 3 | To Do | PACKET-THIN | 1,5,6 | Author the elicitation method | Opens as the work; Notion evidence. |
| CEOS-86 | Story | CEOS-32 | 3 | To Do | PACKET-THIN | 1,5,6 | Traces To is text today. Make it a typed relation | Opens as the work; Notion evidence. |
| CEOS-87 | Story | CEOS-1 | 3 | To Do | PACKET-THIN | 1,5 | Split from CEOS-54 on 2026-09-19 | Opens as the split; no non-goal. |
| CEOS-88 | Spike | CEOS-5 | 3 | To Do | PACKET-THIN | 1,6 | What this spike must answer | Opens as questions; no path to the hunt-read population. |
| CEOS-89 | Story | CEOS-2 | 2 | To Do | DISPATCH | — | — | |
| CEOS-90 | Decision | CEOS-2 | 1 | To Do | DECISION | 1,2,4,5 | The decision is whether the estate has a category | |
| CEOS-91 | Decision | CEOS-2 | 2 | To Do | DECISION | 1,2,4,5,6 | The field's meaning is ruled and recorded | |
| CEOS-92 | Decision | CEOS-6 | 2 | To Do | DECISION | 1,4,5 | This issue is where that rule lives so it survives | |

Row count: **92**.

---

## C. Totals by label

| label | n |
|---|---|
| DISPATCH | 6 |
| DECISION | 27 |
| PACKET-THIN | 37 |
| EPIC-PROSE | 9 |
| BLOCKED | 13 |
| **sum** | **92** |

---

## D. DISPATCH keys only, grouped by parent epic

- **CEOS-2** Board integrity: CEOS-29, CEOS-89
- **CEOS-3** Capture and restore: CEOS-72
- **CEOS-31** Baseline Engine: CEOS-82, CEOS-83
- **CEOS-38** Pipeline: CEOS-63

None under CEOS-1, CEOS-4, CEOS-5, CEOS-6, CEOS-32.

---

## E. DECISION keys that still have no recorded ruling

No Decision (or hidden-ruling) issue has a comment. None has a recorded ruling on the question the issue still asks.

**Typed Decision:** CEOS-7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 22, 55, 58, 59, 60, 78, 90, 91, 92

**Hidden ruling (not typed Decision):**

- CEOS-44 (OneDrive retire/keep)
- CEOS-49 (whether TAP is named in CORE)
- CEOS-53 (project 5 disposition)
- CEOS-62 (which of the other 25 need a contract)
- CEOS-64 (dormant vs install)
- CEOS-66 (hold/ vs stray)
- CEOS-67 (instruction vs description)
- CEOS-68 (tracked doc vs personal)

Prior rulings that do **not** close the open question: CEOS-10 refuse-rather-than-warn; CEOS-12 “converge them” (never ran); CEOS-44 L1-A; CEOS-92 “run the skill every run” (home still unruled).

Randy’s 2026-09-20 morning set, scored DECISION and not rewritten: **CEOS-8, 12, 55, 78**.

---

## F. PACKET-THIN keys that would become DISPATCH after a packet, not after a ruling

Cap 8. Ranked by whether they unblock Track R (relay / LAN / API move) first.

1. **CEOS-27** — add the live probe commands; state CIDR already deleted; name `LAN-ACCESS.md` / `lan-enable.ps1` / `lan-expose.ps1` as the remainder. Unblocks the Wave 3 auth cut.
2. **CEOS-76** — open on the over-broad scheduled-check token; add the four live curl calls.
3. **CEOS-77** — open on unscoped conductor reach; add a non-goal.
4. **CEOS-71** — open on the stdio child still owning Desktop; add a non-goal. Unblocks CEOS-87.
5. **CEOS-26** — add a non-goal and the unprivileged token-read command.
6. **CEOS-25** — open on the live read-oracle; make done a blast-radius remeasure that does not wait on CEOS-27.
7. **CEOS-87** — open on cam-mcp-http still bound to TK421; add a non-goal.
8. **CEOS-61** — add a non-goal. Red lint on the repo that receives the API.

---

## G. What you could not see

- `docs/audit/ceos-*.md` Claude memos were not in this workspace (treated as unused hypotheses).
- CAM board rows, Notion pages, and TK421/undercity live state, except the CEOS-27 probe facts given in the brief.
- Issue changelogs, attachments, remote links, and watchers.
- Comments on non-Decision issues other than the eight hidden-ruling keys above (those eight were empty).
- Whether `customfield_10016` is the official “Story points” UI label; values match the 1/2/3/5 set.
