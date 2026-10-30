# LAZ-VER-001 — Product version log (research-relevant)

**Document ID:** LAZ-VER-001  
**Version:** 0.1  
**Date:** 28 August 2026

Only versions that could have been used to collect research data belong here. Build notes that do not change data fields, consent, or export stay with engineering.

| App version | Platforms | Date in research use | Notes | Studies |
|---|---|---|---|---|
| MVP (TestFlight / APK) | iOS TestFlight; Android APK | Pre-launch | Restricted testing. Confirm whether any research consent was taken. If no, do not treat those data as LAZ-RWE-001. | none yet |
| v1 restricted research release | iOS Unlisted; Play closed testing | not yet | Must show four consent toggles, reserved vital/AI fields empty, wearable/CBT-14 stubs non-breaking | VAL-001, RWE-001 |

## Minimum evidence before a version is “research-ready”

- Intended-purpose text matches LAZ-IP-001
- Four consent toggles stored with wording version and timestamp
- Sleep log export JSON + CSV with raw timestamps
- Append-only change history for diary edits (ePRO audit trail)
- `study_link` field available (study ID, site, consent pack version)
- Release note filed in this folder
