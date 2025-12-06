# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
The **Release Readiness Lead** validates that all requirements are met before deployment:
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Go/no-go decision facilitated with Technical Lead, QA, and Project Lead

## Deployment Checklist
The **Release Readiness Lead** manages this checklist and coordinates with relevant roles:
- [ ] Deployment window scheduled (if needed) — coordinate with Operations
- [ ] Backup or snapshot (if applicable) — verify with Technical Lead
- [ ] Deploy to staging and run smoke tests — QA validation
- [ ] Deploy to production (automated pipeline preferred) — Technical Lead executes
- [ ] Run post-deploy verifications — Release Readiness Lead confirms
- [ ] Announce release to stakeholders and support — coordinate with Stakeholder Liaison

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **Release Readiness Lead** triggers incident response and notifies on-call
  - Technical Lead executes rollback to last known-good release if necessary
  - **Release Readiness Lead** coordinates triage with Technical Lead and Risk Owner
  - **Risk Owner** captures root cause and action items for retrospective
  - **Stakeholder Liaison** communicates incident status to affected stakeholders

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
