# Release Manager Checklist

This checklist ensures that all critical steps are completed before, during, and after a release to minimize risk and ensure smooth deployments.

## Pre-Release Phase (T-3 to T-1 weeks before release)

### Planning & Coordination
- [ ] Release date confirmed and communicated to all stakeholders
- [ ] Release scope finalized with Product Manager and Project Manager
- [ ] Release type identified (Patch/Minor/Major)
- [ ] Deployment window scheduled (if required for maintenance or downtime)
- [ ] Cross-team dependencies identified and coordinated
- [ ] Release branch created and protected
- [ ] Release notes template prepared

### Technical Readiness
- [ ] All planned features completed and PRs merged to release branch
- [ ] All acceptance criteria validated by Product Manager
- [ ] CI/CD pipeline passing (build, tests, linting)
- [ ] Security scans completed with no critical vulnerabilities
- [ ] Performance testing completed (if applicable)
- [ ] Database migrations tested and documented (if applicable)
- [ ] API compatibility verified (backward compatibility for breaking changes)

### Documentation & Communication
- [ ] Release notes drafted with all notable changes
- [ ] Migration steps documented (if required)
- [ ] Known issues documented
- [ ] Rollback plan documented and reviewed
- [ ] Support team briefed on changes and potential issues
- [ ] Communications Lead provided release details for announcements
- [ ] Stakeholders notified of release schedule

## Release Readiness Review (T-1 to T-3 days)

### Go/No-Go Assessment
- [ ] Release readiness meeting conducted with key stakeholders
- [ ] All pre-release checklist items completed
- [ ] No critical blockers or open P0/P1 issues
- [ ] Rollback procedures tested and validated
- [ ] On-call engineer identified and available
- [ ] Project Sponsor approval obtained (for critical releases)

### Staging Validation
- [ ] Deploy to staging environment completed
- [ ] Smoke tests executed successfully in staging
- [ ] User acceptance testing (UAT) completed (if required)
- [ ] Performance validated in staging environment
- [ ] Monitoring and alerting verified in staging

## Deployment Phase (Release Day)

### Pre-Deployment
- [ ] Final go/no-go decision confirmed
- [ ] Team members notified and on standby
- [ ] Backup or snapshot created (if applicable)
- [ ] Deployment window communicated to affected users (if needed)

### Deployment Execution
- [ ] Deployment initiated (automated pipeline or manual process)
- [ ] Deployment logs monitored in real-time
- [ ] Database migrations executed successfully (if applicable)
- [ ] Application starts successfully in production
- [ ] Health checks passing

### Post-Deployment Validation
- [ ] Smoke tests executed in production
- [ ] Critical user flows verified
- [ ] Monitoring dashboards reviewed (error rates, latency, resource usage)
- [ ] Alerts reviewed - no unexpected alarms
- [ ] Sample transactions validated
- [ ] Support team confirms no immediate issues

### Communication & Handoff
- [ ] Release completion announced to stakeholders
- [ ] Release notes published and distributed
- [ ] Support team notified of successful deployment
- [ ] Communications Lead triggered customer-facing announcements
- [ ] On-call engineer briefed on release changes and potential issues

## Post-Release Monitoring (T+1 to T+7 days)

### Health & Performance Tracking
- [ ] Day 1: Monitor error rates and performance metrics closely
- [ ] Day 3: Review cumulative metrics and user feedback
- [ ] Day 7: Final review of release stability and impact

### Issue Management
- [ ] Post-deployment issues tracked and triaged
- [ ] Hotfix process initiated if critical issues identified
- [ ] Rollback executed if necessary (following documented procedure)

### Documentation & Learnings
- [ ] Release retrospective scheduled (within 1 week)
- [ ] Lessons learned documented
- [ ] Process improvements identified and tracked
- [ ] Release metrics recorded (deployment time, issues found, rollback needed, etc.)

## Rollback Procedures (If Needed)

### Rollback Triggers
- Critical production issues affecting core functionality
- Security vulnerabilities introduced
- Significant performance degradation
- Data integrity issues

### Rollback Steps
- [ ] Rollback decision made and communicated
- [ ] Automated rollback initiated (preferred) or manual rollback executed
- [ ] Database rolled back (if schema changes were made)
- [ ] Health checks verified after rollback
- [ ] Stakeholders notified of rollback
- [ ] Root cause analysis initiated
- [ ] Fix planned and scheduled for next release

## Notes
- Customize this checklist based on your specific release process and requirements
- Archive completed checklists for audit and compliance purposes
- Use this checklist in conjunction with [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

**Reference**: This template supports improvements identified in [Issue #4](https://github.com/congdanh305/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)
