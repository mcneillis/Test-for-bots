# Weekly adult sleep literature

Version 1.0. 16 November 2026.

This note covers human studies of adults, about 18 years and older, found in PubMed. The window is records published, or added to PubMed, from 9 to 16 November 2026. The week was not thin. The main sleep search returned 356 records after animal-only records were removed, so the window was not taken back to 2 November.

Child-only and adolescent-only studies, and animal studies, were left out. Full papers were not used. Every number below is taken from the PubMed record. Where a figure is missing, or the record looks inconsistent, that is stated. Nothing here was filled in from memory of the paper.

The 9 November note is not repeated. Its 37 PMIDs were excluded by list. None of those 37 PMIDs fell inside this week’s retrieval.

A cluster of papers in *Sleep*, volume 49, issue 11, carry a journal date of 10 November 2026 but were already in PubMed in July or August. They are in this note because the publication date is inside the window. That is stated on those papers. The latest Entrez date in the download was 15 November 2026. No retrieved record had been added to PubMed on 16 November itself. The search included that day. Records posted later on 16 November are not here.

Citations list the first three authors, then et al., in the same way as the 9 November note. DOIs are the article DOI on the PubMed record, not a DOI taken from the reference list.

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

A judgement from an abstract is a first look. It is not a finished checklist score. This whole note is abstract-level.

## Search record

This record follows the PRISMA-S checklist for the search itself. It is a weekly sweep by one reader, not a full systematic review with two screeners or a peer-reviewed search strategy.

| Item | Detail |
| --- | --- |
| Database | PubMed, which includes MEDLINE |
| Interface | NCBI E-utilities (ESearch and EFetch), public, no login. This uses the same PubMed index as the website |
| Date run | 16 November 2026, UTC |
| Other databases | Embase: not searched. Scopus: not searched. Institutional access was down |
| Registers, citation chasing, authors contacted | Not used |
| Language limit | None |
| Age limit in the search | None. PubMed’s adult filter starts at 19 years and misses new records that have no age tag. Adult status was judged afterwards from the title and abstract |
| Animal limit | On blocks A and B, records indexed as animal-only were removed. Records with no animal or human tag were kept and then read. The supplemental block was not animal-filtered |
| Full text | Not used. Appraisal uses the PubMed abstract, publication type, and citation fields |
| Prior note | 37 PMIDs from the 9 November pack were excluded. Zero of them were in this retrieval |
| Window widened to 2 November | No. The human sleep set was 356 records, well above the threshold of about 10 |
| Peer review of the strategy | None |

Dates in the strings below are inclusive. `[pdat]` is the publication date. `[edat]` is the date PubMed added the record. `[crdt]` is the date the record was created. The create-date search was a check only. It was not added on top of the other results. `[mh]` is a PubMed subject heading. `[tiab]` is title or abstract.

### Block A, adult sleep medicine

Topics in the string: insomnia, sleep apnoea, circadian rhythm, narcolepsy and hypersomnia, restless legs, periodic limb movement, parasomnias including REM sleep behaviour disorder, and sleep with health (sleep quality, duration, disorder, or disturbance).

Publication date only. **173** records.

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
) AND ("2026/11/09"[pdat] : "2026/11/16"[pdat])
```

Date added to PubMed only. **324** records. The same topic string was used with `("2026/11/09"[edat] : "2026/11/16"[edat])`.

Create-date check, not added as extra records. **339**. The same topic string was used with `("2026/11/09"[crdt] : "2026/11/16"[crdt])`.

Published or added in the window. **366** records. After removing animal-only records, add `NOT (animals[mh] NOT humans[mh])`. **356** records. Ten animal-only records dropped out.

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
) AND (("2026/11/09"[pdat] : "2026/11/16"[pdat]) OR ("2026/11/09"[edat] : "2026/11/16"[edat])) NOT (animals[mh] NOT humans[mh])
```

### Supplemental block, CBT-I, wearables, and the phrase “sleep-disordered breathing”

This block was added so that cognitive behavioural therapy for insomnia, actigraphy, and consumer sleep devices were not missed when they lacked the core words. Published or added. **78** records. Create-date check, not added. **67**. Publication date only. **47**. Date added only. **66**.

Of the 78, **55** were already in the human core set. **23** were new. Many of those 23 are childhood activity studies, animal work, or actigraphy used for movement rather than sleep medicine. The adult wearable papers that were new are written up or listed below.

```
(
  "CBT-I"[tiab] OR CBTI[tiab]
  OR "cognitive behavioural therapy for insomnia"[tiab]
  OR "cognitive behavioral therapy for insomnia"[tiab]
  OR "sleep-disordered breathing"[tiab] OR "sleep disordered breathing"[tiab]
  OR actigraph*[tiab] OR "sleep wearable"[tiab] OR "sleep wearables"[tiab]
  OR "consumer sleep"[tiab] OR "sleep tracker"[tiab]
  OR ("mental health"[tiab] AND (sleep[ti] OR insomnia[ti]))
) AND (("2026/11/09"[pdat] : "2026/11/16"[pdat]) OR ("2026/11/09"[edat] : "2026/11/16"[edat]))
```

### Block B, bruxism and sleep-related painful erections

Publication date only. **4** records. Date added to PubMed only. **8** records. Create-date check. **7** records. Published or added. **9** records. Animal-only removal did not drop any. **9** records. Two of the nine were already in block A.

```
(
  Bruxism[mh] OR "Sleep Bruxism"[mh]
  OR bruxism[tiab] OR "teeth grinding"[tiab] OR "tooth grinding"[tiab]
  OR "sleep-related painful erection"[tiab] OR "sleep related painful erection"[tiab]
  OR "sleep-related painful erections"[tiab] OR "sleep related painful erections"[tiab]
  OR "painful nocturnal erection"[tiab] OR "painful erections"[tiab]
  OR SRPE[tiab]
) AND (("2026/11/09"[pdat] : "2026/11/16"[pdat]) OR ("2026/11/09"[edat] : "2026/11/16"[edat])) NOT (animals[mh] NOT humans[mh])
```

Extra check, in case painful erections were indexed only as priapism. **0** records in this window. The same priapism string from 2 to 16 November was also **0**. That wider count was a check only. It did not add papers, and the main sleep window was not widened.

```
(Priapism[mh] OR priapism[tiab]) AND (sleep[tiab] OR nocturnal[tiab] OR "REM"[tiab]) AND (("2026/11/09"[pdat] : "2026/11/16"[pdat]) OR ("2026/11/09"[edat] : "2026/11/16"[edat]))
```

No paper on sleep-related painful erections was found. One football paper matched because PubMed treated “session RPE” (`sRPE`) as the token SRPE. It is not a paper about erections. It is listed under block B and is not a bruxism study.

### What was done with the 386 records

The union of the human core set, the 23 supplemental-only records, and the bruxism records that were not already in the core set was **386** unique PMIDs. Within-search duplicates were removed by PMID. Overlap with the 9 November exclusion list was **0**.

Title and abstract screen, one reader:

- **40** records had a child, infant, adolescent, or youth word in the title and no adult word. They were set aside as outside adult scope. This includes an adolescent trial of amber lenses for delayed sleep-wake phase disorder (PMID 43004031). A title rule is not a perfect age filter. These 40 were not appraised.
- **8** records had a non-human species in the title (mouse, rat, zebrafish, fruit fly, honey bee, or a plant). They were set aside.
- That left **338** records. **25** are written up in full below (20 on sleep medicine, 5 on bruxism). The other adult records were read at title level, and a smaller set of on-topic abstracts was read far enough to set them aside in one line. They did not get the three-part appraisal. Full text was not used for any paper.

Forty-seven of the 386 records had an Entrez date before 9 November. They are in the download because the publication date falls inside the week.

## Block A. Adult sleep medicine

### 1. An oral weight-loss drug, tested in people recruited for sleep apnoea

Malhotra A, Gottlieb DJ, Woehrle H, et al. Orforglipron for Obstructive Sleep Apnea: Results From 2 Randomized Clinical Trials (ATTAIN-OSA). JAMA. Published online November 9, 2026:e2624080. doi:10.1001/jama.2026.24080. PMID: 43002161.

Two phase 3 randomised, double-blind, placebo-controlled trials. Primary research. Level 1. PubMed’s publication type is Journal Article. The abstract describes the trials. Added to PubMed on 9 November 2026. The record has no volume or issue.

1. Adults with moderate to severe obstructive sleep apnoea and a body mass index of 27 or higher were randomised to once-daily orforglipron (maximum tolerated dose, described as equivalent to a 9 mg, 14.5 mg, or 17.2 mg tablet) or placebo for 52 weeks. The trials ran at 66 sites in the United States, Argentina, Brazil, China, the Czech Republic, Germany, Japan, Mexico, and Taiwan. Enrolment was from 11 November 2024 to 23 July 2025, with last follow-up on 30 July 2026. Trial 1 was people not using a mask (positive airway pressure): 363 people, mean age 48.4 years, mean body mass index 37.4, mean pauses 50.7 per hour, 31.4% women. Trial 2 was people already using a mask: 349 people, mean age 51.1, mean body mass index 38.6, mean pauses 57.6 per hour, 26.9% women. On the treatment-regimen analysis, pauses per hour changed by −17.8 with the drug and −4.5 with placebo in trial 1 (difference −13.2; 95% interval −17.7 to −8.7). In trial 2 the change was −17.3 against −5.3 (difference −12.0; interval −17.1 to −6.9). Six of seven pre-set secondary results favoured the drug. Stomach and gut symptoms occurred in 68.0% on the drug against 37.4% on placebo in trial 1, and in 70.6% against 36.6% in trial 2. Registry: NCT06649045, as printed.

2. Random assignment, a placebo, and blinding are strengths, and the sleep result is the reason the trials were built, not a side analysis of a weight trial. Cochrane RoB 2, from the abstract, supports a low level of concern about assignment and blinding. How missing data were handled, and the one secondary result that was not clearly different, need the paper. Placebo also reduced pauses, which is why the comparison matters. The abstract does not give stopping rates or the change in weight.

3. Obesity and sleep apnoea commonly occur together in UK adults. These trials are closer to that combined problem than a general weight-loss trial would be, and they include people already on mask treatment as well as people not using one. No UK site is named. The result is for adults with a body mass index of at least 27 and moderate to severe apnoea. It does not say whether the NHS provides orforglipron.

A publisher research summary of the same trials was indexed the same day (PMID 43002163; doi:10.1001/jama.2026.24226). PubMed lists no authors and no abstract. It is not a second study and is not appraised.

### 2. Digital programmes for insomnia, pooled

Gao S, Zhang B, Li X. Efficacy of Digital Health Interventions for Insomnia: Systematic Review and Meta-Analysis of Randomized Controlled Trials. J Med Internet Res. 2026;28:e90905. doi:10.2196/90905. PMID: 43024947.

Review with a pooled analysis of 44 randomised trials. Secondary research. Level 1 for the pooled averages, with certainty the authors rate from very low to moderate. PubMed classes it as a systematic review and a meta-analysis.

1. The authors searched 12 sources through July 2026 and kept 44 randomised trials (10,521 people; 2004 to 2026; 14 countries). Digital programmes improved insomnia severity (standardised difference −0.91; interval −1.12 to −0.70), sleep efficiency (0.59; 0.45 to 0.72), total sleep time (0.20; 0.11 to 0.29), and sleep quality (−0.61; −0.78 to −0.45). The prediction interval, which asks what a new trial might show, crossed no effect for insomnia severity (−2.04 to 0.22) and for total sleep time. Effects were larger in high-income than in upper-middle-income countries. The authors say the averages are not enough to make digital programmes a standard substitute for face-to-face insomnia therapy.

2. They used Cochrane RoB 2 on the included trials and GRADE on the pooled results. AMSTAR-2 cannot be finished from the abstract: a pre-written plan, a list of excluded trials, and funding of the included trials are not shown. Small-study effects were suggested by their Egger tests. A large average with a prediction interval that includes no effect means the typical new programme might not match the average. That is the result to remember.

3. Digital insomnia therapy is relevant to UK services that cannot offer face-to-face therapy to everyone. This review supports a possible average benefit and, in the authors’ own words, does not support treating an app as the equivalent of a full course of talking therapy. It does not say which NHS app, if any, matches the programmes that were pooled.

### 3. A guided online insomnia course, adapted with autistic adults

Spaargaren KL, Begeer S, Nieuwenhuis S, et al. Effectiveness of guided internet-delivered cognitive behavioral therapy for insomnia in autistic adults (i-Sleep Autism): a randomized controlled trial. Sleep. 2026;49(11):zsag199. doi:10.1093/sleep/zsag199. PMID: 42472472.

Randomised trial. Primary research. Level 2. The record was added to PubMed on 19 July 2026. The journal issue date is 10 November 2026, which is why it is in this window.

1. The course was adapted from an existing online insomnia programme together with seven autistic adults. Then 163 autistic adults with an insomnia score of at least 10 were randomised to five weeks of guided online therapy (82 people) or to a waiting list that received sleep information and sleep-hygiene advice (81). Half completed all five modules, and 56.1% completed four. Insomnia severity improved more with the course (effect size 1.02; interval 0.65 to 1.40). At the end, 37.8% of the course group and 11.1% of the waiting-list group had a clinically meaningful insomnia improvement. The insomnia effect was still present at six months. Pre-sleep arousal fell, and quality of life was higher at the end of the course. Anxiety, depression, and daily functioning did not clearly differ.

2. Random assignment is a strength. People knew which arm they were in, and the comparison was a waiting list plus advice, not face-to-face therapy. Cochrane RoB 2: some concern for the self-reported sleep scores because the design was open, and higher concern if the result is read as proof against specialist therapy. Completion of half the group is a practical limit, and the authors say extra support is needed for people who drop out or do not benefit. The country of the trial is not stated in the PubMed record.

3. Autistic adults in the UK have high rates of insomnia, and specialist talking therapy is scarce. This trial is relevant to that group. It is not a result for autistic children, and it is not a result for adults who are not autistic. The waiting-list design does not show how the course compares with the insomnia therapy already used in NHS services.

### 4. Orexin-2 drugs in narcolepsy type 1, pooled

Yuan L, Huang YB, Chen YX, et al. Efficacy and safety of selective orexin 2 receptor agonists in narcolepsy type 1: a systematic review and meta-analysis of randomized controlled trials. J Neurol. 2026;273(11):710. doi:10.1007/s00415-026-14247-5. PMID: 43012908.

Review with a pooled analysis of randomised trials. Secondary research. Level 1, with low certainty for the wakefulness test and moderate certainty for sleepiness and cataplexy, as graded by the authors.

1. Five double-blind placebo-controlled trials of oral orexin-2 receptor agonists (TAK-994, oveporexton, or alixorexton), lasting 6 to 12 weeks, randomised 550 people. The main pooled analysis used 337. Against placebo, time awake on the Maintenance of Wakefulness Test increased by 22.7 minutes (interval 16.8 to 28.7; prediction interval 8.0 to 37.4). Sleepiness scores fell by 9.8 points (interval −10.9 to −8.8). Weekly cataplexy fell by 69% (rate ratio 0.31; interval 0.23 to 0.41). Passing urine often, urgency, insomnia, and excess saliva were more common on treatment. The TAK-994 programme was stopped after liver injury.

2. The search is named (through 10 September 2026) and GRADE is used. AMSTAR-2 cannot be finished from the abstract. The wakefulness result is inconsistent across trials (I² = 74%), so the 23-minute average is a less stable figure than the sleepiness and cataplexy results, which were consistent. Follow-up is short. One molecule caused liver injury, so a class-wide safety claim is not supported. A letter indexed the same week (PMID 43017656) calls for longer studies of oveporexton and does not add a patient sample. A narrative review (PMID 43030783) covers the same drugs and is not repeated as a separate evidence source.

3. Narcolepsy type 1 is uncommon and is managed in specialist UK centres. These short trials are the strongest new drug evidence in this week’s download. They do not say which of these drugs, if any, is available on the NHS, and they do not replace the need to know about liver injury with TAK-994. The samples are trial volunteers, not an unselected UK clinic list.

### 5. Jaw-muscle exercises did not reduce pauses in mild to moderate apnoea

Hansen DD, Tinbod U, Feng X, et al. Effect of orofacial myofunctional therapy with auto-monitoring on the apnea-hypopnea index in patients with mild-to-moderate obstructive sleep apnea: a multicenter randomized controlled trial. J Clin Sleep Med. 2026;22(1):221. doi:10.1007/s44470-026-00229-x. PMID: 43009707.

Needs a check before the citation is quoted. PubMed names the journal as *Journal of Clinical Sleep Medicine* (electronic ISSN 1550-9397) and gives the DOI as 10.1007/s44470-026-00229-x. That DOI prefix is a Springer prefix, not the prefix long used by this journal. Both fields are copied from the record. Which one is wrong cannot be settled from the record alone.

Multicentre randomised trial. Primary research. Level 2.

1. Adults newly diagnosed with mild to moderate sleep apnoea, and not yet treated, were randomised to 12 weeks of a set jaw and tongue exercise programme or to a waiting list. Sleep was recorded in the laboratory for three nights before and after. Of 104 people (52 in each arm; mean age 47.1 years), the difference in the change in pauses per hour was 0.6 (interval −3.3 to 4.5; p = 0.774). Mean adherence was 64.6% (interval 61.0 to 76.8). Higher adherence was not clearly linked with a larger fall in pauses. Oxygen dips and the sleepiness score did not change. Registry: NCT06079073, first submission 23 August 2023, as printed.

2. A randomised design, laboratory sleep studies, and an intention-to-treat analysis are strengths. The comparison is a waiting list, so people knew whether they were exercising. Cochrane RoB 2: lower concern for the pause count, which comes from the sleep study, and some concern for the sleepiness score. The result is a clear negative on the pre-set outcomes, which is more informative than a small positive from a weaker design. The abstract does not give the country.

3. Exercises for the tongue and jaw are sometimes discussed in UK clinics for milder apnoea. This trial does not show a benefit on pauses, oxygen, or sleepiness over 12 weeks in newly diagnosed adults. It does not test a different exercise plan, and it does not apply to people with severe apnoea or to people already established on a mask.

### 6. Mask treatment and a jaw device: heart-muscle scans at one year

Iyer NR, Ou YH, Bryant JA, et al. Effects of mandibular advancement device versus continuous positive airway pressure on cardiac remodeling in obstructive sleep apnea: a randomized CMR substudy. Sci Rep. 2026;16:36605. doi:10.1038/s41598-026-67940-w. PMID: 43019196.

Randomised imaging substudy. Primary research. Level 2. PubMed also tags it as an equivalence trial. The abstract calls the parent trial a non-inferiority trial (CRESCENT; NCT04119999). Added to PubMed on 12 November 2026. The online date on the record is 24 August 2026.

1. Adults with moderate to severe sleep apnoea, high blood pressure, and raised cardiovascular risk, who agreed to heart scans at the start and at 12 months, used either a mandibular advancement device (36 people) or mask treatment (49). Mean age was 59 years, 89% were men, and mean body mass index was 28.6. A marker of diffuse heart-muscle change (extracellular volume) fell slightly with the device (24.9% to 24.0%) and with the mask (25.1% to 24.4%). The two falls did not differ from each other (p = 0.576). Heart mass, volumes, and function did not differ between groups. At the start, 27% met scan criteria for a thick left ventricle, and mean 24-hour systolic pressure was 126 mmHg.

2. Random assignment and an imaging outcome that the participant cannot easily bend are strengths. Both arms received an active treatment, so the study cannot say whether either beats no treatment. Only people who agreed to two scans are included. Cochrane RoB 2: some concern, mainly from that selected subgroup and from an open device comparison. The volume change is about one percentage point. The abstract does not say whether that size matters to a patient.

3. UK pathways already choose between a mask and a dental device for some adults with sleep apnoea. In this mostly male, high-risk group, one year of either treatment was tied to a small and similar shift in one heart-muscle marker, without a change in heart size or pumping. It is not evidence that either treatment prevents heart attacks. The body size in this substudy is lower than in many UK sleep-apnoea clinics.

### 7. Jaw-advancement surgery: long-term pause counts from non-randomised studies

Monga N, Balachandran R, Sennimalai K, et al. Long-term stability and effectiveness of maxillomandibular advancement for obstructive sleep apnea: systematic review and meta-analysis. Evid Based Dent. Published online November 13, 2026. doi:10.1038/s41432-026-01281-5. PMID: 43026283.

Review with a pooled analysis of non-randomised studies. Secondary research. Level 3. PubMed’s publication type is Journal Article, not Systematic Review. The abstract describes a registered review with a pooled analysis. Needs a check of the full methods before it is treated as a completed systematic review.

1. The review was registered (CRD42021238944) and searched through May 2025 for studies with at least two years of follow-up. Of 1,299 records, 14 studies were kept. Jaw position moved forward and stayed moved on the long-term measures (SNA angle about +6.3 degrees early and +6.2 degrees later; SNB about +4.8 then +5.4). Pauses per hour fell by 40.30 in the long term (interval 32.23 to 48.37). The authors rate the certainty as low, with moderate method concerns on a tool for non-randomised studies (MINORS) in a few studies, and with large differences between studies.

2. A protocol, a named search, PRISMA reporting, and GRADE are strengths. AMSTAR-2 cannot be scored from the abstract. There is no randomised comparison with mask treatment. A before-and-after fall in pauses, pooled from selected surgical series, can look larger than the benefit over usual care. People who reach this operation are a small, severe, and willing subgroup.

3. This operation is uncommon in NHS practice and is considered only after other treatments have failed or are unsuitable. The record supports a large and lasting fall in pauses in the published series, with low certainty. It does not provide a UK complication rate or a comparison with staying on a mask.

### 8. The mask machine’s pause count can miss remaining disease

Malhotra SR, Do QT, Gunn S, et al. Beyond device downloads: residual sleep apnea and hypoxemia missed by flow-based CPAP monitoring. Sleep. 2026;49(11):zsag189. doi:10.1093/sleep/zsag189. PMID: 42436640.

Retrospective comparison of two home recordings on the same nights. Primary research. Level 4. Added to PubMed on 12 July 2026. The journal issue date is 10 November 2026.

1. In a remote sleep service, 465 people contributed 24,939 nights with both a mask download and a home recording that uses cardiopulmonary coupling (SleepImage). The mask’s own pause count averaged 2.4 per hour. The coupling count averaged 12.1. On nights when the mask count was under 5, the coupling count was still at least 5 on 85% of nights and at least 10 on 47.7%. On those same “good” mask nights, 28.3% had at least five minutes with oxygen under 90%, and 10.6% had at least five minutes under 88%.

2. The size, in nights, is a strength. The comparison method is not a laboratory sleep study, so some of the gap may be the method rather than missed apnoea. Nights were taken from people already in a monitoring programme. None of the four named checklists is a device-agreement tool. The main threats are an unrepresentative monitoring cohort and a reference test that has not, in this abstract, been shown to match laboratory scoring on treatment nights.

3. UK mask reviews often rely on the download: hours used, leak, and the machine’s pause count. This record says that a low machine count can sit next to a higher burden on another home test, including low oxygen. It is one service’s retrospective file, not a UK audit, and it does not by itself set a new review standard. The country is not stated.

### 9. Staying in a mask service is not the same as a full response

Sartori G, Caprino R, Crisafulli E. From CPAP Prescription to Long-Term Follow-Up: Care Pathway, Adherence, and Multidomain Treatment Outcomes in Obstructive Sleep Apnea. J Clin Med. 2026;15(21):8296. doi:10.3390/jcm15218296. PMID: 43030439.

Retrospective description of one care pathway. Primary research. Level 4. The article date on the record is 24 October 2026. It was added to PubMed on 14 November 2026, which is why it is in this window. The number 8296 is the article identifier on the record, matching the DOI, not a traditional page range.

1. Of 172 adults who entered a real-world mask pathway, 114 had at least 30 months in which a long-term visit could have happened, and 80 of those 114 attended (70.2%). Attendance was 68.5% and 72.8% at the 24- and 36-month checks. Each extra 10 years of age was linked with higher odds of attending (odds ratio 1.58; interval 1.10 to 2.28). In 94 people with adherence data at two times, device-recorded adherence was 78.7% early and 79.8% later, but 11.7% changed category. At the later visit, a residual pause count under 5 per hour was present in 47.8%, no remaining sleepiness in 87.8%, and a sense of benefit in 89.3%. Of 71 people with all four measures, 45.1% met all four at once, or 63.4% if the pause threshold was relaxed to under 10.

2. There is no comparison pathway. Attendance is among people still in the service’s records. Newcastle-Ottawa does not fit a single-service audit. The useful design point is that the authors kept adherence, residual pauses, sleepiness, and perceived benefit as separate facts. A high average adherence hides the one in nine who changed category, and fewer than half met every target at once.

3. Long-term mask follow-up is part of UK practice, and many services struggle to keep people in clinic. This record, from a country the abstract does not name, suggests that coming back and using the machine are not the same as a full response on pauses. It is one pathway, not a national UK figure.

### 10. Screening questionnaires, including a version that adds menopause

Solecka S, Tomaskova H, Marques-Vidal P, et al. A sex-specific modification of the SARA questionnaire for obstructive sleep apnea screening: Comparative validation against six other tools in the HypnoLaus cohort. Sleep Med. 2026;149:109350. doi:10.1016/j.sleep.2026.109350. PMID: 43002845.

Diagnostic accuracy study in a population cohort. Primary research. Level 4. Added to PubMed on 9 November 2026.

1. In the Swiss HypnoLaus cohort, 1,540 adults (718 women, 822 men) had a laboratory sleep study. Moderate to severe apnoea was at least 15 pauses per hour. NoSAS had the highest overall discrimination (area under the curve 0.741; interval 0.718 to 0.764). An updated SARA score was next (0.693; 0.669 to 0.716), ahead of the original SARA (0.684), Berlin (0.635), SONA (0.579), STOP-Bang (0.575), and the Epworth scale (0.507). Adding menopausal status improved SARA in women (0.675 against 0.627). In women aged 55 or under, updated SARA beat NoSAS (0.616 against 0.509). In lean women, NoSAS sensitivity was 0% and updated SARA sensitivity was 42.3%.

2. A general-population sample and a laboratory reference are strengths. This is not a trial of treatment. The usual tool is QUADAS-2, and it cannot be finished from the abstract. Areas under the curve around 0.6 to 0.7 are only modest. A sensitivity of 42% in lean women still misses more than half of the cases. STOP-Bang’s low score in this population sample is a warning against assuming a clinic questionnaire travels unchanged.

3. UK primary care often uses symptom scores before referral. This Swiss general-population test says that body-size-heavy scores can miss younger, leaner women, and that the Epworth scale did not sort moderate apnoea. It is not a UK derivation, and it does not set an NHS cut-off. The better of the scores was still far from a rule-out test.

### 11. How stable a week of UK Biobank wrist data is

Bailey CP, Wolff-Hughes DL, Hayes HA, et al. Stability of actigraphy-derived sleep and rest-activity rhythm estimates in the UK Biobank. Sleep Health. Published online November 13, 2026. doi:10.1016/j.sleh.2026.10.003. PMID: 43026078.

Reliability study in a national cohort. Primary research. Level 3 as measurement research, not a treatment study. The record has no page range. It also carries the item code S2352-7218(26)00253-6.

1. UK Biobank participants (3,166 people; 51% women; 57% with body mass index at least 25) wore an accelerometer for up to seven days, then repeated testing over two to five years. Most sleep measures were moderately to highly stable. Over the long gap, the intraclass correlation was 0.66 for sleep duration (interval 0.64 to 0.68), 0.57 for the midpoint of sleep, 0.61 for sleep onset, 0.64 for wake after sleep onset, 0.77 for interdaily stability, 0.25 for intradaily variability, and 0.19 for social jetlag (interval 0.14 to 0.24). The authors say a less stable measure can shrink a disease association by a large amount. They give social jetlag as an example of about 80% attenuation.

2. Repeated wear in the same people is the right design. The abstract does not give the age range. None of the four clinical checklists is a reliability tool. A correlation of 0.66 is useful and is not perfect agreement. Social jetlag and intradaily variability were unstable, so a single week is a poor stand-in for those two.

3. This is a UK adult volunteer cohort, which is as close as this week’s download gets to a national UK measurement study. It supports using one week of research-grade wrist data as a reasonable snapshot of usual sleep length over a few years. It does not validate consumer watches, and it warns against treating one week of social jetlag as a person’s usual pattern. The age band is not in the abstract.

### 12. Sleep length and later illness in UK Biobank, watch against questionnaire

Chaput JP, Biswas RK, Ahmadi M, et al. Dose-response associations between sleep duration and health outcomes in adults: comparison between self-reported and device-based measures. Sleep. 2026;49(11):zsag193. doi:10.1093/sleep/zsag193. PMID: 42454954.

Prospective cohort analysis. Primary research. Level 3. Added to PubMed on 15 July 2026. The journal issue date is 10 November 2026.

1. UK Biobank adults aged 40 to 69 wore a wrist accelerometer for seven days and also reported their sleep length. Follow-up averaged 8.0 years. Up to 76,811 people were in the mortality analysis, and 69,153 in the cardiovascular analysis. The curves were an inverse J for death and several diseases, and a U-shape for new depression. A sleep-period time of 7 hours, against a 5-hour reference, had a mortality hazard ratio of 0.70 (interval 0.61 to 0.79). The same 7 hours as total sleep time had a ratio of 0.83 (0.78 to 0.89), and as self-report a ratio of 0.86 (0.74 to 1.00). The lowest estimated risk sat near 7.2 hours for self-report, 7.7 hours for sleep period, and between 6.8 and 9.3 hours for total sleep time. Device associations were stronger for sleep period than for the other two measures.

2. The sample is large, the outcomes include death, and the authors adjusted for many factors. Newcastle-Ottawa fits in outline: a defined cohort and hard outcomes, with leftover confounding still possible. Sleep was measured once. People who sleep very little or very long may already be ill. The self-report 7-hour mortality interval reaches no extra difference from 5 hours. The device results are clearer. UK Biobank volunteers are healthier and more affluent than the UK average, so the curves may not match every UK adult.

3. For UK adults in middle and older age, this is direct evidence, and it still does not cover ages 18 to 39. The practical reading is that questionnaire sleep and watch sleep are not interchangeable, and that the time from going to bed to getting up tracked later illness more strongly here than either “asleep” time or the self-report. It does not show that lengthening sleep would prevent those illnesses.

### 13. Consumer sleep devices did not measure the same thing

Ravindran KKG, Della Monica C, Atzori G, et al. Are different consumer sleep technologies measuring the same essential aspects of sleep? Sleep. 2026;49(11):zsag231. doi:10.1093/sleep/zsag231. PMID: 42631708.

Method-comparison study. Primary research. Level 4. Added to PubMed on 22 August 2026. The journal issue date is 10 November 2026.

1. Seventy-four older adults, 20 of them living with dementia, were recorded at home for 752 paired nights with a research accelerometer (Axivity), a watch (Withings), a bedside sensor (Withings Sleep Analyser), and a diary, plus one laboratory sleep study. Single-night correlations between devices, and with the laboratory study, were weak for most measures (r under 0.3) and moderate for duration and timing (r from 0.3 up to, but not including, 0.7). Against the laboratory study, the devices overestimated total sleep and sleep efficiency, underestimated wake after sleep onset, and agreed poorly on sleep stages. Duration was the only feature with a consistent moderate link between devices. Most measures needed up to seven nights to reach an intraclass correlation of at least 0.7. Registry: ISRCTN10509121, as printed.

2. Wearing several devices on the same nights is the right design, and including people with dementia is a strength for real-world use. One laboratory night cannot stand in for every home night. The sample is small and older. None of the four treatment checklists is a device-agreement tool. The main limit is that a moderate correlation for duration is not the same as interchangeable numbers.

3. UK adults increasingly bring consumer sleep scores to clinic. In this older sample, the country of which is not stated, those scores should not be read as laboratory sleep stages or as interchangeable across brands. Sleep length was the least bad shared measure. A commentary on actigraphy and consumer devices was also indexed (PMID 42664188) with no abstract, so it is not appraised.

### 14. Trazodone for insomnia symptoms: dose and drop-out

Yang X, Fang S, Sun L, et al. Efficacy, Acceptability, and Tolerability of Trazodone in Insomnia Symptoms: A Systematic Review and Dose-Response Meta-Analysis. Clin Drug Investig. Published online November 12, 2026. doi:10.1007/s40261-026-01607-2. PMID: 43018915.

Review with a dose-response pooled analysis. Secondary research. Level 1 for the short-term sleep-quality average, limited by high inconsistency. PubMed’s publication type is Systematic Review. The abstract describes a meta-analysis. The record has no volume, issue, or pages.

1. Thirteen randomised trials (1,366 people), searched through 17 November 2025, compared trazodone with placebo or compared doses. Subjective sleep quality improved (Cohen’s d = 0.67; interval 0.36 to 0.98), with high inconsistency (I² = 80.86%). The dose curve rose at low doses and flattened near 50 mg a day. Estimates above that were sparse. An exploratory 50% effective dose was 15.2 mg a day, and a 95% effective dose was 38.2 mg a day. Ordinary pooling found no clear difference in stopping the drug for any reason, or because of side effects. The dose curve suggested more side-effect stopping as the dose rose. Registry of the review: CRD420251232065.

2. A protocol number and a dose model are strengths. AMSTAR-2 cannot be finished from the abstract. The trials mix different patient groups, which matches the high inconsistency. The effective-dose numbers are, in the authors’ words, exploratory. There is not enough long-term safety information in the abstract. A high average effect with I² above 80% should not be quoted as if every trial showed the same benefit.

3. Trazodone is widely used off label for insomnia in UK adults. This review is about short-term subjective sleep quality in mixed trial populations, not about a licensed insomnia indication, and not about long-term use. The flattening near 50 mg is a research observation from sparse higher-dose data. It is not a dosing instruction.

### 15. Narcolepsy type 1 and type 2: death and stroke in US records

Gautam N, Upadhyay A, Subedi BK, et al. Phenotype-specific differences in mortality and cerebrovascular risk in narcolepsy type 1 and type 2: a real-world propensity score-matched cohort study. Ann Med Surg (Lond). 2026;88(11):7011-7018. doi:10.1097/MS9.0000000000005502. PMID: 43017640.

Retrospective matched cohort using a health-record network. Primary research. Level 3. The article date on the record is 6 October 2026. It was added to PubMed on 12 November 2026.

1. Using the TriNetX US network, analysed on 28 September 2025, adults aged 18 to 75 with a billing code for narcolepsy type 1 or type 2 were matched 1:1 on demographics, other illnesses, and medicines (19,907 pairs). Over 10 years, death from any cause was 1.57% in type 1 and 2.01% in type 2 (hazard ratio 0.764; interval 0.659 to 0.885). Ischaemic stroke was 1.49% against 1.23% (hazard ratio 1.193; interval 1.006 to 1.415). A combined heart endpoint, rhythm problems, and sudden cardiac death did not clearly differ. The authors call the findings hypothesis-generating.

2. The matching and the hard outcomes are strengths. The exposure is an ICD-10 code (G47.411 against G47.419), which can mislabel the type of narcolepsy. Newcastle-Ottawa and ROBINS-I both stumble on that misclassification. The stroke interval only just clears no difference. Absolute gaps are under one percentage point. A lower death rate beside a higher stroke rate is not a simple story, and the design cannot say why.

3. These are US coded records, not UK clinic diagnoses. The absolute risks are small. The result is a reason for specialist interest in stroke risk in narcolepsy type 1, not a figure to quote as a UK patient’s personal risk. It does not test whether treating cataplexy changes stroke or death.

### 16. White-matter lesions in isolated REM sleep behaviour disorder

Mak E, Przybelski SA, Reid RI, et al. White matter microstructure and hyperintensity burden in isolated REM sleep behaviour disorder. Brain Commun. 2026;8(6):fcag414. doi:10.1093/braincomms/fcag414. PMID: 43032853.

Cross-sectional imaging study in a research consortium. Primary research. Level 4.

1. The North American Prodromal Synucleinopathy Consortium contributed 168 people with isolated REM sleep behaviour disorder confirmed on a sleep study. Those classed as clinically impaired (57) had a higher burden of white-matter hyperintensities than those not impaired (111). A few diffusion differences were seen. After the hyperintensity burden was taken into account, only one occipital diffusion measure remained. Diffusion measures lined up with a forward digit-span score and with autonomic symptoms. Hyperintensity burden lined up more broadly with a lower Montreal Cognitive Assessment score, digit span, pegboard speed, and a higher prodromal disease score. Analyses were adjusted for age and sex, and a false-discovery correction was used.

2. Sleep-study confirmation and a correction for multiple tests are strengths. This is one time point, so the lesions may be a fellow traveller of vascular disease rather than part of the sleep disorder’s progression. Newcastle-Ottawa is a loose fit. The consortium is not a UK community sample. “Impaired” is a clinical grouping from the study, and the abstract does not give the full rule.

3. Isolated dream-enactment in adults is assessed in UK neurology and sleep clinics because of the later risk of a synuclein disease. This record says that ordinary small-vessel white-matter change tracks thinking and motor scores in that group, and that diffusion scans added less once those lesions were counted. It is not a UK risk figure, and it does not test a treatment.

A second paper on EEG slowing and later neurological change in the same disorder (PMID 43033093) has no abstract on the PubMed record, so no findings are taken from it.

### 17. Magnetic brain stimulation for insomnia: sleep scores did not beat the sham

Garg N, Garg S, Dhyani M. Efficacy and Safety of Intensive Continuous Theta Burst Stimulation Over the Right Dorsolateral Prefrontal Cortex in Insomnia Disorder: A Randomized Sham-Controlled Trial. Prim Care Companion CNS Disord. 2026;28(6):26m04225. doi:10.4088/PCC.26m04225. PMID: 43024398.

The title in PubMed has no space after the colon. The citation above adds that space for readability. The DOI and the rest of the title are as on the record.

Randomised sham-controlled trial. Primary research. Level 2.

1. Thirty adults with DSM-5 insomnia disorder and a Sleep Condition Indicator score under 16 (15 in each arm) received active or sham continuous theta-burst stimulation to the right dorsolateral prefrontal cortex, 21 sessions over 10 days, at 80% of resting motor threshold. Data ran from October 2024 to January 2026. Both groups improved on every sleep and functioning score, with large within-group effects. The gap between active and sham was not clear for the sleep scores (Pittsburgh p = 0.060; Sleep Condition Indicator p = 0.147; insomnia severity p = 0.720; daytime functioning p = 0.388). A quality-of-life score did favour active stimulation (p = 0.002; partial eta squared 0.242). Three people had a brief mild headache. No serious adverse event is reported. Registry: CTRI/2024/10/075898.

2. A sham arm is a strength, and the sleep results do not favour active treatment. Cochrane RoB 2: some concern, because the trial is small and the abstract does not show whether people could tell sham from active. The quality-of-life result is one of several outcomes in a 30-person trial. Both groups improving is what a sham-controlled design is meant to show, and it argues against reading an uncontrolled before-and-after fall as an effect of the magnet.

3. Neuromodulation for insomnia is not routine NHS care. This trial does not show a sleep-score benefit over sham over 10 days. The registry is Indian. The abstract does not state the country of the participants. It should not be quoted as evidence that this stimulation treats insomnia.

### 18. A nerve procedure for restless legs, with no comparison group

Genç Perdecioğlu GR, Acar AB, Akkaya ÖT. Clinical outcomes following ultrasound-guided posterior tibial nerve pulsed radiofrequency combined with perineural injection in refractory restless legs syndrome. Acta Neurol Belg. Published online November 14, 2026. doi:10.1007/s13760-026-03236-0. PMID: 43026464.

Retrospective before-and-after series. Primary research. Level 4. All three authors are listed.

1. Records of 30 people with refractory restless legs syndrome were reviewed after ultrasound-guided pulsed radiofrequency of both posterior tibial nerves, followed by a perineural injection of dexamethasone and lidocaine. The syndrome score fell from 28.23 to 12.23 at one month and was 17.67 at three months. A restlessness score fell from 7.33 to 3.23 and then 4.60. A sleep-disturbance score fell from 12.17 to 7.80 at three months. All three changes are reported as statistically clear. The one-month and three-month score drops on the syndrome scale were 16.00 and 10.56 points.

2. There is no group who did not have the procedure, and the injection and the radiofrequency were given together, so neither can be credited alone. Symptoms had partly returned by three months. Newcastle-Ottawa does not fit a single treated series. Expectation, other medicines, and regression to the average can all move a score this far. The country is not stated.

3. Refractory restless legs is a real problem in UK neurology and sleep clinics. This 30-person series is a short, uncontrolled signal only. It is not evidence that this procedure should be offered, and the partial return of symptoms by three months is part of the result. A separate dialysis study (PMID 43006170; 89 people aged 60 or over; restless legs in 13.5%) linked higher FGF23 with restless legs and with poorer thinking scores. That is an association in a highly selected kidney population, not a treatment result, and it is not written up in full.

### 19. Insomnia and insulin resistance together, and later high blood pressure

Wu S, Wang Y, Lyu W, et al. Insomnia Modifies the Association Between Insulin Resistance and Incident Hypertension in Hispanic/Latino Adults: A 6-Year Longitudinal Study. Nat Sci Sleep. 2026;18:648160. doi:10.2147/NSS.S648160. PMID: 43032238.

The number 648160 is the article identifier on the record, the same suffix as the DOI, not a traditional page range.

Longitudinal cohort analysis. Primary research. Level 3.

1. In 3,300 Hispanic or Latino adults followed for six years, neither insulin resistance nor insomnia alone was linked with new high blood pressure. The two together were linked with a 39% higher risk (hazard ratio 1.39; interval 1.05 to 1.85). The interaction test was p = 0.045. Among people with insomnia, insulin resistance was linked with a hazard ratio of 1.60 (interval 1.16 to 2.21). Among people without insomnia, that link was not seen. The abstract says the combined pattern was clearest in men and in people younger than 42. Insomnia was measured with the Women’s Health Initiative Insomnia Rating Scale. The insulin cut-point was chosen from the same data with a Youden index.

2. Six years of follow-up and a pre-stated interaction are strengths. Choosing the insulin cut-point inside the same dataset can make the split look cleaner than it is. The abstract says the models were adjusted, but it does not list the factors, so leftover confounding is open. Newcastle-Ottawa fits reasonably for a cohort with a clinical outcome. One interaction p value of 0.045 is a fragile basis for a subgroup story about age and sex.

3. The sample is Hispanic and Latino adults in a US cohort, not a cross-section of UK adults. The pattern, if real, would matter in UK primary care, where insomnia, insulin resistance, and blood pressure often meet. This paper does not show that treating insomnia lowers blood pressure. It suggests that the combination marked risk when each factor alone did not, in this cohort.

### 20. Estimated apnoea subtypes, and a predicted dental-device response

Manners J, Dutta R, Levendowski DJ, et al. Scalable Sleep Apnoea Endotype Profiling and Estimated Oral Appliance Treatment Response in a Large Clinical Cohort. Respirology. Published online November 13, 2026. doi:10.1002/resp.70338. PMID: 43026159.

Application of existing prediction models to a large clinical series. Primary research. Level 4. The record has no volume or pages.

1. Models that use ordinary sleep-study outputs, age, and body mass index were applied to more than 6,500 consecutive home studies with at least 5 pauses per hour (Sleep Profiler). Mean pauses were 28 per hour, mean age 49, mean body mass index 31, and 39% were women. An estimated 29% had only mild anatomical narrowing. Estimated non-anatomical problems were poor airway-dilator muscle function in 23%, high loop gain in 31%, and a low arousal threshold in 29%. Severe impairment in at least one non-anatomical trait was estimated in 62%. About 60% were predicted to respond to a dental device.

2. The scale is a strength, and the authors are clear that these are estimates from models, not invasive physiology and not observed responses to a device. A predicted 60% response is not a measured 60% response. None of the four checklists is a prediction-model tool. The relevant threats are a shift from the people the model was built on, and an optimistic reading of an untested prediction. The country is not stated.

3. UK clinics do not routinely report loop gain or arousal threshold. This paper says those estimates can be produced from home-study outputs at scale. It does not show that using them would improve UK dental-device results. The 60% figure should not be quoted as a success rate.

### Adult papers seen and not written up in full

The three-part appraisal was not done for these. Full text was not used. They should not be quoted as finished appraisals. Figures below are from the PubMed abstract only.

Sleep apnoea, still on topic:

- Sex differences with a dental device, 460 adults: symptoms fell in both sexes; women more often reported trouble keeping the device in the mouth and a dry mouth (PMID 43033746).
- A model of who becomes less sleepy on mask treatment, trained in 139 treated people and tested in 74, had an adjusted R² of 0.313. It beat a guideline rule for a two-point sleepiness change (78.1% against 68.4%) (PMID 42623284). Added to PubMed on 20 August 2026; journal issue 10 November 2026.
- A systematic review of brain MRI after mask treatment included 30 studies and found mixed, mostly small, non-randomised signals. The authors say this does not support routine MRI to track treatment (PMID 42667645). Added 29 August 2026; issue date 10 November 2026.
- Eight studies (435 people with sleep apnoea, 281 controls) pooled higher blood amyloid-β42, total tau, and phosphorylated tau. Inconsistency was high. Oxygen measures lined up with some of the markers (PMID 43034879).
- Gastro-oesophageal reflux in adults with sleep apnoea was pooled at 34% (interval 25% to 44%) across 33 studies and 12,076 people, with extreme inconsistency (I² = 98.2%) (PMID 43024739).
- A scoping review of 36 reports described recurring symptom groups: sleepy, insomnia-like, and minimally symptomatic, plus two further patterns. Symptom burden did not reliably match the pause count (PMID 43021938).
- In one centre, 54 sleepy adults and 45 with apnoea plus insomnia had similar rates of any cardiovascular disease (90.7% and 86.7%) (PMID 43028499). The groups are small.
- In Korean insurance data, polycystic ovary syndrome was linked with a later sleep-apnoea code (hazard ratio 1.483; interval 1.029 to 2.137). Events were uncommon (PMID 43001633).
- A digital thinking-skills battery in 46 people with a range of apnoea severity was stable enough to repeat for only some of the 14 tasks (PMID 43002846).

Insomnia, circadian rhythm, and mental health:

- Open-label dimdazenil 2.5 mg against midazolam 15 mg for 14 days, 185 people. Sleep time rose within the dimdazenil group. The between-group gap was +7.36 minutes. The abstract does not give a confidence interval or a p value for that gap (PMID 42413624). Journal date 15 November 2026. The record was added on 7 July 2026.
- In 202 rotating textile workers, a shift-work sleep disorder definition was met by 34%. Workplace accidents were 46% in that group and 31% in the others (p = 0.036) (PMID 43019583). This is the week’s clearest adult circadian-work paper. The adolescent amber-lens trial (PMID 43004031) was set aside as adolescent-only. No adult randomised trial of a circadian rhythm disorder was written up.
- Cancer and insomnia: pooled prevalence 34.6% (interval 27.2% to 44.1%) in 39 studies and 14,094 people (PMID 43031295). That is not a UK rate.
- Eighteen adults with schizophrenia slept more variably and reported more negative emotion after a night restricted to a four-hour opportunity than after an eight-hour opportunity. Average sleep on the “eight-hour” night was 5.51 hours (PMID 43033642).
- In 176 adults with obsessive-compulsive disorder, group CBT with exposure and group acceptance and commitment therapy showed similar changes in insomnia scores. The trial was powered for the obsessive-compulsive outcome (PMID 43000688).
- EEG machine-learning description of primary insomnia, 50 patients and 50 sleepers (PMID 42759567). Journal date 13 November 2026. Added to PubMed on 18 September 2026.
- Ninety-one women with narcolepsy or idiopathic hypersomnia at one centre reported contraception changes and difficulty getting clear advice. Twenty-two reported a pregnancy after diagnosis. No malformation rate is given (PMID 43025380).
- MRI volumes of hippocampus, amygdala, thalamus, and brainstem did not differ in 54 people with narcolepsy type 1 against 114 controls after correction. Mean age was 21.8 years, so the sample is not adult-only (PMID 43035082).
- European centre counts linked 2010 and 2013 peaks in narcolepsy, including childhood peaks, with influenza seasons (PMID 43012367). Not an adult-only UK incidence.
- Hip-worn “non-wear” overestimated time in bed by about 41 minutes against diaries in 17,855 adults in a cancer-prevention cohort (PMID 43033878).
- In 134 adults with type 2 diabetes, self-reported sleep time was longer than actigraphy, and the gap varied with sex and depressive symptoms (PMID 43006178).
- Perioperative esketamine and postoperative sleep: 23 trials, 2,868 people, better short-term sleep scores and a large increase in drowsiness (risk ratio 12.64). This is an anaesthetic question, not a chronic insomnia trial (PMID 43009776). Added 10 November 2026. Journal date 15 August 2026.
- One evening of moderate cycling and next-day memory after a short night, 88 young adults (PMID 42648715). Added 26 August 2026; issue date 10 November 2026.
- Simulated night driving after either one sleepless night or four short nights, 20 healthy men. Acute loss impaired steering more (PMID 42497088). Added 24 July 2026; issue date 10 November 2026.

Empty abstracts, so no findings are used: the EEG phenoconversion paper (PMID 43033093), a sleep-inertia commentary (PMID 43007331), and the actigraphy commentary (PMID 42664188).

The rest of the 338 included ward and surgical series, student surveys, traditional mixtures, protocols, letters, corrections, and papers in which sleep was a secondary score. They were not appraised.

## Block B. Adult bruxism

No record in this window was about sleep-related painful erections.

### 1. Reflux symptoms and sleep bruxism in a city sample

Machado E, Knorst JK, Maluly Filho M, et al. Is sleep bruxism associated with laryngopharyngeal reflux in EPISONO adult general population? Sleep Med. 2026;149:109362. doi:10.1016/j.sleep.2026.109362. PMID: 43035081.

Cross-sectional analysis of a population sleep study. Primary research. Level 4. Added to PubMed on 15 November 2026.

1. From the São Paulo EPISONO follow-up, 686 adults (380 women, 306 men; mean age 50.1 years) had a reflux-symptom score and sleep-bruxism measures. Reflux symptoms were present in 17%. Among those people, self-reported sleep bruxism was 23.9%, sleep-study bruxism was 33.6%, and both together were 10.4%. Before adjustment, reflux symptoms were linked with more self-reported bruxism. After adjustment, reflux symptoms were not linked with bruxism on any definition. The abstract says that, among people who also had sleep apnoea, reflux symptoms were linked with more bruxism. It does not give that subgroup estimate.

2. A general-population sample and a laboratory sleep study are strengths. Reflux was a symptom score, not an acid test. Bruxism by questionnaire and bruxism on a sleep study disagreed, which is itself a finding. Newcastle-Ottawa is a loose fit for a cross-sectional analysis. The unadjusted link disappearing after adjustment is the main result. The apnoea subgroup is stated without a number, so it cannot be quoted as an effect size.

3. UK adults often have both reflux symptoms and tooth grinding. This city sample does not support a general-population link once other factors are included. It is not a UK prevalence, and the missing subgroup figure should not be filled in. Asking about both symptoms can still be reasonable. This paper does not test treatment of either condition.

### 2. Awake bruxism and sleep bruxism travel together, in a mixed-age review

Porporatti A, Schroder ÂGD, Kuczera MS, et al. Is there an association between awake and sleep bruxism? : a meta-analysis. Clin Oral Investig. 2026;30(12):570. doi:10.1007/s00784-026-07248-1. PMID: 43013101.

Needs a check: the PubMed initials for the second author are printed as “ÂGD”. That leading character looks like an encoding slip for the forename Ângela. It was not corrected here.

Review with a pooled analysis of observational studies. Secondary research. Level 4, because the underlying studies are mostly one-time surveys. The pooled odds ratio is not a treatment effect. PubMed’s age tags include Child. The abstract says the association was still present when adults were looked at separately. It is not a child-only review.

1. Forty-nine studies were included, 41 of them cross-sectional. Most used self-report (35). Only one used a device. The pooled odds ratio for having the other form of bruxism was 3.74 (interval 2.47 to 5.67), from 8,970 people in the sleep-bruxism side of the comparison and 25,730 on the awake-bruxism side. The association was reported as still present in adults, in children, and in the studies with a clinical examination. Heterogeneity was high in every analysis. The adult-only odds ratio is not printed.

2. AMSTAR-2 cannot be scored. The abstract does not mention a protocol registration, a dual screen, or a list of excluded studies. High heterogeneity and a heavy reliance on questionnaires mean the 3.74 figure is a blunt average. A cross-sectional association cannot say which form comes first. Device confirmation is almost absent.

3. For UK dentists and sleep clinics, the useful point is that awake clenching and sleep grinding are often reported together, including in the adult studies inside this pool. The number itself should not be used as a UK odds ratio. The adult-only estimate is not in the abstract. Finding one pattern is a reason to ask about the other. It is not evidence for a splint or a medicine.

### 3. Jaw-muscle thickness in people judged to have bruxism

Akol Görgün E, Öndeş A. Ultrasonographic Evaluation of Masseter Muscle Thickness and Fractal Dimension in Bruxist and Healthy Individuals. Diagnostics (Basel). 2026;16(21):3648. doi:10.3390/diagnostics16213648. PMID: 43028519.

Cross-sectional comparison. Primary research. Level 4. The article identifier 3648 matches the DOI. Added to PubMed on 14 November 2026.

1. Thirty people with clinically judged bruxism and 30 without (15 women and 15 men in each group) had ultrasound of the masseter. Bruxism required grinding or clenching for at least a year, plus tooth wear, muscle tenderness, or morning jaw pain or headache. Mean thickness at rest was 12.95 mm against 9.72 mm. A texture measure during clenching was slightly higher in the bruxism group (1.202 against 1.182) and remained after a correction for several tests. The resting texture difference did not. Thickness measurements were highly repeatable (intraclass correlation 0.967 to 0.980).

2. The comparison group had none of the clinical signs, so the thickness gap may partly be the tenderness and bulk that put people into the bruxism group. This is not sleep bruxism confirmed on a sleep study. The sample is small. Newcastle-Ottawa is a loose fit. The country is not stated. A texture difference of about 0.02 is statistically clear and may be too small to use as a test.

3. UK clinicians sometimes use muscle size as a clue to clenching. This sample supports a thicker masseter in people already labelled as having bruxism on clinical grounds. It does not validate ultrasound as a diagnostic test, and it does not separate sleep bruxism from daytime clenching.

### 4. One case of waking bruxism after stroke, treated for drooling

Majit AA, Harmouche M, Maarad M, et al. Post-stroke Bruxism Improvement Following Botulinum Toxin Injection Into Salivary Glands: A Case Report. Cureus. 2026;18(10):e117962. doi:10.7759/cureus.117962. PMID: 43034565.

Single case report. Primary research. Level 4. The article date is 15 October 2026. It was added to PubMed on 15 November 2026.

1. A 37-year-old woman, four months after a right capsulolenticular haemorrhage, had waking bruxism scored at grade 2 on a standardised bruxism tool, with tonic masseter activity on surface electromyography, plus severe drooling. OnabotulinumtoxinA was injected into both parotid glands (30 units each side) and both sublingual glands (20 units each side) for the drooling. At three weeks, the drooling score fell from 8/9 to 4/9, and the bruxism grade fell from 2 to 1.

2. A single case cannot support a treatment claim. There is no comparison, and waking bruxism can change during stroke recovery. The injection was into salivary glands, not into the jaw muscles. Cochrane RoB 2 does not fit. The electromyography change is described only as a reduction.

3. This does not change UK stroke or dental practice. It is a possible observation about waking jaw activity after an injection given for drooling. Sleep bruxism was not the condition described.

### 5. A vortioxetine case with no abstract

Kelson M, Rodulfo A, Torres A, et al. Probable Vortioxetine-Associated Bruxism: First Reported Case. J Clin Psychopharmacol. Published online November 13, 2026. doi:10.1097/JCP.0000000000002293. PMID: 43019559.

The PubMed record has no abstract. Publication type is Journal Article. The title says this is a first reported case of probable vortioxetine-associated bruxism. Dose, timing, whether the drug was stopped, and what happened next are not in the record. Those facts are unverifiable from PubMed. No appraisal of statistics or of relevance to UK adults can be made. The citation fields above are on the record and were not checked against the full paper, because the full paper was not used.

### Block B records that are not bruxism studies

- PMID 43028651. Randomised trial of botulinum toxin into the masseter and temporalis against oral methocarbamol for temporomandibular myofascial pain, 235 adults (124 toxin, 111 methocarbamol). Bruxism is a keyword, not the enrolled condition. Both groups improved in pain and mouth opening. At five weeks the groups did not clearly differ (pain p = 0.130; opening p = 0.125). An uncorrected right-sided trigger-point difference favoured toxin. This is not evidence about sleep bruxism. Journal date 26 October 2026. Added to PubMed on 14 November 2026.
- PMID 43000605. Narrative review of pulp-vitality testing. Bruxism is named as one of several factors that might change the test. Not a bruxism study.
- PMID 43024956. Elite women’s football and training load. The match is a false hit: “session RPE” was tokenised as SRPE. It is not sleep-related painful erections, and it is not bruxism.
- PMID 42398676. Anxiety, depression, and oral health in paediatric populations. Excluded as child-only. Bruxism was not appraised from it.

## Coverage gaps, and strings that were not run

Embase and Scopus were not searched. Institutional access was down. That is a real gap. Embase indexes more European and conference material than PubMed. Scopus indexes further journals and some non-MEDLINE records. A paper in those databases only would be missing here. The strings below are ready to paste. They were not run. Subject headings should be confirmed in the live thesaurus before anyone relies on a count.

The PubMed window was not widened. The strings below use 9 to 16 November 2026, matching the search that was run.

### Embase.com (Elsevier, Emtree)

Embase’s adult limit is 18 to 64 years. The aged limit is 65 and over. Together they stand in for 18 and over. Age limits miss records that have not yet been indexed with an age. `/pd` is publication date. `/sd` is the date the record was added.

```
('insomnia'/exp OR insomnia:ti,ab,kw
 OR 'sleep apnea syndrome'/exp OR 'obstructive sleep apnea'/exp
 OR 'sleep apnoea':ti,ab,kw OR 'sleep apnea':ti,ab,kw OR 'obstructive sleep':ti,ab,kw
 OR 'sleep disordered breathing':ti,ab,kw
 OR 'circadian rhythm sleep disorder'/exp OR 'circadian rhythm':ti,ab,kw
 OR 'narcolepsy'/exp OR narcolepsy:ti,ab,kw OR cataplexy:ti,ab,kw
 OR 'hypersomnia'/exp OR hypersomnia:ti,ab,kw OR hypersomnolence:ti,ab,kw
 OR 'restless legs syndrome'/exp OR 'restless legs':ti,ab,kw
 OR 'periodic limb movement disorder'/exp OR 'periodic limb movement':ti,ab,kw
 OR 'parasomnia'/exp OR parasomnia*:ti,ab,kw
 OR 'rem sleep behavior disorder'/exp OR 'rem sleep behaviour':ti,ab,kw OR 'rem sleep behavior':ti,ab,kw
 OR 'sleep quality':ti,ab,kw OR 'sleep duration':ti,ab,kw
 OR 'sleep disorder':ti,ab,kw OR 'sleep disturbance':ti,ab,kw
 OR 'cognitive behavioral therapy'/exp OR 'cbt-i':ti,ab,kw OR 'cbti':ti,ab,kw
 OR 'cognitive behavioural therapy for insomnia':ti,ab,kw
 OR 'cognitive behavioral therapy for insomnia':ti,ab,kw
 OR 'actigraphy'/exp OR actigraph*:ti,ab,kw
 OR 'sleep wearable*':ti,ab,kw OR 'consumer sleep':ti,ab,kw OR 'sleep tracker':ti,ab,kw)
AND ([09-11-2026 to 16-11-2026]/pd OR [09-11-2026 to 16-11-2026]/sd)
AND ([adult]/lim OR [aged]/lim)
NOT ([animals]/lim NOT [humans]/lim)
```

Bruxism and painful erections:

```
('bruxism'/exp OR 'sleep bruxism'/exp OR bruxism:ti,ab,kw
 OR 'teeth grinding':ti,ab,kw OR 'tooth grinding':ti,ab,kw
 OR 'sleep-related painful erection*':ti,ab,kw OR 'sleep related painful erection*':ti,ab,kw
 OR 'painful nocturnal erection*':ti,ab,kw OR 'painful erections':ti,ab,kw OR srpe:ti,ab,kw)
AND ([09-11-2026 to 16-11-2026]/pd OR [09-11-2026 to 16-11-2026]/sd)
AND ([adult]/lim OR [aged]/lim)
NOT ([animals]/lim NOT [humans]/lim)
```

There is no Emtree heading in this string for sleep-related painful erections. That concept is free text only. The free-text token `srpe` will also match some session-RPE sports papers, as it did in PubMed. Confirm every `/exp` heading in Emtree before running.

### Ovid Embase

Ovid uses different punctuation. The date-delivered limit below is the usual day-level field (`dd`). Confirm the field name on the local Ovid Embase before running. A publication-date day limit is less consistent across Ovid sites, so date delivered is the paste-ready limit, and publication dates then need a manual check. `$` is Ovid truncation.

```
1 exp insomnia/ or insomnia.ti,ab,kf.
2 exp "sleep apnea syndrome"/ or exp "obstructive sleep apnea"/ or (sleep adj apn?ea).ti,ab,kf. or (obstructive adj sleep).ti,ab,kf. or (sleep adj disordered adj breathing).ti,ab,kf.
3 exp "circadian rhythm sleep disorder"/ or (circadian adj rhythm).ti,ab,kf.
4 exp narcolepsy/ or narcolepsy.ti,ab,kf. or cataplexy.ti,ab,kf.
5 exp hypersomnia/ or hypersomnia.ti,ab,kf. or hypersomnolence.ti,ab,kf.
6 exp "restless legs syndrome"/ or (restless adj legs).ti,ab,kf.
7 exp "periodic limb movement disorder"/ or (periodic adj limb adj movement).ti,ab,kf.
8 exp parasomnia/ or parasomnia$.ti,ab,kf. or (REM adj sleep adj behav$).ti,ab,kf.
9 (sleep adj (quality or duration or disorder or disturbance)).ti,ab,kf.
10 (CBT-I or CBTI).ti,ab,kf. or ((cognitive behavio$r$ therapy) adj3 insomnia).ti,ab,kf.
11 exp actigraphy/ or actigraph$.ti,ab,kf. or (sleep adj wearable$).ti,ab,kf. or (consumer adj sleep).ti,ab,kf. or (sleep adj tracker).ti,ab,kf.
12 or/1-11
13 limit 12 to (adult <18 to 64 years> or aged <65+ years>)
14 limit 13 to dd=20261109-20261116
15 limit 14 not (animal not human)
```

The age-limit wording in line 13 must be confirmed. Ovid’s menu text varies by site.

Bruxism and painful erections:

```
1 exp bruxism/ or exp "sleep bruxism"/ or bruxism.ti,ab,kf. or (teeth grinding or tooth grinding).ti,ab,kf.
2 (sleep-related painful erection$ or sleep related painful erection$ or painful nocturnal erection$ or painful erections or SRPE).ti,ab,kf.
3 1 or 2
4 limit 3 to (adult <18 to 64 years> or aged <65+ years>)
5 limit 4 to dd=20261109-20261116
```

### Scopus advanced search (TITLE-ABS-KEY)

Scopus does not offer PubMed’s day-level publication date in the same way. `ORIG-LOAD-DATE` is the date Scopus added the record. `AFT 20261108` and `BEF 20261117` together cover 9 to 16 November inclusive. This is not the publication date. Adult limits in Scopus depend on keywords and will miss untagged records.

```
TITLE-ABS-KEY(insomnia OR "sleep apnoea" OR "sleep apnea" OR "obstructive sleep" OR "sleep-disordered breathing" OR "sleep disordered breathing" OR narcolepsy OR cataplexy OR hypersomnia OR hypersomnolence OR "restless legs" OR "periodic limb movement" OR parasomnia* OR "circadian rhythm" OR "REM sleep behav*" OR "sleep quality" OR "sleep duration" OR "sleep disorder" OR "sleep disturbance" OR "CBT-I" OR CBTI OR "cognitive behavioural therapy for insomnia" OR "cognitive behavioral therapy for insomnia" OR actigraph* OR "sleep wearable*" OR "consumer sleep" OR "sleep tracker")
AND (ORIG-LOAD-DATE AFT 20261108 AND ORIG-LOAD-DATE BEF 20261117)
AND NOT TITLE-ABS-KEY(mouse OR mice OR murine OR rat OR rats OR zebrafish OR drosophila)
```

```
TITLE-ABS-KEY(bruxism OR "teeth grinding" OR "tooth grinding" OR "sleep-related painful erection*" OR "sleep related painful erection*" OR "painful nocturnal erection*" OR "painful erections" OR SRPE)
AND (ORIG-LOAD-DATE AFT 20261108 AND ORIG-LOAD-DATE BEF 20261117)
AND NOT TITLE-ABS-KEY(mouse OR mice OR murine OR rat OR rats OR zebrafish OR child OR children OR paediatric OR pediatric)
```

After either Scopus string, screen the titles. The animal and child words will miss some records and will occasionally remove an adult paper that only mentions them. The SRPE token will also retrieve some sports papers that report session RPE.

## In short

PubMed on 16 November 2026 was enough to fill the week without going back to 2 November. The largest practice signals were a fall of about 12 to 13 pauses per hour with orforglipron in two dedicated sleep-apnoea trials, a negative jaw-exercise trial in mild to moderate apnoea, a wide and uncertain average benefit from digital insomnia programmes, a short-term benefit of orexin-2 drugs in narcolepsy type 1 with a liver-injury warning for one molecule, and UK Biobank results on sleep length and on how stable a week of wrist data is. Restless legs had one uncontrolled series. Sleep-related painful erections had none. Embase and Scopus were not searched.
