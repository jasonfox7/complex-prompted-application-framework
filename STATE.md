# Project State — [Project Name]

> **Last updated:** [ISO 8601 timestamp]
> **Current phase:** [Phase X.X — Step Name]
> **Status:** [In Progress | Awaiting Human Approval | Blocked | Complete]
> **Framework version:** 4.0

---

## Session Log

<!-- Most recent first. One entry per Orchestrator work session. -->
<!-- Only the Orchestrator writes here. Subagents report status through commits. -->

### [ISO 8601 timestamp] — [Phase.Step] — [Brief description]
- **Started:** [What work began]
- **Completed:** [What finished — update as work completes]
- **In progress at session end:** [What was actively being worked on when session ended]
- **Next action:** [The very next thing to do]
- **Files touched:** [Files created, modified, or deleted]

---

## Phase Checklist

<!-- Check items as they complete. Do not remove or reorder. -->
<!-- Skipped steps: mark [SKIPPED: reason]. -->

### Phase 0 — Research & Feasibility
- [ ] 0.1 Requirements discovery complete
- [ ] 0.2 Technology selection approved by human
- [ ] 0.3 Feasibility report produced
- [ ] **GATE: Human approved Phase 0** — [date or pending]

### Phase 1 — Scouting & Architecture
- [ ] 1.0 Mandatory agent initialization
  - [ ] Wave 1 (parallel): Configuration Agent, Best Practices Agent, Data Agent
  - [ ] Wave 2 (parallel, after Wave 1): Interface Agent, Testing Agent, Dependency Agent
- [ ] 1.1 Scout dispatch complete
- [ ] 1.2 Scout execution
  - [ ] [Module Name]: artifact + report
  - [ ] [Module Name]: artifact + report
  <!-- Add per module as scope is defined -->
- [ ] 1.3 Continuous review complete (all artifacts reviewed)
- [ ] 1.4 Phase 1 progress report produced
- [ ] **GATE: Human approved Phase 1** — [date or pending]

### Phase 1.5 — Dry Integration Review
- [ ] 1.5.1 Interface compatibility audit
- [ ] 1.5.2 Data layer consistency audit
- [ ] 1.5.3 Mandatory service consistency check
- [ ] 1.5.4 Dependency validation
- [ ] 1.5.5 Gap analysis + Dry Integration Report
- [ ] **GATE: Human approved Phase 1.5** — [date or pending]

### Phase 2 — Implementation & Integration
- [ ] 2.0 Core services + data layer
  - [ ] Logger service
  - [ ] Config service
  - [ ] Error service
  - [ ] Data context
  - [ ] Composition root
  - [ ] CLI entry point
  - [ ] Repository implementations
  - [ ] Migration baseline (if applicable)
  - [ ] Seed data (if applicable)
  - [ ] Core services tested
- [ ] 2.1 Scout-to-coder transition
- [ ] 2.2 Module implementation
  - [ ] [Module Name]: implemented + CLI commands
  - [ ] [Module Name]: implemented + CLI commands
  <!-- Add per module -->
- [ ] 2.3 Agent Karen verification
  - [ ] [Module Name]: verified
  - [ ] [Module Name]: verified
- [ ] 2.4 Module-level testing
  - [ ] [Module Name]: tests passing
  - [ ] [Module Name]: tests passing
- [ ] 2.5 Integration testing complete
- [ ] 2.6 Phase 2 completion report
- [ ] **GATE: Human approved Phase 2** — [date or pending]

### Phase 3 — Verification & Delivery
- [ ] 3.1 Final documentation (README.md)
- [ ] 3.2 Human handoff
- [ ] **GATE: Human accepted delivery** — [date or pending]

---

## Key Decisions

<!-- Numbered. Never removed. Never relitigated unless human requests. -->

1. **[Decision title]** — [One-line summary]. Phase [X.X]. Rationale: [brief].

---

## Active Blockers

<!-- Remove when resolved. -->

- [ ] [Description] — waiting on: [human input | dependency | external]

---

## Document Map

<!-- Status: draft | final | not yet created -->

| Document | Path | Status |
|----------|------|--------|
| Framework | ./FRAMEWORK.md | — |
| Feasibility Report | docs/feasibility-report.md | [status] |
| Best Practices | docs/guidance/best-practices.md | [status] |
| Interface Contracts | docs/guidance/interface-contracts.md | [status] |
| Configuration | docs/guidance/configuration.md | [status] |
| Data Layer | docs/guidance/data-layer.md | [status] |
| Testing Standards | docs/guidance/testing-standards.md | [status] |
| Dependency Graph | docs/guidance/dependency-graph.md | [status] |
| Guidance Changelog | docs/guidance/changelog.md | [status] |
<!-- Add artifact rows as modules are defined -->
