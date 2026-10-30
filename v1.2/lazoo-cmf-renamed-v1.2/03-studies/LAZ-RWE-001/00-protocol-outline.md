Amendment pending, 24 October 2026: A heart-rate intended-purpose amendment is in draft under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md), awaiting review by Compliance and a decision by Sara McNeillis. The text below is unchanged and remains current until that amendment is approved. Data protection: see LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md) and the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5].

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the note above are kept as recorded; this path answers them.

Dated note, 24 October 2026: Sara McNeillis made the decision at 16:03 London time ("Add heart rate to Lazoo's intended purpose"). The drafted amendment LAZ-IP-001-AMD-01 and the classification review LAZ-CL-001-REV-01 now await the Compliance gate (/workspace/compliance-reports/lazoo-hr-amendment-gate-2026-10-24.md) and then Sara's approval of the wording. Until then heart rate stays outside Lazoo's cleared intended purpose. The note above is kept as written.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “TBD — pending Sara paste.” Pack stays OPEN. Earlier dates in this file are kept.

# LAZ-RWE-001 — Protocol outline (not for IRAS yet)

**Study ID:** LAZ-RWE-001  
**Version:** 0.1 outline  
**Date:** 28 August 2026  
**Status:** Draft for CI. Do not collect “research” data until this is approved.

## Title

A consented observational research dataset from adults using the Lazoo restricted sleep diary.

## Purpose

Create a reusable, ethically collected dataset of self-reported sleep and lifestyle logs (and, later, empty-but-reserved wearable / core-temp fields) for:

- describing real-world diary use
- supporting future protocol-ready extracts for licensed investigators
- **not** for training a diagnostic model unless toggle 4 is separately consented and a later protocol covers it

There is one layer. This outline is not a second product and it is not evidence of a mark. Clinical claims: TBD — pending Sara paste.

## Design

- Non-CTIMP observational
- Prospective
- Restricted-app users who switch **on** consent toggle 3 (research)
- Toggle 4 (future clinical tools / models) is optional, cannot be required to use the diary, and is **off** as the default analysis population for this protocol
- Withdrawal on toggle 3/4 stops **future** research use of that person’s data

## Population (default)

Adults using Lazoo under a research licence or SHC clinic research invitation. No NHS-identifiable data in the analysis file without mCIA + ethics + the NHS rule in LAZ-CL-001.

## Data

Per the v1 extras build list: sleep log, user-entered lifestyle text, device metadata, consent version, study_link. Vitals and `ai_event` reserved, empty.

Research export: consented users only, pseudonymised, documented dictionary, raw timestamps.

## Governance

- REC review of this protocol and the live consent screens
- DPIA before first research export
- Licence sites: ISF from the template; site PI signs; SHC remains sponsor of the **dataset** unless a written agreement says otherwise
- Do not send outreach to Colin Espie, GSTT/UCLH patient inboxes, or iris.study@ndcn.ox.ac.uk

## What this protocol will not do

- Fill a clinical claim. Claims: TBD — pending Sara paste.
- Run an AI module
- Change clinical care
- Present this outline as UKCA, CE, or a compliance statement
