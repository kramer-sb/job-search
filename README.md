# job-search

Working repo for Brie Kramer's 2026 cybersecurity job search, mainly SOC L1 (Tier 1) Analyst roles, with adjacent IT/security roles evaluated as they come up.

This repo backs a Claude Project that reviews job descriptions against a master resume and logs the results. It's not a portfolio piece, just tracking and reference material for the search itself.

## What's in here

- `CLAUDE.md` - standing instructions for the Claude Project: background, workflow for reviewing a JD, cover letter guidelines, and house style rules for anything drafted here.
- `applications-log.md` - running log of every JD reviewed, with company, role, fit verdict, and status (Reviewed / Applied / Skipped / Interviewing / Rejected / Offer).

The master resume itself lives in the Claude Project's files, not in this repo.

## How it's used

1. Share a job description with the Claude Project.
2. Claude reviews it against the master resume using the `cyber-resume-reviewer` skill and gives a fit verdict first.
3. If the fit is worth pursuing, Claude produces a full report: strongest evidence to preserve, prioritized findings, exact edits, and open questions.
4. The review gets logged in `applications-log.md`.

## Background

- Certifications: GIAC GCCC, GCIH, GSEC, GFACT; CompTIA Security+; (ISC)² CC.
- WiCyS/SANS Technology Institute scholarship alum.
- 2x Salesforce Certified Administrator; prior career in Salesforce/CRM administration and presentation/document specialist work.
- USAF veteran.
