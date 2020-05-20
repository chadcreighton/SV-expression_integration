# SV-expression_integration
Genomic rearrangements exert a heavy influence on the molecular landscape of cancer. New analytical approaches integrating Structural Variants (SVs) with altered gene features represent a framework by which we can assign global significance to a core set of genes, analogous to established methods that identify genes non-randomly targeted by somatic mutation or copy number alteration. There is need for a systematic identification and cataloging of genes that are recurrently altered transcriptionally in cancer as a result of genomic rearrangement. We have developed a systematic analytical approach to integrate SV breakpoint information with the altered expression of nearby genes, whereby, utilizing public genomic datasets, we have cataloged hundreds of genes appearing deregulated by rearrangement-mediated cis-regulatory alterations.

System requirements
- Should work on all operating systems that allow for use of R.
- Software tested on Windows.

Installation guide
- Install R if necessary.

Demo
- Based on PCAWG and TCGA data from Zhang et al., Genome Biology 2019 (PMID: 31610796).
- For a set of genes significant in the Genome Biology study, data provided for the following: SV breakpoint matrix, copy matrix, expression matrix, cancer type and covariates information.
- Expected output are p-values and t-statistics for associating SV breakpoint pattern with gene expression, after correction for copy number alteration and cancer type (same gene ordering as in the data files).
- Expected runtime should not be long.

Instructions for use
- Make sure that file paths in R code reference the data files (SV_distance.txt, cancer_type.txt, etc.) as stored on your computer.
- Run the R-code.
