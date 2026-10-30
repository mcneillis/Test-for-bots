# LAZ-IP-001-AMD-01 — Draft amendment: heart rate trend in Lazoo's intended purpose

**Document ID:** LAZ-IP-001-AMD-01
**Amends:** LAZ-IP-001 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-intended-purpose.md)
**Date:** 24 October 2026
**Status:** DRAFT for review by Compliance and decision by Dr Sara McNeillis. Not approved. Not locked. Not signed. Lazoo is not yet UKCA-marked, and this document makes no compliance statement.

Dated note, 24 October 2026: Sara made the decision at 16:03. This draft now awaits the Compliance gate and then her approval of the wording.

Dated note, 24 October 2026 (17:07): status updated. At 17:07 Sara approved in principle the amendment to the statement of purpose, as relayed by the chief executive's assistant. The amendment is approved in principle by Sara and pending Compliance, and the final wording still needs her approval. The decisions and the revised proposed wording are in section 11. Where section 11 differs from sections 4 to 8, section 11 is the current proposal; the earlier text is kept for the record.

**Manufacturer, sponsor, funder and owner of the intellectual property:** Sleep and Health Clinic App Ltd (12467350). Sleep & Health Clinic Ltd (08904119) gives advice only.
**Source of the request:** Sara McNeillis, 24 October 2026 at 16:03 (British Summer Time): "Add heart rate to Lazoo's intended purpose". Context given by Sara at 16:01 the same day is set out in section 2.

## 1. Why this amendment exists

Sara has asked for heart rate to become part of what Lazoo is intended to do. Lazoo is software as a medical device with a working UK classification of Class IIa, and its intended purpose is insomnia monitoring only (sponsor decision, 13 October 2026). Because the intended purpose governs how a device is classified, any addition to it has to be drafted, reviewed and approved before it is used anywhere else. This document is that draft. Until it is approved, every controlled document keeps its current wording.

## 2. What Sara said on 24 October 2026

At 16:01 Sara described the position as follows. CBT-14 is a chest-worn wearable that shows heart rate as a wellness trend, with a UK General Data Protection Regulation (UK GDPR) Article 9 basis and a data protection impact assessment. The Lazoo app is the companion app for CBT-14. CBT-14 is worn on the left side of the chest, about 20 centimetres below the armpit. The claim for CBT-14 stays at skin temperature trends, and logging of blood oxygen saturation (SpO2) is deferred until it has been bench tested. At 16:03 she asked for heart rate to be added to Lazoo's intended purpose.

Dated note, 24 October 2026: Sara's exact words at 16:01 were "1 yes 2 yes 3 yes 4 wait 5 left 6 wait 7 Lazoo is companion 8 defer until bench tested 9 not yet", answering the CEO's numbered key in the CBT-14 addendum (df23b1e4, from line 388). The paragraph above is a summary of the addendum, not her words. Under decision 2, heart rate is shown subject to an Article 6 basis, an Article 9(2) condition and a DPIA that are still to be signed off; no wearer's heart rate is processed before then. Under decision 5 (line 403), the wear site is the lower lateral chest wall, about 20 centimetres below the armpit fold, on the left side, with rib level still to be settled by the fit study.

## 3. Current wording, quoted exactly

The controlled intended purpose statement, LAZ-IP-001 (sha256 a6e69d5a9687ac5ca78a86fe61210700f479feaeacdf2bb1aa5636170aec1590 on 24 October 2026), has not yet had its purpose text pasted in. Under the heading "Intended purpose" it reads, in full:

Dated note, 24 October 2026: after its header note was inserted, LAZ-IP-001 now has sha256 56ddadcc…; the text below the note is unchanged from a6e69d5a….

> TBD — pending Sara paste.

Its headings "Pregnancy in/out" and "Clinical claims" carry the same words.

The monitoring-only scope decided on 13 October 2026 is recorded in other documents. The draft intended purpose statement (/workspace/out/lazoo-uclh-pack-2026-10-13/INTENDED-PURPOSE-LAZOO-DRAFT-2026-10-12.docx) gives the medical purpose as:

> Lazoo is software as a medical device. Its intended purpose is insomnia monitoring only: it supports a clinician in monitoring insomnia in adults aged 18 and over.

The same draft also says: "The patient receives no diagnosis, treatment or advice from the app and is not the user of its clinical outputs", and "The app is not an emergency service."

The validation protocol LAZ-VAL-001 version 0.5 states: "Intended purpose: insomnia monitoring only (sponsor decision, 13 October 2026). No therapy claims. Lazoo may be used in pregnancy, confirmed 13 October 2026."

## 4. Proposed added wording

The wording below is proposed for insertion after the medical-purpose sentence once the full intended purpose is pasted into LAZ-IP-001. It is written so that heart rate sits inside insomnia monitoring and does not become a separate monitoring function.

> As part of insomnia monitoring, Lazoo may display trends in resting heart rate recorded overnight by the companion wearable CBT-14, worn on the left side of the chest. Heart rate is shown alongside the sleep diary as a trend over nights and weeks, to give the clinician context when reviewing the person's sleep. Lazoo does not diagnose any heart condition or any other condition, does not detect or classify heart rhythm, does not issue alarms, alerts or notifications about heart rate, does not apply thresholds that prompt any action, and is not intended for monitoring in situations where a change in heart rate could result in immediate danger. Heart rate shown in Lazoo is not a measurement for clinical decisions on its own, and the person should seek medical advice in the usual way if they feel unwell.

Dated note, 24 October 2026 (17:07): superseded. The words "resting heart rate recorded overnight" and "as a trend over nights and weeks" in the paragraph above are superseded by Sara's decision at 17:07 that heart rate is recorded over 24 hours, because heart rate together with core body temperature is essential for circadian analysis. The replacement wording is in section 11.3. The paragraph above is kept as drafted, for the record.

Notes on the proposed wording:

- "Resting heart rate recorded overnight" is proposed to keep the scope tied to sleep. Whether CBT-14 records heart rate only overnight, or throughout the day, is to be confirmed by Sara.
- Who sees the heart rate trend, the person, the clinician or both, is to be confirmed. The current draft says the patient is not the user of Lazoo's clinical outputs, so showing heart rate to the patient needs a decision.
- Dated note, 24 October 2026 (17:07): the two points above are answered. Heart rate is recorded over 24 hours (item 7), and the patient and the clinician see heart rate when the patient shares data for their report (item 6). The "overnight" wording is superseded; see section 11.
- The wording deliberately avoids words such as "measure", "detect", "alert", "alarm", "abnormal", "warning", "irregular", "arrhythmia", "atrial fibrillation" and "screening". The reasons are set out in LAZ-CL-001-REV-01.
- Skin temperature trends from CBT-14 are not added by this amendment. Sara's 16:01 message said the claim stays at skin temperature trends for CBT-14; whether skin temperature should also be shown in Lazoo is an open question for her (section 8).
- SpO2 is not added. Sara deferred SpO2 logging until it has been bench tested.
- Dated note, 24 October 2026: Compliance suggests leaving the wear site out of Lazoo's purpose, because it belongs in the CBT-14 instructions for use, and settling the closing sentence once Sara has said who sees heart rate (open question 3).

Dated note, 30 October 2026: Sara McNeillis decided at 08:46 that declining heart rate never stops someone using the chest patch or the app. The heart-rate choice is asked and recorded separately from other consent. Heart rate stays out of the LAZ-VAL-001 validation study (Sara McNeillis, 30 October 2026, 08:45), so the objectives and the sample size are unchanged.

## 5. Pregnancy

The pregnancy position is unchanged. Lazoo may be used in pregnancy as part of its intended purpose (confirmed 13 October 2026). The validation study LAZ-VAL-001 keeps pregnancy as exclusion criterion 7, because use in pregnancy will be evaluated in a separate, dedicated study. Nothing in this amendment changes either statement. Heart rate in pregnancy changes physiologically, and that bears on classification and risk; it is flagged in LAZ-CL-001-REV-01 and as an open question in section 8.

Dated note, 24 October 2026 (17:07): Sara decided that heart rate is hidden in pregnancy (item 8). Use of Lazoo in pregnancy stays as confirmed on 13 October 2026. See section 11.5.

## 6. Tension Sara needs to decide on

On 24 October 2026 at 16:01 Sara described heart rate on CBT-14 as a "wellness trend". That framing works for a wellness product. It does not carry over into Lazoo. Lazoo is a medical device, and anything placed in a medical device's intended purpose becomes part of its medical claim. Once heart rate is written into Lazoo's intended purpose, the heart rate that Lazoo presents is part of a medical device claim for insomnia monitoring. It has to be covered by the classification, the risk file, the clinical evaluation, verification and the instructions for use, and it is no longer a wellness feature.

The question for Sara is: **do you accept that the wellness framing no longer applies to the heart rate that Lazoo presents?**

If the answer is no, the alternative already recorded by Compliance on 24 October 2026 (finding F9 in /workspace/compliance-reports/cbt14-hr-spo2-addendum-gate-2026-10-24.md) is to keep heart rate in the CBT-14 companion phone app and out of Lazoo, which leaves Lazoo's intended purpose and technical file unchanged. Sara's 16:01 message says Lazoo is that companion app; if so, the two positions conflict, and Sara needs to choose one.

Dated note, 24 October 2026: answered. Sara chose Lazoo as the companion app (decision 7) and at 16:03 to add heart rate to Lazoo's intended purpose, so the medical device route is taken and the route of keeping heart rate in a separate CBT-14 app (finding F9) is not. Still open, for Compliance: how CBT-14 itself is classified now that it feeds a medical device (likely as an accessory; gate finding U4).

## 7. Wording guards

These guards are proposed so that the working classification of Class IIa can hold. They are explained in LAZ-CL-001-REV-01.

1. Trend display only. No single-reading display presented as a clinical value, and no "measurement" claim.
2. No alarm, alert, notification, warning, colour-coded threshold or prompt to act, for the person or the clinician.
3. No rhythm analysis, no arrhythmia or atrial fibrillation detection, no heart rate variability claim.
4. No statement that Lazoo detects deterioration, danger or any heart condition.
5. "Not an emergency service" stays in the instructions for use and participant information.
6. Heart rate sits inside insomnia monitoring, and is never described as a separate monitoring purpose.
7. Any change to these guards goes through change control and a new classification review.

## 8. Open questions for Sara

1. Do you accept that the wellness framing no longer applies to heart rate shown in Lazoo (section 6)?
2. Should heart rate instead stay in the CBT-14 companion app and out of Lazoo (Compliance finding F9)? Is Lazoo the CBT-14 companion app, as your 16:01 message says?

   Dated note, 24 October 2026: questions 1 and 2 are answered by decision 7 and the 16:03 decision; see the note in section 6.
3. Who sees heart rate in Lazoo: the person, the clinician, or both?
4. Is heart rate recorded only overnight, or throughout the day?
5. Should heart rate be shown in Lazoo during pregnancy, given that Lazoo may be used in pregnancy?

   Dated note, 24 October 2026 (17:07): questions 3, 4 and 5 are answered by Sara's items 6, 7 and 8, and question 1 by item 11; see section 11. New questions follow in section 11.7.
6. Which UK GDPR Article 9(2) condition should apply to heart rate in Lazoo (see LAZ-DPIA-HR-input-2026-10-24)?

   Dated note, 24 October 2026: Research Governance version 0.2 recommends explicit consent under Article 9(2)(a) with consent under Article 6(1)(a) for an optional heart-rate choice, and Article 6(1)(c) with Article 9(2)(i) for post-market surveillance records. Recommended, pending sign-off of the DPIA.

Dated note, 30 October 2026: Sara McNeillis decided at 08:46 that declining heart rate never stops someone using the chest patch or the app. The heart-rate choice is asked and recorded separately from other consent. Heart rate stays out of the LAZ-VAL-001 validation study (Sara McNeillis, 30 October 2026, 08:45), so the objectives and the sample size are unchanged.

   Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The version 0.2 note above is kept as recorded. Version 0.5.1 keeps the same recommendation and adds the core temperature estimate, the circadian analysis and the pregnancy setting to it (its section 5).
7. Should skin temperature trends also be shown in Lazoo, or does the skin temperature claim stay with CBT-14 alone?

## 9. Related documents

- LAZ-CL-001-REV-01 (/workspace/lazoo-cmf/01-product/LAZ-CL-001-REV-01-heart-rate-classification-review-2026-10-24.md): working classification review.
- LAZ-HR-IMPACT-2026-10-24 (/workspace/lazoo-cmf/01-product/LAZ-HR-IMPACT-2026-10-24.md): impact register.
- LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md): input for Research Governance.
- The CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5].

  Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the entry above are kept as recorded; this path answers them.
- Compliance gate, 24 October 2026: /workspace/compliance-reports/cbt14-hr-spo2-addendum-gate-2026-10-24.md.

## 10. Approval

| Role | Name | Decision | Date |
|---|---|---|---|
| Compliance | to be confirmed | Pending | |
| Sponsor decision | Dr Sara McNeillis | Pending | |

Dated note, 24 October 2026 (17:07): Sara approved the amendment to the statement of purpose in principle. Compliance review is pending, and the sponsor decision in the table above stays pending until Sara approves the final wording.

## 11. Update following Sara's decisions at 17:07

Dated section, 24 October 2026, added after Sara's answers at 17:07 British Summer Time. Nothing above this section has been changed; where an earlier passage no longer matches the current proposal, a dated note has been inserted beside it.

### 11.1 What Sara decided

At 17:07 on 24 October 2026 Sara answered the open questions, as relayed by the chief executive's assistant. The answers that bear on this amendment are:

- **Item 1.** Core temperature is estimated with the quadratic model published by Buller and colleagues in 2013.

  Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.
- **Item 3.** Heart rate is computed on the phone only, until the patient shares their data.
- **Item 4.** Yes. The question this answers is in the chief executive's numbered key, which is not held in the master file, so its content is to be confirmed and is not restated here.
- **Item 5.** "yes show me": Sara asked to see the base intended-purpose text. It is set out in LAZ-IP-001-base-purpose-extract-2026-10-24 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-base-purpose-extract-2026-10-24.md).
- **Item 6.** The patient and the clinician see heart rate when the patient shares data for their report.
- **Item 7.** Heart rate is recorded over 24 hours, not overnight only, because heart rate together with core body temperature is essential for circadian analysis.
- **Item 8.** Heart rate is hidden in pregnancy.
- **Item 9.** Yes: Northern Ireland and the European Union are in scope.
- **Item 10.** Deferred until 25 October 2026.
- **Item 11.** Heart rate is accepted as a medical device function, and the statement of purpose is to be amended.

The earlier decisions stand: the CBT-14 claim stays at skin temperature trends, the optical sensor is used, and blood oxygen saturation (SpO2) is deferred until it has been bench tested.

### 11.2 Status of the amendment

The amendment to the statement of purpose is **approved in principle by Sara (17:07, 24 October 2026) and pending Compliance**. It is not locked or signed, and no controlled document takes the new wording until Compliance has reviewed it and Sara has approved the final words. Item 11 also answers open question 1 in section 8: the wellness framing no longer applies to the heart rate that Lazoo presents. Lazoo is not yet UKCA-marked.

### 11.3 Revised proposed wording

Proposed, subject to Compliance. This replaces the paragraph proposed in section 4, which is kept above for the record.

> Lazoo is software as a medical device. Its intended purpose is insomnia monitoring only: it supports a clinician in monitoring insomnia in adults aged 18 and over. As part of insomnia monitoring, Lazoo may present trends in heart rate recorded across the whole 24-hour day by its companion wearable, CBT-14, so that the daily rhythm of heart rate can be read alongside the sleep diary when the clinician reviews the timing and pattern of the person's sleep. Heart rate is processed on the person's phone and leaves the phone only when the person chooses to share their data for a report; the person and their clinician then see the heart rate trends in that shared report. Heart rate is not shown in pregnancy, although Lazoo itself may still be used in pregnancy. Lazoo does not diagnose any heart condition or any other condition, does not analyse or classify heart rhythm, does not detect atrial fibrillation, does not issue alarms, alerts or notifications about heart rate, applies no thresholds that prompt action, and is not intended for monitoring in situations where a change in heart rate could result in immediate danger. Heart rate trends in Lazoo are not for clinical decisions on their own. Lazoo is not an emergency service.

How this wording reflects the decisions:

- **Heart rate over 24 hours.** The heart rate trend now covers the whole day and night, so that its daily rhythm can be read together with the sleep diary. Sara's reason is circadian analysis, using heart rate together with the core temperature estimate (Buller 2013 quadratic model). The wording keeps this inside insomnia monitoring: it describes the daily pattern as context for the clinician's review of the timing and pattern of sleep. It does not return to the assessment of circadian rhythm disorders, which was in the withdrawn draft of 5 October 2026 and was removed by the scope decision of 13 October 2026. Whether "circadian analysis" should appear in the claim at all is an open question in section 11.7.

  Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.
- **Computation on the phone.** Heart rate is processed on the person's phone and leaves it only when the person shares their data for a report.
- **Who sees heart rate.** The patient and the clinician see heart rate trends in the shared report. The draft intended purpose of 12 October 2026 says the patient "is not the user of its clinical outputs". Showing the trend to the patient changes that, so the final wording of the intended users must say what the patient sees. That is flagged in section 11.6.
- **Pregnancy.** Heart rate is hidden in pregnancy. Device use in pregnancy stays as locked on 13 October 2026 (see section 11.5).
- **Northern Ireland and the European Union.** These markets are now in scope. The intended purpose wording does not change for them, but the regulatory route does: see section 11.5 and LAZ-CL-001-REV-01, section 9.

### 11.4 What stays the same

Lazoo stays a monitoring-only device. Heart rate is presented only as a trend, inside insomnia monitoring. There are no alarms, alerts or notifications about heart rate, no thresholds that prompt action, no heart rhythm output and no atrial fibrillation output. The wording guards in section 7 all still apply, and three are added:

8. No live or real-time display of heart rate, on the phone or for the clinician. Heart rate reaches the clinician only in a report the patient chooses to share, and is reviewed afterwards.
9. Heart rate is hidden for a person who is pregnant. How Lazoo knows this is to be confirmed.
10. No core body temperature figure, curve or label is shown to anyone until Sara has decided whether core temperature is a claimed output (section 11.6) and the wording has been gated again.

The skin temperature trend claim for CBT-14 is unchanged, and SpO2 is not added.

### 11.5 Pregnancy, and Northern Ireland and the European Union

**Pregnancy.** Hiding heart rate in pregnancy narrows what Lazoo shows; it does not narrow who may use Lazoo. Lazoo may still be used in pregnancy for the sleep diary, as decided on 13 October 2026, and LAZ-VAL-001 keeps pregnancy as exclusion criterion 7. The hide is a risk control. It must not be described as a statement that heart rate monitoring is safe or unsafe in pregnancy, because no evidence on heart rate in pregnancy has been gathered. Whether heart rate is still recorded on the phone while it is hidden, and whether any core temperature estimate is hidden too, are to be confirmed, and both matter for the data protection impact assessment.

**Northern Ireland and the European Union.** Under the Windsor Framework, the EU Medical Devices Regulation (Regulation (EU) 2017/745) applies in Northern Ireland, and it applies in the European Union. On the GOV.UK guidance read on 24 October 2026, this means CE marking, an EU-recognised notified body where a third-party assessment is needed, and a sole authorised representative based in the EU or Northern Ireland for a manufacturer based in Great Britain. The reasoning and the sources are in LAZ-CL-001-REV-01, section 9. For data protection, the Research Governance assessment already records that offering Lazoo in the European Union brings in the EU General Data Protection Regulation and means the assessment is reviewed first.

### 11.6 Tension Sara needs to decide on: is core temperature a claimed output?

This is not resolved here.

At 16:01 today Sara kept the claim at skin temperature trends. Decision 1 of the CBT-14 addendum records it as: "Every product statement remains worded as skin temperature trends. The core-temperature estimate from DA-1 stays a research output and is not claimed." The draft intended purpose of 12 October 2026 says that core body temperature measured with CBT-14 is not used. The CBT-14 data-path lock of 18 September 2026 forbids naming or implying core body temperature on the path from CBT-14 to Lazoo.

At 17:07 Sara chose the Buller 2013 quadratic model for core temperature and said that heart rate with core body temperature is essential for circadian analysis. That points to a core temperature estimate inside the product.

Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.

The two positions cannot both stand as written. Some points for the decision:

- If a core temperature estimate is shown to the patient or the clinician, or is used to shape what the clinician sees (for example a circadian summary built from it), it is part of what Lazoo does and has to be in the intended purpose. It would then need its own evidence, stated limits of accuracy, and a change to decision 1 and to the data-path lock.
- An estimate that is computed but never shown and never used would still need a reason to be computed at all, and it would still be processing of health data.
- The design-around review (/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/CBT-14-ARMY-DESIGN-AROUND-2026-10-24.md) reports, from Looney and colleagues (2018), that the Buller 2013 quadratic model is less accurate at rest than the sigmoid model it replaces: bias −0.19 ± 0.29 °C and root mean square error 0.35 °C, against −0.04 ± 0.26 °C and 0.26 °C. Those figures come from published studies in other settings, not from people with insomnia wearing CBT-14 on the side of the chest, and the papers have not been read for this amendment. The model constants are to be read from the paper and checked; they are not reproduced here. The same review describes the quadratic model as a research option with no core figure shown to the wearer, and the patent position remains for the patent attorney.

  Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.

**Question for Sara: is core temperature a claimed output of Lazoo?**

Dated note, 24 October 2026 (Compliance round 4): answered. Sara's answer 1 of 17:07 puts the 2013 Buller core temperature estimate in the product, superseding decision 1 of 16:01 to that extent; see the R4-4 note after section 11.7. Only the display option remains open.

Dated note, 24 October 2026 (Compliance round 5, R5-1): to be exact, two points about the core temperature estimate are still open for Sara, not one: how it is shown (decision R4-D1) and whether it is also hidden in pregnancy (decision R4-D2). Until the display option has been chosen, the estimate has been validated for that use and Compliance has gated it again, no core body temperature figure, curve or label is shown to anyone (guard 10, as read in the R4-4 note).

### 11.7 Open questions for Sara after 17:07

8. Is core temperature a claimed output of Lazoo (section 11.6)? If not, may Lazoo compute it at all, and may it shape anything the clinician sees?
9. Should "circadian analysis" appear in the claim, or should the daily pattern stay described as context for insomnia monitoring, as in the proposed wording?
10. The patient now sees heart rate in the shared report. Do you accept that the intended users wording changes, so that the patient is no longer described as "not the user of its clinical outputs"?
11. How is pregnancy recorded so that heart rate can be hidden: does the patient declare it, or does the clinician set it? Is heart rate still recorded while hidden?
12. When are Northern Ireland and the European Union planned, and who will be the authorised representative?
13. Item 10 is deferred until 25 October 2026.

Dated note, 24 October 2026 (Compliance round 4, R4-4): following the CEO's key to Sara's answers of 17:07: in section 11.1, item 4 means that the wider Lazoo data flow starts only after the data protection impact assessment is signed off and the purpose is approved. Section 11.6 and question 8 are answered: the core temperature estimate is in the product (answer 1), superseding decision 1 of 16:01 to that extent. Guard 10 is read as: "No core body temperature figure, curve or label is shown to anyone until the display option has been chosen, the estimate has been validated for that use, and Compliance has gated it again." Question 9 is folded into the wording: circadian analysis is context for insomnia monitoring, and Lazoo does not diagnose circadian rhythm disorders. Question 10 is answered by answer 6 and becomes a drafting point: the final wording says that the person and the clinician see the trends in the shared report. Questions 11, 12 and 13 stay open. The proposed wording in section 11.3 is replaced, as a proposal, by the revised statement in the base-purpose extract (note R4-2).

Dated note, 24 October 2026 (round 6, items for Clinical Research in CBT-14-HR-DPIA-2026-10-24, version 0.5.1): Research Governance lists four points for this amendment. Recording across the whole 24-hour day is already in sections 11.1 and 11.3 and in the revised statement (note R4-2). The core temperature estimate is in the product under answer 1, as the R4-4 note and the R5-1 note under section 11.6 record; how it is shown (decision R4-D1 in the Compliance gate memo, section 8.5) and whether it is also hidden in pregnancy (decision R4-D2) stay open for Sara. The intended users wording is a drafting point under answer 6: the person and the clinician see the trends in the shared report, and the final words wait on Sara's approval of the revised statement (decision R4-D5). How pregnancy is recorded stays open for Sara (question 11 above, and decision R4-D2). The assessment recommends a single yes-or-no setting that the person sets and clears on the phone (its section 3a); that is a recommendation only, and nothing is decided here. The cross-reference to version 0.5.1 is the dated note at the end of section 11.8.

### 11.8 Related documents added on 24 October 2026

- LAZ-IP-001-base-purpose-extract-2026-10-24 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-base-purpose-extract-2026-10-24.md): the base wording and the proposed statement, for Sara.
- LAZ-CL-001-REV-01, section 9: re-test of the working classification following the 17:07 decisions.
- CBT-14-HR-DPIA-2026-10-24, version 0.3, from Research Governance, pending Compliance review (/workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 d9c87e83928492d66fbf51a3553357107b0e9d2cf782ddcef1eea4e80a57d45f). The version 0.2 citations above are kept as recorded at the time.

Dated note, 24 October 2026 (Compliance round 4, R4-7): Research Governance issued CBT-14-HR-DPIA-2026-10-24, version 0.4, at about 17:20 British Summer Time: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.4-2026-10-24.md, sha256 ddb77632d2cb7d95bda7c44037ffea12cf508f429832be8e082d98f51ff204e0. It supersedes version 0.3 as the working draft, is pending Compliance review and is not signed off. Version 0.3 (d9c87e83…) is kept unchanged.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The version 0.3 entry and the version 0.4 note above are kept as recorded.

## 12. Update following Sara's decisions of 26 October 2026, 23:28

Dated section, 26 October 2026, added after Sara McNeillis's answers at 23:28 London time and her further answer at 23:30 London time. The text above is unchanged. Where this section differs from section 11, this section is the later record. The amendment remains approved in principle by Sara, Compliance review remains pending, and the final wording remains for her to approve.

At 23:28 on 26 October 2026 Sara answered, in her words: "1 no 2 just data recorded 3 skin as per 24 Oct pack / 4 not sure 5 left side of chest". At 23:30 the same evening she added, in her words: "Number from heart rate is fine".

The shared report holds only the recorded data. Section 11.3 has the heart rate leaving the phone in a report which the person and the clinician both see. The revised statement in the base-purpose extract, which the Compliance round 4 note (R4-4) in section 11.7 puts in place of that wording, goes further: the heart rate and the core temperature estimate both leave the phone when a report is shared. These words limit the report to the recorded data, so the estimate no longer leaves with it. The recorded heart rate can still be shared in that report, which is the sharing already decided at 17:07 on 24 October 2026 (item 6). Decision R4-D5, in the round 6 note in section 11.7, is her approval of the final words of the revised statement, including what the person and the clinician see in the shared report. The content of that report is now settled as the recorded data. Her approval of the final words remains outstanding, so the rest of decision R4-D5 remains open. Question 10 in section 11.7 asked whether the intended users wording changes because the person sees heart rate in the shared report. The round 4 note already treats that as a drafting point under her answer 6 of 24 October. The report in that question holds the recorded data. The core temperature calculation stays on the phone, as the next paragraph records.

The 2013 Buller core temperature calculation stays on the phone. It stays out of the shared report. This bears on the test in section 11.6. That section says that a core temperature estimate shown to the patient or the clinician, or used to shape what the clinician sees, is part of what Lazoo does and has to be in the intended purpose, and that an estimate which is computed but never shown is a different case. On the reading that the estimate is visible on the phone, it is shown to the patient, so it is part of what Lazoo does and belongs in the intended purpose, even though the clinician does not see it in the shared report. On the reading that it is calculated on the phone and no figure is shown, it is the second case in section 11.6. ~~Which reading applies is the tension with guard 10, left for Sara below.~~ (struck 26 October 2026, Compliance round 7) Sara's answer at 23:30 means the estimate is to be shown on the phone, so it is part of what Lazoo does and belongs in the intended purpose. Guard 10 sets when it may first be shown. How the estimate is shown, if a figure is shown, remains decision R4-D1, as the notes under section 11.6 and in section 11.7 already say.

In pregnancy, heart rate is hidden and the calculation is not. Heart rate stays hidden, as decided at 17:07 on 24 October 2026 (item 8). The calculation is not hidden. Her sentence at 23:30 is recorded in these terms: in pregnancy the core temperature estimate derived from heart rate stays visible on the phone, and only the raw heart rate is hidden. This answers decision R4-D2, which the note under section 11.6 (R5-1) and the round 6 note in section 11.7 left open, and it answers the same point in section 11.5, on whether any core temperature estimate is hidden. How pregnancy is recorded, and whether the raw heart rate is still recorded on the phone while it is hidden, remain open. Those are question 11 and the remaining part of section 11.5.

The CBT-14 patch is worn on the left side of the chest. This confirms the wear site already recorded in section 2 under decision 5 of 24 October 2026. The rib level, which section 2 left to the fit study, remains with the fit study.

Both CBT-14 temperature sensors face the skin, as in the 24 October pack. Sensor facing was not an open question in this amendment. Question 7, on whether skin temperature trends are also shown in Lazoo, remains open.

Answer 4 falls outside this amendment.

Guard 10 stays in force, in the reading given in the Compliance round 4 note (R4-4) in section 11.7 and repeated in the R5-1 note under section 11.6. No core body temperature figure, curve or label is shown to anyone until the display option has been chosen, the estimate has been validated for that use, and Compliance has gated it again.

~~The tension is left for Sara to settle. One reading is that the calculation stays on the phone and out of the shared report. The other reading is that the estimate stays visible on the phone, including in pregnancy, so that a core temperature figure would be shown there. Sara is asked to say which reading she means. Guard 10 stays in force while that is unsettled: no core temperature figure is shown to anyone until the display option is chosen, validated and gated again. Her sentence at 23:30 is the pregnancy answer recorded above. Decision R4-D1, how the on-phone estimate is shown, remains open.~~ (struck 26 October 2026, Compliance round 7) Guard 10 and Sara's answers fit together. Her answers settle what the person will see: the core temperature estimate on the phone, including in pregnancy, with raw heart rate hidden in pregnancy and the shared report holding the recorded data only. Guard 10 settles when the estimate may first be shown, which is once the display option (decision R4-D1) is chosen, the estimate is validated for that use and Compliance has gated it again. Until then no figure is shown.

What remains open is as follows. How the on-phone estimate is shown remains open (decision R4-D1)~~, together with the tension between these answers and guard 10~~ (struck 26 October 2026, Compliance round 7). How pregnancy is recorded remains open (question 11), including whether heart rate is still recorded while it is hidden (section 11.5). When Northern Ireland and the European Union are planned, and who will be the authorised representative, remains open (question 12). Question 13 remains open. The round 4 note in section 11.7 records that it stays open. Question 13 itself is the item deferred on 24 October 2026 until 25 October 2026. The description of the 2013 Buller model as quadratic remains to be checked against the full paper and against Looney and colleagues (2018), as the notes marked R4-10 say. Final wording remains for Sara to approve, and Compliance review remains pending.
