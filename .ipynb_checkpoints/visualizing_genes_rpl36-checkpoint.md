## Visualizing Genetic Variation in _Drosophila_ Genes

Below is a worked example of how to explore gene regions in IGV using the 60S ribosomal protein L36 (RpL36) as an example. It is designed for you to follow along in IGV.

<br/>

#### 1. Open IGV and reload the dgrp2 VCF file

- "File" --> "Load from File..." --> choose the `dgrp2.vcf` file from your dgrp_vcf folder.
 
- The default genome should still be set to the _D. melanogaster_ dm3 reference genome. If for some reason it isn't, see steps 2 and 3 of the IGV tutorial.



<br/>

#### 2. Navigate to a gene's location using the search box

- As described in step 7 of the IGV tutorial, you can jump to the location of a gene using the search box in the toolbar at the top of the IGV window. Simply type a valid gene name into the search box and press "Go" (shown below for RpL36).

<img src="visualizing_genes_images/1_IGV_search_bar.png" alt="drawing" width="600"/>



<br/>

#### 3. Expanding the gene panel

- After navigating to a gene's location, you will see the focal gene in the center of the gene panel at the bottom of the IGV window.

- By default, the gene panel is in "Collapsed" mode. However, genes coded on opposite strands of DNA can overlap each other, and these genes will not be separately shown in Collapsed mode. Also, there can be more than one version of a gene because of [alternative splicing](https://en.wikipedia.org/wiki/Alternative_splicing), and it is best to view all of them.

- To switch to "Expanded" mode, right click on the gene panel and select "Expanded", as depicted in the image below.

<img src="visualizing_genes_images/2_gene_panel_expanded.png" alt="drawing" width="800"/>


<br/>

#### 4. The IGV gene model

- After expanding the gene panel, you will see all the possible gene versions, with the primary version at the top. In the case of RpL36, there are 5 possible versions of the gene (see below).

- The gene models include 5'UTRs, exons, introns, and 3'UTRs. These are indicated in the image below for RpL36.

- **NOTE:** Recall that DNA molecules have two strands of nucleotides, and that the sequence of each is the reverse-complement of the other. However, as a rule, the reference sequence is only one strand of the DNA molecule. Because genes can be coded on either strand, the IGV gene models include arrows that indicate the direction of the gene relative to the reference sequence. In the case of RpL36, the arrows run in the opposite direction relative to the reference, indicating that RpL36 is coded on the opposite strand. Its coding sequence will therefore be the reverse-complement of the reference sequence.

<br/>

<img src="visualizing_genes_images/3_rpl36_gene_models.png" alt="drawing" width="400"/>


<br/>

#### 5. Amino acid sequence

- When zoomed in further, the gene model will include the amino acid sequence of the protein, as well as start and stop codons (highlighted in green and red, respectively). Again, because of the orientation of RpL36 relative to the reference sequence, the gene runs from right to left.

<img src="visualizing_genes_images/4_start_stop_codons.png" alt="drawing" width="600"/>


<br/>

#### 6. Examining the details of a Single Nucleotide Polymorphism (SNP)

- The image below shows the junction between the first exon and the first intron of RpL36. In the DGRP, there is only one SNP in the first exon of RpL36 (highlighted in the red box). Individuals that carry the alternate allele are shown in cyan, while individuals with the reference allele 

<img src="visualizing_genes_images/5_rpl36_exon_1_snp.png" alt="drawing" width="650"/>

- Of course we want to see information about a given SNP, and therefore how a given DGRP line differs in sequence from the reference, side 

<img src="visualizing_genes_images/6_rpl36_exon_1_snp_details.png" alt="drawing" width="200"/>

- Notice that there is no genome sequence for any of the DGRP lines - only variable sites are shown. For a number of reasons, direct full-genome comparisons across multiple genomes is a very difficult problem. The aim of a VCF file is to simplify the comparison to just those sites that differ for simple variants, such as SNPs, insertions, and deletions. This allows hundreds of genomes to be compared at once via the reference sequence.





