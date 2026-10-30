Amendment pending, 24 October 2026: A heart-rate intended-purpose amendment is in draft under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md), awaiting review by Compliance and a decision by Sara McNeillis. The text below is unchanged and remains current until that amendment is approved. The working classification review for the amendment is LAZ-CL-001-REV-01 (/workspace/lazoo-cmf/01-product/LAZ-CL-001-REV-01-heart-rate-classification-review-2026-10-24.md).

Dated note, 24 October 2026: Sara McNeillis made the decision at 16:03 London time ("Add heart rate to Lazoo's intended purpose"). The drafted amendment LAZ-IP-001-AMD-01 and the classification review LAZ-CL-001-REV-01 now await the Compliance gate (/workspace/compliance-reports/lazoo-hr-amendment-gate-2026-10-24.md) and then Sara's approval of the wording. Until then heart rate stays outside Lazoo's cleared intended purpose. The note above is kept as written.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “TBD — pending Sara paste.” Pack stays OPEN. Earlier dates in this file are kept.

# LAZ-RSK-001 — Risk plan (~~App Ltd~~ SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026) information governance)

**Organisation:** ~~Sleep and Health Clinic App Limited~~ SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026) (12467350)  
**Version:** 0.1 draft  
**Date:** 28 August 2026  
**This draft is not an ISO 14971 file and it is not a finished device risk file.** It covers information-governance and study-conduct risk. Lazoo is SaMD Class IIa (class 2a). Clinical claims: TBD — pending Sara paste. This plan is not UKCA, not CE, and not a compliance statement.

## Purpose

Find and control risks that would (a) fill a clinical claim before Sara pastes it, (b) put app research on the CQC clinic company, or (c) process children’s or school data. The product is already SaMD Class IIa. One layer.

## Identification (current)

| ID | Risk | Rating if uncontrolled |
|---|---|---|
| R1 | Store, PIS, or protocol fills a clinical claim, or reuses killed diagnosis wording | High |
| R2 | ~~App Ltd~~ SHC Sleep Solutions Limited data filed on 08904119 or in a CQC location record | High |
| R3 | Paediatric / school letter used; teaching staff access | High |
| R4 | UCLH PIS used with Chelsea PALS, Gmail, or a fake REC opinion | High |
| R5 | Future-use and model-training bundled as required consent | Medium |
| R6 | A draft CER or DHF treated as finished or as a mark | High |
| R7 | Grant-title wording copied in as if it were the clinical claim | High |
| R8 | Security incident on diary data | High |
| R9 | Retention not defined; data kept with the wrong controller | Medium |

Dated note, 24 October 2026 (round 6, item for Clinical Research in CBT-14-HR-DPIA-2026-10-24, version 0.5.1; proposed, and applies only if LAZ-IP-001-AMD-01 is approved): proposed risk R10, the pregnancy hide. Heart rate is hidden in pregnancy (Sara's answer 8 of 24 October 2026 at 17:07), and the classification review LAZ-CL-001-REV-01 (section 9.6, and guard 5 in section 9.9) treats the hide as a risk control that the working Class IIa view depends on, so it has to work reliably. The risk is that heart rate, or anything calculated from it, is shown or shared for a person who is pregnant because pregnancy is not known, is recorded late, or the control fails. Rating if uncontrolled: to be confirmed. Controls: to be confirmed once Sara has decided how pregnancy is recorded and whether heart rate is still recorded while hidden (LAZ-IP-001-AMD-01, section 11.7, question 11) and whether the core temperature estimate is hidden too (decision R4-D2 in the Compliance gate memo, section 8.5). Research Governance recommends a single yes-or-no setting that the person sets and clears on the phone, and neutral wording for a hidden period in a shared report, so that the clinician cannot infer pregnancy from a gap (assessment, section 3a); these are recommendations only. The pregnancy setting is itself data concerning health. The table above is kept as written.

## Controls

- Purpose not frozen. LAZ-IP-001 is TBD — pending Sara paste.
- Do not write an AI validation report, CER, or technical file in this plan, and do not mark one done
- DHF stub limited to consent versioning and audit trail (LAZ-DHF-001)
- Company lock 12467350 on ~~App Ltd~~ SHC Sleep Solutions Limited papers; UCLH papers in a separate sponsor file
- Paediatric letter in do-not-send (now named lazoo-cmf/archive/Withdrawn documents 2026-08-28/, 30 October 2026)
- Four consent toggles; 3 and 4 default off
- Encryption in transit; access logs; no ads/Customer Match
- 10-year essential-record retention on ~~App Ltd~~ SHC Sleep Solutions Limited storage

## Residual risk

R1–R4 stay open controls. A filled clinical claim before Sara pastes it re-opens R1 and stops enrolment. Store listing was not changed. Pack stays OPEN.

## Review

Compliance reviews this plan when intended purpose, company, or a study site changes, and at least at each protocol version.
