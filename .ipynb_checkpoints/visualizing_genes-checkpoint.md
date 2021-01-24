## Visualizing Genetic Variation in Three _Drosophila_ Genes

In this exercise, you will navigate to specified genes in IGV and take screenshots of the variation that is found there. Below is a worked example of how to explore gene regions using the 60S ribosomal protein L36 (RpL36) as an example. At the end of this document, you will find a description of the exercise.

<br/>

#### 1. Open IGV and reload the dgrp2 VCF file

- "File" --> "Load from File..." --> choose the `dgrp2.vcf` file from your dgrp_vcf folder.
 
- The default genome should still be set to the _D. melanogaster_ dm3 reference genome. If it is not, see steps 2 and 3 of the IGV tutorial.



<br/>

#### 2. Navigate to a gene location using the search box

- As described in step 7 of the IGV tutorial, you can jump to the location of a gene using the search box in the toolbar at the top of the IGV window. Simply type a valid gene name into the search box and press "Go" (shown below for Rpl36).

<img src="visualizing_genes_images/IGV_search_bar.png" alt="drawing" width="600"/>



<br/>

#### 3. Expanding the gene panel

- Because of [alternative splicing](https://en.wikipedia.org/wiki/Alternative_splicing), there can be more than one version of gene. Therefore, after navigating to the gene, we want to see all the possible versions by looking at the expanded view of the gene panel.

- To do so, right click on the gene panel and select "Expanded", as depicted in the image below.

<img src="visualizing_genes_images/gene_panel_expanded.png" alt="drawing" width="800"/>


<br/>

#### 4. The IGV gene model

- After expanding the gene panel, you will see all the possible gene versions, with the primary version at the top. In the case of RpL36, there are 5 possible versions of the gene (see below).

- The gene models include 5'UTRs, exons, introns, and 3'UTRs. These are indicated in the image below for RpL36.

- **NOTE:** Recall that DNA molecules have two strands of nucleotides, and that the sequence of each is the reverse-complement of the other. However, as a rule, reference sequences only show one strand of the DNA molecule. Because genes can be coded on _either strand_, the IGV gene models include arrows that indicate the direction of the gene relative to the reference sequence. In the case of RpL36, the arrows run in the opposite direction relative to the reference, indicating that RpL36 is coded on the opposite strand to the reference. Its coding sequence will therefore be the reverse-complement of the reference sequence.

<br/>

<img src="visualizing_genes_images/rpl36_gene_models.png" alt="drawing" width="400"/>


<br/>

#### 5. Amino acid sequence

- When zoomed in further, the gene model will include the amino acid sequence of the protein, as well as start and stop codons (highlighted in green and red, respectively). 

<img src="visualizing_genes_images/start_stop_codons.png" alt="drawing" width="600"/>


<br/>

#### 6. Accessing the details of Single Nucleotide Polymorphisms (SNPs)

- In the DGRP, there is only one SNP in the first exon of RpL36.  image below shows  SNP, the gene model will include the amino acid sequence of the protein, as well as start and stop codons (highlighted in green and red, respectively).

<img src="visualizing_genes_images/start_stop_codons.png" alt="drawing" width="600"/>




