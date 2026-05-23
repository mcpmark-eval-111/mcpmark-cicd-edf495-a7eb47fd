---
name: 🛠️ Maintenance Report
about: Report a maintenance, housekeeping, or technical-debt task
title: "Maintenance: <short description of the task>"
labels: maintenance, needs-triage
assignees: ''
---

## 🛠️ Maintenance Task

A clear, concise description of the maintenance work that needs to be done.

## 🎯 Why is this needed?

Explain the motivation for this maintenance task. For example:

- Reducing technical debt
- Upgrading dependencies / Node.js versions
- Improving CI / build performance
- Refactoring legacy modules
- Cleaning up dead code or unused assets

## 📝 Scope

List the files, modules, or components that are in scope for this maintenance task.

- `src/...`
- `tests/...`
- `.github/...`

## ⚠️ Risk and Impact

- **User-facing impact**: [None / Minor / Major]
- **Breaking changes**: [Yes / No — describe if yes]
- **Migration steps**: …
- **Rollback strategy**: …

## ✅ Definition of Done

- [ ] Code changes merged
- [ ] Tests added/updated and passing
- [ ] Documentation updated
- [ ] CI green on the main branch

## 🚦 Priority Hint

> Use **medium** or **normal** for routine maintenance, **high**/**important** for items that block other work, and **low**/**minor**/**nice-to-have** for opportunistic cleanups. Reserve **critical**/**urgent**/**production**/**outage** wording for genuine emergencies.

## 🔗 References

- Related issues / PRs: 
- Upstream changelogs / advisories: 

---

_The Issue Management Automation workflow will automatically apply the appropriate priority label and post a "Maintenance Guidelines" comment._
