# Change list, 30 October 2026

Folder: lazoo-company-name-2026-10-30. Each file that was edited was copied to backups/ before it was touched. Nothing was deleted and no file was renamed.

## Companies House record

Checked on 30 October 2026 on the public company overview:

https://find-and-update.company-information.service.gov.uk/company/12467350

Current name: SHC SLEEP SOLUTIONS LIMITED.

Company number: 12467350. Status: Active. Registered office: 32 Watford Road, Northwood, England, HA6 3NT. Incorporated on 17 February 2020.

Previous names shown on that page:

| Name | Period |
| --- | --- |
| SLEEP AND HEALTH CLINIC APP LIMITED | 16 December 2020 to 27 October 2026 |
| CARETEK MEDICAL APP LIMITED | 17 February 2020 to 16 December 2020 |

Filing history, checked the same day:

https://find-and-update.company-information.service.gov.uk/company/12467350/filing-history

The entry dated 27 October 2026 is type CERTNM. It states: company name changed sleep and health clinic app LIMITED; certificate issued on 27/10/26; NM01, change of name by resolution; RES15, change of company name resolution on 2026-10-26.

In the study files the inserted name is written "SHC Sleep Solutions Limited". That is the same registered name, in sentence case rather than the capitals used on the register.

## How the old name was kept

Where the old name refers to company number 12467350, the old words stay in the file and are struck through. In Markdown the strike is ~~old name~~. In Word the same words have strike formatting. The new name is inserted after the strike.

The first time in a file that "Sleep and Health Clinic App Limited" or "Sleep and Health Clinic App Ltd" stands next to 12467350, the inserted text is: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

A later mention of that full name in the same file inserts only: SHC Sleep Solutions Limited.

The first "App Ltd" in a file that means this company inserts SHC Sleep Solutions Limited and this note: short form for company number 12467350, renamed 27 October 2026. Later short forms insert only SHC Sleep Solutions Limited.

Sleep and Health Clinic Ltd and Sleep & Health Clinic Ltd, company number 08904119, are not changed. A count of those names and of 08904119 matches the backups on every edited file.

## Version 0.6, not edited

LAZ-VAL-001-protocol-v0.6-heart-rate-amendment-DRAFT.md and the Word file of the same name were not opened for editing. Their SHA-256 values are the same in OLD-SHA256.txt and NEW-SHA256.txt.

- Markdown: 5d994cd0a07794e2ff1a3e44cd33ead439d41872c2451e68095bf030946bb916
- Word: dfd092bdfd1e0ea0d5c4c0aa43cecde14397487b9f7ad2e5aa949be587defed2

These are the hashes already printed in the version 0.6.1 change note for the approved version 0.6 text.

## Source PDFs, not edited

Four PDFs are in the folder. The HRA notice and the model agreement front page do not name this company. The two NIHR outline PDFs do name Sleep and Health Clinic App Limited, and they also name Sleep and Health Clinic Ltd. They do not print company number 12467350. They are stored copies of submitted outlines. A Markdown or Word strike cannot be put inside them without rewriting the PDF, so they were left byte for byte as filed. The grants README beside them was edited.

## Case report form filled/LAZ-VAL-001-CRF-v0.3.docx

This is the file whose hash begins 546e9cac. It is in the staged folder and in backups/. The backup hash is 546e9cac1852158ed7e11f0798b7ac40eda93bfc1a07b8d5370e9636c41d997b. Both OLD-SHA256.txt and NEW-SHA256.txt list it. The new hash is e225087c9ea3cb265bfde47b791f56b391aec0fd2a99147dfceae827e6964d20. It differs only because the company name was struck through and the new name inserted. The heart-rate decline note is not in this copy. That is deliberate. The note is already in the CRF _human copies (the Markdown and both Word files).

## Checks

Word. For each of the 35 edited Word files, every paragraph in the backup is still present, in order. Where a paragraph changed, the old paragraph text is still inside the new paragraph, with text inserted and strike formatting added on the old name. No paragraph was removed. On the re-check of the version 0.6.1 Word protocol, the "Name given for this draft" paragraph and the 29 October question and note match the backup, including the original strike formatting. The sponsor line is still the edited one. Two paragraphs have been added: the status note, and the 30 October note under the 29 October note. Headers, footers and the document creator field were included where they named the company. The creator field cannot carry Word strike formatting, so the old name is kept there and the new name is marked with ~~ ~~.

Markdown and text. difflib.SequenceMatcher was run on all 46 edited Markdown and text files against their backups, with autojunk turned off. Every file returned only equal blocks and insert blocks. There was no delete block and no replace block. The opcode counts are below.

- lazoo-cmf/README.md: 3 equal, 2 insert
- lazoo-cmf/SOP-CMF-001-management.md: 3 equal, 2 insert
- lazoo-cmf/tmp-roadmap-revA.txt: 3 equal, 2 insert
- lazoo-cmf/00-INDEX.md: 3 equal, 2 insert
- lazoo-cmf/grants-layer2-nihr/README.md: 3 equal, 3 insert (re-checked after the PDF cover note)
- lazoo-cmf/app-ltd-shells/README.md: 5 equal, 4 insert
- lazoo-cmf/02-governance/LAZ-GOV-003-mvp-maths-alignment.md: 3 equal, 2 insert
- lazoo-cmf/02-governance/LAZ-SPN-001-sponsor.md: 15 equal, 14 insert
- lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md: 15 equal, 14 insert
- lazoo-cmf/01-product/LAZ-CL-001-classification-memo.md: 3 equal, 2 insert
- lazoo-cmf/01-product/LAZ-CL-001-REV-01-heart-rate-classification-review-2026-10-24.md: 3 equal, 2 insert
- lazoo-cmf/01-product/LAZ-IP-001-intended-purpose.md: 3 equal, 2 insert
- lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md: 3 equal, 2 insert
- lazoo-cmf/01-product/LAZ-HR-IMPACT-2026-10-24.md: 5 equal, 4 insert
- lazoo-cmf/03-studies/LAZ-STUDY-REGISTER.md: 7 equal, 6 insert
- lazoo-cmf/uclh-feasibility-separate-sponsor/README.md: 5 equal, 4 insert
- lazoo-cmf/uclh-feasibility-separate-sponsor/UCLH-consent-v0.2-recut.md: 5 equal, 4 insert
- lazoo-cmf/uclh-feasibility-separate-sponsor/UCLH-PIS-v0.2-recut.md: 7 equal, 6 insert
- lazoo-cmf/04-templates/data-dictionary.md: 3 equal, 2 insert
- lazoo-cmf/04-templates/consent-four-toggles.md: 9 equal, 8 insert
- lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DPIA-001-short-form.md: 29 equal, 28 insert
- lazoo-cmf/app-ltd-shells/03-compliance/README.md: 3 equal, 2 insert
- lazoo-cmf/app-ltd-shells/03-compliance/LAZ-RSK-001-risk-plan.md: 11 equal, 10 insert
- lazoo-cmf/app-ltd-shells/03-compliance/LAZ-GDPR-001-company-separation.md: 17 equal, 16 insert
- lazoo-cmf/app-ltd-shells/03-compliance/LAZ-QM-001-quality-manual.md: 13 equal, 12 insert
- lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DHF-001-stub-consent-audit.md: 4 equal, 3 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14_human.md: 49 equal, 48 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5_human.md: 79 equal, 78 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4.md: 45 equal, 44 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.2.md: 15 equal, 14 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14.md: 55 equal, 54 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/CHANGES-v0.5.md: 169 equal, 168 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3_human.md: 3 equal, 2 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.2.md: 49 equal, 48 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5.md: 141 equal, 140 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo protocol v0.6.1 change note 2026-10-30.md: 3 equal, 2 insert (re-checked after the lines were dated)
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3.md: 5 equal, 4 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.2.md: 5 equal, 4 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/00-protocol-outline.md: 17 equal, 16 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.3.md: 33 equal, 32 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human.md: 27 equal, 26 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo protocol v0.6.1 2026-10-30.md: 5 equal, 4 insert (re-checked after the three passages were restored)
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.4.md: 69 equal, 68 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/01-essential-documents.md: 15 equal, 14 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.3.md: 59 equal, 58 insert
- lazoo-cmf/03-studies/LAZ-VAL-001/sponsor-documents/README-sources.md: 3 equal, 2 insert

## Review fixes

1. Done. 04-templates/consent-four-toggles.md, section "Proposed addition, 24 October 2026". The two staged lines that opened "Separate recorded choice, 30 October 2026" are struck through. In their place: the dated note that proposed toggle 5 is the one heart-rate choice, and the sentence that heart rate is off unless the participant switches it on, that switching it off is as easy as switching it on, that there is no pressure, that care is not affected, and that stored heart rate is kept until they choose to delete it.
2. Done. The same consent file, directly under that sentence, and LAZ-DHF-001-stub-consent-audit.md, section "What this stub records". Both have the dated note that switching on, switching off, and choosing to keep or delete are recorded separately, with the time and the wording version.
3. Done. Lazoo protocol v0.6.1 change note 2026-10-30.md, after the 08:46 decision. The dated note says that publishing the Data Protection Officer's details and telling the Information Commissioner's Office both wait for Sara McNeillis's yes, that Martin Hickley has not been contacted, and that his confirmation of the lawful basis is still open.
4. Done. Lazoo protocol v0.6.1 2026-10-30.md and the Word copy, straight after the status line that still says "Not approved". The dated note records Sara McNeillis's approval of version 0.6 at 08:45 on 30 October 2026, and that it has not been submitted for ethics review and the MHRA has not been notified. The words "Not approved" and "Version 0.5 remains in force" are still there.
5. Done. The same change note, straight after the 08:46 paragraph. The decline sentence is said to describe the CBT-14 product outside this study, and that participants in LAZ-VAL-001 are not given the chest patch.
6. Done in the change note only. A dated note points the 08:45 source to: as set in protocol v0.6, approved by Sara McNeillis at 08:45 on 30 October 2026. The decline sentences already in the staged files were left as written.
7. Done. filled/LAZ-VAL-001-CRF-v0.3.docx is in the folder, in backups/, and in both hash lists, with the backup hash 546e9cac… and a new hash after the name strike only. The missing heart-rate note is recorded above as deliberate.
8. Done. This change list gives each edited file its own change note below. The repeated decline sentences already in the files were not removed.

## Change note for each file

### lazoo-cmf/00-INDEX.md

**Section:** # Lazoo Clinical Master File — Index

- line 15. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/01-product/LAZ-CL-001-REV-01-heart-rate-classification-review-2026-10-24.md

**Section:** # LAZ-CL-001-REV-01 — Working classification: heart rate trend in Lazoo

- line 7. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/01-product/LAZ-CL-001-classification-memo.md

**Section:** ## 6. IP

- line 63. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/01-product/LAZ-HR-IMPACT-2026-10-24.md

**Section:** # LAZ-HR-IMPACT — Impact register for the heart rate amendment

- line 6. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## 6. Checked and not affected

- line 142. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md

**Section:** # LAZ-IP-001-AMD-01 — Draft amendment: heart rate trend in Lazoo's intended purpose

- line 12. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/01-product/LAZ-IP-001-intended-purpose.md

**Section:** ## Where a later paste must be copied, once Sara supplies it

- line 49. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md

**Section:** # LAZ-DPIA-HR-input — Heart rate in Lazoo: input for the data protection impact assessment

- line 7. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## 4. Data flow

- line 81. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 84. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 6. Pseudonymisation and the LAZ-DS-001 rule

- line 97. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 7. Questions for Research Governance

- line 109. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 109. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 123. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/02-governance/LAZ-GOV-003-mvp-maths-alignment.md

**Section:** ## Approvals gates (unchanged from 5 September 2026, still open)

- line 24. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/02-governance/LAZ-SPN-001-sponsor.md

**Section:** # LAZ-SPN-001 — Sponsor and research governance

- line 13. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 19. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 20. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 21. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Related party and clinical support

- line 29. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 31. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Sign-off

- line 51. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-STUDY-REGISTER.md

**Section:** # Lazoo study register

- line 8. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 14. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 17. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/00-protocol-outline.md

**Section:** (no heading yet)

- line 3. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 3. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 5. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Synopsis

- line 22. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 27. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 6. Data management

- line 81. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 8. IP and publication

- line 94. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 9. What v0.2 must add before IRAS

- line 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/01-essential-documents.md

**Section:** # LAZ-VAL-001 — Essential documents checklist

- line 13. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 19. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 19. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 20. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 23. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 30. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 31. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/CHANGES-v0.5.md

**Section:** #### Change 1

- line 23. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 23. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 23. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 725. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 2

- line 32. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 32. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 32. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 36. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 36. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 36. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 7

- line 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 102. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 9

- line 121. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 121. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 129. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 129. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 131. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 131. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 10

- line 141. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 147. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 148. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 826. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 830. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 12

- line 171. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 20

- line 260. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 21

- line 278. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 278. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 278. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 23

- line 304. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 308. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 27

- line 351. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 355. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 355. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 28

- line 367. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 30

- line 385. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 389. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 389. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 32

- line 409. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 415. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 419. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 34

- line 437. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 441. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 441. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 35

- line 447. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 448. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 449. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 453. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 454. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 455. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 36

- line 473. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 38

- line 493. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 497. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 497. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 40

- line 524. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 41

- line 538. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 539. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 48

- line 617. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 54

- line 681. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 8

- line 800. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 800. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 800. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 801. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 801. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 805. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 805. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 805. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 806. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 806. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 806. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** #### Change 13

- line 862. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 862. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Items that can only be fixed in the i4i draft

- line 932. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 932. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 936. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 940. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 942. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 948. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 952. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 954. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 960. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Research governance corrections, 12 October 2026

- line 970. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Regulation 16 reasoning and Chief Investigator condition, 13 October 2026

- line 1006. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.2.md

**Section:** # LAZ-VAL-001 Case Report Form (CRF) booklet v0.2

- line 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Adverse Events

- line 255. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3.md

**Section:** # LAZ-VAL-001 Case Report Form (CRF) booklet v0.3

- line 24. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Adverse Events

- line 264. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3_human.docx

**Section:** Case Report Form (CRF) booklet for the Lazoo validation study, version 0.3

- word/document.xml paragraph 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3_human.md

**Section:** # Case Report Form (CRF) booklet for the Lazoo validation study, version 0.3

- line 16. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.2.md

**Section:** (no heading yet)

- line 3. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # LAZ-VAL-001 Data Management Plan v0.2

- line 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Data Sources

- line 32. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** ## Storage

- line 94. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 98. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## GDPR

- line 134. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.3.md

**Section:** (no heading yet)

- line 3. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # LAZ-VAL-001 Data Management Plan v0.3

- line 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Data Sources

- line 32. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 33. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 33. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 33. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 34. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 34. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Recruitment

- line 50. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Partner Site and Data Rules

- line 61. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 64. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Storage

- line 115. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 119. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 124. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 126. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## GDPR

- line 155. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4.md

**Section:** (no heading yet)

- line 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 15. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 15. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 19. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # LAZ-VAL-001 Data Management Plan v0.4

- line 32. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Data Sources

- line 50. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 51. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 51. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 52. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 52. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 52. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Recruitment

- line 62. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Partner Site and Data Rules

- line 73. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 73. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 73. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 75. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Storage

- line 118. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 122. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 127. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 129. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## GDPR

- line 160. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 168. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human-superseded-2026-10-24.docx

**Section:** Data Management Plan for the Lazoo validation study, version 0.4

- word/document.xml paragraph 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Document history

- word/document.xml paragraph 25. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 2. Roles and responsibilities for data

- word/document.xml paragraph 41. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 3. Data sources

- word/document.xml paragraph 87. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 92. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 4. Recruitment

- word/document.xml paragraph 96. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 5. Partner site and rules for data sharing

- word/document.xml paragraph 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 7. Storage and security

- word/document.xml paragraph 152. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 9. Data protection (UK GDPR)

- word/document.xml paragraph 171. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human.docx

**Section:** word/document.xml

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Data Management Plan for the Lazoo validation study, version 0.4

- word/document.xml paragraph 12. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Document history

- word/document.xml paragraph 28. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 2. Roles and responsibilities for data

- word/document.xml paragraph 50. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 3. Data sources

- word/document.xml paragraph 98. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 4. Recruitment

- word/document.xml paragraph 107. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 5. Partner site and rules for data sharing

- word/document.xml paragraph 112. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 112. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 114. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 7. Storage and security

- word/document.xml paragraph 163. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 9. Data protection (UK GDPR)

- word/document.xml paragraph 183. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 187. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human.md

**Section:** (no heading yet)

- line 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # Data Management Plan for the Lazoo validation study, version 0.4

- line 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Document history

- line 24. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 2. Roles and responsibilities for data

- line 51. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 3. Data sources

- line 74. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 75. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 4. Recruitment

- line 85. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 5. Partner site and rules for data sharing

- line 95. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 95. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 99. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 7. Storage and security

- line 160. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 9. Data protection (UK GDPR)

- line 193. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 201. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14.md

**Section:** # LAZ-VAL-001 — Prolific and MHRA notes for the Lazoo validation study

- line 9. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** ## Facts these notes use

- line 14. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 16. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A1. Who is controller, and who is processor

- line 80. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 80. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 80. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 80. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A3. International transfers, UK, EU, and US

- line 152. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 152. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A6. Retention and deletion

- line 286. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 286. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A8. What the sponsor must accept or configure

- line 322. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 327. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 331. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### INFERENCE — likely to need 60 days’ notice, including where the study is monitoring only

- line 405. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Software and insomnia, in MHRA’s own words

- line 458. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### In-house / health-institution exemption does not fit App Ltd

- line 480. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 488. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Draft for protocol section 3 — Sara decides

- line 580. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Draft for protocol section 16 — Sara decides

- line 586. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 590. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 597. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 602. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 602. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 633. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Points left not confirmed

- line 643. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Five-line brief

- line 658. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14_human.docx

**Section:** Prolific and MHRA notes for the Lazoo validation study

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Facts on which these notes rely

- word/document.xml paragraph 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 6. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** A1. Who is controller and who is processor

- word/document.xml paragraph 52. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 52. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 52. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** A3. International transfers: UK, EU and US

- word/document.xml paragraph 88. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 88. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** A6. Retention and deletion

- word/document.xml paragraph 155. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** A8. What the sponsor must accept or configure

- word/document.xml paragraph 173. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 186. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** INFERENCE: notice of 60 days is likely to be needed, including where the study is monitoring only

- word/document.xml paragraph 235. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Software and insomnia, in the MHRA’s own words

- word/document.xml paragraph 288. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** The in-house or health institution exemption does not fit Sleep and Health Clinic App Ltd

- word/document.xml paragraph 299. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 303. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Draft for protocol section 3 — Sara decides

- word/document.xml paragraph 349. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Draft for protocol section 16 — Sara decides

- word/document.xml paragraph 352. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 354. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 359. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 362. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 362. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 379. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Points that remain not confirmed

- word/document.xml paragraph 385. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Brief summary

- word/document.xml paragraph 396. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14_human.md

**Section:** # Prolific and MHRA notes for the Lazoo validation study

- line 10. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Facts on which these notes rely

- line 17. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 19. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A1. Who is controller and who is processor

- line 87. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 87. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 87. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A3. International transfers: UK, EU and US

- line 159. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 159. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A6. Retention and deletion

- line 293. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### A8. What the sponsor must accept or configure

- line 329. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 338. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### INFERENCE: notice of 60 days is likely to be needed, including where the study is monitoring only

- line 416. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Software and insomnia, in the MHRA's own words

- line 469. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### The in-house or health institution exemption does not fit Sleep and Health Clinic App Ltd

- line 491. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 499. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Draft for protocol section 3 — Sara decides

- line 591. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Draft for protocol section 16 — Sara decides

- line 597. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 601. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 608. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 613. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 613. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 644. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Points that remain not confirmed

- line 656. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Brief summary

- line 670. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.2.md

**Section:** # Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- line 9. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 15. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ### Cover identifiers

- line 34. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 37. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 38. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Protocol Version History

- line 48. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Document Approvals

- line 60. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Study Summary

- line 110. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 115. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 121. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Sites

- line 192. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Study Procedures

- line 251. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Safety Reporting

- line 374. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Data Management

- line 393. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 397. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Ethics and Regulatory Considerations

- line 428. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 428. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Risk Management

- line 471. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Information Governance and GDPR

- line 484. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Intellectual Property

- line 499. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 501. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Study Management

- line 525. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Archiving

- line 545. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Appendices

- line 580. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.3.md

**Section:** (no heading yet)

- line 3. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 3. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 3. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- line 7. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 13. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 16. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Cover identifiers

- line 32. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 33. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Protocol Version History

- line 45. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 48. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 48. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Document Approvals

- line 57. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 1. Study Summary

- line 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 14. Data Management

- line 363. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 16. Ethics and Regulatory Considerations

- line 386. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Sponsorship

- line 397. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Funding

- line 401. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Contracts and agreements

- line 409. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 410. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 411. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 412. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 413. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 414. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Related party: Sleep and Health Clinic Ltd

- line 420. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 18. Insurance and Indemnity

- line 424. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 21. Risk Management

- line 458. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 22. Information Governance and UK GDPR

- line 472. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 23. Intellectual Property and Data Ownership

- line 486. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Roles and responsibilities

- line 514. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.4.md

**Section:** (no heading yet)

- line 3. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 5. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 5. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- line 9. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 15. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 18. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Cover identifiers

- line 34. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 35. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Protocol Version History

- line 48. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 51. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 51. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Document Approvals

- line 61. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 1. Study Summary

- line 107. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Recruitment route

- line 211. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 14. Data Management

- line 372. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 375. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 16. Ethics and Regulatory Considerations

- line 398. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Sponsorship

- line 409. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Funding

- line 417. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Contracts and agreements

- line 425. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 426. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 427. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 428. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 429. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 430. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 431. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Related party: Sleep and Health Clinic Ltd

- line 437. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 21. Risk Management

- line 478. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 22. Information Governance and UK GDPR

- line 493. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 495. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 23. Intellectual Property and Data Ownership

- line 509. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Roles and responsibilities

- line 552. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Conflicts of interest

- line 573. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5.md

**Section:** (no heading yet)

- line 13. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 13. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 13. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 13. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 15. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 17. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 17. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 17. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** # Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- line 21. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 27. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 30. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Cover identifiers

- line 46. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 47. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 48. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 49. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 49. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 49. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 50. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 53. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Protocol Version History

- line 60. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 63. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 63. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Document Approvals

- line 74. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 75. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 1. Study Summary

- line 120. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 121. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 123. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 127. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 5. Study Design

- line 188. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Site

- line 204. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 204. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 204. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 208. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Recruitment route

- line 222. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 8. Exclusion Criteria

- line 249. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 14. Data Management

- line 378. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 380. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 380. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 16. Ethics and Regulatory Considerations

- line 396. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 402. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Sponsorship

- line 412. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 412. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Funding

- line 420. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 422. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Contracts and agreements

- line 428. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 428. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 429. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 430. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 431. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 432. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 433. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 434. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Related party: Sleep and Health Clinic Ltd

- line 440. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 18. Insurance and Indemnity

- line 448. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 21. Risk Management

- line 474. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 478. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 22. Information Governance and UK GDPR

- line 489. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 489. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 491. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 23. Intellectual Property and Data Ownership

- line 505. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 24. Dissemination and Publication

- line 529. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Roles and responsibilities

- line 545. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 547. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 548. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 549. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Conflicts of interest

- line 563. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 28. Appendices

- line 615. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Appendix O. Sponsor documents

- line 641. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5_human.docx

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 7. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 17. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 20. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Key contacts

- word/document.xml paragraph 46. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Cover identifiers

- word/document.xml paragraph 75. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 77. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 89. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol version history

- word/document.xml paragraph 114. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Signature page

- word/document.xml paragraph 138. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding and support in kind

- word/document.xml paragraph 300. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Role of the sponsor and funder

- word/document.xml paragraph 307. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 1. Study Summary

- word/document.xml paragraph 332. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 334. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Site

- word/document.xml paragraph 403. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 404. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 404. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment route

- word/document.xml paragraph 413. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 8. Exclusion Criteria

- word/document.xml paragraph 438. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 14. Data Management

- word/document.xml paragraph 610. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 611. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Registration and sponsor responsibilities

- word/document.xml paragraph 636. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sponsorship

- word/document.xml paragraph 645. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 645. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding

- word/document.xml paragraph 649. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Contracts and agreements

- word/document.xml paragraph 657. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 661. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 665. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 669. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 673. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 677. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 681. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Related party: Sleep and Health Clinic Ltd

- word/document.xml paragraph 686. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 21. Risk Management

- word/document.xml paragraph 715. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles

- word/document.xml paragraph 737. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 737. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 738. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 23. Intellectual Property and Data Ownership

- word/document.xml paragraph 747. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles and responsibilities

- word/document.xml paragraph 774. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Conflicts of interest

- word/document.xml paragraph 799. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5_human.md

**Section:** # Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- line 13. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 21. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 24. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Key contacts

- line 55. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Cover identifiers

- line 73. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 74. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 80. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Protocol version history

- line 90. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Signature page

- line 104. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Funding and support in kind

- line 214. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Role of the sponsor and funder

- line 220. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 1. Study Summary

- line 255. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 256. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Site

- line 339. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 341. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 341. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Recruitment route

- line 359. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 8. Exclusion Criteria

- line 398. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 14. Data Management

- line 537. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 539. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Registration and sponsor responsibilities

- line 589. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Sponsorship

- line 607. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 607. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Funding

- line 615. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Contracts and agreements

- line 623. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 624. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 625. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 626. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 627. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 628. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 629. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Related party: Sleep and Health Clinic Ltd

- line 635. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 21. Risk Management

- line 677. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Roles

- line 694. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 694. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 696. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 23. Intellectual Property and Data Ownership

- line 714. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Roles and responsibilities

- line 766. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ### Conflicts of interest

- line 784. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo protocol v0.6.1 2026-10-30.docx

The sponsor line still carries the 30 October name strike and the inserted name. Three passages that already described the rename were put back exactly as they read in backups/, including their original strike formatting. A dated note was then inserted under the 29 October note.

**Section:** Sponsor named in version 0.5

- The old name is struck and the new name is inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026). This passage is left as edited.

**Section:** Name given for this draft

- Restored from the backup. It again reads that the draft name is SHC Sleep Solutions Ltd, company number 12467350, with "formerly App Ltd" struck, then "formerly Sleep and Health Clinic App Ltd (name changed 27 October 2026)".

**Section:** Open for Dr McNeillis

- The struck 29 October question is restored from the backup, as one struck sentence.
- The "Dated note, 29 October 2026" in the same paragraph is restored from the backup. It again says the name changed from Sleep and Health Clinic App Ltd to SHC Sleep Solutions Ltd.
- Inserted under that note: Dated note, 30 October 2026: the two lines above already record that company 12467350 was renamed SHC Sleep Solutions Limited on 27 October 2026. Their earlier name is kept as written.

**Section:** Status of this document

- new paragraph after the Not approved status line. fix 4: Sara McNeillis's approval of version 0.6 at 08:45 on 30 October 2026. Old text kept: "(no text removed)". Inserted: Dated note, 30 October 2026: Sara McNeillis approved version 0.6 on 30 October 2026 at 08:45. It has not been submitted for ethics review, and the MHRA has not been notified.

### lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo protocol v0.6.1 2026-10-30.md

The sponsor line still carries the 30 October name strike and the inserted name. Three passages that already described the rename were put back exactly as they read in backups/. A dated note was then inserted under the 29 October note. difflib against the backup: 5 equal blocks and 4 insert blocks. No delete and no replace.

**Section:** Sponsor named in version 0.5

- The old name is struck and the new name is inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026). This passage is left as edited.

**Section:** Name given for this draft

- Restored from the backup. It again reads that the draft name is SHC Sleep Solutions Ltd, company number 12467350, with "formerly App Ltd" struck, then "formerly Sleep and Health Clinic App Ltd (name changed 27 October 2026)".

**Section:** ## Open for Dr McNeillis

- The struck 29 October question is restored from the backup, including its original ~~ pair.
- The "Dated note, 29 October 2026" on the same line is restored from the backup. It again says the name changed from Sleep and Health Clinic App Ltd to SHC Sleep Solutions Ltd.
- Inserted under that note: Dated note, 30 October 2026: the two lines above already record that company 12467350 was renamed SHC Sleep Solutions Limited on 27 October 2026. Their earlier name is kept as written.

**Section:** Status of this document

- inserted paragraph. fix 4: Sara McNeillis's approval of version 0.6 at 08:45 on 30 October 2026. Old text kept: "(no text removed)". Inserted: Dated note, 30 October 2026: Sara McNeillis approved version 0.6 on 30 October 2026 at 08:45. It has not been submitted for ethics review, and the MHRA has not been notified.

### lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo protocol v0.6.1 change note 2026-10-30.md

**Section:** Decisions of 30 October 2026

- The patch-use sentence now begins "Dated note, 30 October 2026:". The words of the sentence are unchanged.
- The company-name paragraph now begins "Dated note, 30 October 2026:". The opening word "Third." is struck through, so it does not read as a third decision by Sara McNeillis. The Companies House record that follows is unchanged.

**Section:** Hashes

- inserted paragraph. dated note that the printed version 0.6.1 hashes predate this pass. Old text kept: "(no text removed)". Inserted: Dated note, 30 October 2026: the version 0.6.1 hashes printed above are the hashes before the company-name strikes and the notes added in this pass. The hashes after this pass are in NEW-SHA256.txt. The version 0.6 hashes printed above are unchanged..

### lazoo-cmf/03-studies/LAZ-VAL-001/sponsor-documents/README-sources.md

**Section:** # LAZ-VAL-001 sponsor documents: model agreement sources

- line 3. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/04-templates/consent-four-toggles.md

**Section:** # Template — four consent toggles (research pack)

- line 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Toggle 3 — Research (optional)

- line 32. later mention. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited.

**Section:** Proposed addition, 24 October 2026 / Separate recorded choice

- dated strike of the staged line, then insertion. fix 1: one heart-rate choice, dated note in place of the opening line. Old text kept: "Separate recorded choice, 30 October 2026. This choice is not one of toggles 1 to 4. Those toggles keep their numbers and their wording.". Inserted: Dated note, 30 October 2026: proposed toggle 5 above is the heart-rate choice that is asked and recorded on its own (Sara McNeillis, 08:46). It is not one of toggles 1 to 4. Those toggles keep their numbers and wording.  I am asked separately about heart rate from my CBT-14 chest patch. Heart rate is off unless I switch it on. If I say no, or switch it off later, I can still use the chest patch an….
- dated strike of the staged line. fix 1: dated strike of the second staged line. Old text kept: "I am asked separately whether heart rate from my CBT-14 chest patch is recorded. If I decline, I can still use the chest patch and I can still use the app. My a…". Inserted: (strike formatting only).

### lazoo-cmf/04-templates/data-dictionary.md

**Section:** ### Heart rate from CBT-14 (proposed)

- line 81. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/README.md

**Section:** # Lazoo Clinical Master File

- line 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/SOP-CMF-001-management.md

**Section:** ## 3. Roles

- line 23. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-CRF-template.docx

**Section:** Case Report Form CRF Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-ISF-template.docx

**Section:** Investigator Site File Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-SOP-template.docx

**Section:** Standard Operating Procedure Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-clinical-study-report-template.docx

**Section:** Clinical Study Report Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-data-management-plan-template.docx

**Section:** Data Management Plan Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-monitoring-plan-template.docx

**Section:** Monitoring Plan Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-protocol-template.docx

**Section:** Sleep and Health Clinic App LtdClinical Research Protocol Template

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 14. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Confidentiality Statement

- word/document.xml paragraph 26. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/SHA-validation-study-template.docx

**Section:** Validation Study Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-CRF-v0.2.docx

**Section:** word/header1.xml

- word/header1.xml paragraph 1. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** LAZ-VAL-001 Case Report Form (CRF) booklet v0.2

- word/document.xml paragraph 8. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Adverse Events

- word/document.xml paragraph 505. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** word/footer1.xml

- word/footer1.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-CRF-v0.3.docx

Company name only. The heart-rate decline note is not added. That is deliberate, because the CRF _human copies already carry it.

**Section:** LAZ-VAL-001 Case Report Form (CRF) booklet v0.3

- word/document.xml paragraph 7. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Adverse Events

- word/document.xml paragraph 486. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-CRF-v0.3_human.docx

**Section:** Case Report Form (CRF) booklet for the Lazoo validation study, version 0.3

- word/document.xml paragraph 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.2.docx

**Section:** word/header1.xml

- word/header1.xml paragraph 1. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** word/document.xml

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** LAZ-VAL-001 Data Management Plan v0.2

- word/document.xml paragraph 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Data Sources

- word/document.xml paragraph 38. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Storage

- word/document.xml paragraph 78. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 83. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 100. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** GDPR

- word/document.xml paragraph 118. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** word/footer1.xml

- word/footer1.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.3.docx

**Section:** word/header1.xml

- word/header1.xml paragraph 1. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** word/document.xml

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** LAZ-VAL-001 Data Management Plan v0.3

- word/document.xml paragraph 8. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Data Sources

- word/document.xml paragraph 37. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 41. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 42. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 42. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 45. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 46. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment

- word/document.xml paragraph 58. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Partner Site and Data Rules

- word/document.xml paragraph 63. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 66. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Storage

- word/document.xml paragraph 97. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 102. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 119. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 120. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** GDPR

- word/document.xml paragraph 137. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** word/footer1.xml

- word/footer1.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.4-superseded-2026-10-24.docx

**Section:** word/document.xml

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 3. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** LAZ-VAL-001 Data Management Plan v0.4

- word/document.xml paragraph 7. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Data Sources

- word/document.xml paragraph 34. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- word/document.xml paragraph 38. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 39. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 42. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 43. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 43. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment

- word/document.xml paragraph 48. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Partner Site and Data Rules

- word/document.xml paragraph 53. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 53. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 53. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 54. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Storage

- word/document.xml paragraph 77. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 82. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 98. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 99. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** GDPR

- word/document.xml paragraph 116. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.4.docx

**Section:** word/document.xml

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 8. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 8. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 10. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** LAZ-VAL-001 Data Management Plan v0.4

- word/document.xml paragraph 15. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Data Sources

- word/document.xml paragraph 42. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- word/document.xml paragraph 46. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 47. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 50. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 51. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 51. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment

- word/document.xml paragraph 56. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Partner Site and Data Rules

- word/document.xml paragraph 61. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 61. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 61. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 62. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Storage

- word/document.xml paragraph 85. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 90. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 106. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 107. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** GDPR

- word/document.xml paragraph 125. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 129. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.4_human-superseded-2026-10-24.docx

**Section:** Data Management Plan for the Lazoo validation study, version 0.4

- word/document.xml paragraph 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Document history

- word/document.xml paragraph 25. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 2. Roles and responsibilities for data

- word/document.xml paragraph 41. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 3. Data sources

- word/document.xml paragraph 87. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 92. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 4. Recruitment

- word/document.xml paragraph 96. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 5. Partner site and rules for data sharing

- word/document.xml paragraph 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 101. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 7. Storage and security

- word/document.xml paragraph 152. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 9. Data protection (UK GDPR)

- word/document.xml paragraph 171. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.4_human.docx

**Section:** word/document.xml

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Data Management Plan for the Lazoo validation study, version 0.4

- word/document.xml paragraph 12. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** Document history

- word/document.xml paragraph 28. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 2. Roles and responsibilities for data

- word/document.xml paragraph 50. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 3. Data sources

- word/document.xml paragraph 98. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 103. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 4. Recruitment

- word/document.xml paragraph 107. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 5. Partner site and rules for data sharing

- word/document.xml paragraph 112. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 112. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 114. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 7. Storage and security

- word/document.xml paragraph 163. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 9. Data protection (UK GDPR)

- word/document.xml paragraph 183. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 187. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.3.docx

**Section:** word/document.xml

- word/document.xml paragraph 2. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 2. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- word/document.xml paragraph 2. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 4. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 9. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 11. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Cover identifiers

- word/document.xml paragraph 27. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 29. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol Version History

- word/document.xml paragraph 53. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document Approvals

- word/document.xml paragraph 77. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 1. Study Summary

- word/document.xml paragraph 133. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 14. Data Management

- word/document.xml paragraph 413. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 16. Ethics and Regulatory Considerations

- word/document.xml paragraph 430. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sponsorship

- word/document.xml paragraph 437. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding

- word/document.xml paragraph 439. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Contracts and agreements

- word/document.xml paragraph 447. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 451. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 455. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 459. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 463. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 467. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Related party: Sleep and Health Clinic Ltd

- word/document.xml paragraph 473. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 18. Insurance and Indemnity

- word/document.xml paragraph 475. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 21. Risk Management

- word/document.xml paragraph 506. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 22. Information Governance and UK GDPR

- word/document.xml paragraph 526. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 23. Intellectual Property and Data Ownership

- word/document.xml paragraph 533. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles and responsibilities

- word/document.xml paragraph 548. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.4.docx

**Section:** word/document.xml

- word/document.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 2. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 2. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- word/document.xml paragraph 2. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 4. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 9. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 11. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Cover identifiers

- word/document.xml paragraph 27. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 29. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol Version History

- word/document.xml paragraph 55. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 67. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 67. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document Approvals

- word/document.xml paragraph 83. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 1. Study Summary

- word/document.xml paragraph 139. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment route

- word/document.xml paragraph 225. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 14. Data Management

- word/document.xml paragraph 422. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 424. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 16. Ethics and Regulatory Considerations

- word/document.xml paragraph 441. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sponsorship

- word/document.xml paragraph 448. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding

- word/document.xml paragraph 452. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Contracts and agreements

- word/document.xml paragraph 460. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 464. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 468. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 472. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 476. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 480. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 484. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Related party: Sleep and Health Clinic Ltd

- word/document.xml paragraph 490. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 21. Risk Management

- word/document.xml paragraph 525. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 22. Information Governance and UK GDPR

- word/document.xml paragraph 547. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 548. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 23. Intellectual Property and Data Ownership

- word/document.xml paragraph 555. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles and responsibilities

- word/document.xml paragraph 579. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Conflicts of interest

- word/document.xml paragraph 608. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.5.docx

**Section:** word/document.xml

- word/document.xml paragraph 4. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 4. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 4. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- word/document.xml paragraph 4. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 5. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 6. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 6. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 6. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 8. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 9. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 10. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Cover identifiers

- word/document.xml paragraph 26. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 28. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 30. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 32. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 32. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 32. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 34. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 40. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol Version History

- word/document.xml paragraph 53. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 73. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 73. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document Approvals

- word/document.xml paragraph 84. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 89. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 1. Study Summary

- word/document.xml paragraph 139. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 141. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 145. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 153. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 5. Study Design

- word/document.xml paragraph 202. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Site

- word/document.xml paragraph 210. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 210. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 210. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 212. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment route

- word/document.xml paragraph 219. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 8. Exclusion Criteria

- word/document.xml paragraph 238. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 14. Data Management

- word/document.xml paragraph 405. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 406. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 406. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 16. Ethics and Regulatory Considerations

- word/document.xml paragraph 414. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 417. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sponsorship

- word/document.xml paragraph 422. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 422. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding

- word/document.xml paragraph 426. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 427. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Contracts and agreements

- word/document.xml paragraph 434. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 435. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 438. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 442. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 446. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 450. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 454. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 458. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Related party: Sleep and Health Clinic Ltd

- word/document.xml paragraph 463. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 18. Insurance and Indemnity

- word/document.xml paragraph 467. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 21. Risk Management

- word/document.xml paragraph 488. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 496. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 22. Information Governance and UK GDPR

- word/document.xml paragraph 509. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 509. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 510. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 23. Intellectual Property and Data Ownership

- word/document.xml paragraph 517. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 24. Dissemination and Publication

- word/document.xml paragraph 529. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles and responsibilities

- word/document.xml paragraph 538. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 542. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 545. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 547. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Conflicts of interest

- word/document.xml paragraph 563. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 28. Appendices

- word/document.xml paragraph 614. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Appendix O. Sponsor documents

- word/document.xml paragraph 671. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.5_human.docx

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 4. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 17. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Key contacts

- word/document.xml paragraph 43. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Cover identifiers

- word/document.xml paragraph 72. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 74. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 86. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol version history

- word/document.xml paragraph 111. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Signature page

- word/document.xml paragraph 135. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding and support in kind

- word/document.xml paragraph 297. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Role of the sponsor and funder

- word/document.xml paragraph 304. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 1. Study Summary

- word/document.xml paragraph 329. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 331. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Site

- word/document.xml paragraph 400. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 401. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 401. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Recruitment route

- word/document.xml paragraph 410. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 8. Exclusion Criteria

- word/document.xml paragraph 435. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 14. Data Management

- word/document.xml paragraph 607. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 608. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Registration and sponsor responsibilities

- word/document.xml paragraph 633. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sponsorship

- word/document.xml paragraph 642. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 642. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Funding

- word/document.xml paragraph 646. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Contracts and agreements

- word/document.xml paragraph 654. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 658. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 662. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 666. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 670. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 674. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 678. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Related party: Sleep and Health Clinic Ltd

- word/document.xml paragraph 683. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 21. Risk Management

- word/document.xml paragraph 712. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles

- word/document.xml paragraph 734. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 734. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 735. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** 23. Intellectual Property and Data Ownership

- word/document.xml paragraph 744. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Roles and responsibilities

- word/document.xml paragraph 771. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Conflicts of interest

- word/document.xml paragraph 796. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/02-hold-samd/HOLD-AI-validation-report-template.docx

**Section:** AI Validation Report Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/02-hold-samd/HOLD-clinical-evaluation-report-template.docx

**Section:** Clinical Evaluation Report Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/02-hold-samd/HOLD-technical-file-template.docx

**Section:** Technical File Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DHF-001-stub-consent-audit.md

**Section:** # LAZ-DHF-001 — Stub only (consent and audit trail)

- line 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** What this stub records

- inserted paragraph. fix 2: separate timed records for on, off, and keep-or-delete. Old text kept: "(no text removed)". Inserted: Dated note, 30 October 2026: switching heart rate on, switching it off, and choosing to keep or delete stored heart rate are each recorded separately, with the time and the wording version shown (CBT-14 heart-rate opt-out note, 30 October 2026)..

### lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DPIA-001-short-form.md

**Section:** # LAZ-DPIA-001 — Short-form DPIA

- line 11. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 16. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** ## 2. Description of processing

- line 29. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 30. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 33. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 33. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 4. Lawful basis (draft)

- line 57. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 5. Retention

- line 63. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 63. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 65. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 6. Risks and controls

- line 73. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 76. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## 7. Sign-off (blank)

- line 85. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 88. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/LAZ-GDPR-001-company-separation.md

**Section:** ## Three files, three controllers

- line 12. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 12. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Current breach to fix

- line 20. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 20. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Retention

- line 24. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 26. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 27. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 28. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/LAZ-QM-001-quality-manual.md

**Section:** # LAZ-QM-001 — Quality manual (App Ltd)

- line 3. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- line 9. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Quality policy

- line 14. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Organisation

- line 26. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 26. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/LAZ-RSK-001-risk-plan.md

**Section:** # LAZ-RSK-001 — Risk plan (App Ltd information governance)

- line 7. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 9. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

**Section:** ## Identification (current)

- line 23. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Controls

- line 39. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 43. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/README.md

**Section:** # 03-compliance — App Ltd (12467350)

- line 3. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/app-ltd-shells/03-compliance/SHA-DHF-template-stub-only.docx

**Section:** Design History File Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/SHA-quality-manual-template.docx

**Section:** Quality Manual Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/03-compliance/SHA-risk-management-plan-template.docx

**Section:** Risk Management Plan Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/04-tmf/SHA-TMF-template.docx

**Section:** Trial Master File Template

- word/document.xml paragraph 2. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/app-ltd-shells/README.md

**Section:** # App Ltd TMF shells

- line 3. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/do-not-send/QUARANTINE-NOT-CONTROLLED-LAZ-VAL-001-protocol-v0.2.docx

**Section:** word/header1.xml

- word/header1.xml paragraph 1. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

**Section:** Concurrent validity and usability of the Lazoo (SHC Digital Sleep Diary) compared with the Consensus Sleep Diary–Morning (CSD-M) in adults

- word/document.xml paragraph 14. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).
- word/document.xml paragraph 20. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 22. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Confidentiality Statement

- word/document.xml paragraph 26. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Protocol Version History

- word/document.xml paragraph 41. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document Approvals

- word/document.xml paragraph 54. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Study Summary

- word/document.xml paragraph 107. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 117. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 129. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Sites

- word/document.xml paragraph 168. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Study Procedures

- word/document.xml paragraph 205. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Safety Reporting

- word/document.xml paragraph 372. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Data Management

- word/document.xml paragraph 383. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 386. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Ethics and Regulatory Considerations

- word/document.xml paragraph 407. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 407. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Risk Management

- word/document.xml paragraph 441. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Information Governance and GDPR

- word/document.xml paragraph 453. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Intellectual Property

- word/document.xml paragraph 460. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.
- word/document.xml paragraph 461. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Study Management

- word/document.xml paragraph 475. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Archiving

- word/document.xml paragraph 495. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Appendices

- word/document.xml paragraph 524. short form App Ltd. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** word/footer1.xml

- word/footer1.xml paragraph 1. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** Document properties, creator

- docProps/core.xml. later mention (core property; strike marked with ~~ because the field has no Word strike). Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/grants-layer2-nihr/README.md

**Section:** # Grants file

- Cover note inserted at the top: Dated note, 30 October 2026: the two NIHR outline PDFs are kept as filed and are not edited. Where they name Sleep and Health Clinic App Limited, that is company 12467350, renamed SHC Sleep Solutions Limited on 27 October 2026. "Sleep and Health App Limited (SHA)" in NIHR514007 is the wording as filed. Sleep and Health Clinic Ltd (08904119) is a separate company.
- line 12. later mention. Old text kept: "Sleep and Health Clinic App Limited". Inserted: SHC Sleep Solutions Limited. The two outline PDFs are not edited.

### lazoo-cmf/tmp-roadmap-revA.txt

**Section:** (no heading yet)

- line 75. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

### lazoo-cmf/uclh-feasibility-separate-sponsor/README.md

**Section:** # UCLH-sponsored feasibility — keep out of App Ltd TMF

- line 1. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).
- line 5. full name next to 12467350. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026).

### lazoo-cmf/uclh-feasibility-separate-sponsor/UCLH-PIS-v0.2-recut.md

**Section:** # Patient information sheet (recut v0.2 — not for issue until REC/HRA and CI sign-off)

- line 5. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Confidentiality and data protection

- line 85. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.

**Section:** ## Recut log (compliance)

- line 122. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

### lazoo-cmf/uclh-feasibility-separate-sponsor/UCLH-consent-v0.2-recut.md

**Section:** # Consent form (recut v0.2 — not for issue until REC/HRA and CI sign-off)

- line 22. later mention. Old text kept: "Sleep and Health Clinic App Ltd". Inserted: SHC Sleep Solutions Limited.
- line 31. short form App Ltd, first in this file. Old text kept: "App Ltd". Inserted: SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026).

