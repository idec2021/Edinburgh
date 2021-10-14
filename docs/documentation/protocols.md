# **Protocols**
<hr style="height:3px;border:none;color:#808080;background-color:#808080;" />

## **SeSaM Protocols**
<hr style="height:1px;border:none;color:#808080;background-color:#808080;" />

*Click on the flow chart to view the protocol*

<html>

<script src="https://cdn.rawgit.com/knsv/mermaid/6.0.0/dist/mermaid.min.js"></script>
<link href="https://cdn.rawgit.com/knsv/mermaid/6.0.0/dist/mermaid.css" rel="stylesheet" />

<div class='mermaid'>
  graph TD; 
  A[<b>Cex DNA Template</b>] -->|FB Generation| B(dATPaS Calibration);
  A -->|Modified FB Generation| C(Biotinylated DNA Generation);
  B --> E(Biotinylated DNA Generation);
  E --> F(Iodofragmentation);
  C --> G(DNA Shearing and Recovery);
  A -->|RB Generation| D(Biotinylated DNA Generation);
  F --> H(Biotinylated DNA Isolation);
  G --> H;
  D --> H;
  H --> |Forward strand DNA| I(Universal Base Addition);
  H --> |Reverse strand DNA| J(Full-length Gene Synthesis);
  I --> J;
  J --> K(<b>Universal Base Replacement</b>);

  click B "#B" "View Protocol";
  click C "#CDE" "View Protocol";
  click D "#CDE" "View Protocol";
  click E "#CDE" "View Protocol";
  click F "#F" "View Protocol";
  click G "#G" "View Protocol";
  click H "#H" "View Protocol";
  click I "#I" "View Protocol";
  click J "#J" "View Protocol";
  click K "#K" "View Protocol";

  style A fill: #FFEBCD
  style B fill: #FFC0CB
  style C fill: #C6E8F5
  style D fill: #C6E8F5
  style E fill: #C6E8F5
  style F fill: #FCD8A4
  style G fill: #E0C6EF
  style H fill: #C1FD9F
  style I fill: #FFD5B9
  style J fill: #FFB9DF
  style K fill: #F5F5F5
</div>

</html>


<br>
### **dATPαS Calibration for Cex and Iodine Fragmentation** ### {#B}

1. Set up a PCR with the component listed in the table below

|| Final concentration | uL in 1 reaction |
| --- | :---: | :---: |
| 5x GoTaq buffer | 1X | 10 |
| 10 mM dNTP mix | 0.2 mM | 1 |
| 1 mM dATPaS | 0.05-0.5 | 2.5 - 25 |
| 10 uM 5&#39; biotinylated forward primer | 12.6 pmol | 1.26 |
| 10 uM Reverse primer | 12.6 pmol | 1.26 |
| pJUMP19\_Cex | 250 ng ||
| GoTaq polymerase | 2.5 unit | 0.5 |
| DIW | Total 50 uL ||

2. Set the thermal cycler following:

| | Temperature | Time | Cycle |
| --- | --- | --- | --- |
| Initial denaturation | 95°C | 2 min | 1 |
| Denaturation | 95°C | 1 min | 30 |
| Annealing | 58°C | 1 min ||
| Extension | 72°C | 1 min 40 sec (1 min/kb) ||
| Final extension | 72°C | 10 min | 1 |
| Hold | 4°C | ∞ ||

3.  After PCR, add 2 uL of 50 mM Iodine prepared in 100% ethanol to a 50-uL PCR
5. Incubate the reaction at 70°C for 1 hour
6. Run samples on agarose gel to analyse the fragmentation
<br>

### **Biotinylated DNA Generation** ### {#CDE}

1. Set up a PCR reaction with the component listed in the table below

|| Final concentration | uL in 1 reaction |
| --- | :---: | :---: |
| 5x GoTaq buffer | 1X | 10 |
| 10 mM dNTP mix | 0.2 mM | 1 |
| 1 mM dATPaS\* | 0.1 mM | 5 |
| 10 uM Forward primer\*\* | 12.6 pmol | 1.26 |
| 10 uM Reverse primer\*\* | 12.6 pmol | 1.26 |
| pJUMP19\_Cex | 250 ng ||
| GoTaq polymerase | 2.5 unit | 0.5 |
| DIW | Total 50 uL ||

\*Only add dATPaS when generating the biotinylated forward strand to be used regarding the original SeSaM protocol
\*\*Use 5&#39;-biotinylated forward primer with non-biotinylated reverse primer for the biotinylated forward strand and use 5&#39;-biotinylated reverse primer with non-biotinylated forward primer for the biotinylated reverse strand.

2. Set the thermal cycler according to the condition suggested below

| | Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 95°C | 2 min | 1 |
| Denaturation | 95°C | 1 min | 30 |
| Annealing | 58°C | 1 min ||
| Extension | 72°C | 1 min 40 sec (1 min/kb) ||
| Final extension | 72°C | 10 min | 1 |
| Hold | 4°C | ∞ ||

<br>
### **Iodofragmentation** ### {#F}

1. Prepare 50 mM Iodine in 100% ethanol
2. Fragment the biotinylated forward strand by adding 2 uL iodione to 50-uL reaction
3. Incubate at 70°C for 1 hour
4. Purify the fragmented PCR product with QIAGEN PCR clean-up kit

<br>
### **DNA shearing and recovery** ### {#G}

1. Purify the biotinylated forward strand using QIAGEN PCR clean-up kit
2. Verify quality of the DNA with A260/A280 ratio– should be between 1.8 – 2.0
3. Dilute the DNA to 10-20 ng/uL
4. Sonicate DNA at 20% amplitude with pulse on 15 sec, pulse off 60 sec. For a smaller volume of DNA (up to 500 uL in microcentrifuge tube), sonicate for 8 cycles. For a larger volume in 15 mL tube, sonicate for 30 minutes
5. Recover diluted DNA by adding 1/10 volume of 3 M Na-Acetate pH 5.2
6. Add 2.5 volume of -20°C 100% ethanol and incubate at -20°C for at least 1 hour
7. Centrifuge DNA at 13,000 rpm for 20 minutes
8. Wash DNA pellet with room-temperature 70% ethanol and centrifuge at 13,000 rpm for 1 minute
9. Discard ethanol and repeat step 8
10. Remove ethanol as much as possible and air-dry DNA pellet at 37°C for 20 minutes, or until completely dry
11. Resuspend the pellet with nuclease-free water.

<br>
### **Biotinylated DNA Isolation- Dynabeads** ### {#H}

1. Wash 50 uL of the Dynabeads™ MyOne™ Streptavidin C1 (Invitrogen) with 1 mL 2X Binding and Washing (B&amp;W) buffer (10 mM Tris-HCl pH 7.5, 1.0 mM EDTA, 2.0 M NaCl)
2. Place the tube on a magnetic rack for 2-3 minutes, then remove the solution
3. Resuspend beads with 100 uL of 2X B&amp;W buffer
4. Add 100 uL of purified PCR product
5. Incubate at room temperature, on a rotator mixer for 1 hour. Set orbital 100 rpm 3 times, reciprocal 90° 20 times and Vibro 5° 5 times.
6. Place the tube on a magnetic rack for 2-3 minutes and discard the solution
7. Wash the beads with 100 uL 1X B&amp;W buffer, mix and place the tube on magnetic rack
8. Discard the washing solution and repeat step 7
9. Melt the non-biotinylated strand by adding 100 uL of 0.1 M NaOH
10. Incubate at 37°C for 10 minutes
11. Place the tube on magnetic rack and remove the solution
12. Add 100 uL of 0.1 M NaOH to the beads and repeat step 11
13. Wash the beads with 100 uL 1X B&amp;W once and discard the solution.
14. Elute ssDNA from the beads by boiling in 50 uL of 0.1% SDS at 95°C for 10 minutes
15. Place the tube back on the magnetic rack and collect the solution
16. Remove SDS from DNA by Monarch®PCR &amp; DNA Cleanup Kit (NEB) following the oligonucleotide clean up protocol
17. Store ssDNA at -20°C until required

<br>
### **Universal base addition – Terminal Transferase** ### {#I}

1. Prepare the reaction following:

| | Final concentration |
| --- | :---: |
| 10X Terminal Transferase buffer | 1X |
| 2.5 mM CoCl2 | 0.25 mM |
| Forward strand ssDNA | 650 ng |
| 10 mM dITP | 0.4 mM |
| 20 U/uL Terminal Transferase | 10 Unit |
| DIW | Total 50 uL |

2. Incubate the reaction in a thermal cycler at 37°C for 30 minutes and 70°C for 10 minutes
3. Purify the ssDNA with Monarch®PCR &amp; DNA Cleanup Kit (NEB) following the oligonucleotide clean up protocol
4. Store ssDNA at -20°C until required

<br>
### **Full-length gene synthesis** ### {#J}

1. PCR using Taq polymerase following:

| | Final concentration | uL in 1 reaction |
| --- | :---: | :---: |
| 10x ThermoPol buffer | 1X | 5 |
| 10 mM dNTP mix | 0.2 mM | 1 |
| Forward strand ssDNA | 500 ng ||
| Reverse strand ssDNA | 60 ng ||
| 10 uM Non-biotinylated reverse primer | 20 pmol | 2 |
| 100% DMSO | 5% | 2.5 |
| 5 U/uL Taq polymerase | 2.5 unit | 0.5 |
| DIW | Total 50 uL ||

2. Synthesis full gene following the SeSaM protocol

| | Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 94°C | 3 min | 1 |
| Denaturation | 94°C | 1 min | 30 |
| Annealing | 52.7°C | 1 min ||
| Extension | 72°C | 1 min 15 sec ||
| Final extension | 72°C | 10 min | 1 |
| Hold | 4°C | ∞ ||

3. Purify the ssDNA with Monarch®PCR &amp; DNA Cleanup Kit (NEB)
4. Store DNA at -20°C until required

<br>
### **Universal base replacement** ### {#K}

1. PCR using Taq polymerase following:

|| Final concentration | uL in 1 reaction |
| --- | :---: | :---: |
| 10x ThermoPol buffer | 1X | 5 |
| 10 mM dNTP mix | 0.2 mM | 1 |
| 10 uM Forward primer | 20 pmol | 2 |
| 10 uM Reverse primer | 20 pmol | 2 |
| Full-length DNA | 1 - 60 ng ||
| 100% DMSO | 5% | 2.5 |
| 5 U/uL Taq polymerase | 2.5 unit | 0.5 |
| DIW | Total 50 uL ||

2. Set the thermal cycler according to the condition suggested below

| | Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 94°C | 3 min | 1 |
| Denaturation | 94°C | 1 min | 30 |
| Annealing | 52.7°C | 1 min ||
| Extension | 72°C | 1 min 15 sec ||
| Final extension | 72°C | 10 min | 1 |
| Hold | 4°C | ∞ ||

3. Run PCR product on 2% agarose gel and perform gel purification
4. Store DNA at 20°C until required

<br>

## **GeneORator protocol**
<hr style="height:1px;border:none;color:#808080;background-color:#808080;" />
### **Reverse Megaprimers generation**

1. Perform asymmetric PCR:

|| Final concentration |
| --- | :---: |
| Q5 reaction buffer | 1X |
| dNTP mix | 0.2 mM |
| Mutagenic forward primers | 25 nM |
| Reverse primer | 0.5 uM |
| pJUMP19\_Cex | 200 ng |
| Q5 high fidelity DNA polymerase | 1 unit |
| DIW | Total 50 uL |

2. Set the thermal cycler at:

|| Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 98°C | 2 min | 1 |
| Denaturation | 98°C | 30 sec | 25 |
| Annealing | 60°C | 20 sec ||
| Extension | 72°C | 40 sec ||
| Hold | 4°C | ∞ ||

3. Purify PCR product with QIAGEN PCR clean-up kit

<br>

### **Megaprimer PCR**

1. Generate the full-length gene using the reverse megaprimers

|| Final concentration |
| --- | :---: |
| Q5 reaction buffer | 1X |
| dNTP mix | 0.2 mM |
| Forward primer | 0.5 uM |
| Mutagenic reverse megaprimer | 0.05 uM |
| pJUMP19_Cex | 0.5 ng |
| Q5 high fidelity DNA polymerase | 1 unit |
| DIW | Total 50 uL |

2. Set the thermal cycler at:

|| Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 98°C | 2 min | 1 |
| Denaturation | 98°C | 30 sec | 25 |
| Annealing | 60°C | 20 sec ||
| Extension | 72°C | 40 sec ||
| Hold | 4°C | ∞ ||
<br>

### **Full-length mutant library purification**

1. Exclude methylated DNA by DpnI digestion:

|| Final content in the reaction |
| --- | :---: |
| PCR product | 50 uL |
| DpnI | 20 U/uL |
| 2.1 Buffer | 1X |
| DIW | Total volume 100 uL |

2. Incubate the reaction at 37°C for 2 hours
3. Inactivate DpnI by incubating at 80°C for 10 minutes
4. Run the digestion reaction on 1% agarose gel
5. Perform gel extraction using the commercial kit

<br>

## **General protocols**
<hr style="height:1px;border:none;color:#808080;background-color:#808080;" />
### **Chemically competent cells**

1. Inoculate a single colony of appropriate cells into 10ml LB media and culture overnight at 37°C, 200rpm
2. Inoculate 1% of the overnight culture into a fresh LB media (100 mL)
3. Incubate at 37 °C, 200rpm until OD600 = 0.3-0.6 (approx. 2 hours)
4. Transfer to 2 x 50 mLtubes and leave on ice for 30 minutes
5. Centrifuge at 4000 x g for 5 minutes at 4 °C
6. Gently resuspend pellet in 25 mL ice cold 0.1 M MgCl2 and keep on ice for 30 minutes
7. Centrifuge at 4000 xg, 5 min for 5 minutes at 4 °C
8. Gently resuspend pellet in 25 mL ice-cold 0.1 M CaCl2 and incubate on ice for 30 minutes
9. Centrifuge at 4000 xg, 5 min for 5 minutes at 4 °C
10. Gently resuspend pellet in 1.25 mL ice cold CaCl2 with 15% Glycerol solution
11. Aliquot 100 uL and flash freeze with liquid nitrogen.  Store at – 80 °C until required
<br>

### **Colony PCR**

1. Prepare 50 uL of sterile water in a PCR tubes
2. Pick a single colony and resuspend in 50 uL water, then draw 5 uL out into a new tube
3. Freeze 5 uL cell suspension at -20°C for at least 10 minutes
4. Prepare the master mix following the table below

|| Final concentration | uL in 1 reaction |
| --- | :---: | :---: |
| 5x GoTaq buffer | 1X | 4 |
| 10 mM dNTP mix | 0.2 mM | 0.5 |
| 10 uM PS1 (forward primer) | 0.1 – 1 uM | 2 |
| 10 uM PS2 (reverse primer) | 0.1 – 1 uM | 2 |
| Cell suspension | 5 uL | 5 |
| GoTaq polymerase | 1.25 unit | 0.1 |
| DIW | Total 20 uL | 6.5 |

5. Mix the master mix with 5 uL cell suspension (DNA template) and PCR according to the condition in the table below

|| Temperature | Time | Cycle |
| --- | :---: | :---: | :---: |
| Initial denaturation | 95°C | 2 min | 1 |
| Denaturation | 95°C | 1 min | 25 |
| Annealing | 58°C | 1 min ||
| Extension | 72°C | 1 min 30 sec (1 min/kb) ||
| Final extension | 72°C | 5 min | 1 |
| Hold | 4°C | ∞ ||

6. Run the PCR product on 1% agarose gel with 100 V for 30 minutes and visualise the result under UV exposition
<br>

### **Heat shock transformation**

1. Defrost chemically competent cells on ice.
2. Add 2ul of plasmid DNA or 10 uL of assembly reaction to 100 uL competent cells
3. Flick the tube to mix and incubate on ice for 30minutes
4. Heat shock at 42Cfor 30 seconds
5. Incubate on ice for 2 minutes
6. Add 1 mL SOC media and recover cellsat 37C, 200 rpm for 1hour
7. Spread100 uL on an appropriate antibiotic LB/agar plate
8. Spin the rest of the cells at 4000 rpm, remove 900 uL of the media, reusupend and spread onto another LB/agar plate
9. Incubate plates at 37C overnight
<br>

### **JUMP assembly ### [ref] : Golden Gate assembly platform**

1. Determine the concentration of the assembly parts with Nanodrop
2. Use DNA calculator (from Promega) to calculate fmol of each part
3. Prepare the assembly parts in the concentration of 20 fmol/uL
4. Set up 20 uL JUMP assembly reaction using 1 uL of all parts (or 20 fmol)
5. Add 2 uL of 10X T4 ligase reaction buffer, 1 uL of either BsmBI (for Level0 assembly) or BsaI-HF (for Level 1 assembly), and 0.25 uL of T4 ligase
6. Add sterile water to adjust the volume up to 20 uL
7. Incubate the reaction following the tables below

Level 0 assembly: BsmBI

| Temperature | Time | Cycle |
| :---: | :---: | :---: |
| 42°C | 15 min | 1 |
| 42°C | 3 min | 30 |
| 16°C | 3 min | |
| 55C | 15 min | 1 |
| 80C | 5 min | 1 |
| 10C | ∞ ||

Level 1 assembly: BsaI-HF

| Temperature | Time | Cycle |
| :---: | :---: | :---: |
| 37°C | 15 min | 1 |
| 37°C | 5 min | 60 |
| 16°C | 5 min | |
| 37°C | 60 min | 1 |
| 80°C | 5 min | 1 |
| 10°C | ∞ | |

8. Transform the reaction directly to the competent cells
<br>

### **Assembly enhancement**

1. Incubate level 1 mutant library with BmtI endonuclease to cleave sfGFP but not Cex

|| Final content in the reaction |
| --- | :---: |
| Level 1 mutant library | 200 ng |
| BmtI | 2 U |
| rCutsmart buffer | 1X |
| DIW | Total volume 10 uL |

1. Incubate the reaction at 37°C for 1 hour
2. Heat inactivate enzyme at 65°C for 20 minutes
3. Directly transform 10-uL reaction to 100 uL _E.coli BL21_ (DE3) competent cells
4. Plate on LB/Agar/Kan/IPTG plate for screening
<br>

### **High-throughput screening of Cex**

1. Spread mutants on LB/agar plate with 50 ug/mL Kanamycin and 0.01 mM IPTG
2. Incubate at 37°C for 48 hours
3. Prepare the screening solution by mixing 7.5 g agarose with 50 mL 1M Sodium phosphate buffer pH 6.5 and 400 mL distilled water
4. Autoclave the screening solution
5. Let the screening solution cooled down by incubating in the water bath at 48°C
6. Add 50 mL of azo-xylan to the screening solution
7. Pour the screening solution on top of the mutant agar plate
8. Let the agarose set and incubate at 37°C for 6 hours, the visible halos indicating the working Cex enzyme
<br>
[Back to top](#)

