# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. This guide is used in conjunction with the Release Manager role to ensure safe and coordinated deployments.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Release Manager sign-off obtained

For a comprehensive pre-release checklist, see the [Release Manager Checklist](release-manager-checklist.md).

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

---

## Additional Resources

- **[Release Manager Checklist](release-manager-checklist.md)**: Comprehensive checklist for release planning, execution, and post-release monitoring
- **[Roles & Personas - Release Manager](octoacme-roles-and-personas.md#release-manager)**: Detailed role definition and responsibilities
- **[Communication Flow Template](communication-flow-template.md)**: Coordinate release announcements and stakeholder communications

---

**Related Issue**: [#4 - Process Improvements for Role Definitions and Documentation Clarity](https://github.com/congdanh305/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)
