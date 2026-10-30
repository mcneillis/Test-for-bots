# LAZ-DPIA-HR-input — Heart rate in Lazoo: input for the data protection impact assessment

**Document ID:** LAZ-DPIA-HR-input-2026-10-24
**Date:** 24 October 2026
**For:** the Research Governance Manager, who owns the data protection impact assessment (DPIA)
**Status:** DRAFT input only. It is not a DPIA, makes no decision on the lawful basis, and makes no compliance statement.
**Controller:** ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026) (12467350). Sleep & Health Clinic Ltd (08904119) gives advice only and is not a controller for Lazoo data.
**Related:** LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md); the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5]; LAZ-DPIA-001 short form (/workspace/lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DPIA-001-short-form.md).

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the line above are kept as recorded; this path answers them.

Dated note, 24 October 2026: Research Governance has issued CBT-14-HR-DPIA-2026-10-24, version 0.3 (/workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 d9c87e83928492d66fbf51a3553357107b0e9d2cf782ddcef1eea4e80a57d45f; Word version /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.docx, sha256 9c969c98c500705fb249ebcccf41d27233ff9093362deb7badec492b7da7173f), which is pending Compliance review. The version 0.2 citations in this note are kept as recorded at the time.

Dated note, 24 October 2026 (Compliance round 4, R4-7): Research Governance issued CBT-14-HR-DPIA-2026-10-24, version 0.4, at about 17:20 British Summer Time: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.4-2026-10-24.md, sha256 ddb77632d2cb7d95bda7c44037ffea12cf508f429832be8e082d98f51ff204e0. It supersedes version 0.3 as the working draft, is pending Compliance review and is not signed off. Version 0.3 (d9c87e83…) is kept unchanged.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). It is the dated cross-reference that version 0.5.1 asks for in this note. The version 0.3 note and the version 0.4 note above are kept as recorded.

## 1. Why this note exists

Sara McNeillis asked on 24 October 2026 for heart rate to be added to Lazoo's intended purpose. At 16:01 she said CBT-14 already shows heart rate as a wellness trend under a UK General Data Protection Regulation (UK GDPR) Article 9 basis and a DPIA. If heart rate flows from CBT-14 into Lazoo, Lazoo processes a new item of special category data for a new purpose, inside a medical device. The existing CBT-14 DPIA covers CBT-14 as described to Research Governance; whether it covers Lazoo is for Research Governance to decide. This note sets out the facts known today and the questions that need answers.

Dated note, 24 October 2026: correction. Under decision 2 of the addendum, the Article 9 basis and DPIA are conditions still to be met, not ones already in place. No wearer's heart rate is processed before sign-off.

## 2. The new data item

| Item | Detail |
|---|---|
| Name (proposed) | Heart rate trend, from CBT-14 |
| Source | CBT-14 chest-worn wearable, worn on the left side of the chest about 20 centimetres below the armpit, sent to the Lazoo app over Bluetooth Low Energy |
| Form | Timestamped heart rate values in beats per minute, summarised as trends over nights and weeks. Sampling rate and whether raw values or summaries are sent are to be confirmed |
| When recorded | Proposed as overnight only; to be confirmed by Sara |
| Who sees it | The person, the clinician, or both; to be confirmed by Sara |
| Not included | Heart rhythm analysis, heart rate variability, SpO2 (deferred until bench tested), core temperature (forbidden in the 18 September 2026 data-path lock) |
| Current state in Lazoo | The research data dictionary (LAZ-TPL-DICT) already reserves `vitals.wearable[]` and a source value `cbt14`, empty in version 1 |

Dated note, 24 October 2026 (17:07): Sara's decisions at 17:07 change this table, as follows. The rows above are kept as recorded at the time.

- **When recorded.** Heart rate is recorded over 24 hours, not overnight only, because heart rate together with core body temperature is essential for circadian analysis. Trends are therefore over days and weeks, not nights and weeks.
- **Who sees it.** The patient and the clinician see heart rate when the patient shares data for their report.
- **Core temperature.** Sara chose the Buller 2013 quadratic model for estimating core temperature from heart rate. If the estimate is computed in Lazoo, it is a new derived item of data concerning health, and it conflicts with the 18 September 2026 data-path lock and with decision 1 of the CBT-14 addendum (a research output, not claimed). Whether it is a claimed output is open for Sara, and it should not be processed until that is decided and this assessment covers it.

  Dated note, 24 October 2026 (Compliance round 4): this is no longer open. Sara's answer 1 of 17:07 puts the core temperature estimate in the product, superseding decision 1 of 16:01 to that extent, so it is a new derived item that this assessment has to cover. The conflict with the data-path lock now needs dated notes from its owners rather than a decision.

  Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.
- **Pregnancy.** Heart rate is hidden in pregnancy, and Lazoo may still be used in pregnancy. Recording that a person is pregnant, in order to hide heart rate, may be a new item of data concerning health; how pregnancy is known, and whether heart rate is still recorded while hidden, are to be confirmed.
- **Territory.** Northern Ireland and the European Union are in scope. Version 0.3 already records that offering Lazoo or CBT-14 to people in the European Union brings in the EU General Data Protection Regulation under Article 3(2), an EU representative under Article 27, EU transfer tools and the EU Medical Device Regulation, and that the assessment is reviewed first. How Northern Ireland users are treated is for Research Governance to confirm.

## 3. Special category data and the Article 9(2) condition

Heart rate linked to a person is data concerning health and is special category data under UK GDPR Article 9. An Article 6 lawful basis and an Article 9(2) condition are both needed. The choice is for Research Governance and the data protection officer, with Sara's decision as sponsor. The options already used in Lazoo documents are:

Dated note, 30 October 2026: the Data Protection Officer is Martin Hickley.

| Use | Options already on file | Where |
|---|---|---|
| Ordinary app use and clinician sharing | Article 6(1)(a) consent with Article 9(2)(a) explicit consent | LAZ-DPIA-001 short form, section 4 |
| Research (toggle 3) | Article 6(1)(a) consent and/or 6(1)(e); Article 9(2)(a) and/or 9(2)(j) research with safeguards | LAZ-DPIA-001 short form, section 4 |
| LAZ-VAL-001 study processing | Proposed: Article 6(1)(f) legitimate interests, with Article 9(2)(j) and the Data Protection Act 2018, for the data protection officer to confirm | LAZ-VAL-001 DMP version 0.4, lawful basis section |

Dated note, 30 October 2026: the Data Protection Officer is Martin Hickley.

These positions differ from each other already. Adding heart rate is a good moment to settle them. Research Governance to decide; no option is recommended here.

Dated note, 24 October 2026: Research Governance version 0.2 now recommends Article 6(1)(a) with Article 9(2)(a) for the optional heart-rate choice (Article 6(1)(b) only if heart rate is made core), and Article 6(1)(c) with Article 9(2)(i) (Data Protection Act 2018, Schedule 1, paragraph 3) for post-market surveillance and vigilance records under UK MDR regulation 44ZH. The Compliance gate agrees.

Dated note, 30 October 2026: Sara McNeillis decided at 08:46 that declining heart rate never stops someone using the chest patch or the app. The heart-rate choice is asked and recorded separately from other consent. Heart rate stays out of the LAZ-VAL-001 validation study (Sara McNeillis, 30 October 2026, 08:45), so the objectives and the sample size are unchanged.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The version 0.2 note above is kept as recorded; version 0.5.1 sets out the lawful basis in its section 5.

## 4. Data flow

1. CBT-14 records heart rate on the body.
2. CBT-14 sends it to the Lazoo app on the person's phone over Bluetooth Low Energy (the path locked by Sara on 18 September 2026 for skin temperature and movement only; heart rate would be a change to that lock).

Dated note, 30 October 2026: Sara McNeillis decided at 08:46 that declining heart rate never stops someone using the chest patch or the app. The heart-rate choice is asked and recorded separately from other consent. Heart rate stays out of the LAZ-VAL-001 validation study (Sara McNeillis, 30 October 2026, 08:45), so the objectives and the sample size are unchanged.

   Dated note, 24 October 2026: the change to the lock is recorded (addendum decision 2), pending sign-off of the DPIA.
3. The Lazoo app stores it on the device and shows it as a trend.

   Dated note, 24 October 2026 (17:07): heart rate is computed on the phone only, until the patient shares their data (item 3). Any core temperature estimate would also be computed on the phone; see section 2.
4. It reaches the ~~App Ltd~~ SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026) server only after the person agrees to transfer (as LAZ-DPIA-001 states for diary data). Server location to be named by IT.
5. It goes to a nominated clinician only if toggle 2 is on, and into research only if toggle 3 is on and an approved protocol includes it. LAZ-VAL-001 version 0.5 does not include it.

   Dated note, 24 October 2026 (17:07): the patient and the clinician see heart rate when the patient shares data for their report (item 6). Whether a shared report passes through the ~~App Ltd~~ SHC Sleep Solutions Limited server, and how it relates to toggle 2, is to be confirmed.
6. Whether the CBT-14 companion app is a separate app holding its own copy is to be confirmed (Compliance finding F9, 24 October 2026).

   Dated note, 24 October 2026: decision 7 makes Lazoo the companion app, so there is no separate CBT-14 app holding its own copy.

## 5. Retention

No retention period for heart rate has been set. The existing defaults are: participant-level diary data as stated in the participant information sheet for each study, otherwise kept while the account is active (LAZ-DPIA-001); trial master file and essential documents at least 10 years after the signed study report (SOP-CMF-001). Research Governance to decide whether heart rate follows the diary default or has its own, shorter period, given that only trends are proposed for display.

## 6. Pseudonymisation and the LAZ-DS-001 rule

The LAZ-DS-001 standing rule, as recorded on 26 September 2026, is that only pseudonymised diary fields and the System Usability Scale may leave after a free-text strip, with no names, NHS numbers, UCLH identity or clinic lists. No controlled file named LAZ-DS-001 was found on 24 October 2026; the rule exists as a recorded standing rule, and the Airlock data ethics note (13 October 2026) describes the older LAZ-DS-001 note as a historical record, with outbound shares now needing a current sponsor-approved data note.

Heart rate is not a diary field and not the System Usability Scale. Read strictly, LAZ-DS-001 does not allow heart rate to leave ~~App Ltd~~ SHC Sleep Solutions Limited at all, even pseudonymised. Before any outbound share of heart rate, the rule, or the current data note that replaces it, would need to be updated by the sponsor. Heart rate time series can also be distinctive, so pseudonymisation alone may not prevent re-identification; aggregated trends lower that risk.

## 7. Questions for Research Governance

1. Does the existing CBT-14 heart rate DPIA cover processing in Lazoo, or is a Lazoo-specific DPIA or update to LAZ-DPIA-001 needed? Please add its path so documents can cite it.

   Dated note, 24 October 2026: path /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md (version 0.2, sha256 ba0e2110…).

   Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The version 0.2 path above is kept as recorded.
2. Which Article 6 basis and Article 9(2) condition apply to heart rate for ordinary use, clinician sharing and research?
3. Does moving heart rate from a wellness product into a medical device's purpose change the lawful basis analysis in the CBT-14 DPIA?
4. What retention period applies to heart rate?
5. Should LAZ-DS-001, or the current data note, be updated to allow pseudonymised heart rate trends to leave ~~App Ltd~~ SHC Sleep Solutions Limited, or should heart rate stay inside ~~App Ltd~~ SHC Sleep Solutions Limited?
6. Is a separate consent toggle or consent wording for heart rate needed? A proposed addition is drafted at the end of the consent template (/workspace/lazoo-cmf/04-templates/consent-four-toggles.md).
7. Does processing of heart rate in pregnancy need specific treatment, given that Lazoo may be used in pregnancy?
8. Where will heart rate be stored, and does it change the server location or processor contracts?

Dated note, 30 October 2026: Sara McNeillis decided at 08:46 that declining heart rate never stops someone using the chest patch or the app. The heart-rate choice is asked and recorded separately from other consent. Heart rate stays out of the LAZ-VAL-001 validation study (Sara McNeillis, 30 October 2026, 08:45), so the objectives and the sample size are unchanged.

Dated note, 24 October 2026 (17:07): further questions following Sara's decisions.

9. Does version 0.3 cover 24-hour recording, rather than overnight only?
10. If a core temperature estimate is computed, even if never shown, which lawful basis and Article 9(2) condition apply, and is it compatible with the data-path lock?

    Dated note, 24 October 2026 (Compliance round 4): the estimate is in the product (Sara's answer 1 of 17:07), so the question is which lawful basis and Article 9(2) condition apply to it, not whether it is computed.
11. Is recording pregnancy, so that heart rate can be hidden, a new item of special category data, and is heart rate still recorded while hidden?
12. Does the shared report travel through the ~~App Ltd~~ SHC Sleep Solutions Limited server, and if so is that a new transfer?
13. For users in Northern Ireland and the European Union, who is the EU representative under Article 27, and which transfer tools apply?
