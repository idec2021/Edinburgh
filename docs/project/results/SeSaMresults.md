# SeSaM method optimisation
<hr style="border:2px solid gray";background-color:gray> </hr>

## **Objective**
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To improve upon the mutational spectrum of error-prone polymerase chain reaction (epPCR) in generating libraries through the optimisation of the sequence saturation mutagenesis (SeSaM) protocol to induce mutations uncommon to Taq polymerase. Additionally, generate a semi-rationally designed mutant library for the eventual identification of positive variants capable of degrading recalcitrant polymers related to industrially relevant waste streams.
</div>
<hr style="border:2px solid gray";background-color:gray> </hr>

## **Results**

## *Sequence Saturation Mutagenesis Optimisation and Troubleshooting*

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In order to obtain results, the original SeSaM protocol was followed. However, the team experienced difficulty in generating a library using the protocol available in the literature. The team therefore sought to optimise the procedure, and to develop a lower cost alternative for future directed evolution studies.</div><br>

<center><img width = "400" src ="https://user-images.githubusercontent.com/92064762/137057903-5519d14f-e498-4071-9e49-53e09850ebec.png"></center>

<div style="text-align: justify">
<em><strong>Figure 1 SeSaM iodofragmentation optimization.</strong> A truncated pyruvate oxidase gene (<em>pox5</em>, 1606 bp) was utilized to demonstrate the fragmentation of DNA incorporated with dATPαS. Iodine concentrations was varied according to the two SeSaM protocol. Samples incubated with a higher iodine show greater smearing which further promoted when incubating at 70 °C</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Two SeSaM methods were published in 2004 and 2008 with contrasting information for the DNA shearing method. Wong et al. (2004) suggested that the random integration of the phosphorothioate nucleotide dATPαS in the first PCR product is cleaved at room temperature with 2μM iodine. On the other hand, Wong et al. (2008) states 2mM iodine at 70oC. Our result indicated that the 2 μM iodine failed to cleave DNA at any incubation condition (Figure 1). A higher concentration of iodine at a higher temperature exhibited more cleavage as observed by the extent of smearing. Therefore, 2 mM iodine at 70°C was chosen for further SeSaM studies.</div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The original SeSaM procedure stipulates the need for three separate DNA purification kits which inherently increases the cost of the method. For this reason, SeSaM was initially tested using the QIAquick Nucleotide Removal kit for every step due to its proposed ability to retain short oligonucleotides. However, DNA concentration measurements throughout the experiment indicated that a high percentage of DNA was being lost throughout the process, resulting in a loss of library variation and increasing the risk of failure. DNA concentration readings showed a significant loss of DNA at several steps throughout the method which was at odds with the theoretical yield. This was particularly noticeable in the Dynabeads elution step and its subsequent purification (Figure 2). After many iterations, it was found that the Dynabeads protocol provided in the SeSaM paper differed in comparison to the manufacturer&#39;s protocol. The SeSaM paper suggests using 10 mM Tris-HCl pH 7.5 with 1 mM EDTA and 1 M NaCl as a wash buffer, whilst the manufacturer&#39;s protocol uses 5 mM Tris-HCl pH 7.5 with 0.5 mM EDTA and 1 M NaCl. Additionally, the immobilisation of DNA on the Dynabeads was changed from 20 minutes on a rotating platform to 1 hour in a rotator mixer in the proposed optimised protocol. The Dynabeads immobilisation yield was subsequently improved with these adjustments with an average yield of 19.5% from the method from the original paper to 56.3% in the optimised protocol, representing a 2.8x increase in yield.</div>
<br>
<center><img width = "650" src ="https://user-images.githubusercontent.com/92064762/137058344-78dd60a7-f311-41dc-8596-b34789296f4c.png"></center>

<div style="text-align: justify">
<em><strong>Figure 2 DNA Quantity Tracking throughout SeSaM Protocol and Optimisation.</strong> FB: forward 5&#39;-biotinylated fragment DNA. RB: reverse 5&#39;-biotinylated template DNA. The SeSaM protocol represents the protocol as stated in Wong et al. (2004). The optimised protocol is the protocol suggested in this study</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Another potential cause for the significant DNA loss is the ssDNA purification, from which it was speculated that the QIAquick Nucleotide Removal kit was not suitable. Approximately 81.3% of DNA was lost after the purification. Ultimately, the Monarch® PCR &amp; DNA Cleanup Kit was utilised using the specified protocol for ssDNA purification. This kit seemed to significantly mitigate the DNA loss since only 42.0% of DNA was lost (Figure 3). Overall, the total amount of DNA retained represents a 5-fold increase between the SeSaM protocol and our optimised protocol.</div>
<br>

<center><img width = "550" src ="https://user-images.githubusercontent.com/92064762/137058527-e8c4bb1f-d67b-4de4-9fc6-55abd9d0b989.png"></center>

<div style="text-align: justify">
<em><strong>Figure 3 DNA Quantity Tracking with Differing Clean-up Kits.</strong> The QIAquick Nucleotide Removal kit was found to have too low a yield for effective library generation. Instead the Monarch PCR &amp; DNA clean-up kit was used following the protocol for ssDNA purification, increasing the yield of DNA.</em></div>
<br>

## *DNA Fragmentation: dATPaS Concentration &amp; Novel Sonication Calibration*

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The gene of interest is fragmented in the SeSaM protocol in order to allow terminal transferase to conjugate a universal base on the 3&#39; end of the forward fragment to induce mutagenesis. The original SeSaM protocol utilises dNTPaS incorporated into the gene of interest for subsequent random shearing across the full gene-length. This must be calibrated to the length of the gene in order to maximise the mutational frequency across the entire gene. The optimum dATPaS concentration for the gene of interest, Cex (<em>Cellulomonas fimi</em>), was determined to be 0.1 mM (Figure 4).</div>
<br>

<center><img width = "450" src ="https://user-images.githubusercontent.com/92064762/137058948-43c0c9cf-c4ca-4124-b402-976d8fd3682b.png"></center>

<div style="text-align: justify">
<em><strong>Figure 4 dATPαS Concentration Calibration Experiment.</strong> Fragmented DNA by an occurring smear on a gel. (1) 1kb NEB DNA ladder, (2) Negative control: PCR reaction with no dATPαS, (3) 0.5 mM dATPαS, (4) 0.3 mM dATPαS, (5) 0.2 mM dATPαS, (6) 0.1 mM dATPαS, (7) 0.05 mM dATPαS.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To achieve maximal mutational frequency, all phosphorothioate nucleotides of dCTPαS, dGTPαS and dTTPαS, as well as dATPαS would be required to be purchased to cleave the gene at every nucleotide position. Owing to the high cost of these modified bases, an alternative DNA shearing method was performed by sonication to explore more accessible alternatives to achieving greater mutational spectra. Various rounds of sonication were performed and are depicted in Figure 5. Increasing the rounds of sonication decreases the concentration of the full-length gene and increases the size of the smear. Much like the calibration experiment with dATPαS, a long smear with minimal full-length gene is desirable to increase the mutational spectrum of the method.</div>

<center><img width = "550" src ="https://user-images.githubusercontent.com/92064762/137059319-8d8245b3-64d6-4ac0-8492-10e944397306.png"></center>

<div style="text-align: justify">
<em><strong>Figure 5 Fragmentation of DNA by Number of Sonication Cycles.</strong> 2% agarose gel showing the fragmented DNA after sonication. (1) 100 bp Promega DNA ladder, (2-10) 0 - 8 cycles of sonication: pulse on 15 sec, pulse off 60 sec, 20% amplitude.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The generation of a mutant library using the phosphorothioate dATP was tracked using gel electrophoresis (Figure 6). Using the aforementioned optimised protocol, both full-length forward 5&#39;-biotinylated DNA and the reverse 5&#39;-biotinylated DNA template were successfully achieved in a sufficient amount to proceed. Unfortunately, the final PCR step, in which the universal base is replaced with standard nucleotides, failed to produce the expected PCR product. The reaction was repeatedly modified by changing several conditions including the annealing temperature, quantity of full-length gene template, and additionally purifying DNA with ethanol precipitation. However, the PCR product was observed as a smear on the agarose gel, and not as a full-length gene product as expected. The method was assumed to have failed for this reason.</div>
<br>

<center><img width = "900" src ="https://user-images.githubusercontent.com/92064762/137059549-878cdaee-d555-43ac-a846-84ae8189bd58.png"></center>

<div style="text-align: justify">
<em><strong>Figure 6 Mutant library generation using dATPαS – SeSaM steps DNA tracking.</strong> (1-9) Forward-biotinylated DNA (1) First PCR product, (2) After iodofagmentation, (3) After QIAquick nucleotide clean-up, (4) Excess DNA unbound to the Dynabead, (5) NaOH melting from the Dynabead, (6) Eluted DNA in 0.1% SDS, (7) First ssDNA purification with Monarch PCR product &amp; DNA purification kit, (8) ssDNA purification after terminal transferase reaction, (9) DNA purified after the full-length gene synthesis. (10-15) Reverse biotinylated DNA (10) First PCR product, (11) After QIAquick nucleotide clean-up, (12) Excess DNA unbound to the Dynabead, (13) NaOH melting from the Dynabead, (14) Eluted DNA in 0.1% SDS, (15) ssDNA purification with Monarch PCR product &amp; DNA purification kit</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As this study aimed to introduce a more cost-effective method, the library generation with the sonication shearing method was carried out. The optimised protocol was followed with the sonicated fragments and was successfully used to generate a full-length gene product (Figure 7).</div>
<br>

<center><img width = "600" src ="https://user-images.githubusercontent.com/92064762/137059810-4c8dc3c2-d444-42f1-875f-09763b0575fa.png"></center>

<div style="text-align: justify">
<em><strong>Figure 7 Final PCR product obtained from the optimised SeSaM.</strong> The Cex-alphaS full-length and Cex-sonicated full-length were loaded on gel in the equivalent amount as in the PCR mixture. pJUMP19_Cex was amplified as a positive control and both Cex-alphaS and Cex-sonicated were set in a PCR with three different concentrations of template: 1 ng, 30 ng, and 60 ng. The sample fragmented by sonication was successfully produced, however the sample fragmented by dATPαS always appeared as a smear for an unknown reason.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The resulting product was successfully assembled via Golden Gate assembled and cloned into <em>E. coli</em> DH5a. Colonies with successful colony PCR results were plasmid prepped and sent for sequencing for the confirmation of mutations with the gene.</div>

<center><img width = "600" src ="https://user-images.githubusercontent.com/92064762/137060078-e21e1a7d-f357-46c7-859c-7b1748b1db71.png"></center>

<div style="text-align: justify">
<em><strong>Figure 8 Mutational Spectrum of the Optimised SeSaM Method with Novel Sonication Shearing.</strong> (A) Number and types of mutation found per clone sequenced. (B) Total types of mutations found from sequencing of mutants.</em></div>
<br>

[Back to top](#3333)
