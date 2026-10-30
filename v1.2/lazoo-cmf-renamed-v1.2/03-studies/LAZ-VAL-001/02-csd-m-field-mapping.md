Change note 3 October 2026 (VAL-001 HOLD fix): These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays TBD — pending Sara paste. Pack stays OPEN. The 28 August 2026 date below is kept.

# LAZ-VAL-001 — CSD-M to Lazoo field mapping

**Document ID:** LAZ-VAL-001-MAP  
**Version:** 0.1  
**Date:** 28 August 2026  
**Status:** Filed for later protocol work. Not a licensed copy of the CSD-M form.

Comparator: Consensus Sleep Diary–Morning (CSD-M), Carney et al. *Sleep* 2012;35:287–302. doi:10.5665/sleep.1642

Do **not** paste the copyrighted CSD-M layout or verbatim stems into the TMF or the app until a Carney / ePROVIDE industry licence is on file. This document is citation + field map + scoring only.

## Scoring lock (SAP)

Primary TST is **calculated**, not CSD-M item 8 (subjective estimate).

`TWAK` = `out_of_bed` − `wake` (or item 6b TASAFA if the SAP prefers that)  
`TST` = (`out_of_bed` − `sleep_attempt`) − `SOL` − `WASO` − `TWAK`  
`TIB` = `out_of_bed` − `in_bed`  
`SE` = `TST` / `TIB` × 100  

These TST, SOL, WASO, and SE formulas are draft study arithmetic for this agreement study. They are not the product claim. The product measure stays TBD — pending Sara paste.


`in_bed` (item 1) and `sleep_attempt` (item 2) must stay **separate**. Naps do not enter nocturnal TST. WASO is the **total** of awakenings excluding the final wake.

Maich et al. 2018 uses TIB from item 1 and can count the in-bed-not-trying interval as sleep. Reed & Sacco 2016 flag that. VAL-001 uses the formula above unless CI signs a Maich variant.

## Mapping

| CSD-M | Construct | Lazoo field | VAL-001 | v1 gap? |
|---|---|---|---|---|
| Date | Morning date | `diary_date` | Admin | Add |
| 1 | Into bed | `in_bed` | TIB | Named |
| 2 | Tried to sleep | `sleep_attempt` | SOL start, TST | Named; keep distinct from 1 |
| 3 | Time to fall asleep | `SOL` (duration). `sleep_onset` derived = attempt + SOL | Secondary SOL | Duration, not an asked clock |
| 4 | Number of wakes (excl. final) | `awakenings_n` | Descriptor | Named |
| 5 | Total length of those wakes | `WASO` = sum `awakenings_detail[].duration` excl. final | Secondary WASO; feeds TST/SE | CSD is a total; array must sum |
| 6a | Final awakening | `wake` | TWAK, TST, SE | Named |
| 6b | Trying after final wake | `twak_try_min` | Optional TWAK | Gap |
| 6c/6d | Earlier than planned | `ema_yn`, `ema_min` | Not an index | Gap |
| 7 | Out of bed for the day | `out_of_bed` | TIB, TWAK, TST, SE | Named |
| 8 | Estimated total sleep | `tst_subjective` | Exploratory vs TST; **not primary** | Gap |
| 9 | Sleep quality (Very poor → Very good) | `sleep_quality` | Core construct, not an index | Gap |
| 10 | Rested/refreshed | `restedness` | Not an index | Gap |
| 11a/b | Nap/doze count and duration | `naps[]` | Not nocturnal TST | Named; include dozing |
| 12–14 | Alcohol, caffeine, sleep meds | `alcohol_n/last`, `caffeine_n/last`, `sleep_med_*` | Covariates | Gap unless already in v1 lifestyle text |
| 15 | Comments | `notes` | — | Not collected in LAZ-VAL-001; dropped from the CRF and Lazoo export. Licence terms to be confirmed. |

## Licence (blocker)

Copyright: Dr Colleen Carney. Not-for-profit unaltered use with citation is described on the Carney lab / consensussleepdiary.com pages. **Industry / for-profit use needs written permission** (fees are charged). SHC/Lazoo is commercial. Request: https://drcolleencarney.com/sleep-diary/

Safe now: this map, DOI, SAP formulae. Not safe until licensed: filing Figure 2 / the PDF in the TMF, or shipping verbatim CSD stems in Lazoo.

UK wording tweaks (soda → soft drink, oz → ml) are a linguistic adaptation; agree with the copyright holder if stems change.

## Sources

- Carney CE et al. Sleep 2012;35:287–302. doi:10.5665/sleep.1642
- Maich KHG et al. Behav Sleep Med 2018;16:117–134. doi:10.1080/15402002.2016.1173556
- Reed DL, Sacco WP. J Clin Sleep Med 2016;12:263–266. doi:10.5664/jcsm.5498
- ePROVIDE: https://eprovide.mapi-trust.org/instruments/consensus-sleep-diary
