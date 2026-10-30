# LAZ-HR-IMPACT — Impact register for the heart rate amendment

**Document ID:** LAZ-HR-IMPACT-2026-10-24
**Date:** 24 October 2026
**Status:** DRAFT for Compliance. Lists every controlled document found that the heart rate amendment (LAZ-IP-001-AMD-01) would affect. No document's existing text has been changed; dated notes were inserted at the top only, and proposed sections were appended at the end of the data dictionary and consent template.
**Sponsor and manufacturer:** Sleep and Health Clinic App Ltd (12467350). Sleep & Health Clinic Ltd (08904119) gives advice only.
**Related:** LAZ-IP-001-AMD-01; LAZ-CL-001-REV-01; LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md); the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5]. Change list for Compliance: /workspace/compliance-reports/hr-amendment-for-gate-2026-10-24.md. Backups: /workspace/_backups/hr-amendment-2026-10-24/.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "path to be added" wording and the version 0.2 citation in the line above are kept as recorded; this path answers them.

## 1. Standard note text

Unless the row says otherwise, the note inserted (or proposed) is:

> Amendment pending, 24 October 2026: A heart-rate intended-purpose amendment is in draft under LAZ-IP-001-AMD-01 (/workspace/lazoo-cmf/01-product/LAZ-IP-001-AMD-01-heart-rate-2026-10-24.md), awaiting review by Compliance and a decision by Sara McNeillis. The text below is unchanged and remains current until that amendment is approved.

Variants used:

- **dp** adds: "Data protection: see LAZ-DPIA-HR-input-2026-10-24 (/workspace/lazoo-cmf/02-governance/LAZ-DPIA-HR-input-2026-10-24.md) and the CBT-14 heart rate data protection impact assessment, owned by Research Governance (path to be added) [CBT-14-HR-DPIA-2026-10-24, version 0.2: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5]."

  Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The dp wording above, including "path to be added" and the version 0.2 citation, is kept as it was inserted in the notes it describes.
- **cl** adds a pointer to LAZ-CL-001-REV-01.
- **crf** adds that heart rate is not collected in LAZ-VAL-001 version 0.5 and the wearable field stays empty, plus the dp sentence.
- **val** adds the LAZ-VAL-001 recommendation in section 3.
- **dpath** (CBT-14 data-path lock) says that, if approved, heart rate from CBT-14 would be added to the Bluetooth Low Energy path to Lazoo, which the lock limits to skin temperature and movement, and that the lock stays current until the amendment is approved and Sara changes it.

## 2. Documents noted on 24 October 2026

The hash shown is the sha256 now, after the note was inserted; the earlier hash is in brackets.

| Path | Current sha256 | What changes if approved | Action taken today |
|---|---|---|---|
| `/workspace/lazoo-cmf/01-product/LAZ-IP-001-intended-purpose.md` | 56ddadccfae685954a6ff5cad55861263f2232819f603e4796aacf49c6aa0955 (was a6e69d5a9687ac5ca78a86fe61210700f479feaeacdf2bb1aa5636170aec1590) | Controlled intended purpose. Purpose text is still "TBD — pending Sara paste." If AMD-01 is approved, the heart rate wording goes in with the full purpose. | Inserted (base note). |
| `/workspace/lazoo-cmf/01-product/LAZ-CL-001-classification-memo.md` | bbd49aa87a2dc8c953192d6c6ff4f044db3aa1286c1bf2f647743ad102724516 (was 9fb4dcc7be8611945e5f8add68b1b8ed653799c2fb2cf5ad9a2bfa6457b5ccb3) | Classification memo. Names no rule today. If approved, revise to cite UK Rule 10 for Great Britain, record heart rate trend display and the wording guards (see REV-01). | Inserted (cl note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5.md` | 7daed44bd05b0c8a0f865f03d44fc26b538a62d38b3a7b005a0c2c334cd3fc71 (was 2496779c1eccbc09f40e4f5b4025afbd7a322508038c65e3c8715c8bfa324c55) | No change to the study. Dated out-of-scope note added (heart rate not an endpoint; wearable field stays empty). | Inserted (val note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5_human.md` | 408068656d36163f105b56001534463e7f079bd28607d3c3e3859e3679f2cbf3 (was 3a9ebf1006d5bd1f6e33767cea44f022689e06a63def5e7bc895d4305edc86ee) | As the protocol .md. | Inserted (val note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4.md` | 4640eb2348441f3c31fa884c9daf71b7314feb4133c50fa23d001d481e75c265 (was 686864b75d8740610adfb2ce15ebfc1b87c6ca90efd28d30d35258b765bd437f) | No change to data handled in VAL-001. Note only. On approval, any later protocol that collects heart rate needs a DMP revision. | Inserted (dp note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human.md` | ff11e6987461323687b05c493104452191940eb0acddc07f829138d294ee066f (was 30d5caa4c323619a86aef659cc7b16faa435bdf492020609dc6943e2089dce03) | As the DMP .md. | Inserted (dp note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3.md` | 94288a2548fafc485f291ce621caeb5df92520712ac1eeb0330c29a571372639 (was ff0b47c01eb1462167cc9a10dbfb181401a5efa9c115b7d8c7c0359b5e570f4d) | No change. Heart rate not collected; the existing check "ai_event / wearable / core_temp unused (empty)" stays. | Inserted (crf note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3_human.md` | 2b1e1790a07ee53b59e99a47036a8b0ae8adf733d5a6b9928fc931dff41b4794 (was f236fdf9ffdcb7493a7cb10431cd86e34afe326772606c46c4cba5478534e2cc) | As the CRF .md. | Inserted (crf note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/01-essential-documents.md` | 91b61bcd383ec3789e26c12a15f9711dcef47a6f465ed447cc80fc48d0fc3438 (was e2d7ed6efb310243b9c9e9624f76133b5ae273933f9985bfba4290a86fac8973) | Essential documents list. On approval, add AMD-01 and REV-01 as filed documents. | Inserted (base note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14.md` | d021e0acda4cad0e4ce3b569dfe665d8439925837a416a3d93745adceb9cd08a (was 9485f860d10ae70148d3b32f8814781eec6c7394927f6ecb56ef128b11b97d36) | MHRA notes on classification. On approval, reconcile with REV-01 (UK Rule 10). | Inserted (cl note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14_human.md` | 6ca2ca5c80e90471f3e35f43ca059789e54b32f7f639c7c47d16ce9ea4998d8a (was 853e8b06e3c4ba55e997481b75d0514c52831291945278f5068e9bac724db3e2) | As the notes .md. | Inserted (cl note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-RWE-001/00-protocol-outline.md` | 9fa3b9c519603243746c9ac84ee2efa8cde14939fcb91aa72238e6be28009812 (was 76d4760849561fbb797ebb9c25e645a397e63164f92ee41bdd57dcb09ac0eb7d) | LAZ-RWE-001 outline reserves wearable fields as empty. On approval, decide whether RWE-001 collects heart rate (needs protocol, DPIA and consent). | Inserted (dp note). |
| `/workspace/lazoo-cmf/04-templates/data-dictionary.md` | f70685c64c7e0c610f04ddbae388f65e2c0b81fe004206817b6d49cb32510f0a (was a183578b488ed10be5030f368e22b1b95e618b08b82ad034c8ca9ef6faf290ed) | Proposed heart rate fields appended at the end, dated 24 October 2026. | Inserted (dp note + appended proposed section). |
| `/workspace/lazoo-cmf/04-templates/consent-four-toggles.md` | 956302109cb1ac104cd44904ba761a136f9a0eeaaa279240b610d28209edaa55 (was ec08cbdd8ea1259cc45e17337eca7b2fca9edeee83f312af8072a8f663dcb8a1) | Proposed heart rate toggle wording appended at the end, dated 24 October 2026. | Inserted (dp note + appended proposed section). |
| `/workspace/lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DPIA-001-short-form.md` | 04c905b610c3b63b454a894f887e783529ab44b3f002af1fc2ec857e11058c8f (was 990a19ecf52ad487f49c4da6d7fe21ee51ce2e540ae2898ad5568bdb048ed958) | Short-form DPIA. On approval, heart rate added as a data item with the Article 9(2) condition chosen by Research Governance. | Inserted (dp note). |
| `/workspace/lazoo-cmf/app-ltd-shells/03-compliance/LAZ-RSK-001-risk-plan.md` | 04e924d928923df91d6f6971820eda0336079d0c028fa30b02c7107d34038f29 (was 25d8ed3a8607c5ac59292f049808f12c5895b08e1a8888661c420d9c9304fecf) | Risk plan states it is reviewed when the intended purpose changes. On approval, add hazards for heart rate trend display (misreading, false reassurance, use as alarm). | Inserted (cl note). |
| `/workspace/lazoo-cmf/app-ltd-shells/03-compliance/LAZ-DHF-001-stub-consent-audit.md` | 2516433a6a4755281dd81f10d5040828fb5a59e75919541e7136a7864921a44c (was e81832862a2a0fe613262d4b16c4a2af23b22d7345376e656bd6481186a8a8b2) | Consent screen audit. On approval, add the heart rate toggle and on-screen intended purpose line. | Inserted (base note). |
| `/workspace/lazoo-cmf/00-INDEX.md` | 0b680c99daf2e3c51509daf18a4dcdfa26f0ec2ea75982b0a301c65d4a6d0d6e (was 6384c88cf7cfcb61aa3201538e056c15866e402f19093dcfbdbca88af8724052) | Index. On approval, list AMD-01, REV-01, HR-IMPACT and DPIA-HR input. | Inserted (base note). |
| `/workspace/out/governance-2026-10-11/LAZ-GOV-AIRLOCK-data-ethics-note.md` | c4c999245ffe6b7c5eeeedfbd71c671dc476d9bb98cfe7997ebbc8494006dd9a (was 0d166f020504292aaf30f4e54f5dedd53c1231bba39f9468e8bb53b23506f0c1) | Airlock data ethics note: says wearable fields are reserved and empty. On approval, update data description and the outbound data note. | Inserted (dp note). |
| `/workspace/out/governance-2026-10-12/LAZ-i4i-alignment-redline.md` | 9659b67b331ec4d5e3c5e45ee1318d55cf7a762f6284a4c34498d432ee9a3e5e (was 7f08c5fb1081b6921cce10a5946c56109f6279620942262ddc6c9c5949e8d422) | i4i application wording redline. On approval, check that the application wording does not imply heart rate is in or out of scope. | Inserted (base note). |
| `/workspace/cbt-14-proto-ready/smaller/mock-C-S3/charge-dock/DATA-PATH.md` | fb28b2a04395a018b5deea44779ef31a659d96ddbc761d8f48d5f2d76ff71725 (was c1fcbf0e44a1dd5c656e49f3f153b3b42e1b7c249e4df6162d88fa438cf7002c) | Sara's CBT-14 data-path lock limits the BLE path to Lazoo to skin temperature and movement. Heart rate in Lazoo needs Sara to change this lock. Three identical copies; all three noted so they stay identical. | Inserted (dpath note). |
| `/workspace/cbt-14-uploads/proto-ready/smaller/mock-C-S3/charge-dock/DATA-PATH.md` | fb28b2a04395a018b5deea44779ef31a659d96ddbc761d8f48d5f2d76ff71725 (was c1fcbf0e44a1dd5c656e49f3f153b3b42e1b7c249e4df6162d88fa438cf7002c) | Sara's CBT-14 data-path lock limits the BLE path to Lazoo to skin temperature and movement. Heart rate in Lazoo needs Sara to change this lock. Three identical copies; all three noted so they stay identical. | Inserted (dpath note). |
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/proto-ready/smaller/mock-C-S3/charge-dock/DATA-PATH.md` | fb28b2a04395a018b5deea44779ef31a659d96ddbc761d8f48d5f2d76ff71725 (was c1fcbf0e44a1dd5c656e49f3f153b3b42e1b7c249e4df6162d88fa438cf7002c) | Sara's CBT-14 data-path lock limits the BLE path to Lazoo to skin temperature and movement. Heart rate in Lazoo needs Sara to change this lock. Three identical copies; all three noted so they stay identical. | Inserted (dpath note). |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-protocol-v0.5_human.docx` | 89936bca84a0ceea9deb0de29f49aa884f13d82c126942fe9edd3b9d4b5118b0 (was 794852044530b1761446f06aed6fe63619454e3cd29fdee34b307bce1a256be8) | Protocol docx: same dated out-of-scope note as the .md, inserted as first paragraph (python-docx). | Inserted (val note). |
| `/workspace/lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.5_human.docx` | 89936bca84a0ceea9deb0de29f49aa884f13d82c126942fe9edd3b9d4b5118b0 (was 794852044530b1761446f06aed6fe63619454e3cd29fdee34b307bce1a256be8) | Protocol docx: same dated out-of-scope note as the .md, inserted as first paragraph (python-docx). | Inserted (val note). |
| `/workspace/lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-protocol-v0.5.docx` | 2dd649277e32d926bbe5cea0256e550391d7a92db0c647964a247ee2c03461d8 (was 18c5b2b8af13b7512abd142cae233fd4b56af3f7fc99cb701bace42dc94c5b76) | Protocol docx: same dated out-of-scope note, first paragraph. | Inserted (val note). |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/Airlock-brief-for-Sara-2026-10-13.docx` | 01cc75a6ed2dc59c9678d66b071953d9523a86c2b0e06e7831d39173d6f4d91c (was 7ef64c5437aa7e9430fe41377f260163b7fa3d5a624128382f8dd61a7f3a20fd) | Airlock brief: dated pending note, first paragraph. Drive copy to be replaced after Compliance passes. | Inserted (base note). |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-AIRLOCK-002-AI-components-one-page-2026-10-11.docx` | 9b55111bf3e429923a08dadc28f46a266e1ce06a796ccfe8d9c0969086991779 (was 07670912dee9d8aea12660e39be5ba5bb99f2ff057ab538511a13d22c7233ef9) | Airlock 002 one-page: dated pending note, first paragraph. Drive copy to be replaced after Compliance passes. | Inserted (base note). |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-i4i-alignment-redline.docx` | ec3b162831cebddc0cf918e00caa498d2e76b8bfb8d37199ad62780058d148ff (was bb4d394f9cddf59fc807584eeb0793a0896e1f54285caa248642b6f6852285e9) | i4i wording: dated pending note, first paragraph. Drive copy to be replaced after Compliance passes. | Inserted (base note). |
| `/workspace/out/governance-2026-10-12/LAZ-i4i-alignment-redline.docx` | f9a3fb428f6ff0b4edf0882f3df4f443aa79df8d8690a70972a0caa37d742944 (was 8fb9d3a446f9579473614f93dda155906e921384a4f1cd6e996481d404d9df7f) | i4i wording: dated pending note, first paragraph. Drive copy to be replaced after Compliance passes. | Inserted (base note). |

Dated note, 24 October 2026 (Compliance round 4, R4-8): for the row above, the current i4i text is the pack copy /workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-i4i-alignment-redline.docx (e3f21f67…), which matches the Drive copy. The 12 October 2026 redline in /workspace/out/governance-2026-10-12/ is a historical record and is not the source for the Drive copy; see the R4-8 note in section 8.

Dated note, 24 October 2026: decision 2 of the addendum (lines 394 and 442) has already recorded the widening of the lock. Read these rows as "recorded, pending sign-off of the DPIA and approval of AMD-01", not as needing Sara to change the lock. (Compliance gate F6, placed after line 51; inserted here at the end of the table so that the table is not split.)

Dated note, 24 October 2026: with its heart-rate header note, the file is now sha256 bbd49aa8…; the content below the note is byte-for-byte the kept 9fb4dcc7. (Compliance gate F11, for the LAZ-CL-001 row above.)

## 3. LAZ-VAL-001 recommendation

**Recommendation: no heart rate endpoint; heart rate recorded as out of scope by a dated note.** Implemented as a dated top note in protocol v0.5 (.md, _human.md and the three permitted docx files); the protocol text is unchanged.

Reasons, from what protocol version 0.5 says:

1. The study's question is agreement between Lazoo and the Consensus Sleep Diary–Morning for calculated total sleep time (primary objective), with secondary agreement on sleep onset latency, wake after sleep onset, sleep efficiency and awakenings, and descriptive completeness, timestamps and System Usability Scale results. Heart rate answers none of these.
2. Section 5 already sets the rule for wearable data: "Wrist actigraphy is not included in this version. Adding it would require a protocol amendment, a named actigraphy device of appropriate regulatory status, and a scoring standard operating procedure for that device." The same reasoning applies to CBT-14 heart rate. CBT-14 is presented as a wellness product and has no medical device status, so it does not meet "a named device of appropriate regulatory status".
3. The case report form checks that "ai_event / wearable / core_temp" fields are unused and empty in version 1. Collecting heart rate would contradict a filed check.
4. A heart rate validation endpoint would need a reference method (for example an electrocardiogram-based reference), a sample size for that endpoint, a DPIA update, new consent wording and ethics approval. None of these exists, and the intended purpose amendment is not yet approved.
5. Adding it now would delay a study whose design is otherwise settled. Heart rate validation belongs in its own protocol once AMD-01 is approved and CBT-14's regulatory status is settled.

Pregnancy stays exclusion criterion 7 in LAZ-VAL-001.

## 4. Documents affected but not edited: note to be added on approval

docx and xlsx files outside the steering permission were not edited. Each needs the standard note when the amendment is approved, unless stated.

| Path | Current sha256 | What changes if approved |
|---|---|---|
| `/workspace/out/lazoo-uclh-pack-2026-10-13/INTENDED-PURPOSE-LAZOO-DRAFT-2026-10-12.docx` | c37b50ba802c2bfd1e627a93bc28af1d8cd602f6ab730c44b0b2ab57ca140aa6 | Draft intended purpose. Holds the monitoring-only wording quoted in AMD-01; the heart rate wording would be added here. Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-AIRLOCK-001-clinical-AI-description-DRAFT-2026-10-11.docx` | 20a51f714a9debac09172405dcef3dea8b95d36c572b19cf04f29af97bf0c409 | Inputs and outputs description. Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-AIRLOCK-002-data-table-2026-10-11.docx` | 31fa02ca25f33ddd9720de18de3eff029fdae0c50a48addbd74a392e9fdec5fb | Data table would gain a heart rate row. Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-GOV-AIRLOCK-data-ethics-note.docx` | d02b687913e065409247589595ef1889c1961e3a232b355bdde92994330f6464 | docx of the ethics note (md noted). Note to be added on approval. |
| `/workspace/out/governance-2026-10-11/LAZ-GOV-AIRLOCK-data-ethics-note.docx` | aeae0388612e6fec00ce75e7f698ca5d97fc0c5aa7292710e04a387727b14adb | As above (differs from the out-pack copy). Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-I4I-001-co-applicant-shortlist-FINAL-DRAFT-2026-10-13.docx` | f264809b983c14bb0da9f622ce6dbbf8611b40df89e6023c3bf668387ad50693 | Co-applicant shortlist; not application wording. Check only; note to be added on approval if it describes the purpose. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/Information-needed-from-Sara-2026-10-13.docx` | 9400d2680f877561c05eb43339b0b1c0c6a66f1b74dd410719050bd6c90ee71b | Add the AMD-01 questions. Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-VAL-001-protocol-v0.5.docx` | 794852044530b1761446f06aed6fe63619454e3cd29fdee34b307bce1a256be8 | Pack copy of protocol v0.5 (same bytes as the _human.docx before today's note). Now out of step with the noted copies. Note to be added on approval, or replace with the noted copy. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-VAL-001-DMP-v0.4.docx` | 100ff34292789cb8a5a072edf85a7ff679f39e7f5ce7636de76ae5aac3446e39 | Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-VAL-001-CRF-v0.3.docx` | bea6a0f93d0edd8e799004a3866e69190417b8167eaa3fcfac79c3221eb83611 | Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-VAL-001-prolific-mhra-notes-2026-10-14.docx` | 029bfa565ed9cb23fbab85f2e9f55c0ec2c749ebcf923f29c73e80eb0a21ff37 | Note to be added on approval. |
| `/workspace/out/lazoo-uclh-pack-2026-10-13/lazoo-placeholder-tracker-2026-10-13.xlsx` | 4402e553beb3b20205abe7c91db1c5b56bfd42e305d92c21db2f58188428bc5b | Add AMD-01 open items. Note to be added on approval. |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-DMP-v0.4_human.docx` (same bytes in filled/) | 100ff34292789cb8a5a072edf85a7ff679f39e7f5ce7636de76ae5aac3446e39 | Note to be added on approval. |
| `/workspace/lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-DMP-v0.4.docx` | c84e7709d5c284d5578d6a80cc4d96d2bfc778279111229aedf0b8a2bfeb437a | Note to be added on approval. |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-CRF-v0.3_human.docx` (same bytes in filled/) | bea6a0f93d0edd8e799004a3866e69190417b8167eaa3fcfac79c3221eb83611 | Note to be added on approval. |
| `/workspace/lazoo-cmf/app-ltd-shells/01-clinical-research-to-fill/filled/LAZ-VAL-001-CRF-v0.3.docx` | 546e9cac1852158ed7e11f0798b7ac40eda93bfc1a07b8d5370e9636c41d997b | Note to be added on approval. |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/LAZ-VAL-001-prolific-mhra-notes-2026-10-14_human.docx` | 029bfa565ed9cb23fbab85f2e9f55c0ec2c749ebcf923f29c73e80eb0a21ff37 | Note to be added on approval. |
| `/workspace/LAZOO-Intended-Purpose-DRAFT-2026-10-05.docx` | 074f342404b9080a33677a438759ce97f076240938b973694881cebbd1d166a1 | Older intended purpose draft (5 October). Likely superseded by the 12 October draft; Compliance to confirm whether it needs a note. |
| `/workspace/lazoo-cmf/grants-layer2-nihr/NIHR514007-i4i-AppLtd-AI-enabled-sleep-diary-outline.pdf` | e2f37b52bf88dc1c880fefb85fcebb99bc313a91d43b0876c6e0cae0c592a9ab | Submitted i4i outline (PDF). Cannot be noted; any full application must use the approved purpose. |

Dated note, 24 October 2026: rows added from the Compliance gate (F9, B11).

| Path | Action on approval | Owner |
|---|---|---|
| `/workspace/out/lazoo-uclh-pack-2026-10-13/Lazoo validation study literature shortlist for approval.docx` | Dated note (it says "insomnia monitoring only") | Clinical Research |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/CHANGES-v0.5.md` | Check only. It is a change log, so a note is optional | Clinical Research |
| `/workspace/Company_Strategy_v2.docx` | Check only. The CEO decides whether a note is needed | CEO |
| `/workspace/CBT14-Intended-Purpose-DRAFT-2026-10-05.docx` | Flag for the CBT-14 register (section 5). It claims the device can "accurately predict core body temperature using AI", which contradicts decision 1 | Innovator |
| SOP-CMF-001, LAZ-QM-001, 05-layer2-samd/README.md, grants-layer2-nihr/README.md, app-ltd-shells/README.md, 04-templates/ISF-licensee.md, Lazoo-00-START-HERE.txt | Check only. Their purpose text is "TBD — pending Sara paste" | Clinical Research |

Dated note, 24 October 2026: after round 2, the pack Airlock brief is d0fce2be…, AIRLOCK-002 is 3faadb32…, the pack i4i redline is e3f21f67… and the pack protocol is 058b7a99… (now noted, Compliance gate F10). LAZ-IP-001 is 4ecef9aa… and LAZ-CL-001 is 6d7095e3…. The LAZ-CL-001 body is still byte-for-byte 9fb4dcc7. The hashes in the rows above are kept as recorded at the time.

## 5. CBT-14 device files (outside the Lazoo file; not edited)

These belong to the CBT-14 design file and are under Compliance review. They were not edited. Proposed note: the standard note, with "for Lazoo" after "intended-purpose amendment".

| Path | Current sha256 | Point for Compliance |
|---|---|---|
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/CBT-14-HR-SPO2-ADDENDUM-2026-10-24.md` | df23b1e418995ca860c7f7e159eb41748bf7f968f0ce8569f7360a623509a58e | Records Sara's 24 October decisions: heart rate as a wellness trend; claim stays at skin temperature trends; SpO2 deferred until bench tested; left side. Compliance to check that the hash it reviewed matches the current one. |
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/CBT-14-AXILLA-REDESIGN-2026-10-23.md` | 5b29a074625e84ad1c653f03f83144a8d2219e7bc088a96f9cfe1247c7589de9 | It records left side (decision 5), heart rate as a wellness trend (decision 2), and that heart rate is an input to CBT-14's core temperature estimator, with the filter running in "the CBT-14 companion phone app (app identity to be confirmed by Sara)". If that app is Lazoo, Lazoo would also host a core temperature estimate, which goes beyond the data-path lock (skin temperature and movement only) and the skin-temperature-trends claim. To be confirmed. |
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/brief.md` | 4b19352c92e80adcc4e55a395c5f7a567a4c3421016495bb2801f535218b2e0a | Names Lazoo as the planned data path for raw samples (as cited in the redesign). |

## 6. Checked and not affected

| Path | sha256 | Why not affected |
|---|---|---|
| `/workspace/lazoo-cmf/01-product/LAZ-VER-001-version-control.md` | f9c6a03b52ef5cda4f845b85a0d477f2ca29b47c9652b468dd23c1da2bb2f8b7 | Version pin; affected only when a build with heart rate is pinned. |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/CHANGES-v0.5.md` | ad03601a8c27185ddf16e83c87bedc86048296b28455d5427d6eb74b0a9a5c39 | Change log of v0.5; historical. |
| `/workspace/lazoo-cmf/03-studies/LAZ-VAL-001/00-protocol-outline.md` | 4ea8d47b4cb6eb89fd43bfb84555b3e73d0f2ca43296748ac5c09e205a2bc891 | Superseded by protocol v0.5. |
| `/workspace/lazoo-cmf/03-studies/LAZ-STUDY-REGISTER.md` | c3a59d4c4d8733a1ea823209b0b93aa4d1f09a0e6ac8f070151db1407de383e4 | No study adds heart rate. |
| `/workspace/lazoo-cmf/04-templates/ISF-licensee.md` | d3833d65f8b2ee582139b49e5af76a682c2ae059224be720ee0536e37f820c15 | Points to LAZ-IP-001 only. |
| `/workspace/lazoo-cmf/app-ltd-shells/03-compliance/LAZ-QM-001-quality-manual.md` | f40759f42459ec681d639a4cd95967bc0b4db120c7e7872c3a6322c04d9012bb | Points to LAZ-IP-001 only. |
| `/workspace/lazoo-cmf/uclh-feasibility-separate-sponsor/` (README, UCLH-PIS-v0.2-recut, UCLH-consent-v0.2-recut) | ab9550b7…, 72fa28e7…, cccad2dd… | Separate sponsor (UCLH); not an App Ltd document. |
| `/workspace/nhs-grok/sleep-diary-intended-purpose-and-sandbox.md` | 64e587bec57cd069261e603275c891349b27df74b42169e72958d19e15955c90 | Not a Lazoo controlled document. |
| Older versions: protocol v0.2–v0.4, DMP v0.2–v0.3, CRF v0.2 (md and docx) | — | Superseded. |
| `/workspace/compliance-reports/lazoo-baseline-2026-10-13-1350/` | — | A record; must not be edited. |
| `/home/box/agent-data/projects/laz-cmf/` | — | Not current; not treated as live. |
| `/cursor/stores/…` | — | Only a literature sweep mentions heart rate; not a controlled document. |

## 7. Not found

- No controlled file named LAZ-DS-001 exists. The rule is known only as a recorded standing rule (26 September 2026).
- No live markdown copies of the Airlock brief, the Airlock 002 one-page, the draft intended purpose or the I4I-001 shortlist; only docx (and a baseline record copy, not edited).
- The CBT-14 heart rate data protection impact assessment owned by Research Governance was not found; path to be added.
- Update, 24 October 2026 (round 2): the assessment is CBT-14-HR-DPIA-2026-10-24, version 0.2 (/workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 ba0e21101aaf89547e5ba3959e20a60a4a55eae10db7e34aa6e71f587477cdc5; docx sha256 597b30ef34008f3b493a5e1572f0411e76aed6b7ac53feb6d349c719591c9a9d), and is now cited in the files above. The LAZ-VAL-001 DMP docx copies in section 4 were regenerated from the updated markdown in round 2; see the change list.

  Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The "not found" entry and the round 2 update above are kept as recorded.

## 8. Round 4 update, following Sara's decisions at 17:07

Dated section, 24 October 2026. The sections above are kept as written.

### 8.1 New facts about the data

At 17:07 Sara approved the amendment in principle, pending Compliance (LAZ-IP-001-AMD-01, section 11). The decisions change the data that the amendment brings into Lazoo:

- Heart rate from CBT-14 is recorded over 24 hours, not overnight only.
- A core body temperature estimate from heart rate, using the Buller 2013 quadratic model, is proposed for circadian analysis. Whether it is a claimed output is open for Sara. It is a new derived health data item, and it conflicts with decision 1 of the CBT-14 addendum and with the CBT-14 data-path lock, which forbids naming or implying core body temperature.

  Dated note, 24 October 2026 (Compliance round 4, R4-10): "quadratic", as attributed to Buller 2013 here, is to be confirmed against the full paper and Looney and colleagues (2018); only the abstract has been checked.
- Heart rate is computed on the phone and leaves the phone only when the patient shares data for a report.
- The patient and the clinician both see heart rate in the shared report.
- Heart rate is hidden in pregnancy. Lazoo itself may still be used in pregnancy. Knowing that someone is pregnant, in order to hide heart rate, may itself be new health data; how it is known is to be confirmed.
- Northern Ireland and the European Union are in scope. This brings in the EU Medical Devices Regulation and CE marking there, and the EU General Data Protection Regulation for users in the European Union.

### 8.2 Data protection impact assessment

Research Governance has issued CBT-14-HR-DPIA-2026-10-24, version 0.3, which is pending Compliance review: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.md, sha256 d9c87e83928492d66fbf51a3553357107b0e9d2cf782ddcef1eea4e80a57d45f; Word version /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-2026-10-24.docx, sha256 9c969c98c500705fb249ebcccf41d27233ff9093362deb7badec492b7da7173f. The version 0.2 citations elsewhere in this register and in other files are kept as recorded at the time and have not been re-noted. Version 0.3 will need to reflect the facts in 8.1, in particular 24-hour recording, the core temperature estimate, the pregnancy hide and users in the European Union.

Dated note, 24 October 2026 (Compliance round 4, R4-7): Research Governance issued CBT-14-HR-DPIA-2026-10-24, version 0.4, at about 17:20 British Summer Time: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.4-2026-10-24.md, sha256 ddb77632d2cb7d95bda7c44037ffea12cf508f429832be8e082d98f51ff204e0. It supersedes version 0.3 as the working draft, is pending Compliance review and is not signed off. Version 0.3 (d9c87e83…) is kept unchanged.

Dated note, 24 October 2026 (round 6): the CBT-14 heart rate data protection impact assessment to cite now is CBT-14-HR-DPIA-2026-10-24, version 0.5.1: /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.md (sha256 41861d51f52ac2ff729ca0daffa39eb94f7d5c6486f0957d39f87fb7f49f53ea), with its Word copy /workspace/out/governance-2026-10-24/CBT-14-HR-DPIA-v0.5.1-2026-10-24.docx (sha256 c5b924fbec1eb8c957b14f15e7525e18c2a3204eecc55d9aa817205856e3cc2d). Version 0.5.1 has been passed by Compliance as a draft for sign-off, not approved, with sign-off pending Sara's 25 October answers (Compliance re-check of about 17:42 London time, /workspace/compliance-reports/cbt14-hr-dpia-gate-2026-10-24.md). The version 0.3 paragraph and the version 0.4 note above are kept as recorded.

### 8.3 CBT-14 files whose hashes have moved

The CBT-14 files in section 5 have been changed by other work since the rows above were written. At about 17:20 British Summer Time on 24 October 2026 the current hashes were:

| Path | sha256 in section 5 | Current sha256 |
|---|---|---|
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/CBT-14-HR-SPO2-ADDENDUM-2026-10-24.md` | df23b1e418995ca860c7f7e159eb41748bf7f968f0ce8569f7360a623509a58e | cb4a401f837b74e1cad4d2f828c78d2bf323eacf4e1897a90d86ea0e3ff04c19 |
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/CBT-14-AXILLA-REDESIGN-2026-10-23.md` | 5b29a074625e84ad1c653f03f83144a8d2219e7bc088a96f9cfe1247c7589de9 | 19edf6c15acb1b78a2362a9a74371dd5f154fcacb983965bc5218ac137025179 |

They were not edited in this round. Decision 1 in the addendum still reads that the core-temperature estimate "stays a research output and is not claimed".

### 8.4 Documents that will need a note if the amendment is approved

In addition to the rows in sections 2 to 5, these will need attention once Sara has decided on core temperature and the amendment is approved:

| Path or document | Why | Owner |
|---|---|---|
| `/home/box/agent-data/projects/shc-product-designs/devices/cbt-14/proto-ready/smaller/mock-C-S3/charge-dock/DATA-PATH.md` (sha256 8cda6bb3431ef857facd36b012202723f395692d426edaa31aa92df4acfc059d) and any other copies | Its core temperature row reads "Forbidden — do not name or imply core body temperature on this path". A core estimate in Lazoo conflicts with it | Innovator, with Compliance |
| CBT-14 addendum, decision 1 | The core estimate "stays a research output and is not claimed" | Sara |
| LAZ-VAL-001 data dictionary and consent form | 24-hour heart rate, the core estimate and the pregnancy hide are new data items, if any enter the study | Clinical Research |
| LAZ-DPIA-001 and CBT-14-HR-DPIA-2026-10-24 | New data items in 8.1, and EU users | Research Governance |
| Airlock ethics note and the i4i documents | Any description of Lazoo's data or outputs | Clinical Research |
| LAZ-CL-001 | To be revised under change control, citing UK Rule 10 for Great Britain and EU Rules 10 and 11 for Northern Ireland and the European Union (LAZ-CL-001-REV-01, section 9) | Compliance |

Dated note, 24 October 2026 (Compliance round 4, R4-8): section 8.1, second bullet, is answered: Sara's answer 1 puts the core temperature estimate in the product, so the conflicts with addendum decision 1 and with DATA-PATH.md need dated notes from their owners rather than a decision. In section 8.4, "the i4i documents" means the pack copy /workspace/out/lazoo-uclh-pack-2026-10-13/LAZ-i4i-alignment-redline.docx (e3f21f67…), which matches the Drive copy; the 12 October 2026 redline in /workspace/out/governance-2026-10-12/ (c5087410…) is a historical record and is not the current i4i text.

### 8.5 New file

- `/workspace/lazoo-cmf/01-product/LAZ-IP-001-base-purpose-extract-2026-10-24.md`: the base intended-purpose wording, copied word for word from LAZ-IP-001 and from the draft of 12 October 2026, with the proposed amended statement, for Sara.
