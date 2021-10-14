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

<img width = "600" src="https://user-images.githubusercontent.com/92064762/137409005-22556bda-7cd3-4fa6-b37f-13880a37f602.png">

POX5 results. In yellow the concentration of the dATPaS used, in white the Iodine concentrations.

RESULTS NOTES: the 2uM iodine concentration failed to produce a smear at both 70 degres and room temperature and in both genes. At the same time, the iodo fragmentation run at 70 degrees showed to be the best performing in both genes and at all concentrations of dATPaS
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
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
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
## July 2021

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
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
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
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
12/07/21

- 200 ul beads used for PCR number 2 and incubated with 20.5 ul of purified BFP (80 pmol tot) at Room temperature for 1.30 hours
- The four PCR reactions were then set up over night with the previous reported protocol, except for an increase number of cycles of for a total of 45. The PCR reaction made with the forward-primer-coated-beads, was not added of the forward primers and their volume in water was added to compensate the lack.
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
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
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
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
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />
16/07/21

- 60 ng of the pcr product (purified) from the previous step (previous day) were used for the final PCR.

Finally, an agarose gel was prepared and run but the results clearly showed something went wrong. THe lack of controls in between the steps after the Dynabeads extraction didn&#39;t make it possible to find the source of the Issues.

<img width = "400" src="https://user-images.githubusercontent.com/92064762/137409319-218105dd-1df5-4f02-87c6-344ca3972d8b.png">
15ul of the last PCR result were run on a 2% agarose gel, water as negative control (which did not work) and gBlock part as positive control.
<br>
<hr style="height:1.5px;border:none;color:#808080;background-color:#808080;" />

26/07/2021

1. Resuspended primers to create 100 uM stock solution of mutagenic primers. Created another stock of 1 uM primers for asymmetric PCR.

|| Final concentration |
| --- | :---: |
| Q5 reaction buffer | 1X |
| dNTP mix | 0.2 mM |
| Mutagenic forward primers | 25 nM |
| Reverse primer | 0.5 uM |
| pJUMP19\_Cex | 200 ng |
| Q5 high fidelity DNA polymerase | 1 unit |
| DIW | Total 50 uL |

With thermocycler at the following thermocycler conditions:

|| Temperature | Time | Cycle |
| --- | --- | --- | --- |
| Initial denaturation | 98°C | 2 min | 1 |
| Denaturation | 98°C | 30 sec | 25 |
| Annealing | 60°C | 20 sec ||
| Extension | 72°C | 40 sec ||
| Hold | 4°C | ∞ ||

Set up asymmetric reactions following protocol, where each reaction represented a group of primers as follows:

| **B40** | **B80** | **S170** | **B200** | **B230** | **B280** | **S280** |
| --- | --- | --- | --- | --- | --- | --- |
| E43 | G79 | N196 | F202 | T232 | S280 | P283 |
| N44 | T81 | D170 | S204 | L234 | V282 | D284 |
| M46 | V83 | Y171 | L206 | D235 || V295 |
| W48 | H85 ||||| F286 ||| S86 ||||||

The final concentration of every mutagenic primer is 25 nM.

1. Run on 1% agarose gel with 1kb NEB ladder. 2 ul of PCR product mixed with 8 ul water and 2 ul 6x loading dye.

![](RackMultipart20211014-4-1lr09cy_html_ac41e50b7d5c3fe9.png)

PCR product purified with QIAgen PCR clean up kit eluting in 30 ul water and DNA quantified with Jenway Nanodrop.

### 27/09/2021

1. Megaprimer DNA used for following PCR as follows:

|| Final concentration |
| --- | :---: |
| Q5 reaction buffer | 1X |
| dNTP mix | 0.2 mM |
| Forward primer | 0.5 uM |
| Mutagenic reverse megaprimer | 0.05 uM |
| pJUMP19_Cex | 0.5 ng |
| Q5 high fidelity DNA polymerase | 1 unit |
| DIW | Total 50 uL |

At thermocycler conditions:

|| Temperature | Time | Cycle |
| --- | --- | --- | --- |
| Initial denaturation | 98°C | 2 min | 1 |
| Denaturation | 98°C | 30 sec | 25 |
| Annealing | 60°C | 20 sec ||
| Extension | 72°C | 40 sec ||
| Hold | 4°C | ∞ ||

1. PCR product was then digested with DpnI to remove template DNA from gel.

|| Final content in the reaction |
| --- | :---: |
| PCR product | 50 uL |
| DpnI | 20 U/uL |
| 2.1 Buffer | 1X |
| DIW | Total volume 100 uL |

1. Digest loaded on gel for extraction at full-length:

![](RackMultipart20211014-4-1lr09cy_html_bc5438b7e7e3a19d.png)

1. Gel extracted with QIAgen gel extraction kit.

| Group | Gel weight | Dissolve buffer volume |
| --- | :---: | :---: |
| B40 | 0.142 | 0.426 |
| B80 | 0.144 | 0.432 |
| S170 | 0.243 | 0.729 |
| B200 | 0.164 | 0.492 |
| B230 | 0.233 | 0.699 |
| B280 | 0.315 | 0.945 |
| S280 | 0.39 | 1.17 |

1. Set O/N JUMP assembly using long conditions.

|| ug/ml | fmol/ul | **ul for 20fmol** | **Vol to add** | **fmoles** | Water to add |
| --- | --- | --- | --- | --- | --- | --- |
| **pJUMP18-Uac** | **211.53** | **98.32** | 0.20\* | **0.81** | **20.000** ||
| 1 | 9.96 | **11.80** | 3.39 | 3.39 | **40.000** | 12.55 |
| 2 | 7.20 | **8.53** | 4.69 | 4.69 | **40.000** | 11.25 |
| 3 | 10.86 | **12.86** | 3.11 | 3.11 | **40.000** | 12.83 |
| 4 | 15.18 | **17.97** | 2.23 | 2.23 | **40.000** | 13.71 |
| 5 | 6.04 | **7.15** | 5.59 | 5.59 | **40.000** | 10.35 |
| 6 | 8.35 | **9.88** | 4.05 | 4.05 | **40.000** | 11.89 |
| 7 | 5.34 | **6.32** | 6.33 | 6.33 | **40.000** | 9.61 |
| (+) control | 8.94 | **10.58** | 3.78 | 3.78 | **40.000** | 12.16 |

\* 1 in 4 dilution.

### 28/07/2021

1. Transformation of assembly reaction into DH5a using transformation protocol.

### 29/07/2021

1. Plate 50 ul on Amp/IPTG LB agar plate.

1. Miniprep and store rest for further assembly of library into Level 1 vectors.

### 30/07/2021

1. Three colonies picked from B200 plate and grown O/N in 5 ml LB with 5 ul Kanamycin.

### 31/07/2021

1. O/N cultures miniprepped and sent for sequencing at Dundee Sequencing.

## September 2021

### 6/09/2021

1. Prepare 0.1 MgCl2 and 0.1 M CaCl2 for competent cells
2. Prepare 50 mg/mL Kanamycin
3. Prepare LB/agar plates: (-), carb, kan
4. Inoculate DH5a with level 0 parts

- pJUMP19 – T7 pro\_P
- pJUMP18 – B0034-MV\_RN
- pJUMP19 – L1U1H08\_CT

1. Nanodrop of OR library (Level 0)

| Sample | ng/uL |
| --- | :---: |
| pJUMP18\_B40 | 495.1 |
| pJUMP18\_B200 | 423.8 |
| pJUMP18\_B230 | 604.1 |
| pJUMP18\_B280 | 555.7 |
| pJUMP18\_S280 | 281.4 |

### 7/09/2021

1. Plasmid prep of Level 0 parts
2. Prepare 60% glycerol
3. Inoculate _E. coli_ BL21 (DE3) and _E. coli_ (DH5a)
4. Streak Level 0 cells on LB/agar plates
5. JUMP assembly of OR library

| Part | ng/uL | bp | fmol/uL | uL plasmid | uL DIW |
| --- | :---: | :---: | :---: | :---: | :---: |
| pJUMP29-1A | 348.15 | 3815 | 138.27 | 2 | 13 |
| pJUMP19 – T7 pro\_P | 157.79 | 3897 | 61.35 | 5 | 10 |
| pJUMP18 – B0034-MV\_RN | 453.56 | 2667 | 257.67 | 1.5 | 13.5 |
| pJUMP19\_Cex | 509.14 | 3968 | 194.41 | 1.5 | 13.5 |
| pJUMP18\_B40 | 495.1 | 3968 | 189.05 | 2 | 13 |
| pJUMP18\_B200 | 423.8 | 3968 | 161.82 | 2 | 13 |
| pJUMP18\_B230 | 604.1 | 3968 | 230.67 | 2 | 13 |
| pJUMP18\_B280 | 555.7 | 3968 | 212.29 | 2 | 13 |
| pJUMP18\_S280 | 281.4 | 3968 | 107.45 | 3 | 12 |
| pJUMP19 – L1U1H08\_CT | 130.7 | 3979 | 49.77 | 6 | 9 |

Total volume 20 uL per reaction

Add 1 uL of each part + 2 uL T4 ligase buffer + 1 uL BasI-HF V2 + 0.25 uL T4 ligase

### 8/09/2021

1. Make competent cells following the protocol

- 200 mL of DH5a and 300 mL of BL21(DE3)
- Inoculate 1% and check OD600 after 1 hour
  - DH5a 0.501
  - BL21(DE3) 0.902
- Make 40 tubes of DH5a, 60 tubes of BL21(DE3)

1. Prepare B&amp;W buffer for Dynabeads

|| Stock concentration | Final concentration | uL |
| --- | :---: | :---: | :---: |
| Tris-HCl pH 8.0 | 1 M | 10 mM | 800 |
| EDTA pH 8.0 | 0.5 M | 1 mM | 160 |
| NaCl || 2 M | 9.35 g |

1. PCR Cex without dATPaS for sonication and reverse biotinylated

PCR for Forward biotinylated DNA without dATPaS for sonication

|| Final concentration | uL in 1 reaction | uL in 8 reactions |
| --- | :---: | :---: | :---: |
| 5x GoTaq buffer | 1X | 10 | 80 |
| 10 mM dNTP mix | 0.2 mM | 1 | 8 |
| 10 uM 5&#39; B-F primer | 12.6 pmol | 1.26 | 10.08 |
| 10 uM R-primer | 12.6 pmol | 1.26 | 10.08 |
| pJUMP19\_Cex | 250 ng | 1 | 8 |
| GoTaq polymerase | 2.5 unit | 0.5 | 4 |
| DIW | Total 50 uL | 34.98 | 279.84 |

PCR ofr Reverse biotinylated DNA

|| Final concentration | uL in 1 reaction | uL in 8 reactions |
| --- | :---: | :---: | :---: |
| 5x GoTaq buffer | 1X | 10 | 80 |
| 10 mM dNTP mix | 0.2 mM | 1 | 8 |
| 10 uM 5&#39; B-F primer | 12.6 pmol | 1.26 | 10.08 |
| 10 uM R-primer | 12.6 pmol | 1.26 | 10.08 |
| pJUMP19\_Cex | 250 ng | 1 | 8 |
| GoTaq polymerase | 2.5 unit | 0.5 | 4 |
| DIW | Total 50 uL | 34.98 | 279.84 |

PCR condition:

| Initial denaturation | 95°C | 2 min ||
| --- | :---: | :---: | :---: |
| Denaturation | 95°C | 1 min | 30 cycles |
| Annealing | 58°C | 1 min |
| Extension | 72°C | 1 min 40 sec |
| Final extension | 72°C | 10 min ||
| Hold | 4°C | ∞ ||

1. 1% agarose gel, 5 uL ladder, 2 uL PCR products

(left FB w/o dATPaS, right RB)

![](RackMultipart20211014-4-1lr09cy_html_cf2c15c5f6ad864a.gif)

1. Purify PCR product – QIAGEN kit
2. Prepare 0.5 M EDTA 500 mL pH 8.0

### 9/09/2021

1. Set PCR to calibrate dATPaS for Cex gene

|| Mastermix (x6) | 0.5 mM | 0.3 mM | 0.2 mM | 0.1 mM | 0.05 mM |
| --- | --- | --- | --- | --- | --- | --- |
| 5X GoTaq buffer | 60 ||||||
| dNTP mix | 6 ||||||
| dATPaS || 25 | 15 | 10 | 5 | 2.5 |
| 5&#39; B-F primer | 7.56 ||||||
| R primer | 7.56 ||||||
| pJUMP19\_Cex | 6 ||||||
| GoTaq pol || 0.5 | 0.5 | 0.5 | 0.5 | 0.5 |
| DIW || 9.98 | 19.98 | 24.98 | 29.98 | 32.48 |
|| 14.52 uL/ Rx ||||||

PCR conditions follow the protocol

1. Sonicate DNA (first attempt)

DNA conc should be 1-20 ng/uL : recommended = 10 ng/uL

Quality A260/A280 should be 1.8 – 2.0

From Bioruptor pico protocol: DNA sonicated at amplitude 20%

![](RackMultipart20211014-4-1lr09cy_html_20e026c173231afc.png)

Aim for 400 bp : sonicate pulse on 15, off 59

Nanodrop FB purified PCR product : 315.1 ng/uL, A260/A280: 1.87

Prepare 9 tubes of 10 ng/uL, 500 uL DNA

Shear DNA varying cycles of sonication 0-8 cycles

1. Run 1% agarose gel of sonicated DNA

Use 5 uL ladder, 10 uL sample + 2 uL loading Dye

![](RackMultipart20211014-4-1lr09cy_html_9236f77cf9b19326.gif)

### 10/09/2021

1. Run 1% agarose gel of iodofragmented DNA

Left-right: 0, 0.5, 0.3, 0.2, 0.1, 0.05 mM dATPaS

2 uL sample, 10 uL 1 kb ladder

![](RackMultipart20211014-4-1lr09cy_html_1c61ca0ec406894a.gif)

1. Run 2% agarose gel of sonicated DNA (same sample, repeat with higher percentage gel)

100 bp ladder (Promega)

![](RackMultipart20211014-4-1lr09cy_html_aa25dc871d6ff977.gif)

1. Try screening method using azo-xylan

Use E.coli BL21(DE3) with Lv.1 Cex on LB agar +Kan+ IPTG plate

Soak filter paper with 0.1 azo-xylan

Put the filter paper on top of colony incubate 37°C leave for 6 hours

1. PCR the FB Cex with dATPaS : follow the protocol
2. Fragment FB PCR product : follow iodofragmentation protocol

1. Sonicate the rest of FB Cex (without dATPaS) – try large batch of DNA

- For 500 uL sonicate amp 20%, on 15 sec, off 59 sec, 8 cycle (equal to 2 minutes)
- For 5 mL : in 15 mL tube, try from 2 min up until enough fragmentation can be seen on gel (2% agarose in TAE, 135V, 20 min)
- Left: 500 uL, Right: 5 mL – 2 min

![](RackMultipart20211014-4-1lr09cy_html_72e654bdfe8fb3ee.gif)

- Left: 500 uL, 2 min, Right: 5 mL, 12 min (10 min longer)

![](RackMultipart20211014-4-1lr09cy_html_28a04dd18a22d018.gif)

- Left: 500 uL, 2 min, Right: 5 mL, 22 min (10 min longer)

![](RackMultipart20211014-4-1lr09cy_html_29e39d300b1d4a0b.gif)

- Left – Right: 2 uL PCR product, 5 uL 100 bp ladder, 20 uL of 500 uL DNA 8 cycles (spin down half way), 20 uL of 500 uL DNA 8 cycles straight, 20 uL of 5 mL DNA 27 min sonication

![](RackMultipart20211014-4-1lr09cy_html_71383b5174fbf712.gif)

### 13/09/2021

1. Azo-xylan screening – nothing happens (leave in 37°C leave for 2 days)
2. SeSaM – optimize the original protocol (see our team protocol)

- PCR FB Cex with dATPaS and fragment DNA with iodine (8 reactions)
- QIAGEN purification (8 reactions)
- Nanodrop: FB 87.4 ng/uL, RB 154.8 ng/uL
- Dynabeads: follow the protocol (use 4 reactions into 2 tubes)
- Keep the washing solution from each step of Dynabeads to investigate DNA lost
- Nanodrop

| DNA | Fraction | Conc. ng/uL | Blank |
| --- | :---: | :---: | :---: |
| FB Cex | Unbound DNA | 21.3 | 1X B&amp;W |
|| Wash 1 | 0.4 | 1X B&amp;W |
|| Wash 2 | 0.4 | 1X B&amp;W |
|| NaOH 1 | 38.5 | 0.1 M NaOH |
|| NaOH 2 | -2.4 | 0.1 M NaOH |
|| Wash 3 | 0.1 | 1X B&amp;W |
| RB Cex | Unbound | 29.9 | 1X B&amp;W |
|| Wash 1 | 0.7 | 1X B&amp;W |
|| Wash 2 | 0.4 | 1X B&amp;W |
|| NaOH 1 | 57.9 | 0.1 M NaOH |
|| NaOH 2 | 2.4 | 0.1 M NaOH |
|| Wash 3 | 0.2 | 1X B&amp;W |

- Elute ssDNA from Dynabeads (50 uL / tube – 2 RB, 2 FB)
- Nanodrop: FB Cex 28.1 ng/uL, RB Cex 73.4 ng/uL
- Purify ssDNA: elute with DIW FB 20 uL, RB 30 uL
- Try second elution with 10 uL for both DNA
- Nanodrop

| DNA | Fraction | Conc. ng/uL |
| --- | :---: | :---: |
| FB Cex | Unbound DNA | 21.3 |
|| Wash 1 | 0.4 |
| RB Cex | Unbound | 29.9 |
|| Wash 1 | 0.7 |

- Terminal transferase : follow the protocol (use 12 uL of ssDNA)
- Purify DNA and nanodrop : Elute1 25.8 ng/uL, Elute2 9.6 ng/uL
- Full-length synthesis : follow the protocol except, use 464.4 ng of FB DNA
- PCR condition deviate from protocol (follow maufacturer&#39;s)

|| Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 95°C | 30 sec | 1 |
| Denaturation | 95°C | 30 sec | 30 |
| Annealing | 52.7°C | 1 min ||
| Extension | 68°C | 1 min 30 sec ||
| Final extension | 68°C | 5 min | 1 |
| Hold | 4°C | ∞ ||

### 14/09/2021

1. Purify Full-length DNA, use Monarch kit, Elute with DIW 20 uL, do second elution using 10 uL
2. Nanodrop full-length gene: Elute1 250.7 ng/uL, Elute2 33.4 ng/uL
3. Universal base replacement use component following the protocol except DMSO, PCR condition follow the protocol (cond.1) and as follow (cond.2):

|| Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 95°C | 30 sec | 1 |
| Denaturation | 95°C | 30 sec | 30 |
| Annealing | 52.7°C | 1 min ||
| Extension | 68°C | 1 min 30 sec ||
| Final extension | 68°C | 5 min | 1 |
| Hold | 4°C | ∞ ||

4. Run agarose gel of PCR product

Left-right: 2 uL PCR product (from step1), 5 uL 100 bp ladder, Condition1, Condition2

![](RackMultipart20211014-4-1lr09cy_html_9703a3741e03495d.gif)

1. Run 2% agarose gel to investigate DNA recovery in each step of SeSaM

_(__1-9) Forward-biotinylated DNA (1) First PCR product, (2) After iodofagmentation, (3) After QIAquick nucleotide clean-up, (4) Excess DNA unbound to the Dynabead, (5) NaOH melting from the Dynabead, (6) Eluted DNA in 0.1% SDS, (7) First ssDNA purification with Monarch PCR product &amp; DNA purification kit, (8) ssDNA purification after terminal transferase reaction, (9) DNA purified after the full-length gene synthesis. (10-15) Reverse biotinylated DNA (10) First PCR product, (11) After QIAquick nucleotide clean-up, (12) Excess DNA unbound to the Dynabead, (13) NaOH melting from the Dynabead, (14) Eluted DNA in 0.1% SDS, (15) ssDNA purification with Monarch PCR product &amp; DNA purification kit_

![](RackMultipart20211014-4-1lr09cy_html_b73c1c45cdf781e.png)

1. Prepare 3M Na-Acetate pH5.2, 500 mL
2. Precipitate sonicated DNA following the protocol, in parallel concentrate DNA with QIAGEN kit – compare
3. Run 2% agarose gel of concentrated DNA

Left-right: 2.5 uL 100 bp ladder, QIAGEN tube1,2, EtOH Precipitation 1,2

![](RackMultipart20211014-4-1lr09cy_html_dcf28f404033600c.gif)

### 15/09/2021

1. Repeat last PCR again with DMSO (follow the protocol), also do control (use pJUMP19\_Cex as template), Do 2 PCR condition like last time
2. Run 2% agarose gel

Left-right( 2 uL in all wells): PCR product from step1, 100 bp ladder, control-cond1, last PCR-cond1, control-cond2, last PCR-cond2

Control looks better using condition 1, thus only do condition1

![](RackMultipart20211014-4-1lr09cy_html_550c987f6b079093.gif)

1. Do PCR again with diluted template: follow the protocol except use 1 ng full-length DNA
2. Run 2% agarose gel to check the PCR product

Left-Right: 2 uL PCR from step1, 5 uL DNA ladder, 2 uL control, 2 uL last PCR

![](RackMultipart20211014-4-1lr09cy_html_804ab22c4e40ca0.gif)

1. Desalt full-length DNA following the protocol
2. Do last PCR again using the desalted DNA: follow the protocol, except use 10 ng and 20 ng template
3. Try azo-xylan screening: follow the protocol (but did not sterile the solution and leave incubated O/N)

### 16/09/2021

1. Run 2% agarose gel of the last PCR (desalted DNA)

Left-Right: 5 uL 100 bp DNA ladder, 2 uL control, 2 uL 10 ng template, 20 ng template

![](RackMultipart20211014-4-1lr09cy_html_df77a7b5af0c6802.gif)

1. Used up all full-length DNA: do Dynabeads again (follow the protocol), Use the concentrated, sonicated DNA in parallel \&gt; do SeSaM up to the full-length synthesis
2. Image the screening plates

![](RackMultipart20211014-4-1lr09cy_html_94763361937d4348.gif)

### 17/09/2021

1. Purify full-length DNA and nanodrop:

Sonicted DNA: 113.8 ng/uL, dATPaS DNA: 225.0 ng/uL

1. Do last PCR following the protocol, but varu DNA template 1, 30, and 60 ng. Use both sonicated DNA and dATPaS DNA
2. Run 2% agarose gel

![](RackMultipart20211014-4-1lr09cy_html_9ef483f1d7b9b4a.png)

1. Prepare azo-xylan screeing solution following the protocol

### 20/09/2021

1. Try MUX and MUC screening : replace the azo-xylan screeni g solution with 0.1 mM MUX or MUC, visualize after 6 hours

![](RackMultipart20211014-4-1lr09cy_html_72ab93c3be84e70b.gif) ![](RackMultipart20211014-4-1lr09cy_html_985c4ec5ba75adcc.gif)

1. JUMP assembly of SeSaM library (sonicated DNA) : do Level 1 assembly (use short cycle protocol)
2. Transform assembly to E.coli BL21(DE3)

### 21/09/2021

1. Did not obtain many white colonies fro the assembly
2. JUMP assembly of SeSaM library (sonicated DNA) : do Level 1 assembly (long cycle)
3. JUMP assembly of OR library
4. Do last PCRof SeSaM using the full-length gene of sonicated DNA again

### 22/09/2021

1. Gel purification of PCR product from SeSaM of the sonicated DNA
2. Do Level 0 assembly of SeSaM library

### 23/09/2021

1. Colony PCR of white colonies obtained from the Level 0 assembly
2. Run 1% agarose gel to check the PCR result

![](RackMultipart20211014-4-1lr09cy_html_62565acbd7616460.gif)

1. Inoculate all positive colonies

### 24/092021

1. Plasmid extraction of 24 clones
2. Run 1% agarose gel compare with wild type

![](RackMultipart20211014-4-1lr09cy_html_9a2d1c54ea5eb2c3.gif)

1. Send 23 plasmids for sequencing

### 29/09/2021

1. Do Cex screening with azo-xylan: incubate for 6 hours, follow the protocol

1. Try the BmtI digestion to enhance the assembly (follow the protocol)

### 30/09/2021

1. Image the screening plates

![](RackMultipart20211014-4-1lr09cy_html_9e8fc95af6821bad.png)

1. The BmtI digestion result in significantly reducing green colonies

