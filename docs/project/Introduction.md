# **INTRODUCTION**
<hr style="height:3px;border:none;color:#808080;background-color:#808080;" />

## **What is the Directed Evolution of proteins?**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The directed evolution of proteins comprises a collection of molecular biology techniques that aims to improve a particular feature of a protein in order to generate a more robust, stable or catalytically active variant in comparison to its original wildtype. This is typically acquired through repeated cycles of mutagenesis, in which variants are either selected or screened in a subsequent process in order to identify mutants with improved desirable features. Random mutations naturally occur due to environmental factors or biological errors and are the basis of the evolutionary process. However, these mutations are typically seldom and therefore not contingent to positive variant identification without deliberate action. Mutations of the protein of interest are therefore induced in laboratories in a variety of ways in a process known as <strong>library generation</strong>.
</div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mutants that arise from the library are transformed into a protein-expressing chassis and compared to the original wild-type strain in order to identify those with improved function of interest. In laboratory settings, directed evolution techniques can create an artificial human-controlled evolutionary pressure, and increase the mutation rate by isolating the gene from its original host, creating a large amount of copies with various mutations. In this way we can simulate thousands or hundreds of thousands of generations in a short period of time and select the best mutants for our purpose while generating useful data about the structure and function of the protein itself.
</div>

## **How are mutant libraries typically generated?**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The mutagenesis of the gene can be carried out in a variety of different ways, and the chosen method is typically dictated by the amount of available data and information on the protein of interest prior to the study. These methods are usually grouped in two separate classes; random mutagenesis and rational design. Random mutagenesis is used to induce mutations at random throughout the gene of interest in a way that simulates natural mutagenesis through the imperfect replication of DNA. Rational design, on the other hand, is adopted when data relating to structure and functionally relevant amino acid residues is available. Specific residues and structural motifs can then be targeted in a fashion which limits the size of the library generated through its targeted approach, however can also increase the probability of positive variant outcomes through its optimised design.
</div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Edinburgh iDEC 2021 team has investigated the library generation techniques of enzymes relevant to the degradation of recalcitrant polymers that are abundant in modern waste streams.
</div>

## **Random mutagenesis**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One of the most widespread methods adopted by laboratories willing to generate mutant libraries is error-prone polymerase chain reaction (epPCR). Polymerase chain reaction (PCR) is a molecular biology technique that harnesses the ability of a thermostable protein called DNA Polymerase to exponentially duplicate a strand of DNA. However, some polymerases, such as Taq Polymerase are not perfect in their proof-reading ability, a property which is exploited in epPCR to induce single mutations throughout the gene. Some mutations are capable of subsequently altering the amino acid residue of the primary sequence despite codon redundancy, thereby generating mutants with a variation of fitness levels across the sequence space. epPCR has proved a successful technique for library generation across a variety of studies, ultimately leading to variants with improved activity or stability. However, epPCR is prone to mutational bias, typically favouring A⦁T⟶G⦁C and G⦁C⟶A⦁T and therefore does not truly represent the essence of random mutagenesis. Additionally, despite epPCR typically representing multiple iterations to increase the number of point mutations per variant, it is statistically highly improbable that mutations are induced next to each other, a phenomenon which is seen as important in positive variant identification due to the epistatic relationship between mutations. The University of Edinburgh iDEC team has therefore explored and proposed an alternative method for random mutagenesis library generation which builds upon the inherent bias of Taq polymerase in order to increase the random mutational frequency of library generation for future directed evolution studies.
</div>

## **What is Sequence Saturation Mutagenesis (SeSaM)?**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SeSaM is a relatively overlooked and undervalued random mutagenesis method which was formulated to build upon the mutational spectrum of epPCR. First developed in the Schwaneberg lab of RWTH Aachen University, its highly innovative design harnesses the use of 5&#39; biotinylated primers, the weakened phosphate backbone of α-thio deoxynucleotides, and the degeneracy of universal nucleotides. Essentially, the incorporation of α-thio deoxynucleotides such as dATPαS are randomly incorporated throughout the gene of interest in an initial PCR. After incubation with iodine, the PCR product is sheared at every position where there is a dATPαS. The 5&#39; forward biotinylated fragments are then isolated using streptavidin-coated magnetic beads from the other fragmented DNA and the reverse strand is melted away with a DNA melting solution. A universal base which is capable of base-pairing with any of the four canonical dNTPs is conjugated to the 3&#39; end of the forward fragment by terminal transferase. Two more subsequent PCRs generate the full length gene and replace the universal base with canonical dNTPs, ultimately generating a mutant library throughout the gene.
</div>
<br>
<center><img width = "700" src ="https://user-images.githubusercontent.com/92064762/136875129-22896fa6-d473-4b0c-9973-59063fc48563.png"></center>
<div style="text-align: justify">
<em><strong>Figure 1 Graphical Summary of the SeSaM Protocol.</strong> dATPαS is a phosphorothioate nucleotide which weakens the phosphate backbone. Two PCR reactions are initially run in parallel. The first (1.A.ii) utilises the Cex forwards (biotinylated) and Cex reverse primers and dATPαS. dATPαS is randomly incorporated into the PCR product at positions where there is an adenine residue. The PCR product is then incubated with iodine, fragmenting the strands at every position where there is a dATPαS. Alternatively, here we propose a more cost-effective strategy for DNA shearing of the forward biotinylated strand using sonication (1.A.i). The forward fragments are then isolated with streptavidin coated magnetic Dynabeads, recovering only the 5&#39; biotinylated fragments, the length of which is determined by the position of the first phosphate backbone nick on the forward strand. The fragments are then elongated with terminal transferase, incorporating deoxyinosine monophosphate (dIMP) to the 3&#39; ends of the forward fragments. The second PCR reaction (2) utilises the Cex forwards and Cex reverse (biotinylated) primers. The PCR product is purified, and the 5&#39; biotinylated reverse template is isolated with Dynabeads. The products of (1) and (2) are then combined to elongate the DNA to the full-length gene in PCR reaction (3). A final PCR reaction (4) replaces the universal base with standard nucleotides and amplifies the mutant library with Cex forwards and Cex reverse primers. As the primers contain BsmbI and BsaI sites, the mutated genes would be able to assemble into pJUMP18-Uac and pJUMP29-1A and transformed for further application and screening. Adapted from (Wong _et al._ 2004).</em>
</div>

## **Why did the team optimise SeSaM?**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The team optimised a variety of technicalities throughout the SeSaM protocol in a way that makes the method more reproducible for future research interested in random mutagenesis library creation for protein directed evolution. SeSaM is an uncommon method and underreported in literature. We hope that our experience can increase its use in research. Our method can now be viewed in our Protocol page. Additionally, the team generated an alternative to the SeSaM process which seeks to decrease the cost of the method, thereby increasing the accessibility of the method to more laboratories with an interest in directed evolution. Owing to the high cost of the α-thio deoxynucleotides potentially creating a barrier to entry of the method, we have developed and optimised an alternative to the DNA shearing method using a standard sonicator. The sonicator, a typical device found in biological laboratories to lyse cells, and similarly shear DNA randomly throughout the gene. This was proven to be successful in generating a mutant library for our gene of interest and represents a novel undertaking in the directed evolution space.
</div>

## **Rational Design Mutagenesis**

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Rational design mutagenesis targets specific amino acid residues of the protein of interest based on prior publicly-available data and information. The use of degenerate NNK codons, where N can be any standard nucleotide (A, T, G or C) and K the keto-group containing nucleotides (T or G), renders this methodology semi-rational, due to the saturation of the residue with all 20 canonical amino acids. Relevant to this project is the targeting of the residues comprising the secondary shell of the active site. It is understood that by coordinating the active site of the enzyme, but not the conserved catalytic amino acid residues themselves, the activity of the enzyme can be increased [1]. A method devised by Sadler and colleagues was followed to generate the library for future screening efforts [2].
</div>
<br>
<center><img width = "700" src ="https://user-images.githubusercontent.com/92064762/136875287-e0752528-3fe9-4980-98ad-f4e4e4c4dea8.png"></center>
<div style="text-align: justify">
<em><strong>Figure 2 Schematic Representation of GeneORator Library Generation using Mutagenic Primers.</strong> An asymmetric PCR (A) involving a limiting amount of mutagenic forward primers was combined with the Cex reverse primer to generate single stranded mutagenic reverse primers. The mutagenic megaprimer was then quantified and set up in a subsequent PCR (B) with the Cex forwards primer to produce rationally designed mutant library. Adapted from Sadler et al. (2018).</em>
</div>
<br>
  References:
  <em>
  <div style="text-align: justify">
  [1] Lee M, Rozeboom HJ, Keuning E, de Waal P, Janssen DB. Structure-based directed evolution improves S. cerevisiae growth on xylose by influencing in vivo enzyme performance. Biotechnol Biofuels 2020 131 [Internet]. 2020 Jan 11 [cited 2021 Aug 12];13(1):1–18. Available from: https://biotechnologyforbiofuels.biomedcentral.com/articles/10.1186/s13068-019-1643-0</div>
  <div style="text-align: justify">
  [2] Sadler JC, Green L, Swainston N, Kell DB, Currin A. Fast and Flexible Synthesis of Combinatorial Libraries for Directed Evolution. Methods Enzymol. 2018 Jan 1;608:59–79.</div></em>
