# Adult sleep literature sweep v1.0

**Search date:** 2 November 2026  
**Window:** 26 October 2026 to 2 November 2026  
**Scope:** adults, sleep medicine, including adult bruxism and sleep bruxism  
**Status:** research only. Nothing has been sent, paid for, published or uploaded. Embase and Scopus were not searched.

This pack reports records that were actually retrieved. Every journal article below has a PubMed identifier and a DOI taken from that record’s own article identifiers. Findings are taken from the abstract retrieved that day. Full texts were not purchased. Where an abstract is ambiguous, incomplete or at odds with its own numbers, that is marked for verification rather than smoothed over.

---

## 1. The week in brief

PubMed acquired 156 adult sleep records between 26 October and 2 November 2026. The item with the widest bearing on UK practice is a joint European Respiratory Society and European Sleep Research Society guideline on continuous positive airway pressure (CPAP) for adult obstructive sleep apnoea, with an electronic publication date of 29 October 2026. It gives a strong recommendation for CPAP when there is excessive daytime sleepiness, and conditional recommendations elsewhere, including a suggestion that either CPAP or no CPAP may be used when sleepiness is absent.

Adult bruxism was thin in the same window. No primary bruxism trial or cohort was first published or first indexed in those seven days. The nearest new cohort is a Pelotas birth-cohort analysis electronically published on 25 October 2026. The latest treatment syntheses on sleep bruxism are from July 2026 and are included, with those dates stated, so the gap is visible.

Several small insomnia trials report short-term symptom change. A Belgian crossover of two mandibular devices in moderate sleep apnoea is small and, on the authors’ own account, confounded by a change in how breathing events were measured. UK-tagged records this week are an uncontrolled medical-cannabis registry in insomnia, a Royal Free London survey of sleepiness in adults with HIV (fieldwork 2018–2019, newly indexed), and a health-economic review of OSA diagnosis framed around UK pathways.

Preprints from medRxiv, bioRxiv and Research Square are listed separately. They are not peer reviewed.

---

## 2. How to read the appraisals

**Level of evidence**, used consistently below:

| Level | Meaning in this pack |
| --- | --- |
| Guideline | Recommendation built on a systematic evidence review, here with GRADE |
| Review of trials | Systematic review or meta-analysis of randomised trials |
| Review of observational studies | Systematic review, meta-analysis or umbrella review of non-randomised research |
| Trial | Randomised or crossover trial |
| Cohort | Prospective or retrospective cohort, including before-and-after series |
| Cross-section | Cross-sectional, case-control or single-night laboratory series |
| Methods or commentary | Instrument paper, narrative review, clinical commentary or case report |
| Preprint | Not peer reviewed |

**Appraisal basis.** Design, sample size, prespecification, adjustment and the main biases are judged from the abstract. That is enough to see the design and the headline numbers. It is not a full risk-of-bias assessment. Loss to follow-up, allocation concealment, exact model specification and unreported outcomes may look different in the full text.

**UK relevance** means how far the people studied resemble adults who use NHS sleep, dental or primary-care services: age, sex, comorbidity, setting and whether the test or treatment exists on a UK pathway. A study can be scientifically sound and still a poor guide to the general UK adult population.

**Dates.** “Indexed” is the Entrez date, the day the record entered PubMed. “E-pub” is the electronic publication date on the record. A paper can be new to PubMed this week and have been published earlier. Both dates are given when they differ.

---

## 3. Search report (PRISMA-S)

### 3.1 PubMed

| Item | Detail |
| --- | --- |
| Database | MEDLINE, via PubMed |
| Interface | NCBI E-utilities (`esearch`, `esummary`, `efetch`), public service, no account |
| URL | https://eutils.ncbi.nlm.nih.gov/entrez/eutils/ |
| Date run | 2 November 2026 |
| Date of coverage, primary | Entrez date (`datetype=edat`) 2026/10/26 to 2026/11/02 |
| Date of coverage, sensitivity | Publication date (`datetype=pdat`) 2026/10/26 to 2026/11/02 |
| Other limits | None. No language limit. No “humans” limit. The adult criteria are inside the string |
| Sort | `pub_date` |
| Retrieval note | `retmax` was set to 10000. The service returned a notice that start and count were adjusted to 0 and 9999. The identifier lists matched the reported counts (156 and 268), so that notice did not cut these sets |

The adult criteria sit inside the string, as MeSH age terms plus free text. PubMed’s sidebar “Adult: 19+ years” filter is MeSH-based and drops many records from the current week, because MeSH indexing lags. A humans-only MeSH limit was left off for the same reason. Animal and paediatric records can therefore appear and were handled at screening.

MeSH was checked in the MeSH database on the same day. The heading is **Sleep Disorders, Circadian Rhythm**. The phrase “Circadian Rhythm Sleep Disorders” is an entry term, not the heading, and a first draft that searched it as a heading was rejected by PubMed. The string below is the one that was run.

**Exact PubMed string**

```
(("Sleep Wake Disorders"[Mesh] OR "Sleep"[Mesh:noexp] OR "Sleep Apnea Syndromes"[Mesh] OR "Sleep Apnea, Obstructive"[Mesh] OR "Sleep Initiation and Maintenance Disorders"[Mesh] OR "Narcolepsy"[Mesh] OR "Restless Legs Syndrome"[Mesh] OR "Disorders of Excessive Somnolence"[Mesh] OR "Sleep Disorders, Circadian Rhythm"[Mesh] OR "Polysomnography"[Mesh] OR "Continuous Positive Airway Pressure"[Mesh] OR "Bruxism"[Mesh] OR "Sleep Bruxism"[Mesh] OR sleep[ti] OR insomnia[tiab] OR "sleep apnea"[tiab] OR "sleep apnoea"[tiab] OR "obstructive sleep"[tiab] OR narcolepsy[tiab] OR "restless legs"[tiab] OR bruxism[tiab] OR "sleep bruxism"[tiab] OR polysomnograph*[tiab] OR CPAP[tiab] OR hypersomnia[tiab] OR parasomnia[tiab] OR "circadian rhythm"[tiab] OR "sleep disorder"[tiab] OR "sleep disordered breathing"[tiab] OR "sleep-disordered breathing"[tiab] OR "positive airway pressure"[tiab] OR somnolence[ti] OR "sleep quality"[ti] OR "sleep duration"[ti] OR bruxist*[tiab] OR "tooth grinding"[tiab] OR "teeth grinding"[tiab])) AND ((adult[MeSH] OR "young adult"[MeSH] OR "middle aged"[MeSH] OR aged[MeSH] OR adult[tiab] OR adults[tiab] OR "middle-aged"[tiab] OR "older adult"[tiab] OR "older adults"[tiab]))
```

**Hit counts for that string**

| Set | Hits |
| --- | --- |
| Entrez date 26 Oct–2 Nov 2026 | 156 |
| Publication date 26 Oct–2 Nov 2026 | 268 |
| In both sets | 56 |
| Entrez date only | 100 |
| Publication date only | 212 |

The publication-date count is not a count of papers published on those seven days. PubMed treats a month-only date such as “2026 Nov” as 1 November, so a window that ends on 2 November pulls in the whole November issue of journals that do not give a day. Among the 212 publication-date-only records, a day-specific electronic publication date inside 26 October–2 November was present for two records: the CPAP guideline (PMID 42860272) and a nap study of prefrontal glutamate (PMID 42785995). Those two are appraised. The other publication-date-only records were not treated as this week’s output.

**Separate bruxism string**, used only because the index week was thin. Same adult filter. Entrez date and publication date each run for 1 September 2026 to 2 November 2026.

```
(bruxism[tiab] OR "sleep bruxism"[tiab] OR "Bruxism"[Mesh] OR "Sleep Bruxism"[Mesh] OR bruxist*[tiab] OR "tooth grinding"[tiab] OR "teeth grinding"[tiab]) AND (adult[MeSH] OR "young adult"[MeSH] OR "middle aged"[MeSH] OR aged[MeSH] OR adult[tiab] OR adults[tiab] OR "middle-aged"[tiab] OR "older adult"[tiab] OR "older adults"[tiab])
```

| Set | Hits |
| --- | --- |
| Entrez date 1 Sep–2 Nov 2026 | 17 |
| Publication date 1 Sep–2 Nov 2026 | 39 |
| Union of those two lists | 43 |
| Also inside the main weekly sleep sets | 8 |

Inclusion from this list used the electronic publication date, not the whole two-month net. Records whose issue date is November 2026 but whose electronic publication was months earlier are dated accordingly in section 8.

### 3.2 What was done with the 156

| Step | Number |
| --- | --- |
| Adult sleep records entering PubMed, 26 Oct–2 Nov 2026 | 156 |
| Appraised individually from that set | 43 |
| Retrieved, listed in Appendix A, not given findings | 113 |
| Added because the electronic publication date fell inside the window even though indexing was earlier | 2 |
| Adult bruxism catch-up, outside that 43, appraised in section 8 | 9 |

Screening was single-reviewer title and abstract review on 2 November 2026. It is a surveillance screen, not a dual-reviewed systematic review. The 113 records in Appendix A were retrieved. They are not given findings, because findings were not extracted. They include animal and basic circadian work, paediatric or perinatal samples, protocols, corrections, letters, and papers in which sleep is a covariate in another condition. A reader who wants one of those topics has the PMID and DOI.

### 3.3 Europe PMC (supplement)

| Item | Detail |
| --- | --- |
| Database | Europe PMC |
| Interface | Europe PMC REST API |
| URL | https://www.ebi.ac.uk/europepmc/webservices/rest/search |
| Date run | 2 November 2026 |
| Result type | `lite` for the sweep, `core` for selected preprint DOIs |
| Hit count | 234 |
| Sources in the returned set | MEDLINE 188, preprints 35, PMC 11 |

This query is a supplement. It is not the PubMed string and it is not an adult MeSH filter.

**Exact Europe PMC query**

```
(TITLE:"sleep" OR TITLE:"insomnia" OR TITLE:"apnoea" OR TITLE:"apnea" OR TITLE:"bruxism" OR TITLE:"narcolepsy" OR TITLE:"CPAP" OR TITLE:"circadian" OR ABSTRACT:"sleep apnoea" OR ABSTRACT:"sleep apnea" OR ABSTRACT:"sleep bruxism" OR ABSTRACT:"obstructive sleep" OR ABSTRACT:bruxism OR ABSTRACT:insomnia OR ABSTRACT:narcolepsy) AND (FIRST_PDATE:[2026-10-26 TO 2026-11-02])
```

### 3.4 medRxiv (supplement)

| Item | Detail |
| --- | --- |
| Database | medRxiv |
| Interface | medRxiv details API |
| URL pattern | `https://api.medrxiv.org/details/medrxiv/2026-10-26/2026-11-02/{cursor}/json` |
| Date run | 2 November 2026 |
| API message | total 478; `count_new_papers` 396 |
| Unique DOIs retrieved by paging the cursor from 0 | 459 |
| Title or abstract matched a sleep, circadian, apnoea, bruxism, narcolepsy or CPAP term | 24 |

**Verification:** the API total (478) and the unique DOIs retrieved (459) differ by 19. That gap was not resolved. Counts of sleep preprints below use the 459 retrieved records. bioRxiv and Research Square items were taken from the Europe PMC preprint set, not from the medRxiv API.

---

## 4. Coverage gaps: Embase and Scopus

These databases were not searched. There was no login and no scraping. The strategies below are ready for Sara to paste. They mirror the PubMed concepts (sleep disorders, sleep apnoea, insomnia, narcolepsy, restless legs, circadian sleep disorders, polysomnography, CPAP, bruxism and sleep bruxism; adults; records added 26 October–2 November 2026). Line numbers assume a fresh Ovid or Scopus session.

Emtree preferred terms should be confirmed on the local tree before the search is relied on. Age-limit labels in Ovid differ by database build. The syntax was checked against public Ovid and Scopus guidance for the date fields, and was not executed.

### 4.1 Ovid Embase

First Date (`dd`) is the documented field for the day a record was first added (formerly Date Delivered). Public Ovid guidance also describes a Revised Date (`.rd.`) for records corrected after they were first added. The `.rd.` range in line 23 should be confirmed on the local Ovid build.

```
1 exp sleep disorder/
2 exp sleep/
3 exp insomnia/
4 exp "obstructive sleep apnea"/
5 exp "sleep disordered breathing"/
6 exp narcolepsy/
7 exp "restless legs syndrome"/
8 exp "REM sleep behavior disorder"/
9 exp "circadian rhythm sleep disorder"/
10 exp polysomnography/
11 exp bruxism/
12 exp "sleep bruxism"/
13 exp "continuous positive airway pressure"/
14 (sleep or insomnia or "sleep apnoea" or "sleep apnea" or "obstructive sleep" or narcolepsy or "restless legs" or "REM sleep behavior" or "REM sleep behaviour" or bruxism or "sleep bruxism" or bruxist* or "tooth grinding" or "teeth grinding" or polysomnograph* or CPAP or "positive airway pressure" or hypersomnia or parasomnia or "circadian rhythm" or "sleep disordered breathing" or "sleep-disordered breathing").ti,ab,kf.
15 or/1-14
16 exp adult/ or exp aged/ or exp "middle aged"/ or exp "young adult"/ or exp "very elderly"/
17 (adult or adults or "middle aged" or "middle-aged" or "older adult" or "older adults").ti,ab,kf.
18 16 or 17
19 15 and 18
20 exp human/
21 19 and 20
22 limit 21 to dd=20261026-20261102
23 21 and 20261026:20261102.rd.
24 22 or 23
```

Optional, if the local limit names match. Confirm the wording in the Ovid limits list before use:

```
limit 21 to (adult <18 to 64 years> or aged <65+ years>)
```

If line 13 or line 8 or line 9 returns a term-not-found error, search the tree for the preferred Emtree heading and keep the free-text line. Do not drop bruxism if the explode on sleep disorder already captures it; the explicit lines are there so a tree change cannot silently omit it.

### 4.2 Embase.com (Elsevier)

```
('sleep disorder'/exp OR 'sleep'/exp OR 'insomnia'/exp OR 'obstructive sleep apnea'/exp OR 'sleep disordered breathing'/exp OR 'narcolepsy'/exp OR 'restless legs syndrome'/exp OR 'REM sleep behavior disorder'/exp OR 'circadian rhythm sleep disorder'/exp OR 'polysomnography'/exp OR 'bruxism'/exp OR 'sleep bruxism'/exp OR 'continuous positive airway pressure'/exp OR sleep:ti,ab,kw OR insomnia:ti,ab,kw OR 'sleep apnoea':ti,ab,kw OR 'sleep apnea':ti,ab,kw OR 'obstructive sleep':ti,ab,kw OR narcolepsy:ti,ab,kw OR 'restless legs':ti,ab,kw OR bruxism:ti,ab,kw OR 'sleep bruxism':ti,ab,kw OR bruxist*:ti,ab,kw OR 'tooth grinding':ti,ab,kw OR polysomnograph*:ti,ab,kw OR cpap:ti,ab,kw OR 'positive airway pressure':ti,ab,kw OR hypersomnia:ti,ab,kw OR parasomnia:ti,ab,kw OR 'circadian rhythm':ti,ab,kw)
AND ('adult'/exp OR 'aged'/exp OR 'middle aged'/exp OR 'young adult'/exp OR 'very elderly'/exp OR adult:ti,ab,kw OR adults:ti,ab,kw OR 'older adult':ti,ab,kw OR 'older adults':ti,ab,kw)
AND [humans]/lim
AND [26-10-2026 to 02-11-2026]/sd
```

**Verification:** `[sd]` is the Embase.com source/first-date field. The day-range syntax above was not executed. If the local interface rejects it, set the on-screen first-date filter to 26 October 2026 through 2 November 2026 and save the query Embase.com generates.

### 4.3 Scopus (TITLE-ABS-KEY)

Scopus has no MeSH or Emtree equivalent in this field. Adult retrieval is free text, so some adult papers that never use the word “adult” will be missed, and some papers that mention adults in passing will be kept. Queen’s University Belfast’s systematic-review guidance describes `ORIG-LOAD-DATE AFT YYYYMMDD` as on or after that date and `BEF` as on or before. That reading was not tested in a Scopus session.

```
TITLE-ABS-KEY ( sleep OR insomnia OR "sleep apnoea" OR "sleep apnea" OR "obstructive sleep" OR narcolepsy OR "restless legs" OR "REM sleep behavio*" OR bruxism OR "sleep bruxism" OR bruxist* OR "tooth grinding" OR "teeth grinding" OR polysomnograph* OR cpap OR "positive airway pressure" OR hypersomnia OR parasomnia OR "circadian rhythm" OR "sleep disordered breathing" OR "sleep-disordered breathing" )
AND TITLE-ABS-KEY ( adult OR adults OR "middle-aged" OR "middle aged" OR "older adult" OR "older adults" )
AND ORIG-LOAD-DATE AFT 20261025
AND ORIG-LOAD-DATE BEF 20261103
```

Optional exclusion, to be used with care because it also drops lifecourse papers:

```
AND NOT TITLE ( child OR children OR pediatric OR paediatric OR infant OR neonatal OR adolescent )
```

---

## 5. Guidance and diagnostic criteria

### ERS/ESRS guideline on CPAP for adult OSA

Testelmans D et al. ERS/ESRS clinical practice guideline for continuous positive airway pressure for the treatment of adult obstructive sleep apnoea. *European Respiratory Journal*. E-pub and indexed publication date 29 October 2026. PubMed record created 11 October 2026. PMID 42860272. DOI 10.1183/13993003.01186-2026.

**Findings.** The task force suggests CPAP for OSA on the basis of effects on sleepiness, other patient-reported outcomes and blood pressure (conditional recommendations). CPAP is strongly recommended when there is excessive daytime sleepiness. Further conditional recommendations cover moderate-to-severe OSA, older adults, and arterial or treatment-resistant hypertension. The task force suggests either CPAP or no treatment when excessive daytime sleepiness is absent, taking other OSA symptoms into account; the same “either CPAP or no treatment” wording is used for atrial fibrillation if the aim is to reduce recurrence, and for impaired glucose metabolism if the aim is glycaemic control.

**Appraisal.** Guideline level. Methods named in the abstract are PICO questions, a systematic review, GRADE, and Evidence-to-Decision voting. Certainty is not one number: the abstract distinguishes a strong recommendation from several conditional ones. The graded table, evidence profiles and vote counts were not in the record retrieved here. MeSH had not yet been applied.

**Population and UK relevance.** Adults with OSA, split into clinical subgroups rather than a single average patient. This is directly relevant to UK sleep services. It should be read beside current NICE guidance on OSAHS; this pack does not restate NICE. The recommendation is European, not a UK commissioning decision.

### Research diagnostic criteria for periodic limb movement disorder

Fulda S et al. Periodic limb movement disorder in adults: history, new research diagnostic criteria and a research agenda. *Sleep Medicine Reviews*. E-pub 17 September 2026. Indexed 27 October 2026. PMID 42945620. DOI 10.1016/j.smrv.2026.102378.

**Findings.** An International Restless Legs Syndrome Study Group task force sets out research diagnostic criteria for adult periodic limb movement disorder. The criteria require frequent periodic limb movements in sleep, clinically important day or night impairment, exclusion of restless legs syndrome, untreated sleep-related breathing disorder, narcolepsy and REM sleep behaviour disorder, and a judgement that the limb movements cause the impairment. A six-level reporting system is proposed for studies.

**Appraisal.** Methods and consensus level, not a new prevalence or treatment estimate. No patient sample and no statistical model. The practical risk is that future papers will mix these research criteria with older clinical definitions. The abstract does not show a formal Delphi denominator or a GRADE profile.

**Population and UK relevance.** The criteria are for adults in research. UK sleep laboratories already see this problem, because limb movements and sleep apnoea often share a night. The criteria do not change NHS coding on their own.

### Sleep assessment in the memory clinic

Suraev A et al. Why sleep assessment belongs in the memory clinic. *Alzheimer’s & Dementia*. Publication date October 2026. Indexed 26 October 2026. PMID 42928412. DOI 10.1002/alz.71880.

**Findings.** A perspective arguing that insomnia, OSA, circadian disruption and REM sleep behaviour disorder are common in memory-clinic patients and are unevenly assessed. The authors describe practice in four international settings and propose a stepped-care approach to detection and referral.

**Appraisal.** Commentary. No new pooled estimate. Useful as a service argument, weak as evidence of benefit from screening.

**Population and UK relevance.** Older adults attending memory clinics. Relevant to UK memory services in principle. The paper does not test an NHS pathway.

### Two Swiss clinical updates, older adults

Touffic C et al. Chronic insomnia in the elderly: balancing innovation and caution. *Revue Médicale Suisse*. Publication date 28 October 2026. Indexed 30 October 2026. PMID 42958977. DOI 10.53738/REVMED.2026.22.981.49191. Language of the article: French. English abstract retrieved.

**Findings.** The authors restate cognitive behavioural therapy for insomnia as first-line treatment and say that, in Switzerland, only 1% of patients can access it. They name prolonged-release melatonin and daridorexant as candidates when a medicine is used longer term.

**Appraisal.** Clinical commentary. The 1% access figure is the authors’ statement about Switzerland. No new trial.

**Population and UK relevance.** Older adults. The access problem will be familiar, but the 1% figure must not be copied onto UK services. The abstract is an English summary of a French article.

Ghidossi A et al. Sleep apnea in older adults: should it always be treated? *Revue Médicale Suisse*. Publication date 28 October 2026. Indexed 30 October 2026. PMID 42958978. DOI 10.53738/REVMED.2026.22.981.49199. French article, English abstract.

**Findings.** The authors say OSA affects more than half of people over 65 and is often missed because insomnia is more prominent than snoring or sleepiness. They argue that a CPAP decision in later life should rest on symptoms, quality of life and a geriatric assessment, because cardiovascular and mortality benefit is uncertain.

**Appraisal.** Commentary. The prevalence sentence is the authors’ summary, not a new UK estimate. It points the same way as the ERS/ESRS guideline’s separation of sleepy and non-sleepy patients.

**Population and UK relevance.** Adults over 65. Relevant to UK geriatric and sleep clinics as a question, not as a local prevalence.

---

## 6. Obstructive sleep apnoea: treatment, risk and detection

### CPAP, diagnosis and cardiovascular risk

Osman A et al., FOUND study group. A systematic review of economic evaluations of strategies to diagnose obstructive sleep apnoea in adults. *Health Economics Review*. E-pub 4 August 2026. Indexed 30 October 2026. PMID 42957848. DOI 10.1186/s13561-026-00823-y.

**Findings.** Twenty-nine economic evaluations were included, 15 alongside trials and 14 model-based. The reviewers’ main applied conclusion is that only four studies used home respiratory polygraphy as a comparator, which limits transfer to UK pathways. They also flag short time horizons, health-state choices, and optimistic assumptions about long-term CPAP adherence.

**Appraisal.** Review of economic studies, not a new cost-effectiveness estimate. Registered CRD42024535732. Narrative synthesis. Heterogeneity of diagnostic thresholds is the point of the paper. No pooled incremental cost-effectiveness ratio is reported in the abstract.

**Population and UK relevance.** Adults with moderate-to-severe OSA in published models, discussed explicitly against the UK burden and home polygraphy. This is one of the few records this week written for a UK decision. It says the current economic evidence does not yet answer the UK question.

Kuczyński W et al. Risk factors for cardiovascular mortality in patients with obstructive sleep apnea. *Sleep*. E-pub 28 October 2026. Indexed 28 October 2026. PMID 42949055. DOI 10.1093/sleep/zsag284.

**Findings.** In 4,368 adults referred for polysomnography and followed for a median 8.6 years, 335 cardiovascular deaths occurred. Independent predictors in the abstract are age (hazard ratio 1.08 per year, 95% CI 1.07–1.10), male sex (1.68, 1.29–2.18), current smoking (1.68, 1.30–2.15), hypertension (1.73, 1.29–2.33), atrial fibrillation (2.16, 1.56–2.98), previous myocardial infarction (1.71, 1.25–2.35) and diabetes (1.37, 1.06–1.76). Nocturnal desaturation was not independent after adjustment. Among people with an apnoea-hypopnoea index (AHI) of at least 15, a “good CPAP response” had a hazard ratio of 0.72 (0.55–0.96). A random-survival-forest model had a C-index of 0.80 on a 70/30 split. Six phenotypes had cardiovascular mortality from 2.9% to 14.4%.

**Appraisal.** Retrospective cohort with cause-specific Cox models, Fine-Gray models and a machine-learning survival model. The design can describe predictors. It cannot show that treating a comorbidity would cut deaths. “Good CPAP response” is not defined in the abstract. The C-index is internal. The closing sentence says mortality was driven by classical risk factors rather than by hypoxaemia or CPAP response, while the CPAP-response hazard ratio above is below 1 and its interval excludes 1. Those two statements need the full model before either is used in a business case.

**Population and UK relevance.** Tertiary-referral adults, country not stated in the abstract, followed for up to 20 years, so the early years of follow-up reflect older practice. The dominance of smoking, blood pressure, atrial fibrillation and diabetes matches what UK cardiovascular clinics already treat. It is a poor basis for telling a symptom-free UK adult that CPAP will or will not extend life.

Zhang Q et al. Multidimensional sleep health and risks of all-cause and cardiovascular mortality: a MAIHDA-based prospective cohort study. *Sleep Health*. E-pub 28 October 2026. Indexed 28 October 2026. PMID 42951777. DOI 10.1016/j.sleh.2026.09.015.

**Findings.** In the Sleep Heart Health Study, 4,340 adults contributed to all-cause mortality analyses and 3,790 to cardiovascular mortality. Six sleep dimensions were combined into 64 profiles. In empty models, the profiles accounted for 8.51% of all-cause and 15.01% of cardiovascular mortality variance. After the separate sleep dimensions and covariates were added, almost all of that between-profile variance was gone (proportional change in variance 99.95% and 78.32%). Healthier continuity and timing went with lower all-cause mortality. Timing was the most consistent cardiovascular signal. Profiles with several unhealthy dimensions had the highest standardised 10-year risk.

**Appraisal.** Prospective cohort, re-analysed with multilevel analysis of individual heterogeneity and discriminatory accuracy. This is a sensible way to ask whether combinations do more than the sum of their parts. Here they largely did not. Sleep was measured in an older US cohort, once, and survival models of this type are sensitive to how “unhealthy” is cut. The abstract does not give the adjusted hazard ratio for each dimension.

**Population and UK relevance.** US community adults in the Sleep Heart Health Study, a historical cohort. Age and adiposity patterns differ from a 2026 UK general-practice list. The clinical reading is modest: adding unhealthy sleep features stacks risk, and there is little sign of a special combination that would change UK case-finding on its own.

### Devices, surgery and weight-loss surgery

Blok J et al. A randomised controlled crossover trial comparing two mandibular repositioning appliances for treatment of moderate obstructive sleep apnoea. *Sleep & Breathing*. E-pub 28 October 2026. Indexed 29 October 2026. PMID 42955526. DOI 10.1007/s11325-026-03821-w.

**Findings.** Sixteen adults in Genk, Belgium, all with moderate OSA (AHI 15.1–29.7), wore SomnoDent Flex and OrthoApnea NOA for three months each. Median AHI fell from 17.6 events/h to 3.1 and 2.3. The between-device difference was +0.16 events/h (95% CI −2.56 to +2.87; p = 0.904). A period effect of +3.82 events/h coincided with a switch from home polygraphy to in-laboratory polysomnography (p = 0.009). AHI under 5 was reached in 12/16 and 10/16. Adverse events were not systematically recorded.

**Appraisal.** Trial level, but very small, unblinded to wearers and clinicians, and scorers only were blinded. The registered primary outcome was change from baseline for each device. The between-device comparison was not prespecified. The authors state that it does not show equivalence, and that period and measurement method are completely confounded. That self-critique is the correct reading.

**Population and UK relevance.** Single-centre European adults with moderate OSA who can use a custom oral appliance. Relevant to UK oral-appliance practice as a signal that two custom devices can look similar, and as a warning against before-and-after AHI claims when the test itself changes. It is not evidence to prefer one named device.

Cuypers S et al. The role of DISE and simulation bite in the selection of non-CPAP treatment modalities in patients with OSA. *Sleep & Breathing*. E-pub 29 October 2026. Indexed 29 October 2026. PMID 42955467. DOI 10.1007/s11325-026-03846-1.

**Findings.** Retrospective series of 82 adults who declined or could not use CPAP. Of 56 advised to use a mandibular appliance who then had a treatment sleep study, 96% met the authors’ success criterion. Tonsillectomy (4 patients) and modified uvulopalatopharyngoplasty (7 patients) had success in 50% and 29%. A chin lift during drug-induced sleep endoscopy predicted appliance success as well as a simulation bite.

**Appraisal.** Retrospective cohort. Success is reported only for people who were advised to have a treatment and who returned for a sleep study, which inflates apparent prediction. Surgical denominators are too small for a rate. The abstract does not define success. Country is not stated.

**Population and UK relevance.** CPAP-intolerant adults in a surgical/dental pathway. UK centres that already use drug-induced sleep endoscopy will recognise the question. The 96% figure should not be quoted as an expected NHS success rate.

Chen TA, Huang TW. Clinical outcomes of combined uvulopalatopharyngoplasty and all-suture anchor tongue base suspension for obstructive sleep apnea. *Medicina (Kaunas)*. E-pub 22 September 2026. Indexed 27 October 2026. PMID 42942358. DOI 10.3390/medicina62101827.

**Findings.** Thirty of 40 consecutive adults with moderate-to-severe OSA who declined or could not use CPAP had postoperative polysomnography at six months or later. Median AHI fell from 50.5 (interquartile range 38.0–68.0) to 15.7 (11.1–21.4) events/h. Epworth score fell from 16.3 ± 2.5 to 7.5 ± 2.4. Nadir saturation rose from 68.5% ± 6.5% to 82.8% ± 9.2%. The authors report surgical success in 22/30 (73%). Complications were mostly mild. No infection, suture rupture or permanent deficit was reported.

**Appraisal.** Single-arm retrospective series. No control group, so the share due to surgery, weight change or night-to-night AHI variation is unknown. “Success” is not defined in the abstract. Complete-case analysis of 30/40 invites attrition bias.

**Population and UK relevance.** Selected surgical adults with severe disease and high baseline sleepiness. A narrow slice of UK practice. It supports feasibility of this implant style, not a change to the usual CPAP-first pathway.

Bant P et al. Long-term changes in subjective daytime sleepiness following tonsillectomy and uvulopalatopharyngoplasty (UPPP). *Medicine (Baltimore)*. Publication date 23 October 2026. Indexed 27 October 2026. PMID 42937758. DOI 10.1097/MD.0000000000050856.

**Findings.** Of 105 adults, 89 (85%) were followed for a mean of six years after tonsillectomy or UPPP. Mean Epworth score fell from 7.29 to 4.37. A fall of at least 2 points occurred in 71.9%. The share with a normal score (10 or under) rose from 75.3% to 92.1%. The unadjusted fall was larger after UPPP than tonsillectomy (4.22 versus 1.81 points), and a model found an interaction with the baseline score.

**Appraisal.** Prospective cohort of routine surgery, without a control group and without a requirement for diagnosed OSA in the abstract. Baseline sleepiness was already in the normal range for most patients, so the absolute gain is small. Six-year subjective scores are open to recall and selection effects.

**Population and UK relevance.** Adults having tonsil surgery, sex mix 26 women and 63 men in the followed sample. Relevant to ear, nose and throat follow-up. It is not evidence that UPPP treats OSA in the general UK adult population.

Bonilla LFS et al. Changes in obstructive sleep apnea severity, upper-airway findings, and health-related quality of life after Roux-en-Y gastric bypass. *Sleep & Breathing*. E-pub 29 October 2026. Indexed 29 October 2026. PMID 42955464. DOI 10.1007/s11325-026-03841-6.

**Findings.** At Hospital de San José, Bogotá, 33 adults were assessed, 30 had surgery and 18 completed both sleep studies. Mean weight fell from 104.4 ± 12.6 kg to 68.5 ± 8.9 kg, body mass index from 38.77 ± 4.94 to 25.82 ± 4.28 kg/m², and AHI from 23.70 ± 8.67 to 8.74 ± 4.35 events/h. Mean AHI change was −14.96 events/h (95% CI −18.69 to −11.22). Residual OSA (AHI at least 5) remained in 15 of 18 (83.3%, exact 95% CI 58.6–96.4%).

**Appraisal.** Prospective before-and-after cohort. Paired tests are appropriate for the completers. There is no control group. Completing both studies was 18 of 33 assessed, so the result describes people who returned. The confidence interval on residual OSA is wide because the numerator is small.

**Population and UK relevance.** Colombian adults with obesity and OSA undergoing bypass. Directionally relevant to UK tier-3 and tier-4 weight services: severity often falls and remission is uncommon. The absolute AHI values should not be used as a UK tariff.

### Metabolic and physiological associations

Pant S et al. Metabolic syndrome in adults with polysomnography-confirmed obstructive sleep apnoea: a systematic review and meta-analysis. *Pulmonary Therapy*. E-pub 27 October 2026. Indexed 27 October 2026. PMID 42944980. DOI 10.1007/s41030-026-00391-w.

**Findings.** Sixty-eight studies from 24 countries (24,663 adults with polysomnography-confirmed OSA and 11,423 without) gave a pooled odds ratio for metabolic syndrome of 3.33 (95% CI 2.86–3.87; I² = 73.8%). A larger body-mass-index gap between groups was associated with higher odds (β = 0.14, p < 0.001). A higher proportion of men was associated with lower odds (β = −0.01, p < 0.010). Registered CRD420251073055.

**Appraisal.** Review of observational studies, three-level random effects, RoBANS for bias. Heterogeneity is large, and body mass index is an obvious confounder that the meta-regression only partly addresses. The association is consistent. It is not evidence that treating OSA removes metabolic syndrome. The authors’ call for routine metabolic screening is a clinical inference.

**Population and UK relevance.** Mixed adult clinic and population samples. Metabolic syndrome is common in UK adults with OSA, so the direction is relevant. The threefold odds ratio is not a UK prevalence and should not be used as one.

Tariq A et al. Hypoxic burden, systemic inflammation and respiratory muscle dysfunction in obstructive sleep apnoea: a multicentre cross-sectional study. *BMJ Open Respiratory Research*. E-pub 26 October 2026. Indexed 26 October 2026. PMID 42933813. DOI 10.1136/bmjresp-2026-004397.

**Findings.** One hundred and thirty-seven adults with suspected OSA at tertiary centres in Lahore had attended polysomnography, inflammatory blood tests and mouth-pressure measurements. Hypoxic burden had the strongest association with OSA severity (η² = 0.73). In a multivariable model, higher body mass index (β = 1.35, p = 0.002), older age (β = 0.25, p = 0.024), higher Epworth score (β = 0.50, p = 0.015) and lower inspiratory muscle strength (β = −0.68, p = 0.007) were associated with greater hypoxic burden (adjusted R² = 0.47). C-reactive protein was associated with body mass index, hypoxic burden and weaker inspiratory muscles (adjusted R² = 0.58).

**Appraisal.** Cross-sectional multicentre study. Linear regression is appropriate for the question asked. It cannot order cause between hypoxia, inflammation and muscle weakness. η² of 0.73 for severity is expected if hypoxic burden and the severity scale share the same oxygen trace. Units of hypoxic burden are not restated in a way that travels without the methods.

**Population and UK relevance.** Pakistani tertiary-care adults. Body size, air quality and referral thresholds differ from a UK sleep list. The pattern (weight, sleepiness, inflammation, weaker inspiratory muscles) is clinically familiar. The coefficients are not portable.

Köse G et al. Sleep architecture disruption and coordinated patterns of inflammatory and extracellular matrix biomarkers in obstructive sleep apnea. *European Archives of Oto-Rhino-Laryngology*. E-pub 31 October 2026. Indexed 1 November 2026. PMID 42966814. DOI 10.1007/s00405-026-10752-5.

**Findings.** Seventy adults with OSA were split into mild-to-moderate and severe. Severe OSA had higher TNF-α, IL-6, MMP-2, MMP-9, desmosine and cellular fibronectin (all p < 0.05). Syndecan-1 was significant after body-mass-index adjustment (p = 0.009). Biomarkers tracked AHI and hypoxic load and were inversely related to N3 sleep. After body-mass-index adjustment, partial correlations inside the inflammatory cluster were r = 0.831–0.921; unadjusted Spearman correlations were ρ = 0.427–0.655.

**Appraisal.** Cross-sectional, many biomarkers, modest sample. ANCOVA and partial correlation are described. The jump from unadjusted to adjusted correlations is large enough that the full covariance model needs checking before anyone treats these as a tight biological cluster. No external validation.

**Population and UK relevance.** Adults with confirmed OSA, country not stated. Mechanistic, not a UK screening panel.

Manzur AR et al. Severe obstructive sleep apnea is associated with cholesterol target non-attainment in patients undergoing cardiac surgery. *Life (Basel)*. E-pub 9 October 2026. Indexed 27 October 2026. PMID 42942276. DOI 10.3390/life16101690.

**Findings.** Secondary analysis of 142 adults awaiting cardiac surgery, tested with in-hospital type III polygraphy. Severe OSA (AHI at least 30) was associated with non-HDL cholesterol of at least 100 mg/dL (adjusted odds ratio 3.49, 95% CI 1.56–7.78), LDL cholesterol of at least 55 mg/dL (2.93, 1.18–7.29) and LDL of at least 70 mg/dL (2.30, 1.03–5.12). Continuous LDL and non-HDL levels were not significantly associated (p = 0.113 and p = 0.100). The non-HDL threshold result remained in statin-treated patients.

**Appraisal.** Cross-sectional secondary analysis. Adjustment included age, sex, body mass index, diabetes and lipid treatment. Threshold models can be significant when the continuous model is not, which is a reason to treat the odds ratios as cut-point findings. Polygraphy is not full polysomnography. The authors correctly say this is not proof of treatment failure.

**Population and UK relevance.** Cardiac-surgical adults, country not stated. Lipid cut-points of 55 mg/dL are in the European target range used in UK secondary prevention. General UK adults without surgical heart disease are a different population.

Cho U et al. Age-dependent association of body mass index and obstructive sleep apnea severity in women. *Sleep & Breathing*. E-pub 31 October 2026. Indexed 31 October 2026. PMID 42965756. DOI 10.1007/s11325-026-03849-y.

**Findings.** In 752 adults at a university sleep laboratory, the association between body-mass-index category and AHI was weaker in women aged 55 or over than in younger women (interaction p = 0.03 for AHI and 0.02 for supine AHI). No age interaction was seen in men. The three-way interaction of body mass index, age group and sex was not significant.

**Appraisal.** Cross-sectional linear models with interactions. A sex-specific interaction without a significant three-way term is a weak basis for a sex-specific rule, and the authors say so. Referral to a university laboratory selects for symptomatic people.

**Population and UK relevance.** Sleep-clinic adults, country not stated. The caution is relevant to UK clinics: body mass index is a blunter clue to severity in older women. It does not replace a sleep study.

Fabozzi A et al. How obstructive sleep apnea differs in COPD and asthma. *Sleep & Breathing*. E-pub 31 October 2026. Indexed 31 October 2026. PMID 42965722. DOI 10.1007/s11325-026-03839-0.

**Findings.** Retrospective single-centre comparison of 66 adults with OSA plus COPD and 35 with OSA plus asthma, using home sleep testing and spirometry. The COPD overlap group had higher AHI, oxygen desaturation index and time with saturation under 90%. The asthma overlap group had more night waking, insomnia symptoms and fatigue. A predicted low arousal threshold was present in 57.1% of the asthma group and 30.3% of the COPD group.

**Appraisal.** Cross-sectional comparison of two clinic groups. Predicted arousal threshold is a model, not a measured arousal. No adjustment set is described in the abstract. Small asthma group.

**Population and UK relevance.** Adults with overlap syndromes, country not stated. Clinically recognisable in UK respiratory-sleep clinics. Rates of a predicted low arousal threshold should not be quoted as measured UK prevalence.

Pirchio R et al. Diagnostic delay length and disease severity are the main predictors of sleep apnea in acromegaly patients. *Frontiers in Endocrinology*. E-pub 12 October 2026. Indexed 27 October 2026. PMID 42936300. DOI 10.3389/fendo.2026.1928818.

**Findings.** Polygraphy in 36 adults with acromegaly (mean age 54.1 ± 12.9 years) found OSA in 17 (47.2%), mostly mild. Longer diagnostic delay was the strongest predictor of AHI and of the oxygen desaturation index, independent of body mass index (both p = 0.04). Epworth score did not differ (p = 0.96). Uncontrolled acromegaly had more apnoeas and worse oxygenation.

**Appraisal.** Prospective single-centre series. n = 36 makes the p = 0.04 predictors fragile. Several comparisons are described without a multiplicity plan in the abstract.

**Population and UK relevance.** A rare-disease clinic population, not the general UK adult population. Relevant to specialist endocrine practice: sleepiness questionnaires missed OSA here.

Wang XY et al. Associations of multiple ambient air pollutants and sleep apnea, sleep architecture and nocturnal oxygenation in adult patients with or without OSA. *Environmental Research*. E-pub 28 October 2026. Indexed 28 October 2026. PMID 42951172. DOI 10.1016/j.envres.2026.126044.

**Findings.** Retrospective polysomnography study of 4,049 adults in Shenzhen. The authors state, as background, that OSA affects an estimated 936 million adults worldwide; that figure is not a result of this study. The lag of 0–180 days was chosen after the analysis. In that window, PM2.5, PM10, NO2, SO2, CO and diurnal temperature range were linked to greater OSA severity. As examples, PM2.5 and PM10 were associated with 1.71 and 1.32 percentage-point increases in N1 sleep, and 1.51 and 1.32 percentage-point decreases in N3. Ozone and diurnal temperature range had the clearest links with oxygenation and sleep continuity. Ozone was U-shaped.

**Appraisal.** Large retrospective cohort with exposure assigned from ambient monitors, which misclassifies personal exposure. Post-hoc choice of the lag window is a material bias. Many pollutants and lags invite false-positive detail. The abstract does not show a pre-registered primary contrast.

**Population and UK relevance.** Urban Chinese adults attending for sleep studies. Pollution mixtures and housing are unlike most of the UK. A general association between dirtier air and lighter, more hypoxic sleep is plausible. These percentage-point estimates are not UK effect sizes.

### Detection tools

Janott C et al. Size matters: a large-scale, real-world dataset of smartphone-based obstructive sleep apnea screening in the general population. *Diagnostics (Basel)*. E-pub 16 October 2026. Indexed 27 October 2026. PMID 42938204. DOI 10.3390/diagnostics16203364.

**Findings.** The Snorefox M phone application contributed 239,132 nights from 31,647 consenting adults (March 2023–December 2025). Of users, 14,351 had at least two valid nights. Valid analysis was achieved on 96.5% of attempts. Mean AHI on the app was 14.3 (median 11.8, SD 11.0). Self-reported age and Epworth score were available for 8,092 users (mean age 54.4, mean Epworth 7.2). Against polysomnography the paper reports sensitivity 0.91 and specificity 0.83 for AHI at least 15, and 0.93 and 0.97 for AHI at least 30, with Pearson r = 0.80. Areas under the curve were 0.951, 0.925 and 0.877 at AHI thresholds of 30, 15 and 10.

**Appraisal.** Methods and dataset paper. The operating characteristics are reported “against PSG”, and the abstract also says performance had previously been validated. The size of the polysomnography sample is not in the abstract, so it is unclear whether these figures are new. App users are self-selected. Mean AHI in this file is not a population prevalence.

**Population and UK relevance.** Adults who chose a consumer app, not a random UK sample. Potentially relevant as a triage adjunct if a UK evaluation repeats the accuracy figures. It is not currently a substitute for NHS home respiratory polygraphy.

López-Zaldivar M et al. Machine learning-based screening for obstructive sleep apnea using photographic craniofacial and speech-derived acoustic features. *Life (Basel)*. E-pub 18 October 2026. Indexed 27 October 2026. PMID 42942334. DOI 10.3390/life16101748.

**Findings.** One hundred and nine adults. The best classification area under the curve was 0.766, from unsegmented facial features. Adding speech did not clearly improve discrimination. The lowest mean absolute error for AHI regression was 14.242 events/h. Several models were highly sensitive and poorly specific. Removing the four highest AHI values changed the regression more than the classification.

**Appraisal.** Cross-sectional diagnostic-accuracy study with nested cross-validation, which is the right guard against optimistic resubstitution. An AHI error of about 14 events/h crosses clinical bands. n = 109 is small for the number of model configurations.

**Population and UK relevance.** Adults, setting not stated. Not accurate enough for UK screening.

Chen YC et al. Domain-specific oral hypofunction in older adults with obstructive sleep apnoea: a case-control study. *Journal of Oral Rehabilitation*. E-pub 26 October 2026. Indexed 26 October 2026. PMID 42933905. DOI 10.1111/joor.70350.

**Findings.** Adults aged 50 or over: 69 with polysomnography-confirmed OSA (AHI at least 5) and 219 controls defined by STOP-Bang under 3. OSA was associated with oral hypofunction (adjusted odds ratio 2.49, 95% CI 1.07–5.81), poor oral hygiene (4.02), oral dryness (4.24) and reduced tongue pressure (4.95). Tongue-pressure loss was more evident in men. Occlusal force and chewing decline were more common in the controls.

**Appraisal.** Case-control. The control definition is a questionnaire, so some controls will have undiagnosed OSA, which biases associations towards the null, while clinic cases are more severe. Several domain-specific odds ratios are reported from one sample. Registered NCT05977296, which is unusual for a case-control study and should be checked so the registration matches the analysis.

**Population and UK relevance.** Adults aged 50 and over, country not stated in the abstract. Relevant to UK dental and speech-and-language colleagues who see older adults with OSA. The control rule would not be used in a UK prevalence survey.

---

## 7. Insomnia, sleep health interventions and related trials

### Trials in which sleep was a main target

Liu XY et al. Cerebellar continuous theta burst stimulation for insomnia disorder: a randomized sham-controlled trial. *CNS Neuroscience & Therapeutics*. Publication date October 2026. Indexed 26 October 2026. PMID 42929074. DOI 10.1002/cns.71231.

**Findings.** Seventy-two adults with insomnia disorder (51 women; mean age 44.3 ± 11.6 years) received two weeks of active or sham cerebellar continuous theta-burst stimulation. A Pittsburgh Sleep Quality Index fall of at least 3 points occurred in 75.0% versus 33.3% (adjusted odds ratio 6.06, 95% CI 2.17–18.50). The adjusted mean difference in Pittsburgh score was −3.34 (95% CI −4.57 to −2.12) after treatment and −3.70 (−4.93 to −2.48) at one month. Insomnia severity, anxiety and depression scores also fell (all p < 0.01). One resting-state connection survived false-discovery-rate correction (p = 0.038). No serious adverse events. Registered NCT05992285.

**Appraisal.** Sham-controlled randomised trial, intention-to-treat, prespecified response definition. One month is short. The imaging analysis is exploratory even with a corrected p value on a single connection. Single-trial evidence. Placebo response in the sham arm was already 33%.

**Population and UK relevance.** Adults with insomnia disorder, mean age in the mid-40s, country not stated in the abstract. Magnetic stimulation of this sort is not a routine UK insomnia treatment. The result is a reason for a larger multicentre trial, not for a change in NICE insomnia practice.

Xu T et al. Electroacupuncture combined with cognitive behavioural therapy for insomnia alleviates insomnia-anxiety comorbidity in gynaecological cancer patients undergoing chemotherapy. *Current Oncology*. E-pub 19 October 2026. Indexed 26 October 2026. PMID 42930195. DOI 10.3390/curroncol33100628.

**Findings.** Seventy-six women on chemotherapy for gynaecological cancer received electroacupuncture plus cognitive behavioural therapy for insomnia, or sham electroacupuncture plus the same therapy, for four weeks. The between-group difference in Pittsburgh score change was −3.11 (95% CI −4.11 to −2.11). Athens score of 6 or under was reached in 71.1% versus 42.1% (p = 0.010). Hamilton anxiety of 14 or under was reached in 92.1% versus 65.8% (p = 0.005). Overall response was 92.1% versus 71.1% (p = 0.016). No serious adverse events.

**Appraisal.** Randomised trial with a sham and an active behavioural therapy in both arms, so the contrast is the needling. n = 76 and four weeks limit durability claims. Several binary endpoints are reported; the abstract identifies Pittsburgh change as a lead result but does not describe multiplicity adjustment. Country is not stated.

**Population and UK relevance.** Women with gynaecological cancer on chemotherapy. Relevant to UK psycho-oncology as a research signal. It is not evidence about insomnia in the general adult population, and electroacupuncture access in the NHS is limited.

Cai J et al. Indirect moxibustion therapy improves insomnia and associated symptoms in patients with schizophrenia. *Trials*. E-pub 29 July 2026. Indexed 26 October 2026. PMID 42928360. DOI 10.1186/s13063-026-09915-w.

**Findings.** Single-centre trial at Shanghai Mental Health Center. One hundred and twenty adults with schizophrenia and insomnia were randomised to indirect moxibustion or sham, for eight weeks, on a background of low-dose dexzopiclone. Pittsburgh scores at week 8 were 10.65 ± 1.54 versus 12.77 ± 2.05. The adjusted change difference was −3.399 (95% CI −4.078 to −2.719) at week 4 and −2.115 (−2.795 to −1.435) at week 8. Quality-of-life scores moved in the same direction (all adjusted p < 0.001). Registered NCT06171308.

**Appraisal.** Randomised sham-controlled trial. Blinding of a heat-based treatment is difficult, and the abstract does not report blinding success. Both arms received a hypnotic, so the result is adjunctive. The week-8 gap is smaller than the week-4 gap. *Trials* often publishes protocols; this record’s abstract reports results, which should be confirmed against the full text before the numbers are cited in a guideline.

**Population and UK relevance.** Chinese specialist mental-health patients. Poor sleep in schizophrenia is relevant to UK mental-health wards. Moxibustion is not standard NHS care, and a single Shanghai centre does not establish generalisability.

Albalak G et al. The effect of physical activity timing on insomnia and sleep quality: a randomized cross-over trial in older adults. *Sleep Medicine*. E-pub 23 October 2026. Indexed 27 October 2026. PMID 42945713. DOI 10.1016/j.sleep.2026.109332.

**Findings.** Adults aged 60–80 with an Insomnia Severity Index of at least 10 did coached activity at 10:00–11:00 or 19:30–20:30 for 14 days each. Sleep data were available for 31 people (mean age 69.8 ± 5 years; 64.5% women). Estimated mean insomnia scores were 14.44 at baseline, 12.37 in an inactive period, 11.87 after morning activity and 12.35 after evening activity. Morning versus evening insomnia difference was β 0.55 (95% CI −0.80 to 1.91). Sleep midpoint was 3:54 a.m. after morning activity and 4:13 a.m. after evening activity. Subjective quality and dim-light melatonin onset did not differ.

**Appraisal.** Randomised crossover, objective under-mattress recording plus daily ratings. n = 31 and 14 days give a narrow test of timing. The insomnia contrast’s interval includes no difference. The abstract labels the midpoint coefficient as “β 0.31 min” (95% CI 0.14 to 0.48). A coefficient of 0.31 minutes does not match a 19-minute gap between 3:54 and 4:13. The clock times are reported here; the unit on the coefficient needs the full text.

**Population and UK relevance.** Older adults with insomnia symptoms, country not stated, likely a research volunteer sample given the melatonin assay. Relevant to UK advice on exercise timing only as a negative result: this trial did not show that morning or evening activity was better for insomnia severity.

Ntoumas I et al. Weighted blanket load and sleep outcomes during daytime napping and overnight sleep: two randomized crossover studies. *Healthcare (Basel)*. E-pub 13 October 2026. Indexed 27 October 2026. PMID 42940462. DOI 10.3390/healthcare14203416.

**Findings.** Twenty healthy young adults tried 7 kg, 9 kg and 14 kg blankets for a 30-minute laboratory nap, and another 20 tried them overnight at home, against control blankets, with portable polysomnography. Nap sleep did not differ. For overnight sustained sleep efficiency, a gender-adjusted model on seven complete cases gave F(1.929, 9.646) = 14.223, p = 0.001, partial η² = 0.740. A sensitivity model without gender, on the same seven cases, was F(3, 18) = 0.630, p = 0.605. A Friedman test also failed to confirm the effect. Systolic pressure was lower after the 9 kg night. The authors call the efficiency result exploratory and model-dependent.

**Appraisal.** Two small randomised crossovers. The manuscript is unusual in reporting that its own main positive overnight finding does not survive a pre-stated sensitivity analysis. That is the correct conclusion: there is no confirmatory evidence here that blanket weight changes objective sleep.

**Population and UK relevance.** Healthy young adults, not patients with insomnia. Consumer weighted blankets are already used in the UK. This study does not support a clinical claim.

### Trials in which sleep was measured alongside another target

Rastegar M et al. Investigating the effect of oral probiotic capsules on postpartum sleep quality in primiparous women: a triple-blind randomised controlled trial. *Sultan Qaboos University Medical Journal*. E-pub 12 October 2026. Indexed 28 October 2026. PMID 42948779. DOI 10.18295/2075-0528.3013.

**Findings.** Sixty first-time mothers in Mashhad, Iran, took a multi-strain probiotic or placebo daily from day 3 for 30 days. Baseline Pittsburgh scores were 9.66 ± 6.21 (probiotic) and 11.70 ± 6.68 (placebo). After treatment they were 6.16 ± 2.75 (change −3.50 ± 5.53) and 6.60 ± 2.66 (change −5.10 ± 6.31). The abstract assigns p = 0.003 to a difference between the intervention group and placebo, and concludes that the probiotic improved sleep. Groups differed in body mass index at baseline. The authors say other demographic and obstetric variables were balanced.

**Appraisal.** Triple-blind randomised trial, n = 60, appropriate in design. The reported mean improvement is larger in the placebo arm, while the conclusion says the probiotic improved sleep. The p value cannot be interpreted until the full text shows which contrast was tested. This result should not be cited as evidence that probiotics improve postpartum sleep.

**Population and UK relevance.** Iranian first-time mothers in the first month after birth. Even if the numbers were consistent, this would be a poor guide to the general UK adult population, and only a partial guide to UK postnatal care.

Ziaie S et al. Effect of melatonin on 24-hour urinary protein excretion and sleep quality in patients with stage 3–4 chronic kidney disease. *Health Science Reports*. E-pub 29 October 2026. Indexed 31 October 2026. PMID 42964503. DOI 10.1002/hsr2.73458.

**Findings.** Seventy-three adults with stage 3–4 chronic kidney disease and proteinuria took melatonin 3 mg at night or placebo for 12 weeks. The primary endpoint, change in 24-hour urinary protein, fell by 52.45 ± 128.19 mg/day with melatonin and 28.69 ± 82.59 mg/day with placebo (difference −23.76 mg/day, 95% CI −74.08 to 26.56; p = 0.92). Pittsburgh score changed by −0.18 ± 0.84 with melatonin and −0.69 ± 1.06 with placebo (p = 0.047). Total cholesterol fell more with melatonin; the abstract gives no cholesterol numbers. Registered IRCT20160412027346N12.

**Appraisal.** Double-blind randomised trial with a prespecified renal primary endpoint, which the confidence interval shows was not demonstrated. The sleep comparison favours placebo on the mean change. A significant cholesterol finding without a reported size is not usable. Multiple secondary endpoints.

**Population and UK relevance.** Adults with non-dialysis stage 3–4 kidney disease, Iranian registry. Relevant to UK renal clinics as a negative primary result. It does not support melatonin as a sleep treatment in this group.

Kang EB et al. Effects of oral L-arginine on everyday persistent fatigue, sleep, and post-exercise lactate recovery in community-dwelling working-age adults. *Nutrients*. E-pub 14 October 2026. Indexed 27 October 2026. PMID 42942946. DOI 10.3390/nu18203375.

**Findings.** One hundred and twenty adults aged 30–59 with persistent fatigue were randomised to L-arginine 3 g/day, 6 g/day or placebo for eight weeks; 119 were analysed. The primary Fatigue Severity Scale fall was greater for 6 g/day than placebo (−6.41 versus −2.23; Holm-adjusted p = 0.024). Pittsburgh sleep scores “improved nominally” (3 g/day p = 0.007; 6 g/day p = 0.045). Mean fatigue scores stayed above the entry threshold. No serious adverse events.

**Appraisal.** Double-blind randomised trial with a stated multiplicity adjustment. The abstract’s word “nominally” means the sleep p values should not be read as confirmatory. Sleep was secondary.

**Population and UK relevance.** Community-dwelling working-age adults with fatigue, country not stated. A supplement trial in tired adults is a weak guide to UK insomnia care.

Liu Q et al. Effects of probiotic supplementation on depression, anxiety, and sleep quality in healthy participants: a systematic review and meta-analysis. *Pharmacological Research*. E-pub 29 October 2026. Indexed 29 October 2026. PMID 42956862. DOI 10.1016/j.phrs.2026.109716.

**Findings.** Twenty randomised trials, 1,508 healthy adults, probiotics versus placebo for at least four weeks. Sleep-quality standardised mean difference −0.37 (95% CI −0.52 to −0.22; I² = 41.67%). Depression −0.23 (−0.36 to −0.10; I² = 4.67%). Anxiety −0.11 (−0.31 to 0.09; p = 0.27; I² = 61.41%). GRADE: moderate for depression and sleep, very low for anxiety. Searches to 18 September 2026.

**Appraisal.** Review of trials. Random-effects or fixed-effects chosen by heterogeneity, which can inflate false confidence, but the sleep interval is away from zero and heterogeneity is moderate. Strains and durations are mixed, and the authors say subgroup claims are exploratory. Healthy volunteers inflate apparent benefit relative to clinical insomnia.

**Population and UK relevance.** Healthy adults, not NHS insomnia patients. A small average effect on questionnaire sleep in well people is not a reason to prescribe probiotics in UK sleep clinics.

### Observational insomnia and UK cohorts

Koye A et al. UK Medical Cannabis Registry: a two-year prospective observational cohort study of clinical outcomes in insomnia. *Neuropsychopharmacology Reports*. Publication date December 2026. Indexed 27 October 2026. PMID 42935025. DOI 10.1002/npr2.70180.

**Findings.** Two hundred and eleven people prescribed cannabis-based medicinal products for insomnia were followed on the UK Medical Cannabis Registry. At baseline, 126 (59.72%) already used cannabis. Single-item sleep quality rose from 2.46 ± 2.10 to 5.14 ± 2.75 at 24 months (mean difference +2.68, 95% CI 2.23–3.14; p < 0.001), with improvement at every reported time point. Baseline scores of 0 (odds ratio 15.49, 95% CI 3.87–65.19) or 1–3 (4.90, 1.87–13.80), and dried-flower products (4.99, 1.27–21.39), were associated with a clinically significant sleep-quality gain at 24 months. Seventeen people (8.06%) reported adverse events. Age over 60 was associated with reporting an adverse event (odds ratio 19.08, 95% CI 1.52–535.75).

**Appraisal.** Prospective cohort without a control group. The authors state that placebo effects, regression to the mean and selection bias cannot be excluded. The adverse-event odds ratio for older age has a confidence interval too wide to guide counselling. p < 0.05 is treated as the significance rule for several time points. This is not evidence of efficacy.

**Population and UK relevance.** UK adults prescribed these products, mostly people who had already used cannabis, in a self-selected registry rather than a random NHS sample. Relevant to UK private prescribing governance. It does not describe the general UK adult population, and it is not a basis for NHS commissioning.

Read AT et al. Prevalence and factors associated with excessive daytime somnolence in adults with HIV: a single-centre UK observational study. *International Journal of STD & AIDS*. E-pub 29 October 2026. Indexed 29 October 2026. PMID 42955910. DOI 10.1177/09564624261499398.

**Findings.** Adults with HIV attending the Royal Free London outpatient service, May 2018 to October 2019. Of 313 participants (median age 52, body mass index 25.9 kg/m², 80% male), Epworth score over 10 was present in 72 (23%, 95% CI 18.5–28.1). Independent associations were male sex (odds ratio 3.45, 95% CI 1.36–8.95), poor sleep quality (1.12, 1.02–1.22) and fatigue (1.04, 1.01–1.06). A sleep study was done in 50 people, of whom 27 had OSA. The minimum prevalence of OSA in the whole sample was 27/313 (8.6%).

**Appraisal.** Cross-sectional clinic survey with logistic regression. Sleep studies were selective, so 8.6% is a floor, not a prevalence. Odds ratios for questionnaire scales are per point and look small because the scales have many points. Fieldwork is seven years old; indexing is what is new.

**Population and UK relevance.** Directly relevant to UK HIV clinics, and specifically to one London centre with a male-majority, middle-aged cohort. Not the general UK adult population. Mental-health symptoms travelled with sleepiness, which matters for how clinics screen.

Bayala YLT et al. Sleep disorders in patients with systemic sclerosis: a systematic review and meta-analysis. *Joint Bone Spine*. E-pub 27 October 2026. Indexed 27 October 2026. PMID 42946201. DOI 10.1016/j.jbspin.2026.106152.

**Findings.** Twenty-three studies, 1,487 adults with systemic sclerosis in all analyses. Poor sleep on the Pittsburgh index, from 11 studies and 820 patients, had a pooled prevalence of 76.49% (95% CI 66.62–84.13; I² = 70.1%; prediction interval 49.66–91.47%). OSA, from five studies and 346 patients, was 40.30% (25.56–57.04; I² = 71.8%; prediction interval 13.95–73.75%). Trim-and-fill moved the poor-sleep estimate to 69.62% (57.33–79.63%). GRADE certainty was low. Registered CRD420251152354. Searches to 15 February 2026.

**Appraisal.** Review of observational prevalence studies, logit random effects, Hartung-Knapp adjustment, Egger test. The authors use a prediction interval and a low GRADE rating, which is appropriate. The intervals are too wide for a single service percentage.

**Population and UK relevance.** Adults with a rare autoimmune disease. Relevant to UK rheumatology and sleep liaison. Not generalisable to adults without systemic sclerosis.

Malasevskaia I et al. The association between sleep and obesity in adults: an umbrella review of meta-analyses. *Health Science Reports*. E-pub 27 October 2026. Indexed 28 October 2026. PMID 42948184. DOI 10.1002/hsr2.73449.

**Findings.** Sixteen systematic reviews with meta-analysis, about 13.8 million adults. Primary-study overlap was low (corrected covered area 0.024). Short sleep was associated with obesity (pooled odds ratio 1.40, 95% CI 1.27–1.55; I² = 83.7%) and long sleep more weakly (1.05, 1.02–1.08; I² = 0%). Both were graded Class III (suggestive) on the Ioannidis scale. Napping, social jetlag and insomnia symptoms were Class IV (weak). Polysomnography studies gave a larger odds ratio (2.70, 1.80–4.05) than self-report (1.14, 0.98–1.33). AMSTAR 2: two high, four moderate, nine low, one critically low. Searches to 1 March 2026.

**Appraisal.** Umbrella review of observational meta-analyses. The grading system stops the authors calling this convincing, which matches the heterogeneity and the low AMSTAR scores of most included reviews. The polysomnography estimate is a selected subset. **Verification:** the abstract prints the PROSPERO number as CRD420261326462, which has an unusual number of digits and should be checked before it is cited.

**Population and UK relevance.** Adults in the included reviews, heavily weighted to self-reported sleep. Short sleep and obesity co-occur in UK population data as well. This review does not show that lengthening sleep would reduce UK obesity.

Amelia VL et al. Associations of circadian clock genes with the risk of depression in adults with sleep disturbances: a systematic review and meta-analysis. *Psychiatry Research*. E-pub 17 October 2026. Indexed 31 October 2026. PMID 42966074. DOI 10.1016/j.psychres.2026.117535.

**Findings.** Twenty-three studies. The abstract says eight genes (CLOCK, NR1D, TIM, CRY, PER2, PER3, ARNTL and CSNK1) were associated with depression in adults with sleep disturbance, and RORA was not. The largest pooled odds ratio named is for CRY, 1.6 (95% CI 1.4–1.8). Searches to 10 July 2025. Registered CRD42023472328.

**Appraisal.** Review of genetic association studies. The abstract does not give the number of people, the genetic model, or I². Candidate-gene meta-analyses are vulnerable to small-study bias and population stratification. Overlapping confidence intervals mean “highest odds ratio” is not a demonstrated ranking. Treat as hypothesis-generating until the full tables are checked.

**Population and UK relevance.** Adults with sleep disturbance in genetic studies, ancestry mix not stated. Not a test, and not relevant to routine UK prescribing.

### Sleep health measurement

Kolko Conlon RP et al. Psychometric validation of the Ru-SATED 4.0 multidimensional sleep health scale in a representative U.S. sample. *Sleep*. E-pub 29 October 2026. Indexed 29 October 2026. PMID 42954867. DOI 10.1093/sleep/zsag285.

**Findings.** Ru-SATED 4.0 covers regularity, satisfaction, alertness, timing, efficiency and duration. Cognitive interviews used 23 adults. The survey used 2,000 adults aged 18–89 from the YouGov US panel, balanced to US age, sex, race/ethnicity and education. A six-item factor model fitted well (RMSEA 0.08, SRMR 0.03, CFI 0.97, TLI 0.95). Internal consistency is reported as r = 0.7, one-month test-retest as r = 0.6, correlations with other sleep scales as absolute r 0.3–0.6, and with depression or anxiety as absolute r 0.3–0.4. People with and without a self-reported sleep disorder differed by Cohen’s d = 0.93, with the interval printed as −1.04 to −0.81.

**Appraisal.** Instrument development using item-response theory and classical test theory, which is the right toolkit. Test-retest of 0.6 is modest for a scale that might be used to track a patient. **Verification:** a positive d with an entirely negative confidence interval is inconsistent as printed and needs the full paper. Representativeness is on demographics, not on health.

**Population and UK relevance.** US adults. A UK service would need a UK calibration before using scores as thresholds. The six dimensions themselves match how UK sleep clinics already talk about sleep health.

Yamada T et al. Prefrontal Glx reduction during the sleep transition is associated with sleep-onset latency. *Journal of Neuroscience*. E-pub 28 October 2026. PubMed record created 24 September 2026. PMID 42785995. DOI 10.1523/JNEUROSCI.0372-26.2026.

**Findings.** Twenty healthy young adults (12 women) had two afternoon naps with polysomnography and medial prefrontal magnetic resonance spectroscopy, using the first-night effect as a within-person disruption. Sleep-onset latency was longer on the first nap. Glutamate plus glutamine fell from wake to sleep on the second nap and did not fall on the first. Larger falls tracked shorter sleep-onset latency and statistically accounted for the session difference. GABA did not change and was not associated with latency.

**Appraisal.** Within-subject experimental neuroscience, n = 20, afternoon naps rather than nocturnal sleep. Mediation in 20 people is fragile. Appropriate as a mechanism paper. No clinical endpoint beyond latency in the laboratory.

**Population and UK relevance.** Healthy young adult volunteers. Not generalisable to UK adults with insomnia. Included because the electronic publication date is 28 October 2026.

---

## 8. Bruxism and sleep bruxism

The index week did not contain a primary adult bruxism trial or cohort. The botulinum-toxin narrative below entered PubMed on 26 October. The other records are the newest adult bruxism papers by electronic publication date, working backwards from 2 November 2026. Issue dates of “November 2026” were ignored when the electronic publication was earlier.

A bruxism-and-depression meta-analysis (PMID 40817890, DOI 10.11607/ijp.9385) has a September 2026 issue date but was indexed on 16 August 2025. It is not treated as new. An orthodontic cohort (PMID 41979177) was electronically published on 14 April 2026 and was not appraised.

### In the index window

Yoshida K. The stomatognathic system as an expanding frontier for botulinum toxin therapy. *Toxins (Basel)*. E-pub 2 October 2026. Indexed 26 October 2026. PMID 42931519. DOI 10.3390/toxins18100428.

**Findings.** Narrative review of botulinum toxin for oromandibular dystonia, bruxism, masticatory pain, salivary disorders and aesthetic masseter use. The author states that evidence and licensing vary by indication and that many uses are off-label. OnabotulinumtoxinA has been approved in Japan for masseter prominence in adults under 65.

**Appraisal.** Narrative review. No new pooled bruxism estimate and no doses that should be copied into practice. Safety and licensing comments are qualitative.

**Population and UK relevance.** Adults, mixed indications. Relevant to UK oral surgery and neurology only as a map of how far practice has run ahead of trials. It is not evidence for routine toxin treatment of sleep bruxism in NHS dentistry.

### Newest primary studies

Lamaison C et al. Sleep and awake bruxism and mental health conditions: a cross-sectional analysis of the 1982 Pelotas birth cohort. *Journal of Dentistry*. E-pub 25 October 2026. Indexed 25 October 2026. PMID 42927863. DOI 10.1016/j.jdent.2026.107135.

**Findings.** At age 40 in the 1982 Pelotas Birth Cohort, southern Brazil, self-reported awake bruxism and sleep bruxism were more prevalent in women (prevalence ratio 1.48, 95% CI 1.27–1.72, and 1.47, 1.27–1.70) and in people with alcohol dependence (1.47, 1.09–1.99, and 1.34, 1.00–1.79). Depression was associated with awake bruxism (1.50, 1.10–2.05) and sleep bruxism (1.41, 1.05–1.90). Probable common mental disorder at both age 30 and age 40, versus never, had prevalence ratios of 2.02 (1.62–2.52) for awake bruxism and 1.52 (1.23–1.88) for sleep bruxism.

**Appraisal.** Cross-sectional analysis of bruxism inside a birth cohort, with mental-health measures repeated at 30 and 40. Poisson models with robust variance match a common outcome. Bruxism is self-reported, so shared reporting with mood can inflate the association. No polysomnography.

**Population and UK relevance.** A near-complete Brazilian birth cohort at 40 is a stronger population sample than a dental clinic, but schooling, alcohol and dental services differ from the UK. The pattern, women and persistent mental-health symptoms, is a fair prompt for UK dentists to ask about mood. It is not a UK prevalence.

Wang J et al. Botulinum toxin type A injection for bruxism following left basal ganglia hemorrhage. *American Journal of Case Reports*. E-pub 10 October 2026. Indexed 10 October 2026. PMID 42855873. DOI 10.12659/AJCR.953163.

**Findings.** A 40-year-old man developed bruxism about three months after a large left intracerebral haemorrhage and decompressive surgery. Caregiver report, masseter hypertrophy, tooth wear and surface electromyography were organised with the Standardised Tool for the Assessment of Bruxism. Splint and heat had not helped. Electromyography-guided onabotulinum toxin, 50 units each masseter in three sites, was followed by less tension and tenderness at 48 hours, still present at six months.

**Appraisal.** Single case, level of a case report. Temporal association is not efficacy. No control and no systematic adverse-event capture beyond this patient.

**Population and UK relevance.** One younger adult after stroke. Relevant only to specialist neurorehabilitation as a hypothesis. Not the general UK adult population.

Machado E et al. Is sleep bruxism associated with general quality of life? Insights from the EPISONO population-based study. *Journal of Oral Rehabilitation*. E-pub 2 October 2026. Indexed 2 October 2026. PMID 42827092. DOI 10.1111/joor.70335.

**Findings.** Of 712 adults in the São Paulo Epidemiological Sleep Study follow-up (2015), 692 completed WHOQOL-Bref (mean age 50.1 years; 385 women). Self-reported sleep bruxism was associated with lower satisfaction with health (rate ratio 0.93, 95% CI 0.88–0.98) and lower social-relationship scores (0.95, 0.92–0.99). Polysomnographic sleep bruxism, alone or combined with self-report, was not associated with quality-of-life scores. Adjusted Poisson models.

**Appraisal.** Cross-sectional analysis of a population sleep cohort. The dissociation between self-report and polysomnography is the important result and argues against treating a questionnaire “yes” as the same exposure as confirmed sleep bruxism. Rate ratios near 1 on a quality-of-life scale are small. Data collection was 2015; the paper is what is new.

**Population and UK relevance.** Urban Brazilian adults in a population sample. Closer to “general adults” than a clinic, and still not the UK in dental attendance or comorbidity. UK clinics should not assume that polysomnography-confirmed bruxism lowers quality of life to the degree self-report suggests.

Waller D et al. Associations between wake-time and sleep-time masticatory muscle activity and clinical correlates in free-living adults. *Journal of Oral Rehabilitation*. E-pub 27 September 2026. Indexed 27 September 2026. PMID 42802104. DOI 10.1111/joor.70325.

**Findings.** Thirty adults (mean age 31.4 ± 11.2 years) who screened high on the Oral Behaviours Checklist contributed 77 free-living electromyography sessions. Sleep-time and wake-time episode frequency, duty time and rhythmic masticatory activity remained associated after adjustment. Tooth wear had little association once age and sex were included. Higher sleep-time rhythmic activity was associated with muscle pain on waking. Activity was not associated with perceived stress, anxiety or the oral-behaviour score.

**Appraisal.** Repeated-measures observational study with a wearable. n = 30 and a high-behaviour sample limit precision and generalisability. Objective measurement is a strength. The null association with the very questionnaire used to recruit them is a useful warning about circular referral.

**Population and UK relevance.** Young and mid-adult volunteers with high self-reported oral behaviours, country not stated. Relevant to UK temporomandibular clinics that rely on questionnaires and tooth wear. Not a prevalence study.

Zhou S et al. Association between mandibular chewing patterns and sleep bruxism characteristics: a clinical observational study. *Sleep & Breathing*. E-pub 1 September 2026. Indexed 2 September 2026. PMID 42681265. DOI 10.1007/s11325-026-03792-y.

**Findings.** One hundred and twenty adults had daytime 3D jaw tracking and one-night laboratory polysomnography with masseter electromyography and audio-video. Versus bilateral alternating chewers, unilateral chewers had a higher bruxism episode index (median 3.2, interquartile range 2.2–4.6, versus 1.9, 1.2–2.8) and higher peak electromyography (38.4% ± 12.6% versus 29.1% ± 10.8% of maximum voluntary contraction). Irregular chewers had a higher tonic share (27.8% versus 14.3%) and longer episodes (8.9 ± 2.7 s versus 6.4 ± 2.1 s). Adjusted β for episode index was +0.88 and +1.21 episodes/h for unilateral and irregular patterns. Models included the apnoea-hypopnoea index.

**Appraisal.** Cross-sectional, one night, which is a weak gold standard for bruxism. Multivariable regression with a sensible covariate list is described. Multiple bruxism metrics raise a multiplicity issue the abstract does not address. Country is not stated.

**Population and UK relevance.** Adults able to attend a laboratory, not a stated population sample. A daytime chewing pattern is not a UK diagnostic test. The result is a research lead.

### Latest syntheses and a methods paper

These three were electronically published in July 2026. They are included because nothing newer of the same type appeared in the index week.

Li D et al. Pharmacologic management of sleep bruxism in adults: a systematic review and meta-analysis of polysomnographic outcomes. *Journal of Oral Rehabilitation*. E-pub 5 July 2026. Issue date September 2026. Indexed 6 July 2026. PMID 42402887. DOI 10.1111/joor.70254.

**Findings.** Nine studies, 116 adults, six of them randomised crossovers. Searches to March 2025. Certainty was low to very low. Clonidine showed the most consistent but modest reduction in sleep-bruxism frequency. Benzodiazepines, dopaminergic drugs and beta-blockers showed no reproducible benefit. Gabapentin reduced rhythmic masticatory activity and improved sleep efficiency in one non-randomised study. No serious adverse events were reported. Exposure was mostly a single night or a short course. The authors say no medicine can be recommended for routine management, ahead of counselling, behavioural strategies and occlusal appliances. Registered CRD420251168064.

**Appraisal.** Review of trials with polysomnographic outcomes, which is the right endpoint and also why the evidence is tiny. “Meta-analysis” in the title sits on a very small randomised subset. Short exposure cannot inform chronic NHS prescribing.

**Population and UK relevance.** Adults with polysomnography-confirmed sleep bruxism in experimental studies. Directly relevant as a brake on medication use in UK dentistry and neurology. Not a general-population prevalence.

Pereira KK et al. Possible association between obstructive sleep apnea syndrome and sleep bruxism in adults: an umbrella review. *Sleep Medicine*. E-pub 9 July 2026. Issue date November 2026. Indexed 14 July 2026. PMID 42447651. DOI 10.1016/j.sleep.2026.109129.

**Findings.** From 1,726 records, eight systematic reviews in adults were included, one with a meta-analysis. Most reported that sleep bruxism and OSA often occur together, with micro-arousals and autonomic activation offered as a shared mechanism. Causality was not shown. AMSTAR-2 quality was mostly low or critically low. Three reviews had low risk of bias on ROBIS. Searches covered 2000 to January 2026 and required polysomnography in the eligible reviews.

**Appraisal.** Umbrella review of observational syntheses. The authors’ own quality ratings are the main result: coexistence is frequently reported and poorly proven. No new pooled odds ratio is given in the abstract.

**Population and UK relevance.** Adults in the included reviews. UK sleep and dental services often see both problems. This review supports asking the question, not treating one in order to cure the other.

Emodi-Perlman A et al. Towards optimized awake bruxism metrics: empirical definition of minimal ecological momentary assessment requirements. *Journal of Oral Rehabilitation*. E-pub 9 July 2026. Issue date November 2026. Indexed 10 July 2026. PMID 42427139. DOI 10.1111/joor.70263.

**Findings.** Three smartphone ecological-momentary-assessment studies were pooled, 327 participants and more than 32,000 reports. Relaxed jaw muscles were reported on 52.2% of prompts, teeth contact 18.6%, bracing 14.5%, clenching 6.9% and grinding 1.4%. Four of five behaviours had intraclass correlation at least 0.86 by three days. Grinding reached 0.81 at two days. A minimum of 12 answered prompts a day gave the authors’ preferred balance of reliability and retention.

**Appraisal.** Methods paper using intraclass correlations against a seven-day reference. Appropriate for a measurement question. Pooled studies may not share a sampling frame. Reliability is not validity against electromyography.

**Population and UK relevance.** Adults who will use a research app, with a young-adult skew suggested by the behaviour mix but not proven from the abstract. Useful if a UK dental study wants a shorter diary. Not a prevalence for UK adults.

### Partly outside the adult scope

García-Moya J et al. Diagnosis of awake bruxism in adolescents and young adults: a systematic review. *Dentistry Journal (Basel)*. E-pub 18 September 2026. Indexed 24 September 2026. PMID 42782993. DOI 10.3390/dj14090606.

**Findings.** Thirteen studies of diagnostic methods in people under 35 were eligible; 11 remained after two high-bias studies were removed. Self-report, ecological momentary assessment, clinical examination and portable electromyography were the main methods. The authors say there is no gold standard and favour a multimodal approach. PROSPERO registration is stated; the number is not in the abstract.

**Appraisal.** Systematic review of diagnostic studies, with JBI, RoB 2 and QUADAS-2 named. Qualitative synthesis only. Age mix is the scope problem.

**Population and UK relevance.** Adolescents and young adults under 35. Only the young-adult portion sits inside this sweep. Do not apply the conclusions to middle-aged or older UK adults without further evidence.

---

## 9. Other sleep disorders

### Narcolepsy

Romero H et al. Psychometric properties of the novel patient-reported Functional Impacts of Narcolepsy Instrument (FINI) using data from phase 3 clinical trials in narcolepsy type 1. *Frontiers in Neurology*. E-pub 15 October 2026. Indexed 30 October 2026. PMID 42959371. DOI 10.3389/fneur.2026.1884901.

**Findings.** FINI is a 28-item patient-reported scale with six domains: tiredness, cognitive functioning, cataplexy, social activities, everyday activities and everyday responsibilities. Pooled data came from two phase 3 trials of oveporexton in narcolepsy type 1 (n = 167, NCT06470828; n = 105, NCT06505031). Factor structure was supported. Most domains had Cronbach’s alpha at least 0.78; everyday activities was 0.63 at the bottom of a 0.63–0.90 range. Test-retest intraclass correlations were at least 0.70 in people who rated themselves stable. Meaningful within-patient change thresholds, as ranges, were about −35 for tiredness and everyday activities, −30 for cognition and everyday responsibilities, −25 for social activities and −20 for cataplexy.

**Appraisal.** Psychometric validation inside industry phase 3 trials. The methods named (known groups, convergence, item consistency, responsiveness, anchor-based change) are appropriate. Trial participants are cleaner and more severe than clinic lists. This paper does not report whether oveporexton works; using it as efficacy evidence would be a mistake.

**Population and UK relevance.** Adults with narcolepsy type 1 in two phase 3 trials. Relevant if a UK centre uses the same instrument. Not a description of UK narcolepsy prevalence or NHS outcomes.

### REM sleep behaviour disorder

Byun JI et al. Gray matter alterations and their atlas-based spatial associations with neurotransmitter distributions in isolated REM sleep behavior disorder. *Sleep & Breathing*. E-pub 29 October 2026. Indexed 31 October 2026. PMID 42965716. DOI 10.1007/s11325-026-03845-2.

**Findings.** Structural MRI in 109 adults with isolated REM sleep behaviour disorder who had at least one follow-up, and 24 age- and sex-matched controls. At baseline, grey-matter volume was lower in the right cerebellar cortex and vermis and higher in the left putamen and pallidum. Those maps correlated spatially with dopamine D2 and dopamine-transporter atlases. People who later phenoconverted had lower baseline volume in the right medial orbital gyrus, and that map correlated with several transmitter atlases. The phenoconversion analysis is described as exploratory.

**Appraisal.** Case-control imaging plus spatial correlation with published atlases. The atlases are not measurements in these patients, so “neurotransmitter” findings are anatomical overlap. Twenty-four controls is a thin reference. Multiple maps and transmitters need the correction scheme in the full text.

**Population and UK relevance.** Adults with isolated REM sleep behaviour disorder, a specialist cohort enriched for future Parkinson’s disease. Relevant to UK neurology research clinics. Not the general adult population.

Ascari F et al. Exploratory metabolomic and metagenomic profiling of fecal samples in isolated REM sleep behavior disorder. *Biomolecules*. E-pub 6 October 2026. Indexed 27 October 2026. PMID 42939710. DOI 10.3390/biom16101456.

**Findings.** Twenty-one adults with isolated REM sleep behaviour disorder and 15 controls. Branched-chain fatty acids were higher, linear short-chain fatty acids were not. Indole was lower; p-cresol and 2-octanone were higher. The microbiome had less *Blautia* and *Faecalibacterium* and more Oscillospirales. A multi-omics model separated the groups with 84.8% cross-validated accuracy inside this sample.

**Appraisal.** Exploratory cross-sectional multi-omics. Cross-validated accuracy in the same small discovery set is expected to shrink in a new sample. The authors call it hypothesis-generating and say phenoconversion was not tested. That reading should be kept.

**Population and UK relevance.** Specialist prodromal cohort, country not stated. No UK service implication beyond research biobanking.

### Periodic limb movements

Arslan Mehdiyev D et al. Respiratory burden and periodic limb movement frequency in adults with elevated PLMI: a retrospective polysomnographic study. *Sleep Medicine*. E-pub 22 October 2026. Indexed 26 October 2026. PMID 42933131. DOI 10.1016/j.sleep.2026.109329.

**Findings.** Consecutive adults with a periodic limb movement index of at least 15 events/h, n = 507. AHI was not associated with the limb-movement index (Spearman ρ = 0.003, 95% CI −0.08 to 0.09). Adjusted change in the limb-movement index was −0.2% per 10 AHI events/h (95% CI −2.2% to 1.8%). Limb-movement index did not differ by OSA severity (p = 0.63). AHI did not predict an index above 30 (odds ratio per 10 events/h 1.05, 95% CI 0.98–1.12). The interaction of limb-movement index and AHI on limb-movement arousals was positive (robust p < 0.001).

**Appraisal.** Retrospective consecutive series, restricted to people who already have frequent limb movements, so the association with AHI is estimated inside a truncated range. Spearman correlation, log-linear regression and a pre-stated interaction are appropriate. Scoring rules for limb movements in OSA are a known source of circularity; the abstract cannot show they were avoided.

**Population and UK relevance.** Sleep-laboratory adults with frequent limb movements, country not stated. Relevant to UK scoring policy: the abstract supports still counting limb movements when OSA is present, and reading arousal linkage more cautiously when AHI is high. Not a community prevalence.

---

## 10. Preprints, 26 October to 2 November 2026

These are not peer reviewed. Numbers below are from the preprint abstract retrieved on 2 November 2026. Two Europe PMC abstracts (daylight; iron and fatigue) were truncated in the record returned; nothing has been added past the truncation.

### Clinical and cohort preprints

Malik TH et al. Prototyping OSA: a new framework for predicting cardiovascular outcomes and CPAP benefit. medRxiv. Posted 30 October 2026. DOI 10.64898/2026.10.30.26366770.

**Findings.** Secondary analysis of the SAVE trial. Gaussian mixture models on 2,676 participants and 88 baseline variables selected five prototypes. Prototypes differed in smoking, diabetes, prior vascular disease, medicines, body mass index, oxygenation, AHI and Epworth score (overall p < 0.001), and in quality of life, Framingham score, major adverse cardiac events and a model-predicted CPAP effect. Prototype 5 was predicted to benefit (p < 0.05). Prototypes 1, 3 and 4 were predicted to have no benefit or possible harm.

**Appraisal.** Preprint. Unsupervised clustering plus a causal survival forest is a discovery method. “Harm” here is a model prediction, not a prespecified randomised contrast inside that subgroup. Five groups chosen by information criteria will look cleaner in the dataset that chose them. External validation is absent, and the authors say it is required.

**Population and UK relevance.** SAVE enrolled adults with OSA and cardiovascular disease. That is closer to UK secondary-prevention clinics than to the general population. It should not be used to withhold CPAP from a sleepy UK patient.

Wyss AB et al. Long sleep and insomnia are associated with reduced global cognitive function across diverse populations. medRxiv. Version 2 posted 29 October 2026. DOI 10.64898/2026.10.19.26365906.

**Findings.** Harmonised baseline data from HCHS/SOL, MESA and ARIC, n = 11,563. Long sleep (9 hours or more) was associated with lower baseline global cognition (β = −0.19, SE 0.03, p = 3.78×10⁻¹⁴) and with poor baseline cognition (odds ratio 1.77, 95% CI 1.49–2.09). Insomnia was associated with poor baseline cognition (1.22, 1.06–1.41; false-discovery-rate p = 0.05) with heterogeneity across studies (p = 0.03). Sleep measures were not associated with change in cognition.

**Appraisal.** Preprint meta-analysis of three cohorts. Cross-sectional associations with a null change result are a classic pattern when long sleep marks illness rather than causing decline. Adjustment is listed and does not include every comorbidity that leads people to spend more time in bed.

**Population and UK relevance.** US multi-ethnic cohorts, including Hispanic/Latino and older Black and White adults. Useful as a warning against reading long sleep as healthy. Not a UK incidence figure.

Ikurumi E et al. A transient decrease in night-to-night variability of REM sleep before myocardial infarction. medRxiv. Posted 28 October 2026. DOI 10.64898/2026.10.26.26366566.

**Findings.** In All of Us, 45 adults with a first myocardial infarction code and at least 180 Fitbit nights were matched to 450 controls. REM-fraction variability fell at days 30–16 before the infarct and moved back at days 15–1 (max-T p < 0.001 against 10,000 random dates). The fall in standard deviation had Cliff’s delta −0.30 (p = 0.004; odds ratio per SD 0.53, 95% CI 0.35–0.80). The authors report that a day-by-day continuous test was null (p = 0.58), that discrimination against a person’s own baseline reached an AUC of at most 0.66, and that this AUC is probably optimistic.

**Appraisal.** Preprint matched cohort with a heavy correction for having chosen the window. n = 45 events is small. Coding of infarcts in a research programme is imperfect. The authors’ own AUC and the null day-by-day test should travel with any mention of the finding. This is not a screening alert.

**Population and UK relevance.** US adults who wear a consumer sleep tracker. Richer, more device-connected and differently coded than the general UK adult population.

Brown EG et al., Parkinson’s Precision Medicine Initiative. Strategies to establish a biologically defined Parkinson’s disease cohort prior to motor symptoms. medRxiv. Posted 28 October 2026. DOI 10.64898/2026.10.26.26366535.

**Findings.** The initiative recruits polysomnography-confirmed REM sleep behaviour disorder and people with hyposmia. CSF alpha-synuclein seed-amplification positivity was 94% in REM sleep behaviour disorder plus hyposmia, 85% in hyposmia plus dream enactment, 40% in REM sleep behaviour disorder without hyposmia, and 55% in hyposmia without dream enactment. Among positive tests, the first two groups had more mood, autonomic and cognitive symptoms.

**Appraisal.** Preprint methods and enrichment paper. The percentages are clinically large. **Verification:** the abstract does not give the denominator for each percentage. Selection into a precision-medicine cohort inflates positivity relative to a community sample.

**Population and UK relevance.** Research volunteers enriched for prodromal Parkinson’s disease. Relevant to UK trial design. Not a prevalence of REM sleep behaviour disorder in UK adults.

Filchenko I et al. Bern Sleep-Wake Registry: temporal extraction of comorbidities from unstructured clinical text using a large language model. medRxiv. Posted 26 October 2026. DOI 10.64898/2026.10.25.26364496.

**Findings.** Annotations from 248 patients and 2,343 entries in the Bern Sleep-Wake Registry were used to test gpt-oss-20b for diagnosis and date extraction across six comorbidity groups. Patient-level F1 was 0.88 for presence of a diagnosis and 0.96 for presence of a date. Earliest-date agreement at day level was 86.73%. Full agreement on the set of dates was 58.19%, similar to human annotators (58.64%). The authors report a 94.65% cut in direct annotation cost.

**Appraisal.** Methods study with a physician reference standard and adjudication. Date-set agreement around 58% is the figure that should limit enthusiasm. A cost percentage depends on how staff time was priced. One model, one registry.

**Population and UK relevance.** Swiss sleep-centre patients. The task is relevant to UK sleep registries. The performance is not a licence to put this model into NHS notes.

Neilson L et al. The Portland SEEQ: a harmonizable questionnaire for environmental exposome profiling in prodromal synucleinopathy. medRxiv. Posted 28 October 2026. DOI 10.64898/2026.10.26.26366216.

**Findings.** Eighty-three adults with polysomnography-confirmed isolated REM sleep behaviour disorder completed a new exposure questionnaire. Definite or probable exposure was reported for pesticides in 38.6%, solvents in 43.4%, welding fumes in 21.0% and heavy metals in 34.1%. Among complete responders, 60.5% reported at least one direct exposure domain and 42.0% at least two. Greater burden tracked autonomic symptoms and did not track longitudinal clinical worsening.

**Appraisal.** Instrument paper, cross-sectional associations, self-reported exposure without external validation. The authors say larger studies are needed. Appropriate humility.

**Population and UK relevance.** Specialist US prodromal cohort. Occupational mixes differ from the UK. No change to UK history-taking beyond research.

Dhawale N et al. Between- and within-person coupling of nocturnal heart rate and glucose. medRxiv. Version 2 posted 27 October 2026. DOI 10.64898/2026.03.04.26347496.

**Findings.** Adults using an Ultrahuman ring and a continuous glucose monitor, January 2024 to June 2025: 2,648 people in 87 countries, 105,196 nights, after filters. A 10 beat/min higher sleeping heart rate was associated with higher nocturnal mean glucose within people (+5.7 mg/dL, 95% CI 5.4–5.9) and between people (+6.5 mg/dL, 5.6–7.3). Within-person glucose variability rose and time in a 70–110 mg/dL range fell. Of 911 sustained wearers, 701 (76.9%) had a positive personal slope.

**Appraisal.** Retrospective wearable cohort, mixed-effects models with person-mean centring, which is the right split of within- and between-person effects. Buyers of two consumer devices are a selected group. Glucose is reported in mg/dL. Version 2 of a March 2026 deposit; the posting in this window is the update.

**Population and UK relevance.** Affluent multi-country device users, not NHS patients. A within-person link between a faster sleeping heart rate and higher nocturnal glucose is biologically plausible and is not a UK screening programme.

Dhawale N et al. Objective sleep tracking for fatigue management in cargo pilots. medRxiv. Posted 30 October 2026. DOI 10.64898/2026.10.28.26366791.

**Findings.** Thirteen cargo pilots wore a smart ring for six months in 2026, 1,504 sleep sessions. Total sleep was 48 minutes shorter on the night before a flight (95% CI 32 to 65) and 28 minutes shorter on the first sleep after (13 to 43). Versus evening operations, sleep was 57 minutes shorter before a departure between 06:00 and 11:59 (14 to 101) and 97 minutes shorter after a landing between 00:00 and 05:59 (37 to 156). Differences between pilots explained 14.1% of sleep-time variance, duty position 2.2%.

**Appraisal.** Observational n = 13, linear mixed models. Intervals for the clock-time contrasts are wide. One operator and one device. No UK Civil Aviation Authority dataset.

**Population and UK relevance.** Commercial cargo pilots, country not stated. A specialist occupational group, not the general UK adult population. The pattern (short sleep before an early duty) matches what UK shift-work clinics already hear.

Sanchez SO et al. Diet quality scores are associated with sleep timing and regularity in emerging adults. medRxiv. Posted 28 October 2026. DOI 10.64898/2026.10.25.26366435.

**Findings.** Actigraphy in 106 adults (median age 22, IQR 2) and Pittsburgh scores in 122. Later sleep midpoint and bedtime were associated with lower DASH and Healthy Eating Index scores after adjustment for sex, body mass index and race (DASH β at least −0.165; Healthy Eating Index β at least −2.180; p ≤ 0.001). The abstract’s conclusion says higher sleep regularity is associated with better diet quality.

**Appraisal.** Cross-sectional student-age sample. Hierarchical regression is described. Diet diaries of at least three days are a weak exposure. The conclusion emphasises regularity, while the coefficients highlighted in the results are timing. That emphasis should be checked in the full preprint. Emerging adults are adults, and they are not representative of middle-aged UK patients.

**Population and UK relevance.** Young US adults, median age 22. Relevant to university health, not to a typical UK sleep-clinic list.

### Methods, diagnostic and disease-specific preprints

Deng G et al. A unified flexible large polysomnography model for sleep staging and downstream clinical screening. medRxiv. Version 5 posted 27 October 2026. Original DOI date 11 December 2024. DOI 10.1101/2024.12.11.24318815.

**Findings.** A model trained on 220,500 hours from 16 public datasets (24,000 recordings). Prospective staging kappa was 0.845 ± 0.066, against an inter-expert kappa of 0.850 ± 0.102. Three-class narcolepsy accuracy was 84.2% (kappa 0.761). Severe OSA screening without respiratory signals had an area under the curve of 0.874. Depression screening was 0.801 in a surrogate-labelled cohort and 0.965 on transfer to a clinically diagnosed cohort.

**Appraisal.** Preprint, version 5 of a deposit that began in December 2024. The staging comparison with experts is the most credible claim. Downstream areas under the curve, especially 0.965, need a leakage and case-mix check that the abstract cannot provide. Not a regulated device.

**Population and UK relevance.** Training data are public research polysomnography, not NHS recordings. Performance will move if UK montages and scoring rules differ. Included because a new version was posted inside the window.

A lightweight convolutional-recurrent network for automatic sleep staging from single-channel EEG. Research Square. Posted 27 October 2026. DOI 10.21203/rs.3.rs-11080933/v1. Author list was not extracted from the core record used here.

**Findings.** A 0.33-million-parameter model on Fpz–Cz EEG. On Sleep-EDF Expanded, healthy sleepers: accuracy 85.2% (95% CI 84.6–85.8), macro-F1 0.81, kappa 0.80. In people with mild difficulty falling asleep: accuracy 82.7% (81.5–83.9), kappa 0.77, N1 F1 0.50. McNemar p = 0.21 versus a larger baseline.

**Appraisal.** Preprint technical validation on a public database. “Mild difficulty falling asleep” is not a clinic diagnosis of insomnia disorder. The authors say diagnosed insomnia and wearable hardware are untested.

**Population and UK relevance.** Research EEGs, mostly healthy sleepers. Not an NHS home-sleep device.

Sleep in progressive supranuclear palsy: a systematic review and meta-analysis of polysomnographic findings. Research Square. Posted 27 October 2026. DOI 10.21203/rs.3.rs-10499352/v1.

**Findings.** Eight studies, 183 adults with progressive supranuclear palsy and 158 controls. The abstract reports lower sleep efficiency, total sleep time and REM percentage, and higher wake after sleep onset, N1 percentage, REM latency and AHI. Sleep latency, N2, N3 and arousal index did not differ significantly. Pooled effect sizes are not in the abstract.

**Appraisal.** Preprint meta-analysis. Direction without a pooled estimate or I² is not enough to quote a magnitude. Small rare-disease literature, likely heterogeneous scoring.

**Population and UK relevance.** Adults with progressive supranuclear palsy, a rare condition seen in UK neurology. Not the general adult population. **Verification:** numeric pooled estimates were not in the abstract retrieved.

Iron deficiency, nocturnal breathing symptoms, and sleep apnea diagnosis in premenopausal women with fatigue or daytime sleepiness: cross-sectional analyses of NHANES 2005–2023. Research Square. Posted 27 October 2026. DOI 10.21203/rs.3.rs-11508928/v1.

**Findings.** Survey-weighted analyses of 6,260 premenopausal women in NHANES. Ferritin under 30 or under 50 ng/mL was not independently associated with fatigue and/or daytime sleepiness (adjusted odds ratios 0.70–1.28, intervals including 1). In 2005–2008, a breathing-symptom index was associated with the composite outcome (adjusted odds ratio per point 1.39, 95% CI 1.14–1.69) and was not clearly associated with fatigue alone (1.22, 0.99–1.49). Of women with frequent breathing symptoms (9.9%), 39.8% had told a doctor about trouble sleeping and 14.0% reported a sleep-apnoea diagnosis.

**Appraisal.** Preprint of a complex survey. The ferritin result is a set of intervals that include no association. The breathing analysis is labelled exploratory and is confined to older cycles. Self-report of a diagnosis undercounts OSA. The Europe PMC abstract was truncated mid-sentence at the end; no text beyond that truncation is used here.

**Population and UK relevance.** US premenopausal women. Relevant to UK primary care as a prompt not to stop at a normal ferritin when a tired woman snores or pauses. NHANES is not the NHS.

Daylight exposure improves sleep and subsequent sleepiness. bioRxiv. Posted 27 October 2026. DOI 10.64898/2026.10.22.761062.

**Findings.** Ten healthy adults (4 men; ages 19–28) took two randomised 3-hour afternoon outdoor walks with clear or heavily filtered goggles, timed from each person’s dim-light melatonin onset. Melatonin timing and the phase angle to sleep onset did not differ. Sleep duration and self-rated sleep quality did not differ. After the brighter walk, delta power accumulated faster, NREM sleep was greater and wake after sleep onset was lower (all p < 0.01). Sleepiness on waking was lower (p < 0.05).

**Appraisal.** Tiny randomised crossover. Objective sleep changed without a circadian-phase change, which is interesting and unstable at n = 10. The retrieved abstract ends mid-sentence in the conclusion; the results above are from the intact results paragraph.

**Population and UK relevance.** Healthy adults in their twenties. Not patients. Afternoon daylight is a general-health behaviour, not a treatment recommendation from this preprint.

---

## 11. What needs verification before it is cited

1. All clinical appraisals are abstract-level unless the section says a preprint abstract was used. Allocation, adherence, missing data and the exact success definitions may differ in the full text.
2. The CPAP guideline’s graded tables and evidence profiles were not retrieved. Quote the recommendation strengths from the abstract only, or read the full guideline.
3. PMID 42948779 (postpartum probiotics): the mean Pittsburgh improvement is larger in the placebo arm, and the abstract still concludes that the probiotic helped, with p = 0.003. Do not cite the conclusion until the contrast is clear.
4. PMID 42945713 (activity timing): the clock times differ by about 19 minutes and the coefficient is printed as 0.31 min. The unit needs the full text.
5. PMID 42954867 (Ru-SATED): Cohen’s d is printed as 0.93 with a negative confidence interval.
6. PMID 42948184 (obesity umbrella review): PROSPERO number printed as CRD420261326462, which has an unusual length.
7. PMID 42938204 (smartphone OSA): sensitivity and specificity are reported without the polysomnography sample size, and the abstract says performance had previously been validated.
8. PMID 42942358 and PMID 42955467: “surgical success” and “success” are not defined in the abstracts.
9. PMID 42949055: “good CPAP response” is not defined, and the abstract’s closing sentence sits awkwardly beside a hazard ratio of 0.72.
10. PMID 42928360 is in the journal *Trials* and reports results. Confirm it is the results paper.
11. PPMI preprint percentages have no denominators in the abstract.
12. The PSP preprint reports directions without pooled effect sizes.
13. Europe PMC truncated the daylight and iron-deficiency abstracts. Incomplete closing sentences were not reconstructed.
14. medRxiv API total 478 versus 459 unique DOIs retrieved.
15. Embase and Scopus strategies were not run. Emtree headings and the Scopus `BEF`/`AFT` bounds need a local check.
16. DOIs were taken from the PubMed summary identifier list. An earlier parse that walked every DOI inside the XML, including references, was discarded and is not used in this pack.

---

## 12. Bottom line for practice

For UK adult sleep services, the one document to read in full is the ERS/ESRS CPAP guideline (PMID 42860272): strong when the patient is sleepy, conditional when they are not. Metabolic risk, blood pressure, smoking and atrial fibrillation remain the cardiovascular story in the large OSA cohort indexed this week. Mandibular devices, tongue-base surgery and phone snoring apps produced papers, all with limits that the abstracts themselves mostly admit. Insomnia trials are small, short and mostly adjunctive. Adult bruxism produced no new primary study inside the seven days; the latest population signals separate self-report from polysomnography and do not support routine medication.

---

## Appendix A. PubMed records indexed 26 October–2 November 2026 that were retrieved and not individually appraised

These 113 records matched the adult sleep string and entered PubMed in the window. Findings were not extracted. DOI is the record DOI. Indexed date is the Entrez date.

| PMID | Indexed | Journal | DOI | Title |
| --- | --- | --- | --- | --- |
| 42928489 | 2026/10/26 | Scand J Caring Sci | 10.1111/scs.70329 | How Nurses Assess Interventions to Promote Patients Sleep on Hospital Wards: Results of a Self-Report Survey. |
| 42933688 | 2026/10/26 | JHEP Rep | 10.1016/j.jhepr.2026.102071 | Sleep and Sedentary Behavior Predict Severity in MASLD but Not MetALD/ALD: A Compositional Analysis. |
| 42931915 | 2026/10/26 | Acta Biochim Biophys Sin (Shanghai) | 10.3724/abbs.2026176 | Maternal sleep deprivation is associated with fetal hypothalamic-hepatic remodeling and long-term metabolic and behavioral alterations in offspring. |
| 42932907 | 2026/10/26 | Am J Physiol Regul Integr Comp Physiol | 10.1152/ajpregu.00240.2026 | Effects of 24-h sleep deprivation on circulating irisin, BDNF, and soluble klotho responses during exercise in the heat in young and older males. |
| 42930612 | 2026/10/26 | Med Sci (Basel) | 10.3390/medsci14060693 | Association Between Sleep-Related Medication Use and Recurrent Falls Among Inpatients: A Five-Year Retrospective Observational Study at a University Hospital. |
| 42928694 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2156 | Evaluating the Efficacy of Comprehensive Nursing Care in Improving the Well-Being of Patients With Colon Cancer Who Developed Postoperative Sleep Disorders. |
| 42928689 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2241 | Effects of Psycho-Cardiology Model-Based Psychological and Behavioural Management on Negative Emotions and Sleep Disorders in Patients With Resistant Hypertension Complicated by Anxiety and Depression. |
| 42928686 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2258 | Efficacy of Guided Imagery Training in Improving Sleep Quality in Patients With Chronic Obstructive Pulmonary Disease and Sleep Disorders. |
| 42928681 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2270 | A Retrospective Study Analysing the Outcomes of Anxiety, Depression, and Sleep Disorders in Post-Chemotherapy Patients With Breast Cancer Based on Symptom-Targeted Supportive Psychological Nursing. |
| 42928680 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2272 | The Association of a Mindfulness-Based Stress Reduction Nursing Model With Quality of Life in Patients With Chronic Tonsillitis Complicated by Anxiety Disorder: A Retrospective Study. |
| 42928678 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2291 | Effects of Mindfulness-Based Stress Reduction Combined With Perioperative Refined Nursing on Postoperative Sleep Disturbances, Anxiety, and Depression in Patients Undergoing Coronary Artery Bypass Grafting. |
| 42928670 | 2026/10/26 | Actas Esp Psiquiatr | 10.62641/aep.2384 | Coping-Strategies as a Mediator Between Symptoms of Sleeping Problems and Risk of Suicide. |
| 42930375 | 2026/10/26 | Clin Pract | 10.3390/clinpract16100189 | Medication Complexity and Insomnia Severity in Psychiatric Outpatients: A Moderation Analysis Across Mood and Non-Mood Disorders. |
| 42930155 | 2026/10/26 | Curr Oncol | 10.3390/curroncol33100588 | Patients' and Providers' Perceptions of the Implementation of a Stepped Care Cognitive-Behavioral Therapy for Insomnia in Routine Cancer Care: A Qualitative Post-Implementation Study. |
| 42931252 | 2026/10/26 | NeuroSci | 10.3390/neurosci7050105 | Neurocognitive Indices of Long COVID: Dysregulated Engagement of Inhibitory Control and Oscillatory Slowing. |
| 42930873 | 2026/10/26 | J Cardiovasc Dev Dis | 10.3390/jcdd13100477 | Heart and Brain: Linking Obesity-Related Inflammation, Cardiovascular Disease and Cognitive Function. |
| 42934899 | 2026/10/27 | Cancer Med | 10.1002/cam4.72426 | Racial and Ethnic Differences in Sleep and Socioeconomic Status Among Cancer Survivors in the United States. |
| 42946059 | 2026/10/27 | Diabetes Res Clin Pract | 10.1016/j.diabres.2026.113627 | Psychosocial and symptom burden across metabolic populations managed in a digitally enabled metabolic care model: a real-world cross-sectional study. |
| 42945339 | 2026/10/27 | PLoS One | 10.1371/journal.pone.0347558 | "Tired but wired" - First-time parents lived experiences of sleep loss, tiredness and wellbeing during the first six months postpartum. |
| 42945316 | 2026/10/27 | PLoS One | 10.1371/journal.pone.0359711 | Dexmedetomidine effects on metabolic rate over 5 days in humans. |
| 42945188 | 2026/10/27 | PLoS One | 10.1371/journal.pone.0361053 | Sleep quality, perceived stress, and dry eye disease among university students in Ghana: A cross-sectional study of individual and joint associations. |
| 42945803 | 2026/10/27 | Biochem Biophys Res Commun | 10.1016/j.bbrc.2026.154805 | Developmental sleep during lethargus is associated with metabolic homeostasis and heritable adaptive responses to infection in Caenorhabditis elegans. |
| 42937802 | 2026/10/27 | Medicine (Baltimore) | 10.1097/MD.0000000000051348 | Pan-immune-inflammation value and sleep disturbances in rheumatoid arthritis: A population-based NHANES study. |
| 42937790 | 2026/10/27 | Medicine (Baltimore) | 10.1097/MD.0000000000051331 | Association between triglyceride glucose-relative fat mass index and obstructive sleep apnea risk: A cross-sectional study from NHANES. |
| 42937756 | 2026/10/27 | Medicine (Baltimore) | 10.1097/MD.0000000000051154 | Associations of sleep disturbance and emotion regulation with perceived workplace safety and fatigue among male firefighters with prior occupational accidents: A cross-sectional study. |
| 42937754 | 2026/10/27 | Medicine (Baltimore) | 10.1097/MD.0000000000051259 | Association of sleep time with all-cause and cardiovascular mortality among individuals with advanced cardiovascular-kidney-metabolic syndrome: A NHANES-based prospective cohort study. |
| 42937745 | 2026/10/27 | Medicine (Baltimore) | 10.1097/MD.0000000000051177 | Sleep duration, sarcopenia, and incident depressive symptoms in Chinese middle-aged and older adults: A prospective cohort study based on CHARLS. |
| 42940590 | 2026/10/27 | Healthcare (Basel) | 10.3390/healthcare14203546 | Characterization of Psychiatric Adverse Events Reported with Levetiracetam in the FDA Adverse Event Reporting System (FAERS). |
| 42940588 | 2026/10/27 | Healthcare (Basel) | 10.3390/healthcare14203544 | Prefecture-Level Mean Elevation, Sleep Duration, and Depressive Symptoms Among Middle-Aged and Older Adults in China: A Cross-Sectional CHARLS Study. |
| 42943007 | 2026/10/27 | Nutrients | 10.3390/nu18203437 | Ketones and Sleep: A Narrative Review of Mechanisms, Preclinical Models, and Human Evidence. |
| 42941674 | 2026/10/27 | J Clin Med | 10.3390/jcm15208163 | Seasonal Variation, Circadian Patterns, and Night Eating Syndrome Among Older Adults: The Mediating Role of Sleep Quality. |
| 42940573 | 2026/10/27 | Healthcare (Basel) | 10.3390/healthcare14203528 | Depressive Symptoms, Insomnia-Related Difficulties and Self-Rated Health Among Community-Dwelling Adults Aged 40 Years and Older in Western China: A Cross-Sectional Structural Equation Modelling Study. |
| 42938917 | 2026/10/27 | Cancers (Basel) | 10.3390/cancers18203385 | Psychosocial Interventions in Cancer Survivorship: A Rapid Scoping Review of the Recent PubMed-Indexed Literature. |
| 42942545 | 2026/10/27 | Medicina (Kaunas) | 10.3390/medicina62102014 | Association Between Sleep Duration and Obesity Phenotypes in Apparently Healthy Korean Adults: A Cross-Sectional Study Using the Korea National Health and Nutrition Examination Survey 2013-2015. |
| 42944391 | 2026/10/27 | Sensors (Basel) | 10.3390/s26206528 | Closed-Loop Acoustic Stimulation of Slow Oscillations Using a Wireless EEG Headband: A Polysomnography-Validated Feasibility Study. |
| 42942955 | 2026/10/27 | Nutrients | 10.3390/nu18203385 | Is Better Diet Quality Linked to Better Competitive Functioning? An Integrative Multi-Analytic Study of Sleep Difficulty and Subjective Vitality Among Chinese Collegiate Athletes. |
| 42940491 | 2026/10/27 | Healthcare (Basel) | 10.3390/healthcare14203446 | Eating Behavior, Body Appreciation, and Sleep Quality in Italian Blind Baseball Athletes: A Cross-Sectional Exploratory Survey. |
| 42942512 | 2026/10/27 | Medicina (Kaunas) | 10.3390/medicina62101981 | High-Flow Nasal Cannula in Adult Acute Care: Physiological Mechanisms, Clinical Evidence, and Persistent Misconceptions. |
| 42935960 | 2026/10/27 | Front Public Health | 10.3389/fpubh.2026.1932196 | Assessment of night eating syndrome and circadian-related characteristics among university students of Rawalpindi and Islamabad. |
| 42935558 | 2026/10/27 | Front Endocrinol (Lausanne) | 10.3389/fendo.2026.1930177 | Sex differences in sleep and memory relationships in older adults at risk for Alzheimer's disease. |
| 42942897 | 2026/10/27 | Nutrients | 10.3390/nu18203325 | Dietary and Lifestyle Correlates of Gut Microbiota Diversity and Composition in Healthy Adults: A Cross-Sectional Pilot Study Informing Longitudinal Research. |
| 42942876 | 2026/10/27 | Nutrients | 10.3390/nu18203305 | Mediterranean Diet Adherence and Sleep Quality in Spanish Adults: Divergent Associations Between Subjective and Objective Measures. |
| 42942255 | 2026/10/27 | Life (Basel) | 10.3390/life16101669 | The Obstructive Sleep Apnea Care Ecosystem in the United States: Clinical Pathways and the Evolving Role of Otolaryngology. |
| 42942252 | 2026/10/27 | Life (Basel) | 10.3390/life16101666 | Prevalence of Chronic Respiratory Diseases, Airflow Obstruction, Sleep Apnea Risk, and Novel Tobacco Use in the Coastal Localities of the Mangalia Municipality: A Cross-Sectional Study of 979 Adults. |
| 42939692 | 2026/10/27 | Biomolecules | 10.3390/biom16101438 | Serum Melatonin at Admission and Discharge in Schizophrenia: A Prospective Longitudinal Controlled Study. |
| 42937137 | 2026/10/27 | Physiol Rep | 10.14814/phy2.71136 | Ketone monoester intake attenuates exercise performance decline in normobaric hypoxia: A post-hoc subgroup analysis of 5 young male adults without acute mountain sickness. |
| 42942387 | 2026/10/27 | Medicina (Kaunas) | 10.3390/medicina62101856 | Menopausal Symptom Burden and Self-Reported Poor Sleep Quality Among Japanese Working Women Aged 40 Years and Older: An Exploratory Cross-Sectional Study. |
| 42946618 | 2026/10/27 | Sleep Med | 10.1016/j.sleep.2026.109267 | Editorial: Supporting the mental health of neurodivergent adults through sleep and circadian based interventions. |
| 42934667 | 2026/10/27 | BMC Womens Health | 10.1186/s12905-026-04754-y | The importance of body fat percentage: associations between fatigue, sleep, body composition, and perceived physical activity barriers in young women. |
| 42934598 | 2026/10/27 | BMC Public Health | 10.1186/s12889-026-28717-y | Association between built environment and sleep duration mediated by air pollution: a cohort study in China. |
| 42934584 | 2026/10/27 | BMC Pulm Med | 10.1186/s12890-026-04493-8 | Characterizing and conceptualizing sleep in adolescents and young adults with cystic fibrosis: a descriptive qualitative study. |
| 42934231 | 2026/10/27 | Transl Psychiatry | 10.1038/s41398-026-04295-w | Attenuated PER3 amplitude in hair follicles is associated with sleep irregularity in schizophrenia. |
| 42949261 | 2026/10/28 | J Health Psychol | 10.1177/13591053261499074 | An examination of psychological well-being and insomnia among older adults in Bangladesh: A moderated mediation of age, perceived stress, and perceived social support. |
| 42948695 | 2026/10/28 | Diabetes Metab Syndr Obes | 10.2147/DMSO.S630672 | Association Between Uncertainty Stress and Insomnia Symptoms Among Chinese Patients with Type 2 Diabetes: The Mediating Role of Healthy Lifestyles Based on a Multicenter Cross-Sectional Survey. |
| 42947726 | 2026/10/28 | Front Cognit | 10.3389/fcogn.2026.1928964 | Cognitive workload across subjective and electrodermal measures in relation to previous-night sleep. |
| 42947684 | 2026/10/28 | Front Clin Diabetes Healthc | 10.3389/fcdhc.2026.1946918 | Body mass index, diabetes, inflammation and survival in COVID-19: a retrospective study evaluating the obesity paradox in an urban hospital center. |
| 42947071 | 2026/10/28 | BMC Psychiatry | 10.1186/s12888-026-08712-8 | Interpretable machine learning for identifying mild cognitive impairment among Chinese patients with obstructive sleep apnea: a multicenter cross-sectional study. |
| 42947169 | 2026/10/28 | BMC Psychol | 10.1186/s40359-026-05267-x | Self-compassion predicts reduced bedtime procrastination through affect pathway: a three-wave longitudinal study. |
| 42947069 | 2026/10/28 | BMC Psychiatry | 10.1186/s12888-026-08464-5 | Metabolic bridge between sleep disturbances and depression: mediating effects of insulin resistance and clinical implications. |
| 42947031 | 2026/10/28 | BMC Psychiatry | 10.1186/s12888-026-08465-4 | Sleep quality, circadian rhythm disruption, functioning, and treatment adherence in major depression: a cross-sectional exploratory study. |
| 42957264 | 2026/10/29 | In Vivo | 10.21873/invivo.14521 | Prevalence of Suspected Obstructive Sleep Apnea Among Patients With Chronic Cough and Relatively Low BMI. |
| 42952077 | 2026/10/29 | Brain Behav | 10.1002/brb3.71882 | Sequential Associations of Sleep Architecture, Nocturnal Oxygenation, and Respiratory Disturbance With a Composite PSG-Derived Rhythm-Event Index. |
| 42952074 | 2026/10/29 | Nurs Crit Care | 10.1111/nicc.70742 | Incidence of Intensive Care Unit Delirium After Heart Surgery: A Feasibility Study of a Forest Environment Intervention. |
| 42957441 | 2026/10/29 | Diabetes Obes Metab | 10.1111/dom.71491 | Daytime Sleepiness, Insomnia Symptoms and Sleep Quality in Adults Entering a Structured Weight-Loss Programme: The SCOOP-RNPC Cohort. |
| 42956436 | 2026/10/29 | J Psychiatr Res | 10.1016/j.jpsychires.2026.10.015 | Corrigendum to "Nightmare disorder and depression: Exploring a neglected clinical association" [J. Psychiatr. Res. 202, (2026), 127-136]. |
| 42955885 | 2026/10/29 | Ocul Immunol Inflamm | 10.1080/09273948.2026.2753565 | Association Between Circadian Rhythm Sleep Disorder and Noninfectious Uveitis: A Retrospective Cohort Study. |
| 42955757 | 2026/10/29 | IEEE Trans Neural Syst Rehabil Eng | 10.1109/TNSRE.2026.3747551 | Cross-Domain Slow Wave Sleep Detection from Single-Lead EEG in Pediatric Congenital Heart Disease Recovery. |
| 42953753 | 2026/10/29 | Nat Sci Sleep | 10.2147/NSS.S636142 | Who's Been Sleeping in My Bedroom? Associations Between Co-Sleeping with Dogs, Cats, or Children and Sleep and Cardiorespiratory Physiology Among WHOOP Users. |
| 42953906 | 2026/10/29 | JMIR Form Res | 10.2196/109259 | Linking Attainment of Wearable-Derived Sleep and Physical Activity Recommendations with Cardiometabolic Biomarkers and Employer Health Care Claims: A Feasibility Study. |
| 42952950 | 2026/10/29 | Front Public Health | 10.3389/fpubh.2026.1814427 | Self-reported long COVID associated with sleep problems and poor sleep quality among adults in Germany: results of the German Health Update 2023 (GEDA 2023). |
| 42952519 | 2026/10/29 | Front Sleep | 10.3389/frsle.2026.1968296 | Black adults show cross-sectional associations between sleep quality and episodic memory retention: an investigation of underlying factors. |
| 42955818 | 2026/10/29 | Cereb Cortex | 10.1093/cercor/bhag184 | Sleep after motor learning enhances post-movement beta synchronization. |
| 42953167 | 2026/10/29 | Cureus | 10.7759/cureus.117063 | Home Sleep Apnea Testing Over 25 Years: A Bibliometric Analysis of Global Research Trends. |
| 42954896 | 2026/10/29 | Indian J Dent Res | 10.4103/ijdr.ijdr_81_26 | Knowledge and Awareness Regarding MDMA among Undergraduate Dental Students in Kerala, India - An Evaluative Study. |
| 42960906 | 2026/10/30 | Med Oral Patol Oral Cir Bucal | 10.4317/medoral.28395 | Salivary Gene Expression and Systemic Inflammatory Markers in Obstructive Sleep Apnea and Periodontal Disease. |
| 42963208 | 2026/10/30 | Sleep Health | 10.1016/j.sleh.2026.09.013 | Personal nighttime indoor temperature and sleep characteristics in adults with type 2 diabetes. |
| 42962739 | 2026/10/30 | Ann Epidemiol | 10.1016/j.annepidem.2026.110311 | Reciprocal Relations Among Cognition, Insomnia, and Depression: A Cross Lagged Panel Model Among Participants of the Mexican Health and Aging Study. |
| 42961871 | 2026/10/30 | PLoS One | 10.1371/journal.pone.0361815 | Effects of a sleep program on sleep, performance and health in university students: Study protocol for a randomised controlled trial. |
| 42961671 | 2026/10/30 | Int Arch Occup Environ Health | 10.1007/s00420-026-02248-w | Workplace noise exposure and sleep among small-scale industrial metal workers in Dar es Salaam, Tanzania: a cross-sectional study. |
| 42961596 | 2026/10/30 | J Clin Sleep Med | 10.1007/s44470-026-00223-3 | Reply to "From shifting the clock to sustaining alignment: toward precision chronotherapy for emerging adults with delayed sleep timing". |
| 42961314 | 2026/10/30 | JMIR Mhealth Uhealth | 10.2196/100064 | The Mediating Role of Sleep Quality in Associations of Smartphone Addiction and Time-Specific Use With Prenatal Depression and Anxiety: Cross-Sectional Observational Study. |
| 42960484 | 2026/10/30 | Top Stroke Rehabil | 10.1080/10749357.2026.2754432 | Motor memory consolidation during sleep after stroke: the rehabilitation timing hypothesis. |
| 42960503 | 2026/10/30 | Monaldi Arch Chest Dis | 10.4081/monaldi.2026.3752 | Association of the six-minute walk test with severity of obstructive sleep apnea: an observational study. |
| 42958704 | 2026/10/30 | Clin Gerontol | 10.1080/07317115.2026.2754949 | Mediating Roles of Sleep Disturbances and Depressive Symptoms in the Association Between Chronic Pain and Cognitive Dysfunction in Older Adults. |
| 42961200 | 2026/10/30 | Cad Saude Publica | 10.1590/0102-311XEN004226 | Sociodemographic and lifestyle correlates of accelerometer-measured 24-hour physical behavior patterns: a cross-sectional analysis of the ELSA-Brasil cohort. |
| 42959782 | 2026/10/30 | Front Nutr | 10.3389/fnut.2026.2010644 | Correction: The effects of magnesium L-threonate (Magtein(®)) on cognitive performance and sleep quality in adults: a randomised, double-blind, placebo-controlled trial. |
| 42959530 | 2026/10/30 | Front Pharmacol | 10.3389/fphar.2026.1960152 | Circadian-melatonin signaling in general anesthesia: molecular mechanisms and perioperative implications. |
| 42959024 | 2026/10/30 | Front Endocrinol (Lausanne) | 10.3389/fendo.2026.1906256 | Association of the metabolic signature of sleep patterns with breast cancer risk: a prospective cohort study. |
| 42958239 | 2026/10/30 | BMC Womens Health | 10.1186/s12905-026-04842-z | Preserved ovarian reserve in night-active versus day-active women: a cross-sectional comparison of neuroendocrine markers. |
| 42958301 | 2026/10/30 | BMC Med Educ | 10.1186/s12909-026-10055-7 | Predictors of academic self-efficacy in medical intern students: the roles of mindful eating, physical activity, sleep quality, and mental workload. |
| 42958059 | 2026/10/30 | BMC Geriatr | 10.1186/s12877-026-07958-x | Network analysis of frailty, sleep quality, and life satisfaction in older patients: a cross-sectional study stratified by chronic disease burden. |
| 42958187 | 2026/10/30 | BMC Psychiatry | 10.1186/s12888-026-08473-4 | Markers of blood-brain barrier and intestinal mucosal barrier in insomnia disorder: an observational study linking wake-promoting neurotransmitters to sleep efficiency. |
| 42958154 | 2026/10/30 | BMC Pulm Med | 10.1186/s12890-026-04537-z | Association between lactic dehydrogenase-to-albumin ratio and all-cause mortality in critical obstructive sleep apnea patients: a retrospective cohort study from the MIMIC-IV database. |
| 42958141 | 2026/10/30 | BMC Public Health | 10.1186/s12889-026-28815-x | Impact of warning labels on energy drink perceptions and purchase intentions among emerging adults in Uruguay. |
| 42958161 | 2026/10/30 | BMC Psychiatry | 10.1186/s12888-026-08470-7 | Sex differences in associations between sleep architecture and CBC-derived immune cell indices in MDD with comorbid insomnia. |
| 42964540 | 2026/10/31 | Int J Cardiol Congenit Heart Dis | 10.1016/j.ijcchd.2026.100712 | Impact of nocturnal oxygen saturation on sleep quality and exercise performance in adult Fontan patients. |
| 42963958 | 2026/10/31 | Appl Psychol Health Well Being | 10.1111/aphw.70249 | Distress, emotional well-being, and sleep quality in daily life: A dual-continuum perspective. |
| 42963931 | 2026/10/31 | Nurs Health Sci | 10.1111/nhs.70442 | The Moderating Effect of Sleep Duration on the Association Between Chronic Disease and Health-Related Quality of Life in Middle-Aged Women. |
| 42966360 | 2026/10/31 | Appl Neuropsychol Adult | 10.1080/23279095.2026.2749611 | The impact of acute sleep restriction on executive functions: A quasi-experimental within-subjects examination of inhibitory control, working memory, and cognitive flexibility. |
| 42966290 | 2026/10/31 | Ecotoxicol Environ Saf | 10.1016/j.ecoenv.2026.120988 | Life stage-specific endocrine disruption by Tris(2-ethylhexyl) trimellitate (TOTM) in zebrafish: Thyroid-neurobehavioral effects and metabolic-reproductive alterations. |
| 42966287 | 2026/10/31 | Ecotoxicol Environ Saf | 10.1016/j.ecoenv.2026.120987 | Co-exposure to octocrylene and polystyrene nanoplastics induces neuro- and reproductive toxicity in zebrafish: Association with circadian rhythm and HPG axis disruption. |
| 42965974 | 2026/10/31 | Soc Work | 10.1093/sw/swag052 | Racial/Ethnic Variations in the Association Between Sleep Problems and Mental Health. |
| 42965972 | 2026/10/31 | Inflamm Bowel Dis | 10.1093/ibd/izag212 | Sleep disturbance in inflammatory bowel disease: clinical associations and gaps in care. |
| 42965657 | 2026/10/31 | Lung | 10.1007/s00408-026-00957-0 | Airway Pressure Release Ventilation Versus Conventional Ventilation in Adults With or at Risk for Acute Respiratory Distress Syndrome: A Systematic Review and Meta-Analysis of Randomized Trials. |
| 42965372 | 2026/10/31 | J Vis Exp | 10.3791/73296 | Adjunctive Trazodone Effects on Sleep, Mood, and Circulating 5-HT and BDNF in Depression. |
| 42964384 | 2026/10/31 | Front Psychol | 10.3389/fpsyg.2026.1917045 | Low-intensity mind-body exercise for mental health in ageing societies: Tai Chi as a scalable intervention across depression, anxiety, insomnia, loneliness, and cognitive decline. |
| 42964230 | 2026/10/31 | Front Psychol | 10.3389/fpsyg.2026.1940441 | Validity evidence for the Clinic Screening Tool for HIV (CST-HIV) addressing factors that undermine health-related quality of life in people living with HIV. |
| 42964047 | 2026/10/31 | Front Endocrinol (Lausanne) | 10.3389/fendo.2026.1954035 | Nocturnal sleep duration, clinical activity score, and thyroid functional remission after radioactive iodine therapy in Graves' disease with thyroid-associated ophthalmopathy. |
| 42965254 | 2026/10/31 | Cureus | 10.7759/cureus.117247 | Association Between Dietary Vitamin Intake and Short Sleep Duration Among Adults in the United States: A Cross-Sectional Analysis of 2021-2023 National Health and Nutrition Examination Survey (NHANES) Data. |
| 42963541 | 2026/10/31 | Mol Brain | 10.1186/s13041-026-01346-7 | Differential circadian time modulates of dentate gyrus and CA1 excitation-inhibition balance and seizure threshold. |
| 42966815 | 2026/11/01 | Eur Arch Otorhinolaryngol | 10.1007/s00405-026-10738-3 | From surgical response to treatment adequacy in adult obstructive sleep apnoea: a further response. |
| 42967585 | 2026/11/01 | Alzheimers Dement | 10.1002/alz.71948 | Objective sleep characteristics and longitudinal change in financial and health literacy in older adults. |
| 42966968 | 2026/11/01 | Cureus | 10.7759/cureus.117273 | Mood and Behavioral Changes in Adult Cerebral X-linked Adrenoleukodystrophy. |


---

## 13. Five-line brief

A new European guideline says CPAP for adult sleep apnoea should be a strong recommendation when the person is sleepy in the day, and a more cautious choice when they are not.
There was almost no new adult tooth-grinding research in the last seven days. The nearest new study, from Brazil the day before, links self-reported grinding with low mood, and it did not use an overnight sleep study.
Small trials this week suggest short-term relief of insomnia from brain stimulation, acupuncture added to talking therapy, or a heat treatment added to a sleeping tablet. They are early, mostly single-centre, and not a change to usual UK care.
A UK cannabis-clinic register shows sleep scores rising over two years in people prescribed cannabis products. There was no comparison group, so the register cannot show that the prescription caused the change.
For ordinary UK adults, the useful message is to look at sleepiness, blood pressure and metabolic health together. A mild number on a sleep test, a phone snoring app, or a dental mouthpiece still needs a proper assessment before it changes treatment.
