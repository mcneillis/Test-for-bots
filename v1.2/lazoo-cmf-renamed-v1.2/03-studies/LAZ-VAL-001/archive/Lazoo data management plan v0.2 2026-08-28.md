> **Superseded on 11 October 2026 by version 0.3** (`LAZ-VAL-001-DMP-v0.3 (now named lazoo-cmf/app-ltd-shells/01 Clinical research/filled/archive/Lazoo data management plan v0.3 2026-10-11.docx, 30 October 2026).md` and `LAZ-VAL-001-DMP-v0.3 (now named lazoo-cmf/03-studies/LAZ-VAL-001/archive/Lazoo data management plan v0.3 2026-10-11.md, 30 October 2026).docx (now named lazoo-cmf/app-ltd-shells/01 Clinical research/filled/archive/Lazoo data management plan v0.3 2026-10-11.docx, 30 October 2026)`). Kept on file for history.

Change note 11 October 2026: Aligned to protocol LAZ-VAL-001 version 0.4. Earlier named university site codes and organisations are removed; the only site reference is the default volunteer code or partner site (to be confirmed). The partner site's processor role, Prolific as the default recruitment route, the rule that no identifiable free text leaves ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited and the rule that any outbound share needs a current data note are set out in protocol version 0.4 and will be added to the next version of this plan. Earlier dates in this file are kept.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “to be confirmed by the sponsor.” Pack stays OPEN. Earlier dates in this file are kept.

Change note 3 October 2026 (VAL-001 HOLD fix): Removed the later separate SaMD file and the instruction to freeze a copy. There is one product. Nothing is frozen. Pack stays OPEN. These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays to be confirmed by the sponsor. Earlier dates in this file are kept.

# LAZ-VAL-001 Data Management Plan v0.2

**Document ID:** LAZ-VAL-001-DMP
**Version:** 0.2 draft
**Date:** 28 August 2026
**Sponsor / controller:** ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026) (12467350)
**Protocol:** LAZ-VAL-001 v0.4
**Research contact:** admin@sleepandhealth.org

> To be confirmed by the sponsor.

Companion to the protocol and CRF. Not an AI training plan. Toggle 4 is off for the default VAL-001 population. AI Validation Report and CER are on hold and must not be written from these data.

## Data Sources

*Purpose:* Name every source that will feed the analysis file, and the sources that must not.

| Source | What is captured | System of record | Notes |
| --- | --- | --- | --- |
| Lazoo v1 restricted app | Self-reported sleep/lifestyle log, consent toggles, app_version, OS, study_link, append-only edit history | App backend (vendor [GAP] not contracted in this DMP) | Apple Unlisted / Play closed testing. Raw timestamps. No scores or flags. |
| CSD-M comparator | Construct values (clocks, durations, counts, ratings) for pairing | Paper or locked PDF source + CRF transcription | Cite Carney 2012 doi:10.5665/sleep.1642. [GAP] industry licence from Colleen Carney required before verbatim stems or publisher PDF enter the TMF. |
| CRF booklet | Eligibility, pairing log, SUS, structured questions, AE/distress, signatures | Paper CRF until eCRF named | Participant ID LAZ-VAL-001-NNN |
| Consent record | Toggle 1–4, wording version, timestamp or wet-ink, withdrawal | Consent file + in-app store | VAL-001 requires 1 and 3; 4 default off |
| Export receipts | JSON + CSV file IDs, date, who pulled | Study folder on ~~App Ltd~~ SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026) storage |  |

### Not data sources for VAL-001

- Not recruited through any NHS organisation's patient lists (including UCLH) or from Sleep & Health Clinic Ltd (08904119) patients.
- NHS electronic records, or clinic notes of Sleep & Health Clinic Ltd (08904119).
- Datasets from studies run by other sponsors.
- Wearable / core-temperature streams (reserved empty; actigraphy switched off).
- ai_event or any model output.
- National registry feeds; CBT-I platforms; phenotyping tools.
- Unlicensed CSD-M PDF images used as if they were the CRF.

Pairing key: participant ID + diary_date. Site code default APP-LTD-VOL. Partner site (to be confirmed): a site code is issued only after the site agreement is signed and the site is opened by the sponsor.


## Collection

*Purpose:* Describe how paired mornings are captured so Lazoo cannot auto-fill CSD-M, and how TST is derived.

### Order of capture

Each morning the participant completes CSD-M first, then Lazoo, in the same sitting. Training states that in_bed and sleep_attempt are two clocks. Lazoo-first is a deviation and is not primary-evaluable by default.

### Lazoo

- Entry on the participant’s device; study code required.
- Fields as data dictionary / protocol construct map.
- Edits allowed; append-only audit (who / what / when); original retained (ALCOA+).
- Export JSON + CSV at close-out (and on CI request). Charts are not a substitute for raw timestamps.
- Reserved empty in v1: vitals.core_temp[], vitals.wearable[], ai_event[].

### CSD-M

- Source: construct worksheet, or licensed instrument once the Carney industry licence is filed.
- Transcription onto CRF daily construct page. Double entry, or single entry plus photograph with a file log.
- Discrepancies logged and resolved before database lock.

### Derived quantities (compute on export / analysis file; store raw clocks too)

- TWAK = out_of_bed − wake
- TST = (out_of_bed − sleep_attempt) − SOL − WASO − TWAK  (PRIMARY; not CSD-M item 8)
- TIB = out_of_bed − in_bed
- SE = TST / TIB × 100
- sleep_onset = sleep_attempt + SOL

These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays to be confirmed by the sponsor.

A primary-evaluable paired morning has sleep_attempt, SOL, WASO, wake, out_of_bed on both diaries, internally consistent, TST ≥ 0. Naps do not enter nocturnal TST. WASO excludes the final wake.

### Usability

SUS (Brooke 1996) and three structured questions on the CRF at day 15. Entered once; no in-app score shown to the participant as a clinical output.

### Consent collection

Toggle wording version stored. Withdrawal of toggle 3 stops future research use; PIS states that a locked analysis set is not unpicked. Toggle 4 not collected on by default.

**[GAP]** eCRF vendor and 21 CFR Part 11 / equivalent validation not chosen. Paper CRF + Lazoo export is the default collection model.


## Storage

*Purpose:* Keep identifiable files on ~~App Ltd~~ SHC Sleep Solutions Limited-controlled storage and keep the analysis file pseudonymised.

| Store | Contents | Access | Status 28 Aug 2026 |
| --- | --- | --- | --- |
| ~~App Ltd~~ SHC Sleep Solutions Limited-controlled drive / folder (to be authorised) | Identifiable CRF scans, consent, CSD-M source photos, export receipts | CI, named delegates, archivist | [GAP] durable location not yet authorised (see LAZ-ARC-001) |
| Lazoo backend | Account, diary, consent toggles, audit trail | Need-to-know engineering + CI delegate | [GAP] processor contract / DPA not filed in this DMP |
| Analysis file | Pseudonymised pairing of Lazoo + CSD-M constructs, derived TST/SOL/WASO/TIB/SE, SUS | Statistician (when appointed) + CI | Not built until first extract |
| CMF / TMF (this file set) | Protocol, DMP, CRF template, logs; no bulk identifiable diaries in chat | CMF manager, CI, auditors, REC on request | Open |

Controller: ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited. Sleep & Health Clinic Ltd (CQC clinic, 08904119) is a different company sharing a registered-office address; it is not the controller for VAL-001 and must not receive identifiable VAL-001 exports by default.

Do not send participant-identifiable files by open email or chat. Default residency: UK. No extra-UK transfer without a documented mechanism.

Key: participant ID on CRF and exports. Initials, if used on a local log, stay off the analysis file. No NHS number in this version.

Back-up: [GAP] backup frequency and restore test not documented. Must be in place before identifiable collection.


## Quality Control

*Purpose:* Specify checks that support measurement agreement, not diagnostic accuracy.

- Consent: 100% of completers have toggles 1 and 3, wording version, and date.
- Pairing log: every morning coded evaluable or not, with deviation code if needed.
- CSD-M transcription: double entry (or photo + single entry) before lock; discrepancy log closed.
- Lazoo: export contains raw timestamps; in_bed distinct from sleep_attempt; audit trail on edits; v1 reserved fields empty.
- Derived TST recomputed independently from raw clocks in the analysis file; do not trust a pre-computed app TST if one is ever present (v1 should not display a clinical score).
- Range checks: SOL, WASO, TWAK ≥ 0; out_of_bed ≥ wake ≥ sleep_attempt; TIB > 0 for SE; flag TST < 0 or > TIB for query — queries are data queries, not clinical flags to the participant.
- SUS: 10 items present or missingness explained; score calculated centrally.
- App version on each export matches the LAZ-VER-001 pin. [GAP] pin outstanding.

Database lock: CI + data manager (when named) sign that pairing, transcription, and export receipts are complete. Unlock only with a file-noted reason.

No QC aimed at “correcting” diaries toward a diagnosis. Queries go to source (participant worksheet or Lazoo audit), not to a clinician interpretation module.


## GDPR

*Purpose:* State controller, intended lawful basis, and outstanding DPIA/DPO gaps.

Controller: ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited (12467350), 32 Watford Road, Northwood HA6 3NT. Contact: admin@sleepandhealth.org.

Sleep diary content may be special-category health data. Clinical claims: to be confirmed by the sponsor.

Intended lawful basis (to be confirmed in the DPIA): UK GDPR Article 6(1)(a) consent for the research copy (toggle 3), with Article 9(2)(a) explicit consent where special-category data are processed. A private company should not assume Article 6(1)(e) public task. Clinic care at Sleep & Health Clinic Ltd is a different processing purpose and a different controller.

**[GAP]** DPIA is a placeholder. DPO not named. Processor contracts (hosting, any eCRF, transcription) not filed. Do not start identifiable collection until these are in place.

Rights: access and rectification via admin@sleepandhealth.org. Withdrawal of toggle 3 stops future research use; data already in a locked analysis set may not be pulled back (PIS must say this in plain language). Toggle 1 withdrawal = stop using the app; local deletion/export offered as the live app allows.

Toggle 4 (future clinical tools / models) is off for VAL-001 unless an amendment says otherwise. NHS-identifiable data are not collected. Do not train a future model on VAL-001 without toggle 4, a protocol that says so, and ethics.

No NHS or clinic PALS line as the privacy contact. No personal Gmail as the controller contact.

Data-protection impact of adding the partner site (to be confirmed) will be assessed in an updated DPIA and set out in the site agreement before the site is opened. The partner site acts as processor for study data on the sponsor's documented instructions.


## Retention

*Purpose:* Set clocks that match SOP-CMF-001 and do not import the CTIMP 25-year rule by default.

Essential records (protocol, PIS/consent, CRF, exports as archived, DMP, approvals, insurance once held): at least 10 years after the signed study report, or longer if a licence contract or REC requires it.

Participant-level research data: the period stated in the PIS / DPIA (default aligned to 10 years unless the DPIA shortens or extends it).

This is not a CTIMP; the 25-year statutory TMF clock does not apply by default.

Destruction: after the retention clock, CI + archivist record what was destroyed. Consent records are not destroyed earlier than the data they explain.

There is one product. VAL-001 is not rewritten into a second file. Nothing in this plan is frozen. Pack stays OPEN. Do not archive an AI Validation Report or CER against this DMP.

**[GAP]** Named archivist not appointed (CI holds the duty). Durable storage location not authorised. Research insurance certificate not on file — retention of that certificate starts when it exists.

End of DMP LAZ-VAL-001 v0.2 (28 August 2026).
