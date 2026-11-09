# Weekly adult sleep literature

Version 1.0. 9 November 2026.

This note covers human studies of adults, about 18 years and older, found in PubMed. The window is records published, or added to PubMed, from 2 to 9 November 2026. The week was not thin. Hundreds of sleep records were retrieved. The papers below are the ones most relevant to ordinary UK adult care, not every sleep paper that week.

Child-only studies and animal studies were left out. Full papers were not used. Every number below is taken from the PubMed record. Where a figure is missing, or the record looks inconsistent, that is stated. Nothing here was filled in from memory of the paper.

A few records were already in PubMed before 2 November and are included because the journal date, or the date of MEDLINE indexing, falls inside the week. That is stated on those papers. No retrieved record had been added to PubMed on 9 November itself. The search included that day, but the day’s new records were not yet posted when the search was run on the morning of 9 November 2026 (UTC).

## How the evidence labels are used

Primary means the paper reports its own data. Secondary means it sums up other papers.

The level is a reading aid, based on the PubMed record:

- Level 1. A large randomised trial, or a review that pools randomised trials.
- Level 2. One randomised trial, or a review of trials that does not pool them.
- Level 3. A study that follows people over time, without random assignment.
- Level 4. A survey at one point in time, a case series, or a before-and-after study with no comparison group.
- Level 5. A narrative review or expert comment.

Named checklists, used only where they fit:

- Cochrane RoB 2, for bias in randomised trials.
- ROBINS-I, for bias when treatments are compared without random assignment.
- Newcastle-Ottawa, for cohort and case-control studies.
- AMSTAR-2, for systematic reviews of treatment or risk.

A judgement from an abstract is a first look. It is not a finished checklist score.

## Search record

This record follows the PRISMA-S checklist for the search itself. It is a weekly sweep by one reader, not a full systematic review with two screeners or a peer-reviewed search strategy.

| Item | Detail |
| --- | --- |
| Database | PubMed, which includes MEDLINE |
| Interface | NCBI E-utilities (ESearch and EFetch), public, no login. This uses the same PubMed index as the website |
| Date run | 9 November 2026, morning UTC |
| Other databases | Embase: not searched. Scopus: not searched. Institutional access was not available |
| Registers, citation chasing, authors contacted | Not used |
| Language limit | None |
| Age limit in the search | None. PubMed’s adult filter starts at 19 years and misses new records that have no age tag. Adult status was judged afterwards from the title and abstract |
| Animal limit | Records indexed as animal-only were removed. Records with no animal or human tag were kept and then read |
| Full text | Not used. Appraisal uses the PubMed abstract, publication type, and citation fields |
| Peer review of the strategy | None |

Dates in the strings below are inclusive. `[pdat]` is the publication date. `[edat]` is the date PubMed added the record. `[crdt]` is the date the record was created. The create-date search was a check only. It was not added on top of the other results. `[mh]` is a PubMed subject heading. `[tiab]` is title or abstract.

### Block A, adult sleep medicine

Topics in the string: insomnia, sleep apnoea, circadian rhythm, narcolepsy and hypersomnia, restless legs, periodic limb movement, parasomnias including REM sleep behaviour disorder, and sleep with health (sleep quality, duration, disorder, or disturbance).

Publication date only. **172** records.

```
(
  "Sleep Initiation and Maintenance Disorders"[mh] OR insomnia[tiab]
  OR "Sleep Apnea Syndromes"[mh] OR "Sleep Apnea, Obstructive"[mh]
  OR "sleep apnoea"[tiab] OR "sleep apnea"[tiab] OR "obstructive sleep"[tiab]
  OR "Sleep Disorders, Circadian Rhythm"[mh] OR "circadian rhythm"[tiab]
  OR Narcolepsy[mh] OR narcolepsy[tiab] OR cataplexy[tiab]
  OR "Disorders of Excessive Somnolence"[mh] OR "Idiopathic Hypersomnia"[mh]
  OR hypersomnia[tiab] OR hypersomnolence[tiab]
  OR "Restless Legs Syndrome"[mh] OR "restless legs"[tiab]
  OR "Nocturnal Myoclonus Syndrome"[mh] OR "periodic limb movement"[tiab]
  OR Parasomnias[mh] OR parasomnia*[tiab]
  OR "REM Sleep Behavior Disorder"[mh] OR "REM sleep behav*"[tiab]
  OR "Sleep Wake Disorders"[mh]
  OR "sleep quality"[tiab] OR "sleep duration"[tiab]
  OR "sleep disorder"[tiab] OR "sleep disturbance"[tiab]
) AND ("2026/11/02"[pdat] : "2026/11/09"[pdat])
```

Date added to PubMed only. **357** records. The same topic string was used with `("2026/11/02"[edat] : "2026/11/09"[edat])`.

Create-date check, not added as extra records. **354**. The same topic string was used with `("2026/11/02"[crdt] : "2026/11/09"[crdt])`.

Published or added in the window. **368** records.

```
(
  "Sleep Initiation and Maintenance Disorders"[mh] OR insomnia[tiab]
  OR "Sleep Apnea Syndromes"[mh] OR "Sleep Apnea, Obstructive"[mh]
  OR "sleep apnoea"[tiab] OR "sleep apnea"[tiab] OR "obstructive sleep"[tiab]
  OR "Sleep Disorders, Circadian Rhythm"[mh] OR "circadian rhythm"[tiab]
  OR Narcolepsy[mh] OR narcolepsy[tiab] OR cataplexy[tiab]
  OR "Disorders of Excessive Somnolence"[mh] OR "Idiopathic Hypersomnia"[mh]
  OR hypersomnia[tiab] OR hypersomnolence[tiab]
  OR "Restless Legs Syndrome"[mh] OR "restless legs"[tiab]
  OR "Nocturnal Myoclonus Syndrome"[mh] OR "periodic limb movement"[tiab]
  OR Parasomnias[mh] OR parasomnia*[tiab]
  OR "REM Sleep Behavior Disorder"[mh] OR "REM sleep behav*"[tiab]
  OR "Sleep Wake Disorders"[mh]
  OR "sleep quality"[tiab] OR "sleep duration"[tiab]
  OR "sleep disorder"[tiab] OR "sleep disturbance"[tiab]
) AND (("2026/11/02"[pdat] : "2026/11/09"[pdat]) OR ("2026/11/02"[edat] : "2026/11/09"[edat]))
```

After removing animal-only records, add `NOT (animals[mh] NOT humans[mh])`. **356** records. Twelve animal-only records dropped out.

Of those 356, one was a book chapter, not a journal article: Coffin-Siris syndrome in GeneReviews (PMID 23556151), with the PubMed record updated on 5 November 2026. It is a genetic syndrome that presents in childhood. It was excluded. That left 355 journal records. Three of them are about bruxism and are written up only in block B, so they are not repeated here. Nineteen papers are written up below.

### Block B, bruxism and sleep-related painful erections

Publication date only. **4** records. Date added to PubMed only. **9** records. Create-date check. **9** records. Published or added. **10** records. Animal-only removal did not drop any. **10** records.

```
(
  Bruxism[mh] OR "Sleep Bruxism"[mh]
  OR bruxism[tiab] OR "teeth grinding"[tiab] OR "tooth grinding"[tiab]
  OR "sleep-related painful erection"[tiab] OR "sleep related painful erection"[tiab]
  OR "sleep-related painful erections"[tiab] OR "sleep related painful erections"[tiab]
  OR "painful nocturnal erection"[tiab] OR "painful erections"[tiab]
  OR SRPE[tiab]
) AND (("2026/11/02"[pdat] : "2026/11/09"[pdat]) OR ("2026/11/02"[edat] : "2026/11/09"[edat])) NOT (animals[mh] NOT humans[mh])
```

Extra check, in case painful erections were indexed only as priapism. **0** records.

```
(Priapism[mh] OR priapism[tiab]) AND (sleep[tiab] OR nocturnal[tiab] OR "REM"[tiab]) AND (("2026/11/02"[pdat] : "2026/11/09"[pdat]) OR ("2026/11/02"[edat] : "2026/11/09"[edat]))
```

No paper on sleep-related painful erections was found. Of the 10 bruxism records, 6 are adult and are written up below. Three are about children and are listed as excluded. One matched only because bruxism was a keyword on a paper about jaw-muscle pain. It is listed and not treated as a bruxism study.

## Block A. Adult sleep medicine

### 1. Weight-loss drug and sleep apnoea

Jastreboff AM, Kaplan LM, Davies MJ, et al. Retatrutide, a Triple Hormone Receptor Agonist, for Treatment of Obesity. N Engl J Med. 2026;395(18):1781-1793. doi:10.1056/NEJMoa2604169. PMID: 42814954.

Phase 3 randomised, double-blind, placebo-controlled trial. Primary research. Level 1. The record was added to PubMed on 30 September 2026. The journal date is 5 November 2026, and MEDLINE indexing is 4 November 2026.

1. Adults with obesity and without diabetes were randomised to weekly injections of retatrutide (4 mg, 9 mg, or 12 mg) or placebo for 80 weeks. In the whole trial of 2,339 people, mean weight change was −17.6%, −23.7%, and −25.0% against −3.9% with placebo. The planned comparisons were the 9 mg and 12 mg doses against placebo. In the 243 participants with obstructive sleep apnoea, breathing pauses per hour changed by −22.9, −34.3, and −31.7 against −9.9 with placebo. For the 9 mg and 12 mg doses the differences from placebo were −24.4 and −21.9 pauses per hour. A second analysis that kept people in their assigned groups gave almost the same sleep result. Knee pain also fell in a subgroup of 574 people with knee osteoarthritis. The most common unwanted effects were stomach and gut symptoms. The abstract does not give the rates.

2. The design is strong: random assignment, a placebo, blinding, and a pre-set analysis. The sleep result is a subgroup, not the result for every person in the trial, so it is less certain than the weight result. Placebo also reduced pauses, which is why the comparison matters. On Cochrane RoB 2, the abstract supports a low level of concern about assignment and blinding. Missing-data handling and the full side-effect table need the paper. The abstract does not give the rates of unwanted effects.

3. Obesity and sleep apnoea commonly occur together in UK adults. The trial supports treating weight as part of sleep apnoea care, and it shows a large effect on pauses in this selected group. It does not say whether the NHS provides retatrutide. People in the trial had obesity and no diabetes, so the result does not automatically cover every adult with sleep apnoea.

### 2. Sleep apnoea and insomnia together

Celik Y, Pihtili A, Kiyan E, et al. Clinical and Polysomnographic Characteristics of Comorbid Insomnia and Sleep Apnoea: Findings From the TURKAPNE Cohort. J Sleep Res. Published online November 3, 2026. doi:10.1111/jsr.70500. PMID: 42974656.

Cross-sectional study of a national clinic database. Primary research. Level 4.

1. Among 12,715 adults who had an overnight sleep study in the Turkish Sleep Apnoea Database, 8,142 (64.0%) had sleep apnoea only, 3,275 (25.8%) had sleep apnoea with insomnia symptoms, 388 (3.1%) had insomnia symptoms only, and 910 (7.2%) had neither. Compared with people who had neither, those with both conditions more often had night-time breathlessness (adjusted odds about 3.9), morning headache (about 3.3), and low mood (about 3.0). Their studies showed both disturbed breathing and more broken sleep, including a longer time to fall asleep and more wakenings.

2. The size and the use of full sleep studies are strengths. Insomnia was based on symptom questions, which is not the same as a clinical diagnosis made over time. The abstract says the odds were adjusted, but it does not list the other factors in the model, so leftover confounding cannot be ruled out. This is a clinic sample, so Newcastle-Ottawa, which is built for cohorts and case-control studies, is only a loose fit. Selection into a sleep clinic is the main limit.

3. The one-in-four figure is for people already in sleep clinics, not for the UK public. The pattern still matters in NHS clinics: apnoea and insomnia symptoms often arrive together, with headache, low mood, and night-time breathlessness. Asking about both is reasonable. The study does not test which treatment should come first.

### 3. Online insomnia course in routine care

Nomeikaitė A, Orobosa G, Hadjistavropoulos HD, Titov N, Dear BF, Scott AJ. The Sleep Course: Examining the feasibility, acceptability, and outcomes of an online sleep intervention for adults with self-reported sleep difficulties. Internet Interv. 2026;46:101018. doi:10.1016/j.invent.2026.101018. PMID: 42990575.

Uncontrolled before-and-after study of a seven-week online course. Primary research. Level 4. Journal date 26 October 2026. Added to PubMed on 6 November 2026.

1. Ninety-five adults with self-reported sleep difficulty used the course in a routine online clinic (78% women, mean age 52). From the start to three months later, insomnia severity improved by a large amount (effect size 1.43) and unhelpful beliefs about sleep also improved (effect size 1.09). Sleep-quality scores and anxiety and depression scores improved by smaller amounts. Satisfaction was 88%, and 73% of lessons were completed. The country of the clinic is not stated in the PubMed record.

2. There is no comparison group. People who seek help often improve anyway, and scores tend to move back toward average. Those two facts can look like a treatment effect. There is no random assignment, so Cochrane RoB 2 and ROBINS-I do not fit a single-group course. The sample is modest and mostly women. Completion and satisfaction are encouraging, and they are not proof that the course beats usual care.

3. Digital insomnia therapy is relevant to NHS services that cannot offer face-to-face therapy to everyone. This paper supports trying a structured online course in ordinary clinics. It should not be quoted as proof of effectiveness.

### 4. What insomnia therapy contains in trials

Roland A, Schoonjans AL, Mairesse O. How Is Cognitive Behavioural Therapy for Insomnia Provided in Randomized Controlled Trials? A Scoping Review. J Sleep Res. Published online November 5, 2026. doi:10.1111/jsr.70481. PMID: 42988787.

Scoping review of randomised trials. Secondary research. Level 2. PubMed classes it as a review. The title says it is a scoping review, and the abstract does not describe a pooled treatment effect.

1. The authors searched PubMed, Embase, and Web of Science and included 514 publications, of which 375 were separate randomised trials of cognitive behavioural therapy for insomnia. About half (197) focused on insomnia alongside another illness. The parts most often reported were stimulus control, meaning getting out of bed when not asleep (86.93%), limiting time in bed (84.53%), work on thoughts about sleep (83.20%), and sleep hygiene advice (78.13%). A few trials left out one of the three core parts, and they rarely said why. The usual course was six sessions. The review says that is more than an earlier suggestion of four. Individual sessions were usually 60 minutes. Groups were usually 90 minutes with four to six people. Delivery was usually face to face, by a psychologist.

2. This maps what trials do. It does not estimate how well therapy works, so AMSTAR-2 is a poor fit. The search is named, and the counting is clear. The abstract does not say whether two people screened papers, or the last search date. Leaving out unpublished courses could skew the picture of “usual” therapy. The percentages are precise, but they describe reporting in papers, which is not the same as what every clinic does.

3. For UK practice, the useful point is the content, not a new success rate. A course that matches the trial evidence usually includes getting out of bed when awake, a planned shorter time in bed, and work on thoughts about sleep, rather than sleep tips alone. Many trials still use a psychologist and in-person sessions, which is a harder fit for large NHS demand than a brief or digital course.

### 5. Phone and app prompts for sleep

Xi A, Harvey AG, Buysse DJ, et al. Ecological Momentary Interventions (EMIs) and Just-in-Time Adaptive Interventions (JITAIs) for sleep and circadian health: A systematic review and meta-analysis. Sleep Med. 2026;149:109349. doi:10.1016/j.sleep.2026.109349. PMID: 42994167.

Review with a pooled analysis of 11 randomised trials. Secondary research. Level 1 for the pooled insomnia results, with low certainty because the trials are few and varied. PubMed’s publication type is Review, not Systematic Review. The authors describe a systematic search and a pooled analysis. Needs a check of the full methods before it is treated as a completed systematic review. The PubMed citation button omitted the volume and article number; both are on the PubMed record.

1. From 4,094 records, the authors kept 11 randomised trials (3 using occasional prompts, 8 using prompts that change with the moment). Pooled results showed better sleep efficiency (standardised difference 0.71), less severe insomnia (−0.87), fewer unhelpful beliefs about sleep (−0.96), and fewer depressive symptoms (−0.76). The sleep-quality result did not clearly differ from no effect. No trial reported a body-clock outcome. The two prompt styles did not clearly differ from each other.

2. Pooling 11 varied programmes gives wide ranges. The beliefs result in particular is compatible with a small or a large effect. They scored trial quality with a physiotherapy trial checklist (PEDro) rather than AMSTAR-2 or Cochrane RoB 2. AMSTAR-2 cannot be completed from the abstract: the abstract does not show a pre-written plan, a list of excluded trials, or funding of the included trials. The authors themselves say the field is early and the clinical importance is uncertain.

3. Apps that prompt people in the moment are attractive for UK digital services. The early evidence suggests improvements in insomnia severity and mood. It does not show a benefit for the body clock, despite the title, and it is too uneven to set a purchasing decision.

### 6. Questionnaires in older psychiatric inpatients

Bailer M, Stein EM, Sprügel MI, et al. Reduced diagnostic accuracy of screening questionnaires in older psychiatric patients at risk for obstructive sleep apnea: an observational cohort study. Sleep Breath. 2026;30(6):306. doi:10.1007/s11325-026-03847-0. PMID: 42993419.

Diagnostic accuracy study in one psychiatric ward. Primary research. Level 4. The PubMed abstract ends mid-word, so the last sentence is incomplete and is not used here.

1. At a psychiatric ward in Erlangen, 128 inpatients thought to be at risk of sleep apnoea had an overnight breathing study and completed questionnaires (72 aged 18–64; 56 aged 65 or over). Admissions ran from June 2016 to December 2022. Older patients had more pauses (median 7.7 per hour against 1.8) and more often had at least mild apnoea (73.2% against 47.2%). In younger adults, the questionnaires had moderate accuracy (area under the curve 0.61 to 0.78, where 0.5 is no better than a coin toss and 1 is perfect). In older adults the scores were lower. The best, BOAH, was 0.59. The others were 0.38 to 0.49, which is poor. Age alone scored 0.70. Body size and symptom questions sorted people poorly. The loss of accuracy in older adults was mainly more false alarms.

2. The breathing study gives a real reference, which is a strength, but it was not a full overnight sleep study in a laboratory. Everyone had already been judged “at risk”, so this is not a test of screening all psychiatric inpatients. The older and younger groups are modest. Cochrane RoB 2, ROBINS-I, Newcastle-Ottawa, and AMSTAR-2 do not fit a diagnostic accuracy study. The usual tool for that design is QUADAS-2, and it cannot be finished from the abstract. The main threats are a selected ward sample and questionnaires used outside the groups they were built for.

3. Older UK adults in mental health wards often have poor sleep, low mood, and tablets that cause drowsiness. A familiar questionnaire can miss or over-call apnoea in that group. Age was more informative than symptoms here. A breathing study is the safer next step when apnoea would change treatment. This is one German ward, not a national UK sample.

### 7. Remote checks on mask treatment

De Armas R, Mezerhane E, Bobrowski A, et al. Effect of remote patient monitoring on PAP adherence and patient-reported outcomes in obstructive sleep apnea: a comparative study. Sleep Breath. 2026;30(6):304. doi:10.1007/s11325-026-03851-4. PMID: 42986562.

Open-label randomised trial. Primary research. Level 2.

1. Adults starting mask treatment (positive airway pressure) for sleep apnoea were randomised to usual coaching or to coaching plus remote monitoring through a web app. Of 196 people (98 in each arm; 65% men; median age 51; median body mass index 32), US Medicare-style adherence was 80.6% with remote checks and 73.5% with usual coaching, a gap of 7.1 points (p = 0.308). Remote checks were linked with fewer nights of a large mask leak and with higher satisfaction, but those gaps were no longer clear after a correction for testing several outcomes at once. The authors say the trial was too small to prove one arm was better.

2. Random assignment is a strength. People knew which arm they were in, so satisfaction and effort could change for that reason. Mask use itself is recorded by the machine, which is harder to bend. Cochrane RoB 2: some concern for the usage outcome, and higher concern for satisfaction, because of the open design. The trial was registered after it had started. Needs a check: the PubMed abstract prints the registration date as “20,250,919” and the web address without a colon (`https//clinicaltrials.gov/study/NCT07182617`). The number NCT07182617 should be confirmed before it is quoted. The main outcome uses a US Medicare rule (more than 4 hours on more than 70% of nights), which is not an NHS target.

3. Remote troubleshooting is already part of many UK mask pathways. This trial does not show a clear gain in use over ordinary coaching. It is not a reason to drop remote support, and it is not proof that an app raises adherence.

### 8. Mask treatment and mood

Kozu Y, Hiranuma H, Itoda Y, et al. Alleviating Depressive Symptoms Through Continuous Positive Airway Pressure Therapy: Long-Term Effects on Patients with Obstructive Sleep Apnea. Sleep Sci. 2026;19(3):1-9. doi:10.1055/s-0046-1819597. PMID: 42997916.

Uncontrolled before-and-after study. Primary research. Level 4. Added to PubMed on 7 November 2026.

1. At one Japanese sleep centre, 170 adults with sleep apnoea who used mask treatment for at least six months had depression scores repeated. In those still using it at two years or more, the total score fell from 40.2 to 37.5. The change was clearest for tiredness, motivation, and making decisions, and it was statistically clear in men. The change in women was in the same direction and was not statistically clear. The abstract says the women’s group was small. The number of people in the two-year comparison is not stated.

2. There is no group who did not use a mask. Mood can change with time, other treatment, and who remains in follow-up. A fall of under 3 points may be too small to matter to a patient. The abstract does not give a threshold for a meaningful change. Newcastle-Ottawa does not fit a single treated group. The main problems are no comparison group, a selected group who kept using the mask, and a sex split that the study was not clearly built to test.

3. Low mood is common in UK adults with sleep apnoea. This paper is compatible with a small mood improvement after long mask use, especially in men, and it is too weak to promise that benefit. It does not replace treatment for depression.

### 9. Nerve stimulator, blood pressure, and metabolism

Lampkin HB, Storm LK, Mcminn ME, Lewis AF, Paul O. Evaluating the impact of hypoglossal nerve stimulator therapy on cardiovascular and metabolic outcomes in sleep apnea patients: A retrospective cohort analysis. Am J Otolaryngol. 2026;47(6):104951. doi:10.1016/j.amjoto.2026.104951. PMID: 42998374.

Retrospective before-and-after cohort. Primary research. Level 4. Published online 25 September 2026. Added to PubMed on 7 November 2026. The author’s name Mcminn is printed that way in PubMed.

1. At one specialist centre, 141 of 210 adults who had a tongue-nerve stimulator implanted between 2017 and 2024 were followed (ages 18–87; 60.3% men). Breathing pauses fell from a mean of 36.0 per hour to 5.9 at the treatment check, and 83.5% met the centre’s use target. Over two years, blood pressure, long-term blood sugar, and body mass index did not change by a statistically clear amount. Average arterial pressure drifted down and was close to a clear change at two years. The abstract does not give that p value.

2. The large fall in pauses is in people who received an implant and stayed in care. There is no comparison with mask treatment or with no device. Blood pressure and weight are affected by medicines and behaviour, which are not separated here. Newcastle-Ottawa is a loose fit for a single treated series. Selection and loss to follow-up are the main threats: 69 of 210 patients were excluded for device removal, transfer, or loss to follow-up.

3. Nerve stimulation is used in some UK centres for selected adults who cannot manage a mask. This record supports a large improvement in pauses among people who keep the device. It does not show a clear improvement in blood pressure, sugar, or weight, so those should not be offered as expected benefits.

### 10. A home sleep test in a blood-pressure clinic

Boutigny A, Motiejunaite J, Balagny P, et al. Implementation of a WatchPAT-Based Diagnostic Pathway for Obstructive Sleep Apnea in a Tertiary Hypertension Center: A Feasibility Study. J Am Heart Assoc. 2026;15(21):e049285. doi:10.1161/JAHA.126.049285. PMID: 42924731.

Prospective single-centre feasibility study. Primary research. Level 4. Added to PubMed on 24 October 2026. Journal date 3 November 2026.

1. Two hundred patients in a specialist blood-pressure clinic had a WatchPAT home test between May 2023 and August 2025. The test worked in 97.5%. Mean time to a result was 3.5 days, against 154 days for a laboratory sleep study. About 30% met treatment criteria straight away, and 22% were classed as not needing treatment. Among those who then had a laboratory study, 83% (95% confidence interval 61% to 94%) of people first called none-to-mild were reclassified as moderate or severe, and 77% needed treatment. Symptoms did not track severity. A score the abstract calls STOP-Bag was not clearly linked with severity after correction for multiple tests.

2. Feasibility is well shown: the test usually worked and was fast. The reclassification figure is the important caution, and it applies to people who were sent on for a laboratory study, not to every mild result. That selected group can make the home test look worse than it is in unselected patients. The abstract does not say how many people had the laboratory study. Cochrane RoB 2 and Newcastle-Ottawa do not fit this service study. Needs a check: the abstract expands the score as Snoring-Tired-Observed-Pressure-BMI-Age-Gender and shortens it to STOP-Bag. That may be a variant or a slip for STOP-Bang. Confirm the name before quoting it.

3. UK clinics more often use home breathing studies than WatchPAT, but the practical point carries across. A fast home test can sort clear cases. Mild or uncertain results in people with high blood pressure still need a careful second look. Symptoms alone were a poor guide in this clinic.

### 11. Computer models of questionnaire screening

Hoang NH, Liang Z. Machine Learning Improves Questionnaire-Based Sleep Apnea Screening: A Multi-Cohort Multi-Visit Validation Study. J Sleep Res. Published online November 5, 2026. doi:10.1111/jsr.70495. PMID: 42989067.

Development and testing of a prediction model on existing cohorts. Primary research (a new analysis of old studies). Level 3 as prognostic research, not a treatment trial.

1. Using the Sleep Heart Health Study and the Wisconsin Sleep Cohort, the authors built models from 42 questionnaire and body-size items, with no overnight monitor. Inside the training data, accuracy was similar across mild, moderate, and severe cut-offs (area under the curve 0.74 to 0.76; sensitivity 67% to 73%; specificity 62% to 70%). A later visit in the same study gave a similar result at the moderate cut-off. When a model trained on the older Sleep Heart Health group was tried on the younger Wisconsin group, it did worse, especially for mild apnoea, where specificity fell to 48.5%. The model leaned on neck size, age, body mass index, and symptoms.

2. Testing in a second cohort is a strength, and the drop in performance is the main result to remember. These cohorts are not new UK primary-care patients. A model that flags almost half of well people at the mild cut-off would create a large extra testing load. None of the four named checklists is a model-validation tool. The relevant threats are a shift in who is in the sample, and an optimistic reading of the internal scores.

3. Simple questionnaires are widely used before NHS sleep testing. A computer score can look more balanced than a short paper score in the data it was built on. This paper says that balance may not travel to a younger or different population. It is not ready to replace current UK referral rules.

### 12. Asthma and poor sleep in middle age

Wang J, Blomberg A, Ekström M, et al. Asthma and Impaired Sleep: Identifying Treatable Traits in the SCAPIS Study. J Asthma Allergy. 2026;19:639747. doi:10.2147/JAA.S639747. PMID: 42992155.

Large cross-sectional cohort analysis. Primary research. Level 4. Journal date 1 November 2026. Added to PubMed on 6 November 2026. SCAPIS is a Swedish middle-aged cohort. The abstract itself does not spell out the country.

1. In 28,828 adults aged 50 to 64, current asthma was linked with poorer sleep (odds ratio 1.56) and with trouble falling asleep (1.59), trouble staying asleep (1.36), early waking (1.31), and any insomnia symptom (1.38). Among people with asthma, uncontrolled asthma, nose and sinus disease, snoring, sleep apnoea, and night-time reflux were linked with worse sleep. Having uncontrolled asthma, sinus disease, and night-time breathing or reflux problems together had the strongest links (odds about 5.7 for poor sleep and 3.6 for any insomnia symptom).

2. The sample is large and the age band is narrow, which helps precision and limits generalisation to younger and older adults. The abstract does not say which factors were adjusted for, so part of the link could be weight, smoking, or other illness. Sleep and asthma were measured at the same time, so the study cannot say which came first. Newcastle-Ottawa is only a loose fit for this cross-sectional analysis.

3. Asthma, reflux, sinus disease, and possible sleep apnoea are common in UK primary care. The paper supports looking for those treatable problems when a middle-aged adult with asthma sleeps badly, rather than treating the sleep complaint in isolation. It does not show that treating them restores sleep.

### 13. A short yoga course for insomnia symptoms

Cheruka CA, Sherman SA, Quinn TD, et al. Effects of a 4-week vinyasa yoga intervention on sleep and cardiovascular health in adults with insomnia symptoms: a pilot randomized controlled trial. Sleep Adv. 2026;7(4):zpag107. doi:10.1093/sleepadvances/zpag107. PMID: 42999866.

Pilot randomised trial. Primary research. Level 2. Journal date 7 October 2026. Added to PubMed on 8 November 2026.

1. Thirty-three inactive adults with insomnia symptoms (insomnia score at least 10; 84.8% women; mean age 34.9) were randomised to four weeks of video yoga three times a week (17 people) or to carrying on as usual (16). Sleep scores, wrist-worn sleep measures, and sleep diaries did not clearly differ between groups. Night-time heart-rhythm measures and daytime blood pressure did not differ. Resting heart rate fell a little with yoga and rose a little in the comparison group (p = 0.047). In people who did the yoga regularly, insomnia scores fell more than in the comparison group (p = 0.002).

2. This is a small pilot with many outcomes. The main sleep comparisons were not clear. The heart-rate result and the “people who stuck with it” result are easy to over-read: sticking with an activity is not the same as being randomised to it, and people who feel better may be the ones who continue. Cochrane RoB 2: high concern, because the trial is open, small, and the standout result is a subgroup. Needs a check: the abstract gives the registry address as NCT05723211 and the registration line as NCT0572321. Confirm the number before quoting it.

3. Yoga is a reasonable activity, and this pilot does not show that a four-week video course improves insomnia or night-time heart measures in adults as a whole. It should not be offered as a proven insomnia treatment in place of a structured talking therapy.

### 14. Sleep-study measures and daytime problems in insomnia

Lee R, Keenan BT, Gerardy B, et al. Physiological Sleep Features Associated With Dimensions of Daily Dysfunction in Insomnia. J Sleep Res. Published online November 5, 2026. doi:10.1111/jsr.70482. PMID: 42984306.

Cross-sectional analysis of a multi-centre consortium. Primary research. Level 4.

1. In the Sleep Apnea Global Interdisciplinary Consortium, 859 adults without sleep apnoea or shift work (368 of them with insomnia; about half women; mean age 44) completed questions on daytime problems and had sleep-study and brain-wave measures. The daytime questions lined up as one score. After allowing for age, sex, and site, a few brain-wave measures looked linked with worse daytime scores, but none remained clear after correction for the number of tests. Sleep-study summaries and brain-wave measures did not explain daytime problems.

2. The sample is large and the authors corrected for multiple tests, which is appropriate and which removed the early hints. People were those already in a research consortium, not a random UK sample. Measuring sleep on one night can miss the night-to-night variation that matters in insomnia. Newcastle-Ottawa is a loose fit. The careful negative result is more trustworthy than the uncorrected hints.

3. In UK practice, insomnia is mainly a clinical diagnosis. This paper supports not expecting a routine sleep study to explain daytime difficulty in adults who do not have sleep apnoea. A study is still needed when another sleep disorder is suspected.

### 15. Repeat sleep studies in narcolepsy type 1

Derre A, Denis C, Beziat S, Jaussent I, Barateau L, Dauvilliers Y. Poor Test-Retest Stability of Nocturnal REM Sleep Onset Markers in Narcolepsy Type 1. Sleep. Published online November 4, 2026. doi:10.1093/sleep/zsag292. PMID: 42980365.

Reliability study in a specialist clinic series. Primary research. Level 3. The sample includes children and adults. It is not a child-only study, and the abstract does not give separate adult results.

1. Two hundred and twenty-seven untreated people with narcolepsy type 1 (108 male; mean age 31.6 years) had two overnight studies. Dream sleep starting within 15 minutes of falling asleep was present on both nights in 41.8%, on one night only in 35.7%, and on neither night in 22.4%. Agreement between the two nights was poor (kappa 0.26, where 0 is chance and 1 is perfect). A direct jump into dream sleep was also unstable. People with the finding on both nights were younger, fell asleep faster on daytime nap testing, and had lower hypocretin, a brain chemical that is low in this condition. The finding was not used to make the diagnosis, which avoids circular reasoning.

2. Two studies in the same untreated people is the right design for a stability question. Mixing children and adults, with a wide age spread (standard deviation 14.8 years), means the result is not a pure adult figure. The abstract does not give the adult-only kappa. Kappa of 0.26 is a strong statement of poor repeatability, and the confidence interval (0.14 to 0.39) stays in the poor range. None of the four named checklists is a reliability checklist. The main limit for UK adults is the mixed age sample.

3. Narcolepsy type 1 is uncommon and is diagnosed in specialist UK centres. The practical point is that one night without early dream sleep, or even two such nights, does not rule the condition out. Daytime nap testing and hypocretin remain the more stable clues in this record. Do not apply the percentages as adult-only UK figures until an adult split is available.

### 16. Long sleep, insomnia, and thinking skills

Wyss AB, Zhang Y, Brown MR, et al. Long Sleep and Insomnia are Associated with Reduced Global Cognitive Function across Diverse Populations. Preprint. medRxiv. 2026;2026.10.19.26365906. doi:10.64898/2026.10.19.26365906. PMID: 42990482.

Preprint, posted 29 October 2026 and added to PubMed on 6 November 2026. It has not been reviewed by a journal. Primary research, a new analysis of three cohorts. Level 3 for the cross-sectional link. Treat it as provisional.

1. In 11,563 adults from three US cohorts, long sleep (9 hours or more) was linked with lower overall thinking scores at the start (standardised difference −0.19) and with higher odds of a poor score (odds ratio 1.77). Insomnia was linked more weakly with a lower starting score and with poor scores (odds ratio 1.22); that insomnia result was less secure after a correction for multiple tests. Short sleep, daytime sleepiness, and moderate or severe sleep apnoea were also examined. None of the sleep measures was linked with a fall in thinking scores between visits.

2. Harmonising three cohorts is a strength, and the long-sleep result was consistent across them. The important negative finding is the lack of a link with decline over time. A cross-sectional link can mean that illness leads to long sleep, rather than long sleep damaging thinking. The preprint has not had journal review, so reporting could still change. Newcastle-Ottawa can be applied in outline: the cohorts are relevant and the outcome is measured, while leftover illness and the direction of cause remain open.

3. UK memory clinics often hear that a patient sleeps a long time or sleeps badly. This provisional analysis says both are linked with worse thinking scores at one time, and it does not show that they predict a later drop. It is not a reason to treat long sleep as a proven cause of dementia. Wait for journal review before using the figures in guidance.

### 17. Broken daily rhythm and death in adults with arthritis

Zhao Z, Sheng P. Rest-activity rhythm fragmentation, functional limitation, and mortality in adults with arthritis: A nationally representative cohort study. Sleep Health. Published online November 6, 2026. doi:10.1016/j.sleh.2026.10.007. PMID: 42995091.

Analysis of a national survey with wrist monitors and later deaths. Primary research. Level 3.

1. From the US National Health and Nutrition Examination Survey, 7,920 adults had at least four valid days of wrist movement, and 2,182 of 7,904 with a known arthritis status had arthritis. Arthritis was linked with a more broken rest-activity pattern and with less movement in the most active 10 hours of the day. The broken pattern was largely accounted for by limited function. Each step up in brokenness (one standard deviation) was linked with higher death from any cause (hazard ratio 1.18 overall, and 1.19 in people with arthritis), after adjustment. The route from arthritis to death did not appear to run through the broken rhythm.

2. The survey weights and the adjustment for other illness are strengths. Arthritis and function are partly self-reported. Wrist movement is not the same as sleep. The abstract does not give the length of follow-up or the number of deaths, so the clinical size of the risk is hard to picture. Newcastle-Ottawa fits reasonably: a defined community sample and a hard outcome (death), with residual confounding still possible. The hazard ratio of about 1.2 per step of brokenness is modest.

3. Arthritis, poor function, and broken sleep are common in older UK adults. This US sample suggests that a fragmented rest-activity pattern marks higher mortality, including in arthritis, and that disability explains much of the fragmentation. It does not show that fixing the rhythm would lengthen life. Wearable scores are not an NHS test.

### 18. Sleep in chronic lung disease, including restless legs

Theorell-Haglöw J. Sleep in COPD: an understudied and clinically important issue. Ups J Med Sci. 2026;131. doi:10.48101/ujms.v131.14699. PMID: 42991390.

Narrative review by one author. Secondary research. Level 5. PubMed lists volume 131 and the DOI, and no page range. Needs a check if a page is required for a quotation.

1. The review says that people with COPD often have lighter sleep, less deep sleep, less dream sleep, more wakenings, and shorter sleep. It cites studies in which 40% to 70% report poor sleep. Night-time breathlessness, cough, wheeze, phlegm, and low oxygen may contribute. Insomnia, sleep apnoea, and restless legs syndrome are described as more common in COPD than in people without it, and poor sleep is linked with anxiety, depression, fatigue, and worse quality of life. These figures are taken from earlier studies. This paper does not report a new patient sample.

2. There is no search strategy, no quality rating, and no pooled analysis in the abstract. AMSTAR-2 does not fit a narrative review, and a score would be low if it were forced. The 40% to 70% range is wide. Single-author narrative reviews can select the studies that fit the argument.

3. COPD is common in UK adults, and poor sleep is often put down to the lung disease alone. The useful point is to ask separately about insomnia, pauses in breathing, and restless legs, because each has its own treatment. This review does not provide those treatments’ success rates. No adult trial or cohort focused on restless legs was indexed in this week’s PubMed window. A separate pregnancy case series of pramipexole (PMID 42968356; 11 pregnancies, 10 of them for restless legs) found no repeated pattern of major birth defects. That series is too small to guide treatment or to reassure, and it is not written up in full here.

### 19. Dream-enactment as an early neurological sign

Ravindranath N, Bhat A, Gohar A. Rapid Eye Movement Sleep Behavior Disorder as a Prodromal Manifestation of Alpha-Synucleinopathies. Cureus. 2026;18(10):e117597. doi:10.7759/cureus.117597. PMID: 42997636.

Narrative review. Secondary research. Level 5. Journal date 7 October 2026. Added to PubMed on 7 November 2026.

1. The review describes REM sleep behaviour disorder, in which people move during dreams because the usual paralysis of dream sleep is lost. It states that isolated disease of this type is strongly linked with later Parkinson’s disease, dementia with Lewy bodies, or multiple system atrophy, often after a long gap, and that smell loss, constipation, blood-pressure drops, anxiety, and mild thinking changes can appear first. It discusses scans, a protein seed test, and symptom treatment, including clonazepam and melatonin. It does not report a new patient sample or a new rate of later neurological disease.

2. This is a narrative summary of earlier work. AMSTAR-2 does not fit. The claim that most people with a confirmed isolated disorder later develop one of these neurological diseases is the review’s reading of past research, not a figure produced this week. No percentage from this paper should be quoted. Cureus narrative reviews are not a strong source for a new practice rule.

3. For UK neurology and sleep clinics, the practical point is recognition and safety: witnessed dream-enactment in an adult deserves assessment, not reassurance that it is only a bad dream. Injury prevention matters. This paper should not be the source for a personal risk figure. A second narrative review on the same topic was also indexed (PMID 42984845) and is not repeated here.

### Adult papers seen and not written up in full

The rest of the block A records were lower priority for ordinary UK adult care, or they were the wrong study type. They included ward-noise projects, surgical case series, traditional herbal mixtures, animal and cell work, letters, corrections, and editorials. Child-only studies were left out. Forty-two titles contained a word such as child, infant, or adolescent and were checked so that adult papers were not dropped by mistake.

These were read far enough to set aside, and they should not be used as UK practice points without the full paper:

- A Pakistan review pooled insomnia prevalence at 51% across 15 surveys (7,287 people), with extreme inconsistency between studies (PMID 42972157). That is not a UK rate.
- A Chinese analysis linked longer sleep with later stroke in adults with abnormal blood sugar (PMID 42988909). Sleep was taken from the 2020 survey, while strokes were counted across earlier waves as well, so the time order is unsafe.
- A review of Tai Chi plus magnetic brain stimulation in older adults pooled three trials and 211 people (PMID 42994860). The sleep result was sensitive to single trials.
- In Olmsted County, adults with open-angle glaucoma had a slightly higher later chance of a sleep apnoea diagnosis (hazard ratio 1.17; interval 1.00 to 1.36; PMID 42970460). The interval reaches no extra risk.
- A re-analysis of two US cohorts linked a “high loop gain” breathing pattern with heart disease, and the link weakened when age was handled as a continuous number (PMID 42969922). The measure is not an NHS test.
- Eleven preprints were in the download. Only the thinking-skills preprint is written up above. The others are not journal articles.

## Block B. Adult bruxism

No record in this window was about sleep-related painful erections.

### 1. A Japanese registry of sleep bruxism

Okuhara S, Abe Y, Hata K, et al. Multicenter Sleep Bruxism Clinical Registry in Japan: Development of the registry and exploratory analysis of data-driven clinical subgroups. J Prosthodont Res. 2026;70(4):611-618. doi:10.2186/jpr.JPR_D_25_00361. PMID: 41672511.

Multicentre registry with an exploratory grouping analysis. Primary research. Level 4. Added to PubMed on 11 February 2026. Journal issue date 6 November 2026.

1. Seven Japanese dental schools registered 910 adults who had a jaw-muscle recording in sleep, including patients and healthy volunteers. Of these, 524 had sleep bruxism confirmed on the jaw-muscle recording. A statistical sorting method found four groups: younger people with few symptoms (35.3%), middle-aged women with frequent morning symptoms and high awareness (16.2%), middle-aged people with marked tooth wear but low awareness (22.3%), and younger people with frequent symptoms (26.2%). The high-symptom groups differed in the type of muscle bursts.

2. A standard muscle recording is a strength, and the mix of patients and volunteers should not be read as a population rate. The four groups come from one dataset and may not reappear elsewhere. The abstract does not report treatment or long-term harm. Newcastle-Ottawa does not fit an exploratory grouping exercise. The main limit is generalisability beyond Japanese dental-school clinics.

3. UK dentists and sleep clinics see both people who know they grind and people who only have tooth wear. This registry supports that those can be different groups. It does not say which splint, medicine, or exercise works, and the group percentages are not UK prevalence figures.

### 2. Hands-on treatment compared with home exercises

Bayhan MS, Kadioğlu MB, Evli̇ C, et al. Manual therapy versus home exercise in the treatment of bruxism: a randomized controlled trial with ultrasonographic, elastographic, and electromyographic assessment. BMC Oral Health. 2026;26(1):2184. doi:10.1186/s12903-026-09472-3. PMID: 42983785.

Randomised trial. Primary research. Level 2. Published 8 August 2026. Added to PubMed on 5 November 2026.

1. Thirty adults with probable bruxism were randomised to hands-on treatment or home exercise for eight weeks (15 in each). Both groups improved in pain, a jaw-pain questionnaire, bruxism severity, tender spots, and jaw and neck movement. Ultrasound, elasticity scans, and muscle electrical activity also moved in a favourable direction. Neither approach won overall. Home exercise did better for some neck movements, temple-muscle thickness, and neck-muscle elasticity. The person measuring outcomes was blinded. The country is not stated in the abstract.

2. The trial is small and short, and “probable” bruxism is not the same as sleep bruxism confirmed by a sleep recording. Both groups got active care, so the study cannot say whether either beats no treatment or a bite splint. Cochrane RoB 2: some concern, because participants knew their treatment, the sample is small, and several outcomes were measured. Needs a check: the PubMed abstract cuts the trial registration off at “TRIAL REGISTRATION: C”.

3. For UK adults with bruxism-type jaw pain, a home exercise plan looked as useful in the short term as hands-on therapy in this small trial. That is a practical option where physiotherapy time is limited. It is not evidence about tooth splints, and it is not limited to sleep bruxism.

### 3. Bite relationship and bruxism in young adults

Taghian M, Sadri L, Ahmadigorji SM, Hosseinnataj A, Mollaei M, Etezadi T. Relationship of dental malocclusions with development of bruxism in adults. Dent Res J (Isfahan). 2026;23:33. doi:10.4103/drj.drj_139_25. PMID: 42974305.

Cross-sectional survey. Primary research. Level 4. Journal date 8 October 2026. Added to PubMed on 3 November 2026.

1. Among 564 adults aged 18 to 25 (324 with a bite problem and 240 without), questionnaire bruxism was present in 29.6% overall, daytime bruxism in 27.3%, and sleep bruxism in 9.6%. Bruxism was more common in the bite-problem group. Each extra year of age was linked with 16% lower odds. Chipped incisor edges and a sleep disorder were linked with about 9-fold and 3-fold higher odds. A higher psychological-symptom score was linked with slightly higher odds. The country of the patients is not stated in the abstract. The journal is based in Isfahan.

2. Bruxism was self-reported, not recorded in a sleep study, so sleep bruxism is likely to be misclassified. Bite problems and tooth wear can be the result of grinding rather than the cause, and a one-time survey cannot separate those. The age band is only 18 to 25. Newcastle-Ottawa is a loose fit. The very high odds for chipped teeth may partly be the same condition measured twice.

3. Young UK adults with a bite problem may report more grinding, and psychological symptoms and sleep complaints travel with it. This does not show that orthodontic treatment prevents bruxism. The 9.6% sleep-bruxism figure should not be used as a UK rate.

### 4. Does sleep apnoea cause sleep bruxism, or the reverse?

Liu Y, Wang Z, Qin J, Wu D, Li S. [Research on obstructive sleep apnea and sleep bruxism]. Lin Chuang Er Bi Yan Hou Tou Jing Wai Ke Za Zhi. 2026;40(11):1015-1020. doi:10.13201/j.issn.2096-7993.2026.11.010. PMID: 42973031.

Two-sample genetic causal analysis (Mendelian randomisation). Primary research. Level 3 as causal genetic evidence, which is only as good as the genetic instruments. The paper is in Chinese with an English abstract. Needs a check: the PubMed citation tool omitted the article title. The English title above is the translated title on the PubMed record, not a re-translation.

1. Using public genetic data for sleep apnoea and FinnGen data for sleep bruxism, the authors tested both directions. Sleep apnoea did not clearly cause sleep bruxism (odds ratio 1.71, interval 0.67 to 4.32). Sleep bruxism did not clearly cause sleep apnoea (odds ratio 1.01, interval 0.99 to 1.03). Several statistical variants gave the same qualitative result.

2. This method asks whether inherited liability to one condition changes the other. It does not describe patients in a clinic. The first interval is wide, so a moderate effect of apnoea on bruxism is not excluded. The abstract does not state the ancestry of the samples. A genetic null result does not mean the two conditions never occur together. None of the four clinical checklists fits this design. The relevant threats are weak genetic instruments and a sample that may not match UK ancestry.

3. UK clinicians often see grinding and sleep apnoea in the same person. This study does not support telling patients that one directly causes the other. It also does not justify ignoring either condition. The clinical overlap can still be real even if the genes do not show a direct causal path.

### 5. Jaw exercises after stroke, for waking bruxism

Umasankar Y, Suganthirababu P, Srinivasan V, et al. Preliminary effects of proprioceptive neuromuscular facilitation-based jaw exercises compared with conventional jaw exercises in post-stroke patients with awake bruxism behaviors: A randomized pilot study. Cranio. Published online November 4, 2026. doi:10.1080/08869634.2026.2745060. PMID: 42981491.

Randomised pilot. Primary research. Level 2. This is waking bruxism after stroke, not sleep bruxism.

1. Ten adults after stroke, five in each arm, did either a facilitation jaw programme plus ultrasound or conventional jaw exercises plus ultrasound, four times a week for four weeks. Both groups opened the jaw more and changed muscle activity. The facilitation group opened further (mean 51.6 mm against 42.78 mm). Masseter and temporalis electrical activity did not differ clearly between groups. It was a single centre.

2. Ten people cannot support a treatment claim. The abstract does not describe blinding. Cochrane RoB 2: high concern because of the size, the open exercises, and the short follow-up. A difference of several millimetres of opening may matter to a therapist and still be unstable in a sample this small.

3. This does not change UK stroke or dental practice. It is a pilot signal about waking jaw clenching after stroke, in a very selected group. Sleep bruxism was not the target.

### 6. The cost of bite splints in the Brazilian public system

Silva PLPD, Lemos GA, Cavalcanti YW, Batista AUD. Análise de impacto orçamentário da oferta de dispositivos oclusais no Sistema Único de Saúde [Analysis of budgetary impact of the offer of occlusal devices in the Unified Health System]. Cien Saude Colet. 2026;31(10):e08142024. doi:10.1590/1413-812320263110.08142024. PMID: 42987061.

Budget model. Not a clinical study of patients. Secondary in the sense that it does not collect new health outcomes. The English title is the PubMed translation of a Portuguese paper.

1. From a municipal-payer point of view, the authors priced one occlusal splint at 149.81 Brazilian reais, with a sensitivity range of 104.93 to 194.71. Supplying 4,240,551 splints, brought in at 5% more each year for five years, had an incremental cost of about 635 million reais. The abstract gives smaller totals for small, medium, and large municipalities. The devices were for temporomandibular disorder, face pain, or bruxism. The paper does not measure pain, tooth wear, or sleep.

2. A budget model stands or falls on who is assumed to need a device and what the device costs. Those assumptions are only sketched in the abstract. It is not a trial, so the clinical checklists do not fit. There is no evidence here that splints work. The currency and the health system are Brazilian.

3. NHS costs cannot be read off these reais figures. The only practice point is that offering a splint to every adult with jaw pain or bruxism is a large budget decision. Effectiveness for UK adults is not answered by this paper.

### Block B records that are not adult bruxism studies

- PMID 42992269. Sleep bruxism and anxiety in children aged 7 to 12. Excluded as child-only.
- PMID 42986808. Family stress and clinical findings in children aged 8 to 11 with sleep bruxism. Excluded as child-only.
- PMID 42989354. Nail biting in children aged 8 to 12 with ADHD. Bruxism is mentioned only as another repetitive behaviour. Excluded as child-only.
- PMID 42988094. A suggested way to group primary jaw-muscle pain. Bruxism appears as a keyword, not as the study. Not treated as a bruxism paper.

## Coverage gaps, and strings that were not run

Embase and Scopus were not searched. That is a real gap. Embase indexes more European and conference material than PubMed. Scopus indexes further journals and some non-MEDLINE records. A paper in those databases only would be missing here. The strings below are ready to paste later. They were not run, so the subject headings should be confirmed in the live thesaurus before anyone relies on the count.

### Embase.com (Emtree)

Embase’s adult limit is 18 to 64 years. The aged limit is 65 and over. Together they stand in for 18 and over. Age limits miss records that have not yet been indexed with an age. The date fields are publication date (`/pd`) and the date the record was added (`/sd`).

```
('insomnia'/exp OR insomnia:ti,ab
 OR 'sleep apnea syndrome'/exp OR 'obstructive sleep apnea'/exp
 OR 'sleep apnoea':ti,ab OR 'sleep apnea':ti,ab OR 'obstructive sleep':ti,ab
 OR 'circadian rhythm sleep disorder'/exp OR 'circadian rhythm':ti,ab
 OR 'narcolepsy'/exp OR narcolepsy:ti,ab OR cataplexy:ti,ab
 OR 'hypersomnia'/exp OR hypersomnia:ti,ab OR hypersomnolence:ti,ab
 OR 'restless legs syndrome'/exp OR 'restless legs':ti,ab
 OR 'periodic limb movement disorder'/exp OR 'periodic limb movement':ti,ab
 OR 'parasomnia'/exp OR parasomnia*:ti,ab
 OR 'rem sleep behavior disorder'/exp OR 'rem sleep behaviour':ti,ab OR 'rem sleep behavior':ti,ab
 OR 'sleep quality':ti,ab OR 'sleep duration':ti,ab
 OR 'sleep disorder':ti,ab OR 'sleep disturbance':ti,ab)
AND ([02-11-2026 to 09-11-2026]/pd OR [02-11-2026 to 09-11-2026]/sd)
AND ([adult]/lim OR [aged]/lim)
NOT ([animals]/lim NOT [humans]/lim)
```

Bruxism and painful erections:

```
('bruxism'/exp OR 'sleep bruxism'/exp OR bruxism:ti,ab
 OR 'teeth grinding':ti,ab OR 'tooth grinding':ti,ab
 OR 'sleep-related painful erection*':ti,ab OR 'sleep related painful erection*':ti,ab
 OR 'painful nocturnal erection*':ti,ab OR srpe:ti,ab)
AND ([02-11-2026 to 09-11-2026]/pd OR [02-11-2026 to 09-11-2026]/sd)
AND ([adult]/lim OR [aged]/lim)
NOT ([animals]/lim NOT [humans]/lim)
```

There is no Emtree heading in this string for sleep-related painful erections. That concept is free text only. Confirm every `/exp` heading in Emtree before running. Ovid Embase uses different punctuation, so these strings are for Embase.com.

### Scopus advanced search

Scopus does not offer PubMed’s day-level publication date in the same way. The load date below is the date Scopus added the record, which is the closer match to “indexed this week”. It is not the publication date. Adult limits in Scopus depend on keywords and will miss untagged records.

```
TITLE-ABS-KEY(insomnia OR "sleep apnoea" OR "sleep apnea" OR "obstructive sleep" OR narcolepsy OR cataplexy OR hypersomnia OR hypersomnolence OR "restless legs" OR "periodic limb movement" OR parasomnia* OR "circadian rhythm" OR "REM sleep behav*" OR "sleep quality" OR "sleep duration" OR "sleep disorder" OR "sleep disturbance")
AND (ORIG-LOAD-DATE AFT 20261101 AND ORIG-LOAD-DATE BEF 20261110)
AND NOT TITLE-ABS-KEY(mouse OR mice OR murine OR rat OR rats OR zebrafish)
```

```
TITLE-ABS-KEY(bruxism OR "teeth grinding" OR "tooth grinding" OR "sleep-related painful erection*" OR "sleep related painful erection*" OR "painful nocturnal erection*" OR SRPE)
AND (ORIG-LOAD-DATE AFT 20261101 AND ORIG-LOAD-DATE BEF 20261110)
AND NOT TITLE-ABS-KEY(mouse OR mice OR murine OR rat OR rats OR zebrafish OR child OR children OR paediatric OR pediatric)
```

After either Scopus string, screen the titles. The child words and animal words will miss some records and will occasionally remove an adult paper that only mentions them.

## In short

PubMed on 9 November 2026 was enough to fill both topics for this week. The largest practice signals were a fall in breathing pauses with retatrutide in adults with obesity and sleep apnoea, the frequency of insomnia symptoms alongside apnoea in sleep clinics, the content and digital delivery of insomnia therapy, the weakness of apnoea questionnaires in older psychiatric inpatients, and a small short-term gain from either home exercise or hands-on care in probable bruxism. Restless legs had no dedicated adult treatment study. Sleep-related painful erections had none. Embase and Scopus remain uns searched.
