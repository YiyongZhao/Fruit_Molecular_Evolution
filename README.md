### Materials and Methods


### Angiosperm Fruit/Ovary Development-related Gene Families Analysis and Identification of Gene Duplication Events

<p align = "justify">
Our investigation employed the BUSCO strategy to ensure comprehensive and high-quality genomic and transcriptomic representation, resulting in a curated collection of data from 423 seed plant species, inclusive of 82 newly sequenced genomes. This extensive dataset enabled a focused examination of gene families associated with fruit and ovary development. 
The interested gene families were classified into two categories: MADS-box and non-MADS-box families. We utilized the HMMER suite (v3.3.2)[1] for the identification of MIKC gene family homologs, applying an E-value cutoff of 1e-5 to select for sequences that featured both SRF-TF and K-box domains. Subsequent amino acid sequences were aligned using MAFFT (v7)[2], with the alignment parameters set to automatic adjustment for optimal performance. PAL2NAL software[3] facilitated the conversion of these alignments into their corresponding nucleotide sequences, which were then refined using the alignment tool PASTA[4]. Phylogenetic trees for each gene family were constructed using IQ-TREE[5], employing the GTR+G model with 1000 bootstrap replications to estimate maximum-likelihood (ML) trees. TreeFix[6] was employed to reconcile the ML gene trees with species trees, thereby enhancing phylogenetic accuracy. </p>
<p align = "justify">
To delineate the five lineages within the MADS-box gene family, we selected protein sequences from Arabidopsis thaliana and tomato as reference gene markers. These were the AG, AP1, AP3/PI, SEP, and SOC1/TM3 lineages. Similarly, for the identification of five non-MADS-box gene families, we referenced 43 protein sequences from the same model organisms, using BLASTP with an E-value threshold of 1e-10 to ensure specificity. PhyloTracer software (https://github.com/YiyongZhao/PhyloTracer) was then implemented to visualize gene duplication events within these gene families. All the data related to gene family analsyis, including genome and transcriptome sequences, gene markers, species trees, and phylogenetic trees in Newick and PDF formats for the ten gene families studied, are freely available in public GitHub repository (https://github.com/YiyongZhao/Fruit_Molecular_Evolution).</p>
<p align = "justify">
Figure 1: A summarized phylogenetic tree of 423 seed plant species with a BUSCO-based gene completeness assessment for gene family analysis. species names in blue indicate the addition of 82 newly sequenced public genomes. </p>
Table 1: Information of genome and transcriptome data included and gene BUSCO completeness assessment in this study for angiosperm fruit evolution related gene family analysis.
Table 2: Gene names and IDs of Arabidopsis thaliana and Solanum lycopersicum in the phylogenetic analyses.

Reference:
1.	Finn RD, Clements J, Eddy SR: HMMER web server: interactive sequence similarity searching. Nucleic Acids Res 2011, 39(suppl_2):W29-W37.
2.	Katoh K, Standley DM: MAFFT multiple sequence alignment software version 7: improvements in performance and usability. Mol Biol Evol 2013, 30(4):772-780.
3.	Suyama M, Torrents D, Bork P: PAL2NAL: robust conversion of protein sequence alignments into the corresponding codon alignments. Nucleic Acids Res 2006, 34(suppl_2):W609-W612.
4.	Mirarab S, Nguyen N, Guo S, Wang LS, Kim J, Warnow T: PASTA: Ultra-Large Multiple Sequence Alignment for Nucleotide and Amino-Acid Sequences. J Comput Biol 2015, 22(5):377-386.
5.	Nguyen LT, Schmidt HA, von Haeseler A, Minh BQ: IQ-TREE: a fast and effective stochastic algorithm for estimating maximum-likelihood phylogenies. Mol Biol Evol 2015, 32(1):268-274.
6.	Wu Y-C, Rasmussen MD, Bansal MS, Kellis M: TreeFix: Statistically Informed Gene Tree Error Correction Using Species Trees. Syst Biol 2012, 62(1):110-120.

</p>
