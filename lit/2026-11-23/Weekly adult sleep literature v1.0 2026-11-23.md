# Weekly adult sleep literature v1.0

**Pack date:** 23 November 2026  
**Window:** records published or indexed 16–23 November 2026, inclusive  
**Scope:** adult sleep medicine, adult bruxism and sleep bruxism, and sleep-related painful erections (SRPE)  
**Database searched:** PubMed, via NCBI E-utilities  
**Not searched:** Embase, Scopus (no institutional access). Ready-to-paste strings are in the coverage-gaps section.

This pack is a research summary of abstracts. It is not medical advice, and it is not a treatment recommendation. Titles are left as published. Commentary is in British English. Nothing below was inferred beyond the PubMed record. Where a figure, covariate list, or country is absent from the abstract, that absence is stated.

The publication window was not thin, so it was not widened.

## How evidence is labelled in this pack

These labels are a local reading aid for this pack. They are not a guideline grade.

| Label | Meaning in this pack |
| --- | --- |
| 1 | Systematic review of randomised trials, with or without meta-analysis or network meta-analysis |
| 2 | Randomised trial |
| 3 | Systematic review of observational studies |
| 4 | Cohort or other longitudinal observational study, including a large records study |
| 5 | Cross-sectional study |
| 6 | Narrative review, position statement, Delphi consensus, or regulatory summary |

Appraisal tools that would apply to the full paper are named (RoB 2, ROBINS-I, Newcastle–Ottawa Scale, AMSTAR-2). Scores were not assigned. Full text was not retrieved, so domain judgements would be unreliable.

## PRISMA-S search record

| Item | Record |
| --- | --- |
| Database | PubMed (MEDLINE and PubMed-not-MEDLINE records as returned by Entrez) |
| Interface | NCBI E-utilities, `esearch.fcgi` and `efetch.fcgi`, no API key |
| Date searched | 23 November 2026 (UTC) |
| Who ran it | Literature sweep for this repository |
| Language limit | None |
| Species or age limit at search | None. Adult status was judged at screening, because many new records have no Medical Subject Headings (MeSH) age tags yet |
| Date limits | Two separate searches, then combined: entry date (EDAT) 16–23 November 2026, and publication date (PDAT) 16–23 November 2026 |
| Records from the entry-date search | 372 |
| Records from the publication-date search | 194 |
| Records in both searches (overlap) | 180 |
| Unique records after combining the two date searches | 386 |
| Removed because they were already in the 9 November or 16 November packs | 2 (PMID 43035081; PMID 43035082) |
| Records screened (title, then abstract where the title was in scope) | 384 |
| Records included | 24 (12 secondary, 12 primary) |

PMID 43035081 is an adult general-population paper on sleep bruxism and laryngopharyngeal reflux (EPISONO). PMID 43035082 is an imaging paper. Both were retrieved again this week and were removed before screening, as requested.

### Exact PubMed strategy

The strategy below is the one that returns the counts in the table. Truncation was not placed inside quotation marks, because PubMed does not treat an asterisk inside a quoted phrase as a wildcard. The bare acronym SRPE was left out of the main strategy. A separate check showed that SRPE[tiab] matches “session rating of perceived exertion” (sRPE).

**Concept strategy (one block):**

```
(
  "Sleep Wake Disorders"[mh]
  OR "Sleep Apnea Syndromes"[mh]
  OR Bruxism[mh]
  OR "Sleep Bruxism"[mh]
  OR Polysomnography[mh]
  OR "Continuous Positive Airway Pressure"[mh]
  OR sleep[ti]
  OR insomnia[tiab]
  OR "sleep apnea"[tiab]
  OR "sleep apnoea"[tiab]
  OR "obstructive sleep"[tiab]
  OR "central sleep apnea"[tiab]
  OR "central sleep apnoea"[tiab]
  OR narcolepsy[tiab]
  OR cataplexy[tiab]
  OR hypersomnia[tiab]
  OR "excessive daytime sleepiness"[tiab]
  OR "restless legs"[tiab]
  OR "restless leg"[tiab]
  OR "Willis-Ekbom"[tiab]
  OR "periodic limb movement"[tiab]
  OR "periodic limb movements"[tiab]
  OR parasomnia[tiab]
  OR parasomnias[tiab]
  OR "REM sleep behavior"[tiab]
  OR "REM sleep behaviour"[tiab]
  OR "REM sleep behavior disorder"[tiab]
  OR "REM sleep behaviour disorder"[tiab]
  OR "circadian rhythm"[tiab]
  OR ("shift work"[ti] AND sleep[tiab])
  OR "delayed sleep phase"[tiab]
  OR "advanced sleep phase"[tiab]
  OR "shift work sleep"[tiab]
  OR bruxism[tiab]
  OR "sleep bruxism"[tiab]
  OR "teeth grinding"[tiab]
  OR "tooth grinding"[tiab]
  OR "sleep-related painful erection"[tiab]
  OR "sleep-related painful erections"[tiab]
  OR "sleep related painful erection"[tiab]
  OR "sleep related painful erections"[tiab]
  OR "sleep-related erection"[tiab]
  OR "sleep-related erections"[tiab]
  OR "sleep related erection"[tiab]
  OR "sleep related erections"[tiab]
  OR "nocturnal penile tumescence"[tiab]
  OR CPAP[tiab]
  OR "continuous positive airway pressure"[tiab]
  OR "hypoglossal nerve"[tiab]
  OR "mandibular advancement"[tiab]
  OR "cognitive behavioural therapy for insomnia"[tiab]
  OR "cognitive behavioral therapy for insomnia"[tiab]
  OR "CBT-I"[tiab]
  OR "obesity hypoventilation"[tiab]
)
```

**Search A, indexed this window:** concept strategy AND `("2026/11/16"[EDAT] : "2026/11/23"[EDAT])` → 372  
**Search B, published this window:** concept strategy AND `("2026/11/16"[PDAT] : "2026/11/23"[PDAT])` → 194

PubMed reported that the quoted phrase `"painful nocturnal erection"[tiab]` is not an indexed phrase. It was tested and then left out. The plural `"painful nocturnal erections"[tiab]` was also tested inside the sensitivity run and did not add an eligible SRPE paper.

### SRPE sensitivity search

`SRPE[tiab] AND ("2026/11/16"[EDAT] : "2026/11/23"[EDAT])` returned 2 records. The publication-date version of the same acronym search returned 1, which was already in those 2.

- PMID 43043379. Acute effects of transcranial direct current stimulation on repetition volume during back squat exercise. The abstract uses sRPE for session rating of perceived exertion. This is not SRPE.
- PMID 43058885. Federated learning and wearable training-load data in elite football. The abstract again uses sRPE. This is not SRPE.

Both were excluded. Eligible SRPE papers in this window: 0.

### Screening

All 384 titles were available from the PubMed export. Letters, editorials and errata accounted for 20 records. Titles referring to children or adolescents accounted for 44. Titles referring to non-human experiments accounted for 9. Those groups overlap: 71 unique records were set aside on those rules.

The remaining titles were read. Abstracts were read when the title could be adult clinical sleep medicine, adult bruxism, or SRPE, with priority for randomised trials, systematic reviews, large cohorts, and consensus or position statements. Twenty-four records were included. The other in-scope abstracts were not given a full entry. Reasons included a narrow sample, a protocol without results, a preprint with a less direct clinical question, a narrative review, or a stronger paper on a similar question already in the pack. Examples that were read and not given a full entry are listed under coverage gaps.

One included paper (PMID 42715935) has a journal date of 16 November 2026 and a MEDLINE date of 16 November 2026. Its first Entrez date is 9 September 2026. It is in the pack because it meets the publication-date limit. The earlier Entrez date is stated in that entry.

## Secondary evidence

### 1. Selective orexin-2 receptor agonists in narcolepsy type 1

Ali A, Sajjad A, Talha M, Waqar K, Tanveer A, Mehmood A, et al. Short-Term Efficacy and Safety of Oral Selective Orexin-2 Receptor Agonists in Narcolepsy Type 1: An Updated Systematic Review and Meta-Analysis of Randomized Trials. Neuropsychopharmacol Rep. 2026;46(4). doi:10.1002/npr2.70189. PMID: 43044571.

**Design and level:** systematic review and meta-analysis of randomised, double-blind, placebo-controlled trials. Label 1.

**(1) Key findings**  
Five trials, 550 participants, treatment periods of 6–12 weeks. Compared with placebo, the Maintenance of Wakefulness Test improved by 21.91 minutes (95% CI 15.11 to 28.70; I² = 84.5%), the Epworth Sleepiness Scale fell by 9.28 points (95% CI 7.96 to 10.60; I² = 0%), and the weekly cataplexy incidence rate ratio was 0.34 (95% CI 0.22 to 0.55; I² = 36.1%). Treatment-emergent adverse events were more common (risk ratio 1.89, 95% CI 1.44 to 2.48), including insomnia, urinary symptoms and salivary hypersecretion. Stopping for adverse events was imprecise (risk ratio 3.73, 95% CI 0.50 to 28.03). Dropping TAK-994 left the efficacy estimates in a similar range. Wakefulness results still varied a lot between trials (I² = 69.9% after that exclusion).

**(2) Methods and population**  
The abstract reports a search of five databases and two trial registries to 15 September 2026, generalised least squares for shared-placebo comparisons, random-effects models with restricted maximum likelihood, modified Knapp–Hartung confidence intervals, and Mantel–Haenszel risk ratios for sparse harms. The authors used RoB 2. AMSTAR-2 was not applied here. The wakefulness estimate is statistically heterogeneous, so a single pooled minute-gain is a poor summary of every regimen. Follow-up is short. Uncommon and long-term harms are not established by these trials.

**(3) UK adult relevance**  
Narcolepsy type 1 is uncommon, so this is specialist care rather than a finding about the general adult population. The abstract does not say whether any trial was done in the UK, and it does not describe a UK licence. The size of the average short-term effects, and the gap on long-term safety, are the points a UK reader can take from the abstract.

### 2. Wake-promoting drugs and oxybate formulations in narcolepsy

Jiang Q, Gu Z. Comparative efficacy, safety, and dosing convenience of wake-promoting agents and sodium oxybate formulations for narcolepsy: a systematic review and network meta-analysis. BMC Neurol. 2026;26(1). doi:10.1186/s12883-026-05257-x. PMID: 43040281.

**Design and level:** systematic review and frequentist network meta-analysis of randomised trials. Label 1.

**(1) Key findings**  
Fourteen trials, 1,811 participants. The search was updated to 15 July 2026 and, on the authors’ account, found no new completed trial suitable for the main network. Solriamfetol 300 mg ranked highest for the Epworth Sleepiness Scale (mean difference −5.47; P-score 0.9692). For the Maintenance of Wakefulness Test, low-sodium oxybate (mean difference 11.80 minutes; P-score 0.9549) and solriamfetol 300 mg (P-score 0.9216) ranked highest. Traditional sodium oxybate 6 g ranked highest for weekly cataplexy (P-score 0.9978). The abstract says solriamfetol 300 mg increases gastrointestinal risks, without giving that risk estimate in the conclusion. The authors describe any “balance” claim for once-nightly sodium oxybate as an interpretation, not a formal weighted ranking.

**(2) Methods and population**  
P-scores rank treatments inside this network. They are not absolute clinical effects, and they do not replace head-to-head trials. PROSPERO CRD420261297749 is reported. RoB 2 or AMSTAR-2 scores are not in the abstract. Indirect comparisons depend on the trial set available to 15 July 2026. Doses are specific: a rank for solriamfetol 300 mg does not transfer to other doses.

**(3) UK adult relevance**  
This is specialist narcolepsy practice. Access and licensed products differ by country. The abstract does not provide UK costs, National Health Service use, or a comparison against UK commissioning criteria.

### 3. First approvals of oveporexton for narcolepsy type 1

Brown MB. Oveporexton: First Approval. Drugs. 2026. doi:10.1007/s40265-026-02401-2. PMID: 43040185.

**Design and level:** regulatory approval summary. Label 6. This is not a trial and not a systematic review.

**(1) Key findings**  
The abstract states that oveporexton is an oral selective orexin receptor 2 agonist, and that it received a first approval in China on 22 July 2026 for adolescents aged 16 years and older and for adults with narcolepsy type 1. It then states approvals on 5 August 2026 in the United States and on 24 August 2026 in Japan for adults with narcolepsy type 1. Further filings and phase III trials are described as ongoing. No efficacy numbers are reported in this abstract.

**(2) Methods and population**  
There is no sample, no comparator, and no analysis to appraise. RoB 2, ROBINS-I, the Newcastle–Ottawa Scale and AMSTAR-2 do not apply to a licensing summary. The China wording includes people aged 16 and 17 as well as adults. The US and Japan wording in the abstract is restricted to adults. This summary cannot be checked against the licence documents from the abstract alone.

**(3) UK adult relevance**  
The abstract does not report a UK approval. A UK reader should treat this as news of approvals elsewhere, sitting next to the short-term trial meta-analysis above, and not as a statement about UK availability.

### 4. Digital programmes for adult insomnia

Wang X, Zhao Y, Wang L, Du C, Ding K, Wen Q, et al. Comparative efficacy of different digital technologies in adults with insomnia: a systematic review and network meta-analysis of randomized controlled trials. Front Psychiatry. 2026;17:1929377. doi:10.3389/fpsyt.2026.1929377. PMID: 43065642.

**Design and level:** systematic review and Bayesian network meta-analysis of randomised trials in adults. Label 1.

**(1) Key findings**  
Twenty-six trials, 6,353 adults, search to 7 February 2026, eight types of digital programme. The abstract reports that digital programmes reduced insomnia severity on the Insomnia Severity Index (mean difference 3.31, 95% CI 2.48 to 4.15; I² = 67%), improved the Pittsburgh Sleep Quality Index (mean difference 1.52, 95% CI 1.07 to 1.97; I² = 0%), and shortened sleep-onset latency (mean difference 12.60 minutes, 95% CI 7.66 to 17.55) and wake after sleep onset (mean difference 16.93 minutes, 95% CI 8.90 to 24.96). The authors assign favourable ranks to digital cognitive behavioural therapy for insomnia, including combinations with wearables or biofeedback, and they also say that several of those ranks rest on few trials and sparse direct comparisons.

**(2) Methods and population**  
The authors used RoB 2 and GRADE for network meta-analysis. AMSTAR-2 was not applied here. The Insomnia Severity Index result is heterogeneous (I² = 67%), and the abstract reports the mean difference as a positive number while describing a reduction, so the sign convention is not fully explicit. Ranks (SUCRA) for thinly studied programmes are uncertain, which the authors state. Long-term effects are not established.

**(3) UK adult relevance**  
Insomnia is common in UK adults, and digital cognitive behavioural therapy is already one of the delivery routes in routine practice. These trials are not described as UK trials. The average symptom change is modest, the programmes are not interchangeable, and the abstract does not show which products are in UK use.

### 5. Cognitive behavioural therapy for insomnia after stroke or traumatic brain injury

Evison C, Goodwin H, Vanstone A. A systematic review and meta-analysis of randomized controlled trials investigating cognitive behavioural therapy for insomnia in stroke and traumatic brain injury populations. Neuropsychol Rehabil. 2026:1-23. doi:10.1080/09602011.2026.2763514. PMID: 43044630.

**Design and level:** systematic review and meta-analysis of randomised trials. Label 1. PubMed’s publication-type tag is “Review”; the abstract describes a systematic review of trials.

**(1) Key findings**  
Nine trials were included and seven entered the main meta-analysis. Cognitive behavioural therapy for insomnia was associated with a lower Insomnia Severity Index (mean difference −3.07, 95% CI −4.46 to −1.67) and a lower Pittsburgh Sleep Quality Index (mean difference −1.81, 95% CI −2.82 to −0.80). Anxiety symptoms showed a small effect (Hedges’ g −0.30, 95% CI −0.49 to −0.12). Depressive symptoms showed a small-to-moderate effect that was not statistically significant (Hedges’ g −0.36, 95% CI −0.84 to 0.12; p = 0.1146). The abstract’s closing sentence groups depression with the anxiety benefit. The depression confidence interval includes no effect.

**(2) Methods and population**  
Random-effects models, with heterogeneity and sensitivity analyses stated. The authors used RoB 2. Databases named: Scopus, PubMed, Embase and PsycINFO. AMSTAR-2 was not scored here. Stroke and traumatic brain injury were pooled. The abstract does not give the combined sample size. That missing total is a limit of this abstract-level reading.

**(3) UK adult relevance**  
The finding applies to adults after stroke or brain injury, not to insomnia in general. A mean Insomnia Severity Index change of about 3 points is around the range often discussed as a modest shift. It does not, from this abstract, establish the effect in UK rehabilitation services.

### 6. Mandibular advancement device and continuous positive airway pressure

Murrieta Bruciaga LM, Liang AC, Castillo YC, Sibilla Chacon IM, Beltrán Covarrubias SA, Ocoró-Vallecilla A, et al. Mandibular advancement device vs continuous positive airway pressure in obstructive sleep apnea: An updated systematic review and meta-analysis. Sleep Med. 2026;149:109361. doi:10.1016/j.sleep.2026.109361. PMID: 43067176.

**Design and level:** systematic review and meta-analysis. Label 1 for the trial evidence included; the abstract says “18 studies” and does not state that every study was randomised. PubMed tags it as a Review.

**(1) Key findings**  
Eighteen studies, 1,244 participants. PROSPERO CRD420251081182. The authors report that continuous positive airway pressure (CPAP) did better on minimum oxygen saturation (mean difference −4.54, 95% CI −5.50 to −3.59; I² = 50.2%), oxygen desaturation index (mean difference 6.54, 95% CI 3.70 to 9.38; I² = 85.4%) and arousal index (mean difference 4.40, 95% CI 1.22 to 7.58; I² = 77.5%). The mandibular advancement device group had greater adherence (mean difference 1.43, 95% CI 1.10 to 1.77; I² = 55.6%; the unit is not stated in the abstract) and a modest difference on some blood-pressure measures. Baseline apnoea–hypopnoea index moderated the treatment effect (β = 0.82, 95% CI 0.30 to 1.35).

**(2) Methods and population**  
Random-effects style pooling is implied by the I² statistics; the software is named as R 4.6.0. The contrast direction behind each mean difference is not fully spelled out, so the numbers should be read with the authors’ statement of which group improved. Heterogeneity is high for the desaturation and arousal results. Adherence in these studies is a major confounder of any clinical comparison, and the abstract calls for trials with objective adherence and cardiovascular events. RoB 2 or ROBINS-I is not named in the abstract. AMSTAR-2 was not scored here.

**(3) UK adult relevance**  
Obstructive sleep apnoea is common in UK adults, and both CPAP and a mandibular device are used. This abstract supports a familiar pattern, that overnight respiratory indices favour CPAP while nightly use favours the oral device, and it does not identify who in a UK clinic should be offered which treatment.

### 7. Sleep disturbance in Alzheimer’s disease

Sharma A, Raj R, Azmi MO, Puchakayala N, Kaur A, S P, et al. Pharmacological and non-pharmacological management of sleep disturbances in Alzheimer's disease: A systematic review and meta-analysis. J Alzheimers Dis. 2026. doi:10.1177/13872877261504983. PMID: 43066573.

**Design and level:** systematic review and network meta-analysis of randomised trials. Label 1. The PubMed author list records the sixth author as “S P”.

**(1) Key findings**  
Twelve trials, 936 participants, 32 arms. Search to July 2026. PROSPERO CRD420250653178. The abstract reports that zolpidem and zopiclone reduced fragmentation (nocturnal awakenings, standardised mean difference −1.09; wake after sleep onset, −0.86) on the basis of a single short-term trial. Suvorexant increased total sleep time (standardised mean difference 0.376; this clause is duplicated in the abstract). Lemborexant 2.5 mg reduced nocturnal awakenings (standardised mean difference −0.98). Walking, bright light and the NITE-AD programme reduced nocturnal awakenings, and combined light and melatonin reduced daytime sleep. Melatonin alone, trazodone and mirtazapine were described as limited or inconsistent. The authors suggest considering non-drug approaches first and using dual orexin receptor antagonists for selected outcomes, and they say Z-drugs need caution.

**(2) Methods and population**  
Frequentist random-effects network meta-analysis using Hedges’ g, with a Bayesian sensitivity analysis. Outcomes were total sleep time, wake after sleep onset, nocturnal awakenings, sleep efficiency, daytime sleep and daytime naps. Several estimates come from one trial, so the network is fragile. The standardised mean difference of about 1 for Z-drugs is large and rests on that single short-term source. AMSTAR-2 was not scored. Harms of sedative-hypnotics in dementia are a known clinical concern; this abstract does not re-quantify falls or confusion.

**(3) UK adult relevance**  
This applies to adults with Alzheimer’s disease and disturbed sleep, including people in care settings, not to the general adult population. UK prescribing context is not discussed. The single-trial Z-drug estimates should not be read as a reason to prefer those drugs.

### 8. Excessive daytime sleepiness in older adults

Xiong Y, Tao S, Meng X, Tang L, Huang L, Fu H, et al. Prevalence and Risk Factors of Excessive Daytime Sleepiness in Older Adults: A Systematic Review and Meta-Analysis. J Am Med Dir Assoc. 2026;28(1):106511. doi:10.1016/j.jamda.2026.106511. PMID: 43068552.

**Design and level:** systematic review and meta-analysis of prevalence and associations. Label 3.

**(1) Key findings**  
Forty-three studies. Pooled prevalence of excessive daytime sleepiness in adults aged 60 years and older was 16.9%. Prevalence differed by region (lowest reported in East Asia at 13.0%, highest in Western Asia at 21.8%) and by the Epworth Sleepiness Scale cut-off. Factors associated with higher prevalence included male sex, obesity, malnutrition, urinary incontinence, and several long-term conditions (dementia, Parkinson’s disease, cerebrovascular disease, depression, diabetes, chronic obstructive pulmonary disease, insomnia and obstructive sleep apnoea). The abstract says hypnotic use “may serve as a protective factor”.

**(2) Methods and population**  
Search of eight databases, including Chinese-language sources, to October 2025. Fixed- or random-effects models for prevalence and odds ratios. The abstract does not report I² or the odds ratios themselves. The hypnotic association is cross-sectional in character and is open to confounding by indication, survival and differing definitions of sleepiness. It is not evidence that hypnotics prevent daytime sleepiness. AMSTAR-2 was not scored. A Newcastle–Ottawa or JBI prevalence checklist would be the relevant tool for the included studies; scores are not in the abstract.

**(3) UK adult relevance**  
Daytime sleepiness in older adults is a general UK clinical problem. A pooled figure of 16.9% is not a UK prevalence. The abstract gives no UK stratum. Case-mix, the Epworth cut-off and region all moved the estimate.

### 9. Obstructive sleep apnoea and lung cancer

He H, Chen S, Ren Q, Wei W, Pan Z, Liu J, et al. Obstructive sleep apnea and lung cancer risk: a systematic review with meta-analysis. Neoplasia. 2026;83:101399. doi:10.1016/j.neo.2026.101399. PMID: 43051096.

**Design and level:** systematic review and meta-analysis of cohorts. Label 3.

**(1) Key findings**  
Eight cohort studies were reviewed. Seven with adjusted hazard or risk ratios, covering 7,641,402 people, were pooled. The random-effects hazard ratio for lung cancer was 1.24 (95% CI 1.03 to 1.49). Studies with six to nine years of follow-up gave a hazard ratio of 1.32 (95% CI 1.27 to 1.38). Six retrospective cohorts gave a hazard ratio of 1.21 (95% CI 0.99 to 1.47), which includes no difference. Egger’s test p = 0.744, which the authors say is under-powered because there are few studies.

**(2) Methods and population**  
Search to September 2024, so this is not a synthesis of cohorts published after that date. The review itself was indexed in this week’s window. Adjustment was required for the seven pooled estimates, but the covariate sets are not listed in the abstract and may differ. Residual confounding by smoking is an obvious threat in any sleep-apnoea and lung-cancer comparison; the abstract does not show how completely smoking was handled. ROBINS-I or the Newcastle–Ottawa Scale would apply to the cohorts. AMSTAR-2 was not scored. This is an association, not a demonstration that treating sleep apnoea changes cancer risk.

**(3) UK adult relevance**  
Both conditions occur in UK adults. The abstract does not identify UK cohorts. The retrospective subset is compatible with no association, so the pooled result should be held lightly.

### 10. Masticatory muscles in bruxism

Yüzbaşıoğlu Ü, Ekici E, Taş S. Morphological and Mechanical Properties of Masticatory Muscles in Individuals With Bruxism: A Systematic Review and Meta-Analysis. J Oral Rehabil. 2026. doi:10.1111/joor.70381. PMID: 43040594.

**Design and level:** systematic review and meta-analysis of comparative observational studies. Label 3. The PubMed tag is Review.

**(1) Key findings**  
Nine studies. Masseter stiffness was higher in people with bruxism (standardised mean difference 1.87, 95% CI 0.53 to 3.22). Masseter and anterior temporalis thickness did not differ significantly. How bruxism was defined changed the thickness result: self-reported bruxism went with greater thickness, and polysomnography-confirmed bruxism went with lesser thickness. The authors’ conclusion is that stiffness, rather than thickness, is the more consistent finding.

**(2) Methods and population**  
PROSPERO CRD420261433530. PubMed, Web of Science and Scopus. The reviewers used the Newcastle–Ottawa Scale. Star scores are not in the abstract, so they are not repeated here. The stiffness confidence interval is wide, which fits a small and varied set of studies. Ultrasound, elastography and myotonometry were eligible and are not the same measurement. Treatment effects are not studied. AMSTAR-2 was not scored.

**(3) UK adult relevance**  
Bruxism is seen in adult dental and orofacial-pain practice in the UK. This abstract does not give a UK prevalence, and it does not show that measuring stiffness should change care. The split by diagnostic method is a warning against pooling self-report with sleep-laboratory bruxism.

### 11. Position statement on hypoglossal nerve stimulation

Dhanda Patil R, Losavio P, Huntley C, Suurna M, Durr M. International Surgical Sleep Society Position Statement: Hypoglossal Nerve Stimulation for Obstructive Sleep Apnea in Adults. Otolaryngol Head Neck Surg. 2026. doi:10.1002/ohn.70517. PMID: 43037012.

**Design and level:** society position statement based on a literature review. Label 6. It is not a GRADE guideline and not a new meta-analysis.

**(1) Key findings**  
The group searched PubMed, Embase and Cochrane for 2010–2026 and used 43 studies. Across those studies they summarise surgical response as a range from 67% to 83%, and nightly use as 5.6 to 7.7 hours. Predictors such as body mass index, age, sex and insomnia were mixed. Complications are described as uncommon and as something to discuss before implantation. The statement’s conclusion is that hypoglossal nerve stimulation is one option within adult obstructive sleep apnoea care.

**(2) Methods and population**  
The 67–83% range is a span across studies, not a pooled response rate. There is no new risk-of-bias scoring in the abstract. Selection into implant cohorts is highly filtered, so those response figures do not apply to unselected adults with sleep apnoea. Conflicts of interest are not described in the abstract.

**(3) UK adult relevance**  
Hypoglossal nerve stimulation is a specialist option for a minority of adults with obstructive sleep apnoea. This is an international surgical society statement. It does not describe National Health Service eligibility or UK outcome data.

### 12. European Delphi consensus on screening for sleep apnoea in obesity

Gordon J, Pollock KG, Lau E, Manco M, Yumuk V, Baker JL, et al. DISC-OSA: A European Delphi Consensus on OSA Screening in People with Obesity. Adv Ther. 2026. doi:10.1007/s12325-026-03853-4. PMID: 43050104.

**Design and level:** two-round modified Delphi consensus among 26 experts. Label 6. Consensus is not a substitute for screening trials.

**(1) Key findings**  
All 20 statements met the pre-set rule of at least 70% agreement and an interquartile range of 1 or less on a 5-point scale. The panel’s statements emphasise screening adults with obesity who also have cardiometabolic disease, placing screening inside a structured pathway, and referring onwards for diagnosis. The STOP-Bang questionnaire is the panel’s suggested first tool, with nocturnal oximetry or polysomnography as further options. Reporting followed ACCORD 2024. Experts came from European Association for the Study of Obesity collaborating centres.

**(2) Methods and population**  
A Delphi study measures agreement among selected experts. It does not estimate the sensitivity of STOP-Bang, the yield of screening, or the effect of screening on cardiovascular outcomes. The threshold (70%) is a convention of this study. The abstract does not list conflicts of interest. ROBINS-I and AMSTAR-2 do not fit this design.

**(3) UK adult relevance**  
Obesity and obstructive sleep apnoea commonly occur together in UK adults. This is a European expert framework, including UK-linked authorship on the byline, and it is not national UK guidance. Whether STOP-Bang is the right first tool in a given UK service is not settled by a consensus vote.

## Primary studies

### 13. Telemedicine auto-adjusting positive airway pressure and blood pressure

Yi H, Dong X, Zhang C, Li Z, Yang W, Zuo Y, et al. The Effect of Telemedicine-Based APAP Management on 24-Hour Ambulatory Blood Pressure in Patients with Obstructive Sleep Apnea: A Randomized Clinical Trial. Am J Respir Crit Care Med. 2026. doi:10.1093/ajrccm/aamag627. PMID: 43035945.

**Design and level:** randomised non-inferiority trial. Label 2. PubMed has not tagged the publication type as a randomised trial; the abstract describes randomisation.

**(1) Key findings**  
344 adults with suspected obstructive sleep apnoea were randomised to telemedicine-based or in-person auto-adjusting positive airway pressure care for 3 months. The non-inferiority margin for the between-group difference in change in 24-hour mean blood pressure was 1.5 mmHg. Of 344, 256 finished follow-up (127 in person, 129 telemedicine). The telemedicine-minus-in-person difference was −0.59 mmHg (95% CI −2.42 to 1.25) in the intention-to-treat analysis and −1.21 mmHg (95% CI −3.24 to 0.81) in the completer analysis. Both upper limits were below 1.5 mmHg. The abstract reports no clear difference in device use, patient-reported outcomes or metabolic measures.

**(2) Methods and population**  
The margin of 1.5 mmHg is small, and the confidence intervals are wider than that margin even though they meet the non-inferiority rule on the upper side. About a quarter of randomised participants did not complete follow-up. The abstract does not say how missing blood-pressure data were handled in the intention-to-treat analysis. Blinding of the care model is not realistic; the outcome is ambulatory blood pressure, which reduces some observer bias. RoB 2 was not scored. Country is not stated in the abstract.

**(3) UK adult relevance**  
Remote follow-up of positive airway pressure is a live question for UK sleep services. This trial supports non-inferiority on one blood-pressure contrast over 3 months, within the authors’ margin. It does not show that telemedicine lowers blood pressure more than in-person care, and it does not report UK service costs or safety signals.

### 14. Beliefs and symptoms during components of insomnia therapy

Yan Z, Meng F, Meng L, Song M, Xing H, Wang Z, et al. Temporal associations between dysfunctional sleep beliefs and insomnia severity in CBT-I subcomponents: A randomized dismantling trial. J Psychosom Res. 2026;212:113035. doi:10.1016/j.jpsychores.2026.113035. PMID: 43063859.

**Design and level:** randomised dismantling trial. Label 2.

**(1) Key findings**  
120 participants were randomised to full cognitive behavioural therapy for insomnia, cognitive therapy, behavioural therapy, or treatment as usual, delivered weekly for 8 weeks in the active arms. The Insomnia Severity Index and the 16-item Dysfunctional Beliefs and Attitudes about Sleep scale were measured at baseline, week 4 and week 8. All three active treatments reduced insomnia severity and dysfunctional beliefs. In growth-curve models, beliefs carried an indirect effect for the full therapy and for cognitive therapy, and not for behavioural therapy. Cross-lagged paths differed by treatment and by time interval. The abstract does not give the between-group differences on the Insomnia Severity Index.

**(2) Methods and population**  
Four arms and 120 people means roughly 30 in each arm, which is small for latent growth and cross-lagged models with several belief subscales. Multiple paths raise the chance of pattern-finding. There is no statement of allocation concealment, blinding or a pre-specified primary endpoint in the abstract. RoB 2 was not scored. Country is not stated. The mediation results are about pathways, not about how large the clinical effect was.

**(3) UK adult relevance**  
The question, whether changing sleep-related beliefs is part of how insomnia therapy works, matters for adult insomnia treatment generally. This abstract does not show that one component is clinically superior, and it does not locate the trial in the UK.

### 15. Acetazolamide plus oxygen in obstructive sleep apnoea

Landry SA, Joosten SA, Collet J, Preston T, Thomson LDJ, Beatty CJ, et al. Combination acetazolamide and supplemental oxygen markedly improves ventilatory control instability and OSA severity. Chest. 2026. doi:10.1016/j.chest.2026.11.015. PMID: 43067377.

**Design and level:** randomised, single-blind, crossover trial. Label 2. Registration ACTRN12616001297415.

**(1) Key findings**  
Twenty-two adults with moderate to severe obstructive sleep apnoea (15 men, 7 women) took acetazolamide 500 mg daily or placebo for 7 days. On the last nights they had polysomnography with oxygen at 3 L/min or sham oxygen. Against placebo plus sham, combination treatment reduced loop gain by 0.26 (95% CI 0.32 lower to 0.20 lower) and reduced a flow-based apnoea–hypopnoea index by 23.3 events per hour (95% CI 26.6 lower to 13.1 lower), about a 55% relative reduction. Loop gain fell further than with either drug or oxygen alone. The flow-based index with combination treatment was not clearly lower than with acetazolamide alone (difference −3.4 events per hour, 95% CI −8.5 to 1.6).

**(2) Methods and population**  
The sample is small and the exposure lasts a week. Single-blind design leaves some performance bias; the main outcomes are taken from polysomnography. The flow-based index is scored without the usual desaturation or arousal rules, so it is not the apnoea–hypopnoea index used in routine reports. Crossover carry-over is not discussed in the abstract. RoB 2 was not scored. The title’s wording is stronger than the comparison against acetazolamide alone, which was not superior on the breathing-event index.

**(3) UK adult relevance**  
This is a short physiological study in selected adults with sleep apnoea, not a treatment trial for general UK practice. Acetazolamide and night-time oxygen are not established routine alternatives to positive airway pressure on the basis of this abstract.

### 16. Sleep regularity and incident hypertension in UK Biobank

Potts KS, Kianersi S, Faquih T, Noordam R, Rutter MK, Sofer T, et al. Sleep Irregularity and Risk of Incident Hypertension in the UK Biobank. medRxiv. 2026. doi:10.64898/2026.11.12.26367978. PMID: 43060184.

**Design and level:** prospective cohort using accelerometry. Label 4. **This record is a preprint. It is not peer-reviewed.**

**(1) Key findings**  
Among 55,572 UK Biobank participants without hypertension and not on antihypertensive drugs (60% women, mean age 61), with at least five valid accelerometry days in 2013–2015, 5,713 developed hypertension over 7.9 years. A within-person standard deviation of sleep duration above 90 minutes, compared with 30 minutes or less, had a hazard ratio of 1.18 (95% CI 1.06 to 1.31). The lowest fifth of the sleep regularity index, compared with the highest fifth, had a hazard ratio of 1.40 (95% CI 1.29 to 1.52). Results were described as similar across subgroups. Sleep regularity and a genetic hypertension score were each associated with risk, without evidence of interaction.

**(2) Methods and population**  
Cox models adjusted for demographic, socioeconomic and lifestyle factors and for employment schedule. Outcome ascertainment used linked records. UK Biobank is healthier and less deprived than the UK population, and one week of accelerometry is a short sample of lifelong sleep. Residual confounding and reverse causation remain possible. The preprint status means the numbers may change. ROBINS-I or the Newcastle–Ottawa Scale would apply; they were not scored. The abstract’s suggestion that regular sleep schedules are a prevention target is a hypothesis, not a result of a trial.

**(3) UK adult relevance**  
This is directly a UK adult cohort, aged mainly in the 50s to 70s, and it is one of the most relevant records in the window for the general UK population. It is still an association from a preprint. It does not show that making sleep more regular lowers blood pressure.

### 17. Night-time light, cardiac structure and cardiovascular events

Dai J, Dai W, Heianza Y, Qi L. Nighttime light exposure and cardiac structure and function. Eur Heart J. 2026;47(43):6489-6502. doi:10.1093/eurheartj/ehag563. PMID: 42715935.

**Design and level:** prospective UK Biobank cohort. Label 4. Journal date 16 November 2026. First Entrez date 9 September 2026. MEDLINE date 16 November 2026.

**(1) Key findings**  
Wrist accelerometry with a light sensor was worn for 7 days by participants in 2013–2015. Cardiac magnetic resonance about 3 years later was available for 11,071 people. Incident cardiovascular disease and mortality analyses used 73,286 people over 8–10 years. High night-time light exposure above 3 lux, compared with none, was associated with a more concentric left ventricle and small reductions in deformation and function. The abstract gives examples of 2.4% (95% CI 1.6% to 3.1%) greater height-indexed left-ventricular mass and 1.9% (1.1% to 2.7%) lower myocardial contraction fraction. Over follow-up, high versus no exposure was associated with a 29% (12% to 49%) higher heart-failure risk, 15% (4% to 27%) higher atrial fibrillation risk, 24% (7% to 44%) higher myocardial infarction risk, 33% (11% to 59%) higher stroke risk, and 26% (5% to 52%) higher cardiovascular mortality. Shorter sleep duration was reported to mediate 24% to 49% of most imaging associations.

**(2) Methods and population**  
Models were multivariable. Light and sleep were measured for one week, years before many of the events. UK Biobank selection bias applies. Mediation by sleep duration does not show that light acts only through sleep, and it does not separate light from shift work, urban environment and deprivation. The abstract says the models were multivariable and does not name the covariates. ROBINS-I would be the matching tool; it was not scored. The imaging differences are small in percentage terms. The event associations are larger and still observational.

**(3) UK adult relevance**  
This is a UK adult dataset and is relevant to the general population in a way that clinic samples are not. Night-time light is common. The study does not show that changing bedroom light changes heart structure or prevents events.

### 18. Sleep–wake profiles and dementia in Whitehall II

Vidil S, Danilevicz IM, Dugravot A, Cavaillès C, Ocampo NG, Singh-Manoux A, et al. Sleep-Wake Cycle Profiles and Incident Dementia and Cognitive Decline in Older Adults. JAMA Netw Open. 2026;9(11):e2644843. doi:10.1001/jamanetworkopen.2026.44843. PMID: 43050188.

**Design and level:** prospective UK cohort. Label 4.

**(1) Key findings**  
Accelerometry from the 2012–2013 wave of Whitehall II was used in 3,973 dementia-free adults aged 60 or older (median age 68.4 years; 26% women). Over a median 12.3 years, 379 dementia cases were identified from electronic health records. Compared with a profile of robust rest–activity rhythm, light activity and good sleep, a profile of poor rhythm, low activity and poor sleep had a hazard ratio of 1.94 (95% CI 1.32 to 2.84), and a profile of high-level, low-amplitude rhythm with restless sleep had a hazard ratio of 1.96 (95% CI 1.27 to 3.03). In 3,806 people with cognitive tests, the poor-rhythm and low-activity profile and the most sedentary profile had faster 10-year decline (global cognitive z-score differences −0.14 and −0.28). Among people with a robust rhythm and higher activity, cognitive results were similar regardless of sleep.

**(2) Methods and population**  
Nine profiles were built from 36 metrics, which is a data-driven classification and can be sample-specific. The abstract does not list the covariates in the hazard models. Dementia from records will miss undiagnosed cases. Whitehall II is an occupational cohort and, in this analysis, three-quarters male, so it is a poor mirror of all older UK adults. Prodromal dementia can disturb sleep and activity years before diagnosis, which means the association may be early disease rather than a cause. ROBINS-I or the Newcastle–Ottawa Scale would apply; they were not scored.

**(3) UK adult relevance**  
High, for older UK adults, with the limits above. The abstract does not show that changing a sleep–wake profile delays dementia. The authors say further studies would be needed to test interventions.

### 19. Dual orexin receptor antagonists, falls and delirium in dementia

Liu TH, Chu CC, Liu CY, Wu JY, Tsai YW, Chang HA, et al. Risk of falls and delirium associated with dual orexin receptor antagonists versus benzodiazepines and Z-drugs in older adults with dementia. Transl Psychiatry. 2026;16(1). doi:10.1038/s41398-026-04394-8. PMID: 43039931.

**Design and level:** retrospective matched cohort in electronic health records (TriNetX). Label 4.

**(1) Key findings**  
From 17,226 adults aged 65 or older with dementia and insomnia, 734 pairs remained after propensity-score matching. New use of suvorexant, lemborexant or daridorexant, compared with benzodiazepines or Z-drugs, started within a month of a dementia diagnosis. Over 12 months, dual orexin receptor antagonist use was associated with lower recorded falls (hazard ratio 0.35, 95% CI 0.18 to 0.71), delirium (0.39, 95% CI 0.23 to 0.65), hospitalisation (0.31, 95% CI 0.21 to 0.47) and emergency visits (0.32, 95% CI 0.20 to 0.50). Mortality was not clearly different (0.77, 95% CI 0.53 to 1.11). Mean age was 83.5 years, and about two-thirds were women.

**(2) Methods and population**  
Matching reduces some baseline imbalance. It does not remove unmeasured differences in frailty, care setting, or why one drug was chosen. Effect sizes this large in records data need caution. Falls and delirium are incompletely captured in coded data. There is no measure here of whether insomnia improved. The design is not a trial, so RoB 2 does not apply. ROBINS-I would be appropriate and was not scored from the abstract. The authors’ phrase “safer alternative” is their interpretation of associations.

**(3) UK adult relevance**  
Insomnia in older adults with dementia is a UK clinical problem, and benzodiazepines and Z-drugs are widely used. This network is not a UK dataset. The abstract is a safety comparison, not evidence that these drugs should be substituted in UK practice.

### 20. Sex, age and mortality in a Swedish sleep-apnoea clinic cohort

Peker Y, Holtstrand Hjälm H, Thunström E, Glantz H, Pihtili A, Eulenburg C. Sex-specific differences in mortality in obstructive sleep apnea: results from the Sleep Apnea Patients in Skaraborg (SIS) Study. Ann Am Thorac Soc. 2026. doi:10.1093/annalsats/aaoag358. PMID: 43055360.

**Design and level:** clinic cohort with mortality follow-up. Label 4.

**(1) Key findings**  
The cohort included 3,843 adults with an apnoea–hypopnoea index of at least 5. Over a median 5.9 years (interquartile range 4.6 to 7.2), 421 people died. Mortality was 10.0% in women (120/1,203) and 11.4% in men (301/2,640), despite lower sleep-apnoea severity in women. In severe disease, men had higher mortality than women (hazard ratio 1.50, 95% CI 1.09 to 2.05). Mild and moderate strata did not show a clear sex difference. The sex-by-severity interaction p-value was 0.110. Among people aged 50 or under, the hazard ratio for men versus women was 0.34 (95% CI 0.14 to 0.87), which the authors say rests on few events. Among people over 50, men with severe disease had a hazard ratio of 1.58 (95% CI 1.15 to 2.18). Treatment was associated with lower mortality in the over-50 group (hazard ratio 0.52, 95% CI 0.40 to 0.67).

**(2) Methods and population**  
Cox models adjusted for age, obesity, current smoking, diabetes, Epworth score, hypertension, cardiovascular disease and cerebrovascular disease. The interaction test does not confirm that severity modifies the sex association, even though the severe stratum is significant on its own. The treatment association is observational and open to confounding by who receives and continues treatment. The younger-women finding is explicitly fragile. The Newcastle–Ottawa Scale or ROBINS-I would apply; they were not scored.

**(3) UK adult relevance**  
This is a Swedish clinic population with diagnosed sleep apnoea, not a sample of UK adults. The pattern that matters for a general reader is heterogeneity by age and severity, plus the authors’ own caution on the younger group. It should not be quoted as a UK mortality rate.

### 21. Nocturnal hypoxaemia after ischaemic stroke, and later death

Roux M, Garnier P, Ollier E, Moulhi L, Monier M, Camdessanché JP, et al. Nocturnal hypoxaemic parameters from cardiorespiratory holter monitoring are associated with all-cause mortality in post-ischaemic stroke patients: The CHUTE study. Sleep Med. 2026;149:109353. doi:10.1016/j.sleep.2026.109353. PMID: 43035083.

**Design and level:** retrospective single-centre cohort. Label 4.

**(1) Key findings**  
Of 3,595 adults hospitalised with stroke in Saint-Étienne between 2010 and 2020, 1,113 who had cardiorespiratory Holter monitoring were included (mean age 65.8 years, standard deviation 14.4; 61% men). By 23 December 2023, 288 had died, with deaths identified from the French national death register. Mean nocturnal oxygen saturation below 90% had a hazard ratio of 1.46 (95% CI 1.04 to 2.04). An oxygen desaturation index of at least 15 per hour had a hazard ratio of 1.58 (95% CI 1.24 to 2.00). Time with saturation below 90% for at least 10% of the night had a hazard ratio of 1.34 (95% CI 1.05 to 1.72). Desaturation duration and slope were not clearly associated.

**(2) Methods and population**  
Only patients who underwent Holter monitoring were included, which is a selected slice of the stroke ward. Cox models are reported. The abstract does not list the covariates, so it is unclear how far stroke severity, smoking and cardiac disease were handled. Night-time hypoxaemia is a marker as well as a possible contributor. ROBINS-I or the Newcastle–Ottawa Scale would apply; they were not scored. This is not a trial of treating sleep apnoea after stroke.

**(3) UK adult relevance**  
Sleep-disordered breathing after stroke is a recognised clinical issue in UK stroke services. These hazard ratios come from one French centre and from patients selected for monitoring. They do not estimate the effect of treatment.

### 22. Sleep bruxism episodes and respiratory events

Chen Y, Yu M, Tian Y, Luo L, Xu Y, Han F, et al. Beyond the RMMA Index: Respiratory-Event Context and Episode Duration in Adults With Obstructive Sleep Apnea and Sleep Bruxism. J Oral Rehabil. 2026. doi:10.1111/joor.70385. PMID: 43046277.

**Design and level:** retrospective polysomnography series in adults with both conditions. Label 4, closer to a mechanistic cohort than to an outcome study.

**(1) Key findings**  
Ninety-four adults with obstructive sleep apnoea and sleep bruxism contributed 3,774 rhythmic masticatory-muscle episodes. Of these, 2,686 (71.2%) fell within 20 seconds of a respiratory event, more than a within-night chance model (0.733 versus 0.273). Compared with episodes near obstructive apnoeas, episodes near central apnoeas were more often before the event (odds ratio 2.67, 95% credible interval 1.76 to 4.19) or overlapping it (odds ratio 3.26, 95% credible interval 2.03 to 5.29). Of post-event episodes, 43.0% (486) started within 5 seconds of a respiratory arousal. Shorter episodes were associated with a greater burden of respiratory events, desaturation and arousal. The cohort is described as mostly male and relatively young.

**(2) Methods and population**  
The chance model and the Bayesian multinomial mixed model are appropriate to clustered episodes inside a night. The sample is people who already have both diagnoses, so it cannot estimate how often the two conditions occur together. Temporal closeness is not proof that one causes the other. There is no treatment result. ROBINS-I is a poor fit for a within-night timing study; a formal tool was not applied.

**(3) UK adult relevance**  
Adults with both sleep apnoea and sleep bruxism are seen in UK dental and sleep clinics. This abstract suggests the muscle events are often organised around breathing events, with more than one pattern. It does not say whether treating the breathing disorder changes tooth wear or jaw pain.

### 23. Bruxism-related signs in adults without a prior diagnosis

Usdat Ozturk A, Palaz CH. Association Between Lifestyle Habits, Anxiety Levels, and Bruxism-Related Signs in Undiagnosed Adults. Oral Health Prev Dent. 2026;24:1159-1168. doi:10.3290/j.ohpd.c_2853. PMID: 43059044.

**Design and level:** cross-sectional dental-clinic study. Label 5. The MeSH tags include an adolescent term as well as adult terms. The abstract restricts the sample to adults aged 18–60 years with no previous bruxism or temporomandibular diagnosis.

**(1) Key findings**  
188 adults attending routine dental examinations were examined for tooth wear, jaw pain, facial pain, joint sounds and parafunction, and they completed questions on smoking, alcohol, coffee, exercise, antidepressant use and the Generalised Anxiety Disorder-7 scale. After adjustment, occlusal tooth wear remained associated with older age and smoking. Antidepressant use remained associated with jaw pain and facial pain. The tooth-wear association with antidepressants weakened after adjustment, which the authors link to the older age of those users. Anxiety severity was associated with stress-related headache, and not with the objective dental signs in the way lifestyle and antidepressants were. Adjusted odds ratios are not printed in the abstract.

**(2) Methods and population**  
This is a single group at routine dental visits, not a population sample, and not polysomnographic sleep bruxism. Adjusted logistic models included age, sex, smoking, alcohol, coffee, antidepressants, exercise and anxiety category. “Undiagnosed” means no prior label, which is different from a sleep-laboratory diagnosis. Cross-sectional data cannot order anxiety, antidepressants and jaw pain. The Newcastle–Ottawa Scale can be adapted for cross-sectional work; it was not scored. No effect sizes are available from the abstract, which limits interpretation.

**(3) UK adult relevance**  
Jaw signs and antidepressant use are common in UK adult primary care and dentistry. The setting is not described as UK. The useful point is methodological: self-reported anxiety and objective tooth wear did not travel together after adjustment, so a questionnaire is a weak stand-in for dental signs.

### 24. Tongue-base collapse and positive airway pressure use

Lee CW, Storey M, Botting Z, Cheong R, McNeillis S, Veer V. Tongue Base Collapse as an Independent Risk Factor for CPAP Non-Compliance in Obstructive Sleep Apnoea. Clin Otolaryngol. 2026. doi:10.1111/coa.70198. PMID: 43068900.

**Design and level:** retrospective single-centre cohort of adults assessed for alternatives to positive airway pressure. Label 4.

**(1) Key findings**  
Seventy-five consecutive adults with obstructive sleep apnoea had drug-induced sleep endoscopy between 1 October 2024 and 1 October 2025 because alternatives to positive airway pressure were being considered. Forty-three (57.3%) had not met a use threshold of at least 4 hours on at least 70% of nights in the previous 30 days. Severe tongue-base collapse (more than 50%) was associated with not meeting that threshold (odds ratio 4.67, 95% CI 1.46 to 16.20). The association remained after adjustment for age, sex, body mass index, apnoea–hypopnoea index and other collapse sites (adjusted odds ratio 7.17, 95% CI 1.56 to 40.99; area under the curve 0.811). A Firth penalised model gave an adjusted odds ratio of 4.72 (95% CI 1.23 to 21.69). Each higher collapse grade had an adjusted odds ratio of 2.68 (95% CI 1.25 to 6.35). Total collapse burden was not associated.

**(2) Methods and population**  
The sample is enriched for people already struggling with, or being considered for alternatives to, positive airway pressure. The odds ratios should not be applied to all adults starting treatment. Confidence intervals are very wide, as expected with 75 people. Drug-induced sleep endoscopy is sedation, not natural sleep. The Firth analysis is a sensible check and gives a smaller estimate than the standard adjusted model, which shows the estimate is unstable. ROBINS-I would apply; it was not scored. Country of the clinic is not stated in the abstract. The journal is linked to ENT-UK.

**(3) UK adult relevance**  
The question is relevant to UK adults who do not get on with positive airway pressure and are referred for surgical assessment. This abstract supports an association, in that selected group, between tongue-base collapse and low nightly use. It does not show that surgery changes use.

## Coverage gaps

### Embase and Scopus

Embase and Scopus were not searched. Institutional access was not available. The strings below are ready to paste and then deduplicate against the PubMed PMIDs in this pack. Emtree headings were not re-checked in the live Embase thesaurus. If Embase rejects a heading, delete that heading and keep the free-text lines. Do not add the bare acronym SRPE. In this week’s PubMed run it retrieved session rating of perceived exertion, not sleep-related painful erections.

**Embase, entry date 16–23 November 2026.** Run again with `/pd` in place of `/sd` if the aim is publication date rather than database entry date, then deduplicate.

```
('sleep disorder'/exp OR 'insomnia'/exp OR 'sleep disordered breathing'/exp OR 'narcolepsy'/exp OR 'restless legs syndrome'/exp OR 'parasomnia'/exp OR 'bruxism'/exp OR 'polysomnography'/exp OR insomnia:ti,ab OR 'sleep apnoea':ti,ab OR 'sleep apnea':ti,ab OR 'obstructive sleep':ti,ab OR narcolepsy:ti,ab OR cataplexy:ti,ab OR hypersomnia:ti,ab OR 'excessive daytime sleepiness':ti,ab OR 'restless legs':ti,ab OR 'restless leg':ti,ab OR parasomnia:ti,ab OR parasomnias:ti,ab OR 'REM sleep behavior':ti,ab OR 'REM sleep behaviour':ti,ab OR 'circadian rhythm':ti,ab OR bruxism:ti,ab OR 'sleep bruxism':ti,ab OR 'teeth grinding':ti,ab OR 'tooth grinding':ti,ab OR 'sleep-related painful erection':ti,ab OR 'sleep-related painful erections':ti,ab OR 'sleep related painful erection':ti,ab OR 'sleep related painful erections':ti,ab OR 'nocturnal penile tumescence':ti,ab OR cpap:ti,ab OR 'continuous positive airway pressure':ti,ab OR 'hypoglossal nerve':ti,ab OR 'mandibular advancement':ti,ab OR 'cognitive behavioural therapy for insomnia':ti,ab OR 'cognitive behavioral therapy for insomnia':ti,ab OR 'obesity hypoventilation':ti,ab) AND [16-11-2026 to 23-11-2026]/sd
```

An age limit such as `AND ([adult]/lim OR [aged]/lim OR [very elderly]/lim)` will drop records that Embase has not yet indexed with an age tag. That is the same problem as a PubMed adult filter this week. Screening is safer. Human limits have the same issue.

**Scopus advanced search, records added 16–23 November 2026.** Confirm the date-field names in the local Scopus interface. `ORIG-LOAD-DATE AFT 20261115 AND ORIG-LOAD-DATE BEF 20261124` is meant to include 16 November and 23 November. Scopus does not mirror PubMed’s publication-date field in one portable line. A publication-year limit of 2026 alone is much wider than this week.

```
TITLE-ABS-KEY ( insomnia OR "sleep apnoea" OR "sleep apnea" OR "obstructive sleep" OR narcolepsy OR cataplexy OR hypersomnia OR "excessive daytime sleepiness" OR "restless legs" OR "restless leg" OR parasomnia OR "REM sleep behavior" OR "REM sleep behaviour" OR "circadian rhythm" OR bruxism OR "sleep bruxism" OR "teeth grinding" OR "tooth grinding" OR "sleep-related painful erection" OR "sleep-related painful erections" OR "sleep related painful erection" OR "sleep related painful erections" OR "nocturnal penile tumescence" OR cpap OR "continuous positive airway pressure" OR "hypoglossal nerve" OR "mandibular advancement" OR "obesity hypoventilation" OR polysomnography ) AND ORIG-LOAD-DATE AFT 20261115 AND ORIG-LOAD-DATE BEF 20261124
```

### Topics that were thin or empty

- **SRPE.** No eligible paper. The only acronym hits were false matches, PMIDs 43043379 and 43058885.
- **Bruxism.** The eligible adult material this week was the muscle systematic review, the polysomnography timing study, and the dental cross-sectional study. A further adult EPISONO bruxism paper (PMID 43035081) was excluded because it was already in an earlier pack. A dental-student survey (PMID 43065029) was not given a full entry.
- **Restless legs syndrome.** A narrative review was indexed (Ibrahim A, Stefani A. Restless Legs Syndrome: Current Concepts in Diagnosis and Treatment. Neurol Clin. 2027;45(1):149-166. doi:10.1016/j.ncl.2026.08.006. PMID: 43045432). It was not given a full entry because it is not a systematic review. Its abstract describes alpha-2-delta ligands as preferred long-term treatment over dopamine agonists, citing a 2025 American Academy of Sleep Medicine source. That statement was not re-checked against the guideline.
- **Age tags.** MeSH age limits were not used at search. Some included records may still contain a minority of younger adults. A long-term narcolepsy type 1 cohort that mixed children and adults (PMID 43050735) was not included.
- **Full text, tools, and language.** Abstracts only. RoB 2, ROBINS-I, Newcastle–Ottawa and AMSTAR-2 were not scored. Non-English records were not given full entries. Several Chinese-language clinical papers were in the export, including a single-arm fire-needle study tagged as a clinical trial (PMID 43039831), and were not appraised from the English abstract field alone.
- **Preprints.** One preprint was included (PMID 43060184) because it is a large UK Biobank analysis, and it is marked as not peer-reviewed. Other preprints, including a hypoxic-burden and CPAP paper (PMID 43060605) and a US complementary-therapy survey (PMID 43067870), were not given full entries.
- **Other adult papers read and not given a full entry.** An antenatal randomised trial of sleep hygiene and progressive muscle relaxation in pregnant women with obesity (PMID 43047746, n = 100). A component network meta-analysis of pulmonary rehabilitation in chronic obstructive pulmonary disease that could not pool sleep outcomes because only four studies reported them (PMID 43051663). A small systematic review of electrical vestibular stimulation for insomnia (PMID 43065333; five trials, heterogeneous). A narrative review of psychedelics and sleep that mixed animal and human studies and was not prospectively registered (PMID 43054774).
- **Earlier packs.** PMIDs supplied from the 9 November and 16 November packs were removed if retrieved. Only 43035081 and 43035082 fell inside this search.

### Uncertainty

- Pagination is cited only when PubMed supplied a volume, issue or page. Several records are ahead of print and have a DOI only.
- The sixth author of PMID 43066573 is stored in PubMed as “S P”. That string was kept.
- Country is stated only when the abstract or the cohort name states it. Journal affiliation was not treated as the study country.
- Hazard ratios and mean differences are copied from abstracts. Where the abstract’s own conclusion is stronger than its interval (depression after brain injury; combination acetazolamide versus acetazolamide alone; hypnotic drugs and daytime sleepiness), the interval is the finding reported here.
