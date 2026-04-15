# OctoAcme — Cross-Functional Collaboration Checklist

## Purpose
Provide a lightweight, shared checklist to reduce handoff ambiguity across kickoff, planning, execution, release, and retrospective moments.

## When to use
- At project kickoff to set ownership and communication expectations
- At each lifecycle transition (planning, execution, release, retrospective)
- When escalations or go/no-go decisions are needed

## Lifecycle Collaboration Checklist

### 1) Kickoff
- [ ] Problem statement, success metrics, and scope reviewed — **Owner: Product Manager**
- [ ] Delivery timeline, milestones, and communication cadence confirmed — **Owner: Project Manager**
- [ ] Initial architecture constraints and dependencies identified — **Owner: Solutions Architect**
- [ ] Initial UX discovery/research approach defined — **Owner: UX Designer**
- [ ] Test strategy outline and quality risks captured — **Owner: QA Lead**

### 2) Planning
- [ ] Backlog items include clear acceptance criteria and owner — **Owner: Product Manager**
- [ ] Estimates, sequencing, and capacity assumptions reviewed — **Owner: Project Manager + Developers**
- [ ] Technical design and integration risks documented — **Owner: Solutions Architect + Developers**
- [ ] UX artifacts are ready for implementation (flows, mockups, edge cases) — **Owner: UX Designer**
- [ ] CI/test gating approach confirmed for planned scope — **Owner: QA Lead + DevOps Engineer**

### 3) Execution
- [ ] PRs include issue linkage and acceptance criteria traceability — **Owner: Developers**
- [ ] Blockers and dependency changes are escalated in weekly syncs — **Owner: Project Manager**
- [ ] Defect triage and quality trends reviewed regularly — **Owner: QA Lead**
- [ ] Pipeline and environment health monitored for delivery impact — **Owner: DevOps Engineer**
- [ ] Product and UX feedback loops are active during sprint demos — **Owner: Product Manager + UX Designer**

### 4) Release
- [ ] Go/no-go criteria reviewed (quality, risk, rollback readiness) — **Owner: Project Manager + QA Lead + DevOps Engineer**
- [ ] Release notes and stakeholder communication drafted — **Owner: Product Manager + Project Manager**
- [ ] Deployment, smoke tests, and post-release checks executed — **Owner: DevOps Engineer + QA Lead**
- [ ] Outstanding risks and mitigation owners confirmed — **Owner: Project Manager**

### 5) Retrospective
- [ ] Cross-functional feedback captured (product, delivery, quality, ops, design) — **Owner: Project Manager**
- [ ] Improvement actions assigned with owners and due dates — **Owner: Project Manager + Product Manager**
- [ ] Architecture, UX, quality, and operations follow-ups added to backlog — **Owner: Solutions Architect + UX Designer + QA Lead + DevOps Engineer**

## Escalation & Decision Points
- **Scope trade-off needed?** Product Manager proposes options; Project Manager logs decision and impact.
- **Delivery risk to milestone?** Project Manager escalates to Product Lead and Sponsor with mitigation options.
- **Architecture conflict or unresolved dependency?** Solutions Architect facilitates decision with Developers and Product Manager.
- **Quality gate failing near release?** QA Lead and DevOps Engineer recommend go/no-go; Project Manager records final decision path.
- **Production incident after release?** DevOps Engineer leads operational response; Project Manager coordinates stakeholder communication.
