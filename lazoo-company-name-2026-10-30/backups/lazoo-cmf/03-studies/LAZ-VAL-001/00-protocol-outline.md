Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “TBD — pending Sara paste.” Pack stays OPEN. Earlier dates in this file are kept.

Change note 3 October 2026 (VAL-001 HOLD fix): Setting is invited adult volunteers of Sleep and Health Clinic App Ltd (12467350). Identifiable files stay on App Ltd 12467350 storage. Sleep & Health Clinic Ltd (08904119) is advice only. The device-investigation wording is removed. Vigilance, and whether this study is a UK MDR clinical investigation, are not decided while intended purpose is TBD — pending Sara paste. TST, SOL, WASO, and SE in this outline are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays TBD — pending Sara paste. The Word protocol is not the current protocol. Pack stays OPEN. Earlier dates in this file are kept.

> **Superseded as the working protocol.** Use `LAZ-VAL-001-protocol-v0.4.md` (11 October 2026) only; versions 0.3 and 0.2 are kept for history. The Word protocol is quarantined and must not be opened as the current protocol. This outline remains for history. Sponsor for VAL-001 is Sleep and Health Clinic App Ltd (12467350). Sleep & Health Clinic Ltd (08904119) is advice only.

# LAZ-VAL-001 — Protocol outline (not for IRAS yet)

**Study ID:** LAZ-VAL-001  
**Version:** 0.1 outline  
**Date:** 28 August 2026  
**Status:** Draft for CI. Not a complete protocol. Do not submit.

## Title

Concurrent validity and usability of the Lazoo digital sleep diary compared with the Consensus Sleep Diary in adults.

## Synopsis

| Item | Proposal |
|---|---|
| Sponsor | Sleep and Health Clinic App Ltd (12467350) |
| CI | Dr Sara McNeillis (proposed) |
| Design | Prospective, paired, 14 consecutive mornings. Non-CTIMP. UK MDR clinical investigation: not decided in this outline |
| Product | Lazoo, SaMD Class IIa (class 2a). One layer. Intended purpose: TBD — pending Sara paste. |
| Comparator | Consensus Sleep Diary–Morning (CSD-M), Carney et al. *Sleep* 2012;35:287–302 |
| Setting (default) | Invited adult volunteers of Sleep and Health Clinic App Ltd (12467350). Not patients of Sleep & Health Clinic Ltd (08904119). The clinic company is advice only. **No NHS site** until the register says otherwise |
| Duration | Screening + 14 diary mornings + short usability interview |
| Sample size | Feasibility target **30 completers** (≥10 of 14 paired mornings). Formal Bland–Altman precision to be calculated at v0.2 |
| Registration | If this remains research, register (e.g. ISRCTN / OSF) before first participant, per HRA transparency policy |

## 1. Rationale

Digital diaries used as research outcome tools need evidence that they capture the same constructs as the Consensus Sleep Diary and that the electronic system is fit for that purpose (complete timestamps, editable with audit trail, exportable raw values). Clinical claims: TBD — pending Sara paste.

## 2. Objectives

**Primary:** Agreement between Lazoo and CSD-M for total sleep time (TST) over paired nights.

**Secondary:**

- Agreement for sleep onset latency (SOL), wake after sleep onset (WASO), sleep efficiency (SE), number of awakenings
- Completeness (nights with both diaries; item-level missingness)
- Timestamp integrity and audit-trail completeness on Lazoo edits
- Usability (System Usability Scale + three structured questions)
- Optional subset: concordance with wrist actigraphy, if a device is available. Vigilance, and whether this study is a UK MDR clinical investigation, are not decided while intended purpose is TBD — pending Sara paste.

## 3. Participants

- Adults ≥18 years
- Able to use the restricted app in English
- Willing to complete Lazoo **and** CSD-M each morning for 14 days
- Exclude: inability to give consent; current participation in another sleep-diary trial that would duplicate nights; anyone for whom completing two diaries would be clinically inappropriate

NHS patients are **not** enrolled under this outline. If that changes, stop and add HRA Approval, mCIA, and the NHS-data rule in LAZ-CL-001.

## 4. Procedures

1. Consent (written or REC-approved remote). Consent pack version stored on the user record.
2. Issue study code / login. App must not be publicly listed.
3. Training: one walkthrough of Lazoo morning diary and CSD-M. CSD-M completed first on paper or locked PDF so Lazoo cannot auto-fill it.
4. 14 mornings: CSD-M then Lazoo, same sitting. No in-app interpretation.
5. Day 15: return CSD-M, complete SUS, short interview.
6. Optional nights 1–14: actigraphy on a named, CE-marked logger, scored to a pre-specified rule. File the scoring SOP if this arm is switched on.

## 5. Endpoints and analysis (v0.1)

- Primary: Bland–Altman of night-level TST (Lazoo minus CSD-M), mean bias and 95% limits of agreement, with clustered nights within participant
- Secondary: same for SOL, WASO, SE; ICCs; completion rates; SUS
- No diagnostic cut-points. No “valid for insomnia” claim in the report.

TST, SOL, WASO, and SE in this outline are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays TBD — pending Sara paste.

Sample size at v0.2: calculate n so the 95% CI around limits of agreement for TST is usable (target to be set with a sleep statistician). 30 completers is a feasibility floor, not the final n.

## 6. Data management

- Lazoo export: JSON + CSV, raw timestamps, study_link, consent version, app version
- CSD-M: source worksheets retained; double-entered or photographed with a file log
- Edits on Lazoo: append-only audit trail (who/what/when). Original value retained
- Identifiable files stay on Sleep and Health Clinic App Ltd (12467350) storage. Analysis file pseudonymised. Sleep & Health Clinic Ltd (08904119) is advice only
- No training of a future model on these data unless toggle 4 was collected **and** the protocol / PIS said so. Default for VAL-001: **toggles 1 and 3 only**; toggle 4 off unless CI explicitly adds it

## 7. Ethics and governance

- This is research. REC review before first participant.
- Not a CTIMP. UK MDR clinical investigation: not decided in this outline. The old not-a-device reason is withdrawn.
- Insurance: research certificate filed before enrolment.
- Deviation log in this folder.
- Safety: signpost if a participant reports distress. Clinical claims: TBD — pending Sara paste. This outline does not invent a vigilance pathway and does not mark UKCA, CE, or compliance.

## 8. IP and publication

Sleep and Health Clinic App Ltd (12467350) is the sponsor of the protocol, the app, and the study dataset. Sleep & Health Clinic Ltd (08904119) is advice only. Investigators may publish the validation results. No store copy may claim “validated to diagnose” off this study.

## 9. What v0.2 must add before IRAS

- Final n and analysis plan signed
- Exact CSD-M items mapped to Lazoo fields (use the data dictionary)
- Whether actigraphy is in or out
- PIS / consent on Sleep and Health Clinic App Ltd (12467350) letterhead. Not Sleep & Health Clinic Ltd (08904119)
- Site list
- Insurance certificate
- App version pin
