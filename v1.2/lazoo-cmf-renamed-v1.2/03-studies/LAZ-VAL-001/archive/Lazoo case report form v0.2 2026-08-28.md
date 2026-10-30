> **Superseded on 12 October 2026 by version 0.3** (`LAZ-VAL-001-CRF-v0.3.md (now named lazoo-cmf/03-studies/LAZ-VAL-001/Lazoo case report form v0.3 2026-10-12.md, 30 October 2026)` and `LAZ-VAL-001-CRF-v0.3.docx (now named lazoo-cmf/app-ltd-shells/01 Clinical research/filled/Lazoo case report form v0.3 2026-10-12.docx, 30 October 2026)`). Kept on file for history.

Change note 11 October 2026: Aligned to protocol LAZ-VAL-001 version 0.4. Earlier named university site codes are removed; the only site reference is the default volunteer code or partner site (to be confirmed). Exclusion criterion 6 now matches the protocol. Earlier dates in this file are kept.

Change note 5 October 2026: Sara McNeillis lock. Working position is MHRA SaMD Class IIa (class 2a), one layer only. This replaces the 3 October 2026 Class IIb working position. Clinical claims, purpose, pregnancy in/out, and Gantt claim slots left as “to be confirmed by the sponsor.” Pack stays OPEN. Earlier dates in this file are kept.

Change note 3 October 2026 (VAL-001 HOLD fix): The adverse-event section is a study log. The diagnostic-vigilance purpose and the manufacturer incident-report sentence are removed. Clinical claims stay to be confirmed by the sponsor. These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays to be confirmed by the sponsor. Pack stays OPEN. Earlier dates in this file are kept.

# LAZ-VAL-001 Case Report Form (CRF) booklet v0.2

**Document ID:** LAZ-VAL-001-CRF
**Version:** 0.2 draft
**Date:** 28 August 2026
**Sponsor:** ~~Sleep and Health Clinic App Ltd~~ SHC Sleep Solutions Limited (company number 12467350; then named Sleep and Health Clinic App Limited, renamed 27 October 2026) (12467350)
**Protocol:** LAZ-VAL-001 v0.4
**Research contact:** admin@sleepandhealth.org

**Intended purpose (verbatim):**

> To be confirmed by the sponsor.

This CRF does **not** reproduce Consensus Sleep Diary–Morning question stems. CSD-M constructs are transcribed as clock times, durations, counts, and ratings. Verbatim stems and the Carney PDF must not be filed until an industry licence from Dr Colleen Carney is on file (Carney et al., Sleep 2012;35:287–302. doi:10.5665/sleep.1642).

This CRF does not fill a clinical claim. Clinical claims: to be confirmed by the sponsor. Do not add scores, flags, CBT-I, or phenotyping. Reserved empty: vitals.core_temp, vitals.wearable, ai_event.

Participant ID format: `LAZ-VAL-001-NNN`. Completer: ≥10 of 14 paired mornings evaluable for calculated TST.

## Participant ID

*Purpose:* Identify the person without using NHS numbers or clinic hospital stickers.

Complete at screening. Never reuse an ID. If a number is allocated in error, retire it and file a note.

| Field | Entry | Rules |
| --- | --- | --- |
| Participant ID | LAZ-VAL-001-___ | Three digits, 001–999 |
| Initials (optional, local log only) | ___ | Not in the analysis file |
| Date of consent | dd/mm/yyyy | Must match consent record |
| Consent-pack version shown |  | Store the version, not only yes/no |
| Toggle 1 (use diary) on? | Y / N | Required |
| Toggle 2 (share with clinician) on? | Y / N / not asked | Optional; not required for VAL-001 |
| Toggle 3 (research) on? | Y / N | Required |
| Toggle 4 (future clinical tools / models) on? | Y / N | Default N; not required |
| Consent method | Wet ink / REC-approved remote |  |
| App version issued (LAZ-VER-001 pin) |  | [GAP] pin outstanding — do not issue until pinned |
| Platform | iOS Unlisted / Android closed testing | Not a public store |
| Study code / login issued | Y / N  date ______ |  |
| Site code | APP-LTD-VOL | Default. Partner site (to be confirmed): a site code is issued only after the site agreement is signed and the site is opened by the sponsor. |

Staff initials _____  Date _____


## Visit Details

*Purpose:* Log screening/training, the 14 mornings, and day-15 close-out.

### Visit 0 — screen and train

| Item | Entry |
| --- | --- |
| Visit date | dd/mm/yyyy |
| Mode | In person / video / telephone + e-consent |
| Inclusion criteria all yes? | Y / N  (if N, do not enrol) |
| Exclusion criteria all no? | Y / N  (if N, do not enrol) |
| Training completed (CSD-M then Lazoo; in_bed ≠ sleep_attempt)? | Y / N |
| CSD-M source format issued | Paper construct worksheet / licensed PDF (only if Carney licence on file) / locked PDF without verbatim stems |
| Participant instructed: CSD-M first, then Lazoo, same sitting | Y / N |
| Staff initials |  |

### Mornings 1–14 — pairing log (one row per morning)

Evaluable for primary TST only if both diaries have sleep_attempt, SOL, WASO, wake, out_of_bed, internally consistent. Mark Lazoo-first as a deviation; not primary-evaluable by default.

| M | Diary date | CSD-M done? | Lazoo done? | Order CSD then Lazoo? | TST fields complete both? | Late (>24 h)? | Deviation code | Staff |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 2 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 3 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 4 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 5 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 6 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 7 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 8 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 9 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 10 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 11 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 12 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 13 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |
| 14 |  | Y/N | Y/N | Y/N | Y/N | Y/N |  |  |

N evaluable paired mornings _____   Completer (≥10)? Y / N

Deviation codes: D1 Lazoo first; D2 missed CSD-M; D3 missed Lazoo; D4 missing TST field; D5 clocks inconsistent; D6 other (file note).

### Day 15 — close-out

| Item | Entry |
| --- | --- |
| Date | dd/mm/yyyy |
| CSD-M source returned / photographed | Y / N   file log ID ______ |
| Lazoo export JSON received | Y / N   file ID ______ |
| Lazoo export CSV received | Y / N   file ID ______ |
| App version on export matches pin | Y / N / pin not yet issued |
| SUS completed | Y / N |
| Three structured questions completed | Y / N |
| Optional interview | Y / N / declined |
| Toggle 3 withdrawal requested? | Y / N  (if Y, stop future research use; locked analysis set rule as PIS) |
| Continues Lazoo under toggle 1 only? | Y / N |
| Staff initials |  |


## Eligibility

*Purpose:* Tick protocol criteria. This is not a diagnostic interview.

### Inclusion — all must be Yes

| # | Criterion | Y/N |
| --- | --- | --- |
| 1 | Aged ≥18 years at consent |  |
| 2 | Able to read and complete diaries in English |  |
| 3 | Able and willing to use restricted Lazoo (iOS Unlisted or Play closed testing) for 14 mornings |  |
| 4 | Willing to complete CSD-M then Lazoo each morning for 14 consecutive mornings, same sitting |  |
| 5 | Able to give informed consent; contact via admin@sleepandhealth.org / PIS phone |  |
| 6 | Toggle 1 on and toggle 3 on (toggle 4 not required) |  |

### Exclusion — all must be No to enrol

| # | Criterion | Y/N (Yes = exclude) |
| --- | --- | --- |
| 1 | Unable to give informed consent |  |
| 2 | Current other sleep-diary research that would duplicate the same nights |  |
| 3 | CI/delegate judges two diaries for 14 days inappropriate (file note; not an app diagnosis) |  |
| 4 | Unable to complete entries in English |  |
| 5 | No compatible device / unwilling to use unlisted or closed-testing app |  |
| 6 | Identified through any NHS organisation's patient lists, or a patient of Sleep & Health Clinic Ltd (08904119) |  |

Not recruited through any NHS organisation's patient lists (including UCLH) or from Sleep & Health Clinic Ltd (08904119) patients.

Eligible to enrol? Y / N     Staff _____  Date _____

If ineligible: ID still retired; do not recycle.


## Medical History

*Purpose:* Collect only non-diagnostic background needed to describe the sample. Do not code diseases or imply Lazoo is a diagnostic.

This study does not take a diagnostic medical history. Do not attach clinic letters, problem lists, or NHS records. Do not write suspected diagnoses on this form.

| Field | Entry | Notes |
| --- | --- | --- |
| Date of birth (or age in years if DOB not required by PIS) |  | Analysis file uses age or month/year as DPIA allows |
| Sex | Female / Male / Prefer not to say / Other: ____ |  |
| Currently keeps a sleep diary? | Y / N   paper / other app / none | Descriptor |
| Shift work in the last 14 days? | Y / N | Affects diary interpretation; not a diagnosis |
| Usual main sleep is at night? | Y / N / varies |  |
| How heard about the study | Invitation / university conversation / other: ____ | Not an NHS trust referral pathway |

Lifestyle items that exist on CSD-M (alcohol, caffeine, sleep medication) are collected on the daily construct worksheet as user-reported diary fields, not as a coded medication history.

If the participant volunteers a health condition, record only if needed for a safety file note. Do not enter it as a Lazoo output.


## Assessments

*Purpose:* Transcribe CSD-M constructs, confirm Lazoo export fields, and capture usability — without CSD-M stems and without scores generated by the app.

### Daily construct worksheet (CSD-M source → CRF)

One worksheet per morning. Copy values from the source document. Do not paste copyrighted question wording onto this form. Units: clock times 24-hour HH:MM; durations in minutes. If a licensed CSD-M PDF is later filed, transcribe from it the same way.

Participant ID ______   Morning number __ / 14   Diary date __________   Transcribed by _____ date _____   Second entered by _____ date _____   Discrepancy? Y/N log ID ____

| Construct (not a stem) | Field code | Value | Missing? |
| --- | --- | --- | --- |
| Clock time into bed | in_bed | HH:MM  date if previous day: ______ | Y/N |
| Clock time tried to sleep | sleep_attempt | HH:MM  date if previous day: ______ | Y/N |
| Time to fall asleep (duration) | SOL | minutes ______ | Y/N |
| Number of wakes excluding final | awakenings_n | integer ______ | Y/N |
| Total length of those wakes | WASO | minutes ______ | Y/N |
| Clock time of final awakening | wake | HH:MM ______ | Y/N |
| Minutes trying after final wake (optional) | twak_try_min | minutes ______ / not collected | Y/N |
| Earlier than planned (optional) | ema_yn / ema_min | Y/N / minutes ______ / not collected | Y/N |
| Clock time out of bed for the day | out_of_bed | HH:MM ______ | Y/N |
| Subjective estimated total sleep (item 8 construct) | tst_subjective | minutes ______ | Y/N — exploratory; NOT primary |
| Sleep quality (very poor → very good) | sleep_quality | category as collected ______ | Y/N |
| Rested / refreshed | restedness | category as collected ______ | Y/N |
| Nap or doze count and duration | naps[] | count __  total minutes __ | Y/N — not nocturnal TST |
| Alcohol / caffeine / sleep medication (user report) | alcohol_* / caffeine_* / sleep_med_* | text/count as collected | Y/N |
| Comments | notes |  |  |

### Calculated fields (do not ask the participant; compute both diaries the same way)

- TWAK = out_of_bed − wake
- TST = (out_of_bed − sleep_attempt) − SOL − WASO − TWAK   ← PRIMARY
- TIB = out_of_bed − in_bed
- SE = TST / TIB × 100
- sleep_onset (derived) = sleep_attempt + SOL

These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays to be confirmed by the sponsor.

Central programmer computes these on the analysis file. Optional calculator check on the CRF: TST minutes ______  consistent clocks? Y/N  TST ≥ 0? Y/N

### Lazoo export receipt (same morning)

Do not re-type the whole diary if the export is the source. File the JSON/CSV and record:

| Check | Y/N |
| --- | --- |
| Export contains diary_date matching this morning |  |
| in_bed present and distinct from sleep_attempt |  |
| sleep_attempt, SOL, WASO, wake, out_of_bed present |  |
| Raw timestamps present (not chart-only) |  |
| app_version, study_id=LAZ-VAL-001, consent_pack_version present |  |
| If any field edited: audit who/what/when and original value retained |  |
| ai_event / wearable / core_temp unused (empty) as required for v1 |  |

### Day 15 — System Usability Scale (Brooke, 1996)

Instrument: 10 items, 1 = strongly disagree to 5 = strongly agree. Score later 0–100. Cite Brooke 1996. This is usability of the app for the diary task in this study. Clinical claims: to be confirmed by the sponsor.

| Item | 1 | 2 | 3 | 4 | 5 |
| --- | --- | --- | --- | --- | --- |
| 1. I think that I would like to use this system frequently |  |  |  |  |  |
| 2. I found the system unnecessarily complex |  |  |  |  |  |
| 3. I thought the system was easy to use |  |  |  |  |  |
| 4. I think that I would need the support of a technical person to be able to use this system |  |  |  |  |  |
| 5. I found the various functions in this system were well integrated |  |  |  |  |  |
| 6. I thought there was too much inconsistency in this system |  |  |  |  |  |
| 7. I would imagine that most people would learn to use this system very quickly |  |  |  |  |  |
| 8. I found the system very cumbersome to use |  |  |  |  |  |
| 9. I felt very confident using the system |  |  |  |  |  |
| 10. I needed to learn a lot of things before I could get going with this system |  |  |  |  |  |

SUS total (0–100, calculated later) ______

### Three structured questions (original to VAL-001)

1. After training, could you complete the Lazoo morning diary without help?  Y / N    Free text: __________
2. Was anything in Lazoo confusing compared with the paper or PDF diary?  Free text: __________
3. Would you be willing to use Lazoo for a longer research period?  Y / N    Free text: __________

Interview notes (optional; not a clinical assessment): ________________________________

Actigraphy: not in protocol v0.4 — no CRF page.


## Adverse Events

*Purpose:* Study log for distress or other events that come to attention. Clinical claims: to be confirmed by the sponsor.

Clinical claims: to be confirmed by the sponsor. Use this log for distress while keeping diaries, study-procedure events, or other events the CI becomes aware of from consent to close-out.

Signpost: GP, NHS 111, Samaritans 116 123. Do not use any NHS or clinic PALS line on ~~App Ltd~~ SHC Sleep Solutions Limited (short form for company number 12467350, renamed 27 October 2026) sheets. Notify sponsor at admin@sleepandhealth.org within 24 hours of CI awareness of a serious event.

| AE# | Onset date | Description | Outcome | Related to study procedures? Y/N/unk | Serious? Y/N | Signposted? Y/N | CI initials |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 |  |  |  |  |  |  |  |
| 2 |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |

None reported for this participant: tick _____  Staff _____  Date _____

Vigilance, and whether this study is a UK MDR clinical investigation, are not decided while intended purpose is to be confirmed by the sponsor.


## Signatures

*Purpose:* Attribute entries and lock the booklet at close-out.

| Role | Name | Date | Signature |
| --- | --- | --- | --- |
| Person completing pairing log |  |  |  |
| CSD-M first transcriber |  |  |  |
| CSD-M second transcriber / verifier |  |  |  |
| Person filing Lazoo export |  |  |  |
| CI or delegate — close-out review |  |  |  |

I confirm that this CRF contains no verbatim unlicensed CSD-M stems, no diagnostic interpretation, and no NHS-site enrolment.

Queries: log ID ______  resolved Y/N  date ______

Booklet complete / withdrawn early (reason) ________________

**[GAP]** Wet-ink or 21 CFR Part 11-equivalent eCRF system not yet chosen. Paper CRF is the default until the DMP names an eCRF vendor.
