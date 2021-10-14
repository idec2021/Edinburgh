# Lab notebooks


# Lab Notebook

## June 2021

21/6/21

Reagents for SeSam have arrived, but we still didn&#39;t get the parts from IDT, so we decided to proceed with experimenting the first steps of the SeSaM.

1. concentrations of dATPaS and different temperatures for the Iodine incubation, as suggested in wong et al. 2004 and Wong et al. 2008, were tested on two different genes:

**PCR**

- POX5 (1606 bp) - Pyruvate oxidase (fragment) - gene from _Lactobacillus plantarum_, from synthesised parts with the following PCR reagents

| 5X buffer | 10 |
| --- | --- |
| dNTPs | 1 |
| F | 5 |
| R | 5 |
| gotaq | 0.5 |
| template | 10 |
| dATPaS | \* |
| water | \* |
| **tot** | 50 |

\*dATPaS 10mM dilution and water remaining water added:

| **dATPaS/water** |
| --- |
| mM | ul | h20 |
| 0.05 | 2.5 | 16 |
| 0.1 | 5 | 13.5 |
| 0.15 | 7.5 | 11 |
| 0.2 | 10 | 8.5 |
| 0.25 | 12.5 | 6 |

- GshF (532 bp) - Bifunctional glutathione synthetase (fragment) - gene from _Streptococcus thermophilus_ from genomic DNA with the following PCR reagents

| 5X buffer | 10 |
| --- | --- |
| dNTPs | 1 |
| F | 5 |
| R | 5 |
| gotaq | 0.5 |
| template | 10 |
| dATPaS | \*\* |
| water | \*\* |
| **tot** | 50 |

\*\*dATPaS 10mM dilution and water remaining water added:

| **dATPaS/water** |
| --- |
| mM | ul | h20 |
| 0.05 | 2.5 | 26 |
| 0.1 | 5 | 23.5 |
| 0.15 | 7.5 | 21 |
| 0.2 | 10 | 18.5 |
| 0.25 | 12.5 | 16 |

**Iodo fragmentation**

incubations were run at 70 C or room temperature (RT) for 1 hour by adding Iodine to final concentrations of 2mM and 2uM iodine.

![](RackMultipart20211014-4-my4ruj_html_9bde1fa939d164e4.png)

POX5 results. In yellow the concentration of the dATPaS used, in white the Iodine concentrations.

RESULTS NOTES: the 2uM iodine concentration failed to produce a smear at both 70 degres and room temperature and in both genes. At the same time, the iodo fragmentation run at 70 degrees showed to be the best performing in both genes and at all concentrations of dATPaS

30/6/21

Received the parts from IDT. Hence, we test sesam on a recombinant keratinase rMtaKer from Meiothermus taiwanensis (~900bp)

| **reagent** | **ul** |
| --- | --- |
| Taq DNA polymerase | 0.5 |
| dNTP mix | 1 |
| dATPaS | 6.25 |
| forward primer | 2 |
| reverse primer | 2 |
| DNA | 4.1 |
| buffer | 10 |
| water | 24.15 |
| _tot_ | _50_ |

PCR product was directly purified with the MyOne Dynabeads 1C, but at the end of the process the amount of DNA extracted was lower than 1ng/ul, therefore we didn&#39; carry on with this batch.

possible causes:

- DNA concentration from PCR could be low
- some step in the dynabeads purification process following Wong et al 2004 protocol might be faulty and we might be loosing DNA at some point.

6/07/21

- Dynabeads protocol suggests to use a slightly different protocol from the one suggested by Wong et al 2004, so we decided to follow the first. Moreover, the Dynabeads instructions state to use purified DNA, while Wong et al. didn&#39; t specify it. We prepared a new batch of binding and washing buffer according to dynabeads&#39; manufacturer instruction and followed those (3 washing with 1x B&amp;W solution and 2 washing with NaOH)

- we carried out two PCR batch each (25 ul each)
- we tested each step in the dynabeads purification by nano-dropping the discarded fluid at each step to assess at what critical point we usually lose the most DNA.
- We split one PCR product (50 ul) into two 25 ul, purified one with the QiaQuick PCR purification kit and one kept raw and run the

results:

| **purified PCR** | **initial DNA** | **incubation loss** | **w1** | **w2** | **loss in NaOH** | **incub. loss** | **NaOH**** loss **|** SDS boiling **|** tot recovery: **|** %tot lost **|** concentration after QIAquick **|** final yield **|** QIAquick yields** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| _ng/ul_ | 148.6975 | 48.174 | \&lt;0 | \&lt;0 | 33.86 ||| 15.1 ||| 3.25 |||| _quantity__ul_ | 25 | 50 ||| 25 ||| 25 ||| 30 |||
| _**tot (ng)**_ | 3717.4375 | 2408.7 ||| 846.5 | 64.8% | 22.8% | 377.5 | 10.15% | 87.57% | 97.5 | 2.6% | 25.8% |
| **non-purified PCR** ||||||||||||||
| _mean:_ | 148.6975 | 60.43 | \&lt;0 | \&lt;0 | 24.12 ||| 9.06 ||| 1.73 |||| _quantity ~ ul_ | 25 | 50 ||| 25 ||| 25 ||| 30 |||
| _**tot (ng)**_ | 3717.4375 | 3021.5 ||| 603 | 81.3% | 16.2% | 226.5 | 6.09% | 97.50% | 51.9 | 1.4% | 22.9% |

Trouble-shooting

After confrontation with supervisors and other researchers, we decided to test a few more things. Moreover, the QIAquick nucleotide removal kit has shown to be less efficient than forecasted (~25% yield only instead of about 50%).

- we ordered a new kit: Monarch®PCR &amp; DNA Cleanup Kit (NEB) as QIAquick was clearly responsible for a great loss of DNA along the process, never going above ~25%

- We began a new cycle of SeSaM from the beginning. using the same PCR protocol as before, but increasing the number of cycles to 45 to increase DNA yield.

First, we purified the primers lest they could contain traces of freebiotin that would saturate the beads. PCR product and Iodine fragmentation were performed as previous experiments.

then we pset a new experiment with 4 different tubes for PCR:

1. PCR with biotinylated-purified-forward-primers
2. PCR with beads coated in purified forward primers
3. PCR with biotinylated-reverse-primers (non-purified)
4. PCR with normal Primers

The third would be the control for full length genes, to gain knowledge about how much the fragmentation impacts the QIAquick and dynabeads extraction, while the forth was a negative control to see if the purification would impact the results. 100 ul each

9/7/21

- primer purification performed.

diluted biotinylated forward primers (BFP) and biotinylated ul of stock Primers were diluted to 10mM (1:10) to a final volume of 100 ul, then purified with the QIAquick nucleotide removal.

efficiency prooved to be low once again

before QIAquick:

Forward: 43.71 ng/ul \*100 ul =4371 ng

reverse: 42.44 ng/ul \*100 ul =4244 ng

after QIAquick:

Foerward: 27 ng/ul \*30ul = 810 ng

reverse: 36 ng/ul \* 30ul = 1080 ng

18 and 25% recovery rate respectively.

12/07/21

- 200 ul beads used for PCR number 2 and incubated with 20.5 ul of purified BFP (80 pmol tot) at Room temperature for 1.30 hours
- The four PCR reactions were then set up over night with the previous reported protocol, except for an increase number of cycles of for a total of 45. The PCR reaction made with the forward-primer-coated-beads, was not added of the forward primers and their volume in water was added to compensate the lack.

14/7/21

The three reactions with the forward biotinylated primers were incubated with Iodine (as previously indicated) and then purified with dynabeads (PCr with coated dynabeads skipped the incubation step)

The incubation and the NaOH discarded liquids were collected and nanodropped (data reported in table). Then, concentrations were measured after the collection from the dynabeads and after the purification with the QIAquick.

|| inc. | NaOH | SDS water | total after beads+qiagen | elongation+ qiagen || ||||
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RB (ng/ul) | 64.82 | 27.61 | 27 | 46.5 ||||||||
|| 62.87 | 28.1 | 25.18 | 47.82 |||||||| | 65.18 | 29.69 | 29.5 | 56.79 |||||||||||||||||||
| average(ng/ul): | 64.29 | 28.46666667 | 27.22666667 | 50.37 |||||||
| Volume(ul): | 400 | 200 | 200 | 30 ||| QIAgen yields | total yeild | loss in dynabeads: | total initial DNA |
| tot: | 25716 | 5693.333333 | 5445.333333 | 1511.1 ||
 || 27.75% | 4.10% | 85.22% | 36854.66667 |
| Beads ourified | 76.04 | 11.32 | 16.48 | 13.96 | 19.75 |||||||| 72.59 | 9.55 | 14.73 | 15.94 | 18.03 |||||||
|| 72.24 | 11.3 | 14.35 | 16.77 | 18.82 |||||||| 350 ||||||||||| average: | 73.62333333 | 10.72333333 | 15.18666667 | 15.55666667 | 18.86666667 ||||||
| Volume(ul): | 400 | 200 | 200 | 30 | 30 || QIAgen yields | total yeild | loss in dynabeads: | total initial DNA || tot: | 29449.33333 | 2144.666667 | 3037.333333 | 46.7 | 566 || 15.37% | 1.35% | 91.23% | 34631.33333 |
| pcr with beads | 263.3 | 5.83 | 7.74 | 9.64 | 13.96 |||||||| 260.8 | 6.18 | 8.3 | 4.49 | 12.94 |||||||| 27.9 | 4.14 | 7.64 | 4.79 | 12.53 ||||||||||||||||
| average: | 26.6666667 | 5.383333333 | 7.893333333 | 6.306666667 | 13.14333333 ||||||| Volume(ul): | 400 | 200 | 200 | 30 | 30 || QIAgen yields | total yeild | loss in dynabeads: | total initial DNA |
| tot: | 106666.6667 | 1076.666667 | 1578.666667 | 189.2 | 394.3 || 11.98% | 0.17% | 98.56% | 109322 |
| Old forwards | 11.4 | 7.07 | 13.8 | 11.3 | 17.27 |||||||| 116.6 | 10.42 | 13.65 | 10.16 | 17.85 |||||||| 120.1 | 9.8 | 13.44 | 10.51 | 17.82 ||||||||||||||||||| average: | 117.3666667 | 9.096666667 | 13.63 | 10.65666667 | 17.64666667 ||||||| Volume(ul): | 400 | 200 | 200 | 30 | 30 || QIAgen yields | total yeild | loss in dynabeads: | total initial DNA || tot: | 46946.66667 | 1819.333333 | 2726 | 319.7 | 529.4 || 11.73% | 0.62% | 94.71% | 51492 |

15/07/21

- Terminal transferase step was performed as follow:

| **Term Trans protocol** | ul |
| --- | :---: |
| term trans buffer | 5 |
| CoCl2 of 2.5 mM stock | 5 |
| DNA fragments | 27 |
| dITP of 10 mM stock | 2 |
| Term trans (20 U/ul) | 0.5 |
| water | 10.5 |

Then, the full-length elongation was performed as follow:

| **Taq** DNA polymerase | 0.5 |
| --- | :---: |
| dNTP mix | 1 |
| reverse primer Mtaker (no biotin) | 2 |
| 10x buffer | 5 |
| Forward template | 27 |
| Reverse template: 60 ng | 1.6 |
| water | 12.4 |
| _tot_ | _50_ |

with program:

| **temperature** | **time** |
| --- | :---: |
| 95 | 2` |
| 95 | 30` |
| 57 | 1` |
| 68 | 1` |
| 68 | 10` |

core steps for 45 cycles

16/07/21

- 60 ng of the pcr product (purified) from the previous step (previous day) were used for the final PCR.

Finally, an agarose gel was prepared and run but the results clearly showed something went wrong. THe lack of controls in between the steps after the Dynabeads extraction didn&#39;t make it possible to find the source of the Issues.

![](RackMultipart20211014-4-my4ruj_html_1404b5fe449d4458.png)

15ul of the last PCR result were run on a 2% agarose gel, water as negative control (which did not work) and gBlock part as positive control.

