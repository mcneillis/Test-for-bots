Amendment pending, 24 October 2026: A heart-rate intended-purpose amendment is in draft under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md), awaiting review by Compliance and a decision by Sara McNeillis. The text below is unchanged and remains current until that amendment is approved. Data protection: see LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md) and the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5].

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the note above are kept as recorded; this path answers them.

Dated note, 24 October 2026: Sara McNeillis made the decision at 16:03 London time ("Add heart rate to Lazoo's intended purpose"). The drafted amendment LAZ-IP-001-AMD-01 and the classification review LAZ-CL-001-REV-01 now await the Compliance gate (/workspace/compliance-reports/lazoo-hr-amendment-gate-2026-10-24.md) and then Sara's approval of the wording. Until then heart rate stays outside Lazoo's cleared intended purpose. The note above is kept as written.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “TBD — pending Sara paste.” Pack stays OPEN. Earlier dates in this file are kept.

# LAZ-DPIA-001 — Short-form DPIA

**Controller:** Sleep and Health Clinic App Limited, company number **12467350**, 32 Watford Road, Northwood HA6 3NT  
**Not** Sleep & Health Clinic Ltd 08904119. **Not** CQC provider 1-14614784057.  
**Product:** Lazoo. SaMD Class IIa (class 2a). One layer. Not a wellness product. Not “not a medical device”.  
**Version:** 0.1 draft  
**Date:** 28 August 2026  
**Status:** OPEN. Working draft for App Ltd. DPO named person still blank. Not signed. Not frozen. Not UKCA. Not CE. Not a compliance statement.

## 1. Need for a DPIA

Yes. Special-category health data, new processing, app + research use.

## 2. Description of processing

| Item | v1 |
|---|---|
| What | Self-reported sleep and lifestyle diary (bed/wake, awakenings, naps, notes). Charts/history of what the user typed. Optional share of that history. Optional research copy. |
| Clinical processing | TBD — pending Sara paste. School records and children’s data are not in the first-wave note from 28 August 2026. |
| Who | Adults using the restricted research app (study code / closed testing) |
| Where | User device; App Ltd server only after the user agrees to transfer. UK/adequate location to be named by IT before go-live |
| Recipients | App Ltd staff on a need-to-know basis; nominated clinician only if toggle 2 is on; named investigators on an approved protocol only if toggle 3 is on |
| Not recipients | Sleep & Health Clinic Ltd as controller; CQC clinic systems; advertisers; schools; teaching staff; Google Customer Match |

Dated note, 24 October 2026 (round 6, item for Clinical Research in CBT-14-HR-DPIA-2026-10-24, version 0.5.1, for the rows on where data is held and who receives it): under Sara's answer 3 of 17:07 ("3 yes on phone only until it is shared by patient"), heart rate and the core body temperature estimate are processed and held on the person's phone only, and leave it only when the person chooses to share their data for a report. The recipient on sharing is the person's clinician. Whether that clinician is App Ltd staff or works for an outside organisation, and so who controls the shared copy, is pending Sara (assessment decision 5), as is whether a report goes straight from the phone or through an App Ltd server (assessment decision 6). The assessment recommends that the pregnancy setting stays on the phone and is never included in a shared report (its section 3a); how pregnancy is recorded is pending Sara. The rows above, written for the sleep diary, are kept as written. Research Governance's list gives these as lines 25 and 26; in this file they are the "Where" and "Recipients" rows, lines 27 and 28.

Dated note, 24 October 2026 (Compliance round 6, R6-1): to be exact, heartbeats are detected on the CBT-14 patch, and heart rate and the core body temperature estimate are worked out from them on the person's phone. What "on phone only" means for the CBT-14 patch itself, including what the patch detects, holds and passes to the phone, is still open (decision R4-D4 in the Compliance gate memo, section 8.5), so the note above describes the phone and the shared report and does not settle the patch. The note above is kept as written.

## 3. Intended purpose (must match LAZ-IP-001)

TBD — pending Sara paste.

## 4. Lawful basis (draft)

| Processing | Article 6 | Article 9 |
|---|---|---|
| Use the diary (toggle 1) | Consent 6(1)(a) | Explicit consent 9(2)(a) |
| Share with nominated clinician (toggle 2) | Consent 6(1)(a) | Explicit consent 9(2)(a) |
| Research (toggle 3) | Consent and/or task in the public interest 6(1)(e) once a protocol exists | Explicit consent 9(2)(a) and/or research 9(2)(j) with safeguards |
| Research (toggle 3) — dated row, 24 October 2026, supersedes the research row above | Legitimate interests 6(1)(f), or task in the public interest 6(1)(e) only where a public task genuinely exists | Research 9(2)(j) with Data Protection Act 2018, Schedule 1, paragraph 4, subject to the UK GDPR Articles 84A to 84D safeguards and research ethics approval. Consent to take part remains the ethical safeguard, not the lawful basis. Source: CBT-14-HR-DPIA-2026-10-24, version 0.2, section 5 |
| Heart rate in Lazoo (proposed consent choice 5) — dated row, 24 October 2026, applies only if LAZ-IP-001-AMD-01 is approved | Consent 6(1)(a) | Explicit consent 9(2)(a) |
| Post-market surveillance and vigilance records — dated row, 24 October 2026 | Legal obligation 6(1)(c) | Public health 9(2)(i) (Data Protection Act 2018, Schedule 1, paragraph 3; arrangement to be confirmed by the Data Protection Officer and legal adviser) |
| Future tools/models (toggle 4) | Consent 6(1)(a) — optional, off by default | Explicit consent 9(2)(a). **Never** NHS-identifiable data without a separate contract and ethics |

Dated note, 24 October 2026 (round 6, item for Clinical Research in CBT-14-HR-DPIA-2026-10-24, version 0.5.1, for the heart rate row at line 43): Research Governance recommends that explicit consent under Article 9(2)(a), with consent under Article 6(1)(a), covers heart rate, the core body temperature estimate, the circadian analysis and the pregnancy setting within Lazoo, and the sharing of a report with the person's clinician at the person's request (its section 5). The estimate is calculated from heart rate on the phone, so turning heart rate off also stops the estimate. The pregnancy setting is itself data concerning health. The final choice of basis remains Sara's, on the Data Protection Officer's advice, and whether consent choice 5 is extended or a separate choice is added for the estimate is pending Sara (assessment decision 4). The rows above are kept as written.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The research row at line 42 cites version 0.2, section 5, and is kept as recorded.

Clinic treatment is a different controller and a different basis. Do not rely on “medical care” for App Ltd research data.

## 5. Retention

| Record | Period |
|---|---|
| App Ltd TMF / essential documents | At least 10 years after signed study report (SOP-CMF-001), on App Ltd storage |
| Participant-level diary data | As stated in the PIS for that study; default: keep while the account is active, then as the PIS |
| UCLH feasibility data | UCLH controller — does **not** sit on this DPIA or on App Ltd servers as a UCLH dataset |
| Paediatric / school trial data | Not collected. Letter killed |

## 6. Risks and controls

| Risk | Control |
|---|---|
| A clinical claim written before Sara pastes it | Purpose is not frozen. Claims: TBD — pending Sara paste. Do not treat a draft as a finished CER. Store listing was not changed. |
| Wrong company holds the data | App Ltd 12467350 only. No CQC clinic EPR, no 08904119 as controller |
| Child / school processing | First wave adult only. Paediatric letter in do-not-send |
| Broad “future research” bundled into care | Four separate toggles; 3 and 4 default off |
| Personal Gmail / informal contacts | Research contacts @nhs.net / App Ltd domain only |
| Identifiable data in chat or ads | Ban. No Customer Match, no remarketing of health data |
| Retention too short or too long | 10-year essential records; PIS period for person-level data; DPO to confirm |

## 7. Sign-off (blank)

| Role | Name | Date |
|---|---|---|
| DPO / data protection lead | *to be named* | |
| App Ltd director | | |
| CI for any study using this processing | | |

ICO registration number: *insert App Ltd registration, not the clinic’s.*
