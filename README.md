# Runbook Rehearsal — Legacy-Config Retirement

> **Disposable sandbox.** This repository exists solely to rehearse the team runbook for retiring legacy configuration files. It is safe to delete after the drill.

This is a throwaway project for the legacy-config retirement runbook rehearsal:

- `config/legacy-settings.yaml` — legacy settings file, marked with `# DEPRECATED-RUNBOOK-MARKER-7QF3`
- `config/legacy-features.yaml` — legacy feature flags, marked with `# DEPRECATED-RUNBOOK-MARKER-7QF3`
- `src/app.py` — ordinary application code with no deprecation marker (must survive cleanup)

Rehearsal objective: locate every file carrying the deprecation marker, confirm each is genuinely legacy, retire only the marked files, and open a pull request back to `main` for review.
