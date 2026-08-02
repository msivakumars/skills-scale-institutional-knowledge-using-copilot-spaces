# Release Management Checklist

Purpose:
A concise checklist teams can adopt to ensure releases are coordinated, safe, and observable.

Pre-release
- [ ] Release Manager assigned and release window scheduled
- [ ] All PRs merged for this release are linked to issues and have approvals
- [ ] CI passes and security scans are green
- [ ] Rollback plan documented and tested (if feasible)
- [ ] Release notes drafted and reviewed by Product Marketing
- [ ] Stakeholders and on-call notified of release schedule
- [ ] Required migration steps or data operations documented

Staging Validation
- [ ] Deploy to staging using the same pipeline as prod
- [ ] Run smoke tests and critical E2E flows
- [ ] Run performance/load checks if release touches infra or scale
- [ ] Verify observability: dashboards, alerts, and logs are in place

Production Deployment
- [ ] Deploy via automated pipeline during agreed window
- [ ] Monitor key dashboards and alerts for the first X minutes/hours
- [ ] Run post-deploy smoke tests
- [ ] Confirm rollback steps are available and tested

Post-release
- [ ] Announce release to stakeholders and support
- [ ] Collect data and validate success metrics (Data Analyst/PdM)
- [ ] Capture any incidents or action items and add to backlog
- [ ] Update release register and change log
