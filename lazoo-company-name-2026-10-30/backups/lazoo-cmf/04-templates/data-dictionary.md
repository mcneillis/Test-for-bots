Amendment pending, 24 October 2026: A heart-rate intended-purpose amendment is in draft under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md), awaiting review by Compliance and a decision by Sara McNeillis. The text below is unchanged and remains current until that amendment is approved. Data protection: see LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md) and the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5].

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the note above are kept as recorded; this path answers them.

Dated note, 24 October 2026: Sara McNeillis made the decision at 16:03 London time ("Add heart rate to Lazoo's intended purpose"). The drafted amendment LAZ-IP-001-AMD-01 and the classification review LAZ-CL-001-REV-01 now await the Compliance gate (/workspace/compliance-reports/lazoo-hr-amendment-gate-2026-10-24.md) and then Sara's approval of the wording. Until then heart rate stays outside Lazoo's cleared intended purpose. The note above is kept as written.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “TBD — pending Sara paste.” Pack stays OPEN. Earlier dates in this file are kept.

# Template — Lazoo research data dictionary (v1)

**Document ID:** LAZ-TPL-DICT  
**Version:** 0.1  
**Date:** 28 August 2026

Field names below are the research-facing names. Engineering may differ; map them in the next revision from the live schema.

## Identity and study

| Field | Type | Notes |
|---|---|---|
| user_id | stable ID | Not a display name |
| study_id | string | e.g. LAZ-VAL-001 |
| site_id | string | e.g. SHC, SSRC |
| consent_pack_version | string | Version shown |
| consent_t1_t4 | booleans + timestamps | Withdrawal logged |
| app_version | string | |
| os | string | |
| source | enum | manual \| wearable \| cbt14 \| import |

## Sleep log (core)

| Field | Type | CSD-M map (working) |
|---|---|---|
| diary_date | date | Night of |
| timezone | IANA | |
| in_bed | datetime | CSD: time got into bed |
| sleep_attempt | datetime | CSD: time tried to sleep (if collected) |
| sleep_onset | datetime | CSD: time fell asleep |
| awakenings_n | int | CSD: number of awakenings |
| awakenings_detail[] | datetime + duration | CSD: WASO construction |
| wake | datetime | CSD: final wake |
| out_of_bed | datetime | CSD: time out of bed |
| naps[] | datetime + duration | |
| notes | text | User text. Do not type a clinical claim in this field. |

Derived clinical metrics: TBD — pending Sara paste.

## Lifestyle (user-entered text only)

caffeine, alcohol, medications as **text**, not a coded medical history.

## Reserved, empty in v1

`vitals.core_temp[]`, `vitals.wearable[]`, `ai_event[]` — present in export, unused until a later protocol.

## Export rules

- JSON + CSV
- Raw timestamps, not only charts
- Research export: toggle 3 on, pseudonymised
- VAL-001 also keeps paired CSD-M fields in a separate table keyed by user_id + diary_date

## Proposed addition, 24 October 2026

Draft only, under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md). Not in force until approved by Compliance and Sara McNeillis. Not collected in LAZ-VAL-001 version 0.5. Data protection: LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md) and the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5].

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the paragraph above are kept as recorded; this path answers them.

### Heart rate from CBT-14 (proposed)

| Field | Type | Notes |
|---|---|---|
| vitals.heart_rate[] | array of {timestamp: datetime with timezone, bpm: integer} | Heart rate received from CBT-14 over Bluetooth Low Energy, with source = cbt14. CBT-14 is worn on the left side of the chest. Overnight only, to be confirmed. Sampling rate, and whether raw values or summaries are received, to be confirmed. |
| vitals.heart_rate_trend[] | array of {diary_date: date, resting_hr_bpm: integer, n_samples: integer} | One value per night, derived for trend display only. Derivation method to be confirmed and fixed under change control. |
| hr_source_device | string | Pseudonymous pairing identifier for the CBT-14 unit. Format to be confirmed. |

Rules for these fields:

- Trend display only. There are no flag, alert, threshold, rhythm, arrhythmia, atrial fibrillation or heart rate variability fields, and none may be added without a new classification review (LAZ-CL-001-REV-01).
- Raw timestamps are kept, as for the sleep log, and exported in JSON and CSV.
- Research export only with toggle 3 on and an approved protocol that names heart rate. Under the LAZ-DS-001 rule as recorded, only pseudonymised diary fields and the System Usability Scale may leave, so heart rate stays inside App Ltd until that rule or the current data note is updated by the sponsor.
- SpO2 is not added; it is deferred until bench tested. Core temperature stays reserved and empty.
