# Metrics & Instrumentation Guidelines

Purpose:
Provide a lightweight guide to help teams define, instrument, and report on success metrics so features are shipped with measurable outcomes.

Define metrics early
- Identify 1–3 success metrics for each feature (e.g., conversion rate, error rate, latency)
- Specify metric owners (usually Data Analyst or PdM)
- Document dashboards and measurement windows

Instrumentation
- Add stable, well-documented event names and properties
- Ensure privacy/compliance checks on telemetry data
- Include SLI/SLO definitions when feature impacts reliability

Dashboards & Alerts
- Build a dashboard for the feature's success metrics
- Set meaningful alerts for regressions in critical metrics
- Assign alert owners and a runbook for triage

Validation & Post-release
- Validate metrics against expected ranges after deployment
- Run experiments or A/B tests where applicable and track cohorts
- Share findings with PdM, PM, and Stakeholders

Quick template (to include in issue/PR)
- Metric name:
- Owner:
- Dashboard link:
- Instrumentation checklist:
  - [ ] Event tracked
  - [ ] Property names documented
  - [ ] Data quality validated
