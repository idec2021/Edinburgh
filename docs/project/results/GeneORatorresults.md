# **Semi-Rational Mutagenesis: GeneORator**
<hr style="height:3px;border:none;color:#808080;background-color:#808080;" />

## *Mutant Library Design*

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Residues of the secondary shell active site were selected for saturation mutagenesis using Protein Contact Atlas (PDB code: 2HIS), selecting the innermost cellobioside substrate (GLC602) as the centre of the active site. The residues were then grouped together if the residues appeared closely together in the protein primary sequence, therefore denoting regions close to the active site pocket. These residues were chosen Following a study by Lee et al. (2020) on the directed evolution of xylose isomerase from Piromyces for improved catalytic activity (1). The groups were also formed based on the number of contacts they had with the active site to gauge the impact of such factors on enzymatic activity.</div>
<br>

<center><img width = "550" src ="https://user-images.githubusercontent.com/92064762/137063279-7518bb3b-0607-48cf-9cbc-33979c87c3d7.png"></center>

<div style="text-align: justify">
<em><strong>Figure 1 Semi-rational  mutant library design.</strong> Figure generated on Protein Contact Atlas, PDB code: 2HIS. The size of the circles represents the number of contacts the residue has with the residues of the inner shell. Groups with a high average number of contacts include: B40, B80, B200, B230 and B280. Groups with a low average number of contacts include: S170 and S280. B: group with high number of contacts with the primary shell, S: group with low number of contacts with primary shell.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The first PCR is set as an asymmetric PCR, in which the Cex reverse primer is 20x more concentrated than the mutagenic forwards primer. This generates a primarily single stranded PCR product, known as a mutagenic megaprimer, of varying lengths with the induced mutation incorporated. The length of the mutagenic megaprimer is set by the length of the full-length gene minus the position of the first annealing base pair (Figure 2).</div>
<br>

<center><img width = "480" src ="https://user-images.githubusercontent.com/92064762/137063422-688350fa-f0ee-4ba2-8d21-c3e4658dbd89.png"></center>
  
<div style="text-align: justify">
<em><strong>Figure 2 Primary Asymmetric PCR.</strong> Expected lengths of the ssDNA megaprimers: B40: 1242bp, B80: 1139bp, S170: 867bp, B200: 766bp, B230: 680bp, B280: 541bp, S280: 533bp.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The reverse mutagenic megaprimers were purified, quantified, and set up in a following reaction with the Cex forwards primer (Figure 3). A separate positive control was run with equal concentration of the Cex forwards and Cex reverse primers. The PCR product was then digested with DpnI to ensure that the methylated template was no longer functional, thereby eliminating the possibility of wild-type transformation in downstream applications.</div>
<br>

<center><img width = "700" src ="https://user-images.githubusercontent.com/92064762/137063591-40d4e19e-1742-4db0-bf65-2f23133aeaeb.png"></center>
  
<div style="text-align: justify">
<em><strong>Figure 3 Secondary PCR using Mutagenic Megaprimers.</strong> All experiments show bands that represent the mutagenic megaprimers which were a part of the experiment. Bands of ~1350 bp that resembled the positive control (+) were extracted from the gel.</em></div>
<br>
<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The desired 1363 bp product was extracted using a gel extraction kit, quantified, and cloned into a level 1 expression vector using Golden Gate assembly.</div>
<br>
## *Mutant Library DNA Sequencing*

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Three colonies from the B200 mutant library were grown overnight after positive colony PCR results. The liquid cultures were plasmid prepped and sent for sequencing and confirmed to have mutations consistent with the NNK codon. All three sequences had mutations at the Serine 204 residue, with one mutation reflecting a S204N mutation, and the two others S204G mutations (Figure 4). Herein lies a limitation of NNK codons, where despite the reduced number of possible codon variations in comparison to NNN, some amino acids are still biased in favour of others.</div>
<br>

<center><img width = "500" src ="https://user-images.githubusercontent.com/92064762/137063802-a62ab27d-3b18-4bd0-a0c5-679499548afc.png"></center>

<div style="text-align: justify">
<em><strong>Figure 4 Sequencing Results of the S204 Codon.</strong> The original codon codes for serine. The three colonies sequenced all code for a mutation at this codon, one for asparagine, and two for glycine. Figure generated on Benchling.</em></div>
<br>

## *High-Throughput Screening*

<div style="text-align: justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The mutant library was screened for the enhanced endo-1,4-B-xylanase activity through the appearing halos around mutant colonies (Figure 5). The colony harbors an intact Cex hydrolyse 1,4-B-glycosidic bond between azo dye and xylan creating a clearance zone around E.coli colony. The libraries were cloned twice into cloning and expression vectors. This cloning strategy was found as a bottleneck of the library generation where an empty backbone could accumulate from each assembly or the failed assembly could hinder gene expression, obstructing the screening that require expressed enzymes. For this reason, this study is only able to screen 3 libraries: B200, B230 and S280. Three controls were applied to investigate the screening method. Wild-type harboured in expression vector and a same-batch assembly were demonstrated as positive control while a backbone pJUMP29-1A with the original sfGFP reporter gene serving as a negative control.</div>
<br>

<center><img width = "650" src ="https://user-images.githubusercontent.com/92064762/137064053-d2ac1285-0603-4d3d-92fb-ee3aaee13ea3.png"></center>

<div style="text-align: justify">
<em><strong>Figure 5 Xylanase Screening of GeneORator Mutant Library.</strong> (A) (i-ii) positive controls of wildtype Cex, (iii) empty vector negative control. (B) (i) B200 mutant library, 65% of white colonies creating zones of clearing assumed to harbour functional Cex mutant (ii-iii) B230 mutant library, no functional Cex mutant is observed (C) (i-iii) S280 mutant library, 80% of white colonies creating zones of clearing assumed to harbour functional Cex mutant.</em></div>
<br>
<em>
Reference:
<div style="text-align: justify">
1. Lee M, Rozeboom HJ, Keuning E, de Waal P, Janssen DB. Structure-based directed evolution improves S. cerevisiae growth on xylose by influencing in vivo enzyme performance. Biotechnol Biofuels 2020 131 [Internet]. 2020 Jan 11 [cited 2021 Aug 12];13(1):1–18. Available from: https://biotechnologyforbiofuels.biomedcentral.com/articles/10.1186/s13068-019-1643-0
</div></em>
<br>
[Back to top](#)
