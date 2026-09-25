# disease-gene-bioinformatics

# Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar
**Name:** Francis Kyle A. Oficiar
**Associated gene:** APP
**Associated disease:** Early on-set Alzheimer's Disease

# PART B. Locate Your Gene in the UCSC Genome Browser
| Field                                    | Answer                         |
| ---------------------------------------- | ------------------------------ |
| **a. Official gene symbol**              | APP                            |
| **b. Full gene name**                    | Amyloid beta precursor protein |
| **c. Chromosome**                        | Chromosome 21                  |
| **d. Genome assembly used**              | GRCh38 / hg38                  |
| **e. Genomic coordinates shown in UCSC** | chr21:25,880,550–26,170,770    |
| **f. DNA strand (+ or -)**               | + (forward strand)             |
| **g. Approximate gene size or length**   | ~290,221 bp                    |

<img width="1050" height="919" alt="image" src="https://github.com/user-attachments/assets/08654073-70e3-498b-9a9a-670ad218944e" />

# PART C. Understand the Gene Structure: Exons, Introns, and Transcripts

| Field                                        | Answer                                                                                                                                                                                                                                                                                                         |
| -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **a. Number of exons (selected transcript)** | **18 exons**                                                                                                                                                                                                                                                                                                   |
| **Chosen transcript**                        | **APP (RefSeq: NM_000484.4 – MANE Select transcript)**                                                                                                                                                                                                                                                         |
| **b. Multiple transcripts/isoforms visible** | **Yes**                                                                                                                                                                                                                                                                                                        |
| **c. Difference between exon and intron**    | An **exon** is a segment of a gene that is retained in the mature mRNA after splicing and may contain coding sequences or untranslated regions, while an **intron** is a non-coding intervening sequence that is transcribed but removed during RNA processing and therefore is not present in the final mRNA. |
| **d. Relative length (introns vs exons)**    | The **introns are much longer than the exons**, as seen by long connecting lines between small exon boxes.                                                                                                                                                                                                     |
<img width="1050" height="740" alt="image" src="https://github.com/user-attachments/assets/167b0592-a8c3-4360-a2ba-df35f6d83616" />

# PART D. Turn On and Examine Genome Browser Tracks

a. Which gene annotation track did you use?
**I used the NCBI RefSeq genes annotation track, with GENCODE also visible.**

b. Were ClinVar-related variant marks visible within or near your gene?
**Yes. ClinVar variant marks are visible within the APP gene region, shown as multiple variant markers in the ClinVar track.**

c. Were some regions more conserved than others?
**Yes. The conservation track shows that some regions have stronger conservation signals than others, indicating differences in sequence conservation across the region.**

d. Did conserved regions correspond mainly to exons, introns, both, or another region?
**The stronger conservation signals appear mainly around coding/exonic regions, although some conserved sequences can also occur in non-coding regions.**

e. Why can strong conservation suggest biological importance?
**Strong conservation suggests that a DNA region has been preserved across species because changes in that region may affect an important biological function. Therefore, highly conserved regions may be under evolutionary selection and can be functionally important.**

<img width="1050" height="1370" alt="image" src="https://github.com/user-attachments/assets/30e42bd2-9101-4cf3-82d2-a1031b1e552c" />

# PART E. Select One Variant in NCBI ClinVar

| Required information      | Answer                                                                             |
| ------------------------- | ---------------------------------------------------------------------------------- |
| **Gene**                  | **APP**                                                                            |
| **Variant/HGVS**          | **NM_000484.4(APP):c.2077G>A (p.Glu693Lys)**                                       |
| **rsID / ClinVar ID**     | No rsID is shown in the ClinVar record; the record accession is **RCV006461186.1** |
| **Chromosome & position** | **Chr21:25891856 (GRCh38)**                                                        |
| **Associated condition**  | **Alzheimer disease**                                                              |
| **Clinical significance** | **Pathogenic**                                                                     |
| **Review status**         | **criteria provided, single submitter**                                            |
| **Last evaluated**        | **August 20, 2025**                                                                |

<img width="1050" height="273" alt="image" src="https://github.com/user-attachments/assets/b14a1d33-843f-452d-868e-1d8b8bc27b16" />

# PART F. Find Your Selected Variant Back in UCSC

a. Where is the variant located relative to your gene?
**The variant is located within the APP (amyloid beta precursor protein) gene on chromosome 21, in the coding portion of the gene.**

b. Is it in an exon, intron, UTR, splice region, or another region?
**It is located in an exon (exon 17) of the APP transcript, rather than an intron or UTR. The variant is in the same coding exon that contains other well-known APP variants around codons 693–717.** 

c. Is it likely in a coding or non-coding region?
**It is in a coding region. ClinVar annotates it as a missense variant, changing the APP protein from glutamic acid (Glu/E) to lysine (Lys/K) at position 693.** 

d. How might the variant affect the gene or gene product?
**Because the variant changes one amino acid in the APP protein (p.Glu693Lys), it can alter the protein’s properties or function. ClinVar reports experimental evidence that this change affects APP function and notes that the affected residue is clinically significant.** 

e. What additional evidence would be needed before concluding that the variant causes disease?
**Additional evidence could include independent clinical observations, segregation of the variant with disease in families, population-frequency data, functional laboratory studies, and consistent evidence from multiple clinical laboratories or research studies. These types of evidence help establish whether the variant is truly associated with disease rather than relying on a single annotation.**

<img width="1050" height="353" alt="image" src="https://github.com/user-attachments/assets/75c97af2-8c34-482c-872a-37bd08eee79d" />

# Part G. Short reflection 

1.	What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?
UCSC showed me the detailed genomic organization of the APP gene, including its exons, introns, and the exact position of the selected variant. It also showed how the variant overlaps with the gene's coding region and other genomic anotations.
2.	Why is knowing the exact genomic location of a disease-associated variant useful?
   Knowing the exact location helps determine whether the variant is an exon, intron, UTR, or another regulatory region. It also allows researchers to connect the variant to specific transcripts and predict how it may affect the gene or its protein product.
3.	What is one limitation of predicting a variant's effect only from its genomic location?
   Genomic location alone cannot tell us whether a variant actually changes protein function or causes disease. Functional experiments, clinical evidence, population data, and other supporting evidence are needed to establish its significance.
4.	What was the most interesting feature you observed about your assigned gene?
   The Most interesting feature was seeing the APP variant directly within a coding exon in the UCSC genome browser. It was interesting to connect the exact genomic position of the variant with its predicted amino-acid change and disease association.

# LINK AND SOURCES

**NCBI ClinVar**
https://www.ncbi.nlm.nih.gov/clinvar/variation/18099/?term=%22RCV006461186%22+AND+351%5BGENEID%5D
**UCSC Genome Browser**
https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr21%3A25880550%2D26170770&hgsid=4175136597_pxFuFGEvdRrLA8ztXK8hDf1FQoln

# SUBMISSION INFORMATION 
**ASSIGNED GENE: APP**
**SELECTED CLINVAR VARIANT: NM_000484.4(APP):c.2077G>A (p.Glu693Lys)**   
**DATE OF SUBMISSION: 09/25/26**
