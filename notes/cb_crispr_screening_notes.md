---
title: Example document for taking notes on CRISPR screening technology using markdown and github & objectives
author: Katharine Chen
date: 2023-06-26
---

# Objectives
1. Learn how to write in markdown 
2. Read up on CRISPR-Cas9 basic biology and its application as a high-throughput screening tool
3. Version control your notes using git/github

# Instructions
- You can use this document as an example template for how to write in markdown format (this document is written in markdown)
  - Go to https://github.com/kychen37/rasilab_spelman_2023/tree/main#markdown for what markdown is and why we use it
  - Learn some of the basic formatting that is commonly used in markdown, for example:
    - bullet points (dashes -)
    - bold (**bold**)
    - italic (_italic_)
    - headers (use # at the very front of the line)
- Once you feel more familiar with markdown, go to the [CRISPR_biology_resources.md](https://github.com/kychen37/rasilab_spelman_2023/blob/main/learning_resources/CRISPR_biology_resources.md) document and go through the various links at your own pace
- As you go through the various resources, take notes as you normally would using markdown format
- Save your notes in markdown format in the "notes" directory with the file name "initials_crispr_screening_notes.md" (with your initials instead of the word 'initials')
- Feel free to ask me any questions that arise at any point in this process!

# notes
# **CRISPR 101 Ted Talk**
-   a method scientists use to edit DNA, and genes within viruses, embryos, adult cells and living species
-  crispr locus keeps a copy of previous viruses  
-   introduction of double stranded DNA cuts,ang trigger cells to prepare rejuvination
-   technology is being used on mice to disrupt genes in specific areas, such as color within mice
-   can also be used in humans for enhancement or to create designer humans
-   consider theraputic and non theraputic results, also consider ethical aproach to this technique in humans
# **What is RISPR-Cas9**
-   allows for genetic manipulation
-   DNA mutation in enzyme Cas9, and RNA specifically gRNA that is pre-designed, and later binds to DNA sequence-
-   RNA is designed to bind to a specific site within the DNA, then the cell will recognise that the DNA is damaged and attempt to repair. the also sometimes use DNA repair machinery to introduce changes more than one gene in the genome
-   This is a potential treatment method for various medical conditions such as cancer, hepratits B and high cholesterol
# **Khan Academy video: CRISPR Cas-9**
-   virus insert its DNA into other cells, and the cells read the genetic information as if it were thier, alowing the virus to continue to replicate and eventually take over the body
-   cas genes are places in the middle of the DNA, and then hunt for complimentary DNA strands
-   can be used to assist countries who suffer from mal nutrition, and can now cut DNA in areas that were previously inaccesible.
-   CRISPR-cas-9 is the most acurate, can only be used with reognized PAM sequences.    
# **CRISPR-Cas9 Screening Libraries**
-   use gRNA for maximm knockout efficency without comporomising specificity, therefor it is high yeild
# **NIH: CRISPR Genetic Screens**
-   bacterial genome editing system used to perturb-alter the function of genes in cells and tissue 
-   CRISPR system involves using the Cas9 enzyme guided by a single guide RNA to target specific genes
- Cas9 introduces double stranded DNA breaks at target site, allowing for small insertionsa nd deletions, resulting in the loss of functional, or enhancement of a mutation. This can allow high yeild results for specific phenotypical intrests. 
-   The sgRNA is typically ordred through public repositories, or can be custom designed to the users liking 
-   Here are the steps: 1 decide what target genes will be studied, and what resources are needed. 2 what cells should be used to all expression of Cas9 enzyme. 3 assay, screen cells to achieve the desired phenotypess, and other genetic factors that may be desireable. 4 analysis, measure and evaluate the screen outputs.
-    Some delivery methods can give rise to undesired effects, such as cytotoxicity or innate immunity responses 
-    the preferred delivery is by utilizing lentivirus (a genus of retroviruses that cause chronic and deadly diseases), which can stably integrate into the genome of the host and express Cas9 and RNA components. 
-  CRISPR screens involve applying selective stress to cells, often using drugs or ultraviolet radiation, to decrease the abundance of cells with lower fitness. Not limited to cell fitness assays alone, as researchers have combined CRISPR with fluorescence-activated cell sorting (FACS) to activate desired phenotypes, such as cytokine expression. Novel assays can be developed, like using an antibiotic resistance assay for active Hedgehog signaling, allowing for targeted selection in CRISPR screens. 
-   To measure changes in sgRNA abundance, sgRNA sequences are amplified from genomic DNA isolated before and after the screen. This is used to dictate how much a gene will be enriched.
-   CRISPR screens offer a powerful alternative approach to make new discoveries in investigative dermatology, enabling the identification of therapeutic targets in keratinocyte cancers, melanomas, genetic skin diseases, and the exploration of noncoding genomic regions contributing to skin disease.
limitations: labor and resource intensice, requires independent and functional techniques, and likely new tech.cb
# **CiBER-seq dissects genetic networks by quantitative CRISPRi profiling of expression phenotypes**
-   new method for dissecting genetic networks by using CRISPRi profiling of expression phenotypes
-    allows for precise control of gene expression by using deactivated Cas9 (dCas9) proteins and precise measurement of gene expression of specific phenotypes
-    can be used to identify key genes and pathways involved in specific biological processes, diseases, and harmful mutations
-    comparing the expression phenotypes of different genetic variants, CiBER-seq allows researchers to infer the functional relationships between genes.
-    potential to greatly advance our understanding of complex genetic networks and provide insights into disease mechanisms 
# **RNA-linked CRISPR (ReliC) screening elucidates gene regulatory networks in human cells**
-   mRNA transfer information from genes to proteins, the purpose of mRNA is to carry protein information from DNA in a cell to its cytoplasm, the mRNA is then read and is translated to base codons into amino acid growing protein chains. 
-   four diffrent types of mRNA mutations: point mutation-replacement of one base with another. Frameshift- addition or reoval of a base in a sequence. Nonsense- mutation that creates a stop codon, preventing the production of a protein in its entirety. Missense- the subsitutaiton of one amino acid for another. 
-   **RNA metabolism and its binding to proteins**
-   includes diverse processes that regualte the synthesis, processing transport and degreationof RNA molecules, allowing gene expression and maintaning cell homeostasis.
-   rNA-binding proteins are important in RNA metabolism bc they interact with RNA molecules. Rna binding proteins recognize specific RNA sequences or structures and mediate various functions, like splicing, polyadenylation, stability, and translation regulation.
-   RNA binding proteins can regulate RNA metabolism through direct interactions with RNA, influencing its localization, stability, or processing
-   either enhance or inhibit translation by interacting with specific elements in the mRNA
-   polyadenylation: addition of a poly(A) tail to an RNA transcript typically on the mRNA
-   cytoplasmic mRNA decay: post transcriptioanls mechanism in human cells with gene transcription, pre-mrna, and transport mechanisms from mrna regulate ultimate level of protein-encoding gene expression. Bascially a way that allows for gene transcription. 
-   their metabolic pathways are commonly studied in yeast: due to the simplicity, conservation, avalibility, simple cell enviroment,similarity within metabolic pathways, mechanisms mRNA synthesis, processing, transport, decay and more. 
-   Limitations: 
    -  Pooled CRISPR screens: disruption of RNA metabolism doesn't necessarily manifest with growth or viability defects: this is likely due to silent mutation, that dont affect the outcome of yeast. 
    -   FACS- based CRISPR screening: disruption of RNA metabolism may not alter protein levels, liekly encoding for a stop codon, therefore is this a non-sense mutation
