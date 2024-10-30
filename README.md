# RhizCom - Rhizosphere Community microbiome assembly during sequential succession

R scripts for the analyses used in Garrido-Sanz and Keel, "Priority effects of heritable seed-borne bacteria drive early assembly of the wheat rhizosphere microbiome". Preprint available on [BioRxiv](https://doi.org/10.1101/2024.10.21.619384).

Raw 16S rRNA amplicon reads and metagenome sequencing data are available in the NCBI Sequence Read Archive (RSA) under BioProject accession number [PRJNA1169405](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1169405).

Files include.
1. Amplicon sequence analysis: R script, metadata, ASV sequence table, taxonomy table, and CFUs.
2. Metagenome analyses: R script and other required files. A sample data "RhizCom_subset.rds" file is provided to execute the metagenome analyses. The file contains only high-quality bins instead of the full dataset.

The code was developed and tested in R (version 4.1.1 or 4.4.1), running on RStudio (version 2024.04.2 Build 764) on a Dell workstation with an Intel(R) Xeon(R) Gold 6248R CPU processor, 384 GB of RAM, and Windows 10 Pro operating system.

The packages and versions required to run the code are: agricolae (version 1.3-7), ape (version 5.8), Biostrings (version 2.70.3), car (version 3.1-3), circlize (version 0.4.16), ComplexHeatmap (version 2.20.0), dada2 (version 1.30.0), data.table (versión 1.15.4), DECIPHER (versión 2.30.0), DESeq2 (version 1.44.0), dplyr (version 1.1.4), ggalluvial (version 0.12.5), ggforce (0.4.2), ggh4x (version 0.2.8), ggnewscale (version 0.5.0), ggplot2 (version 3.5.1), ggplotify (version 0.1.2), ggpmisc (version 0.6.0), ggpubr (version 0.6.0), ggrepel (version 0.9.5), ggsci (version 3.2.0), ggtern (version 3.5.0), ggtree (version 3.12.0), ggtreeExtra (version 1.14.0), gridExtra (version 2.3), KEGGREST (version 1.44.1), metagenomeSeq (version 1.43.0), metagMisc (version 0.5.0), Nonpareil (version 3.5.3), pairwiseAdonis (version 0.4.1), pals (version 1.9), pathview (version 1.44.0), phangorn (version 2.11.1), phyloseq (version 1.46.0), phyloseq.extended (version 0.1.0.9000), picante (version 1.8.2), plotly (version 4.10.4), qiime2R (version 0.99.6), ranacapa (version0.1.0), RColorBrewer (version 1.1-3), scales (version 1.3.0), scico (version 1.5.0), seqinr (version 4.2-36), speedyseq (version 0.5.3.9021), SQMtools (version 1.6.3), stats (version 3.1-3) tidyverse (version 2.0.0) and vegan (version 2.6-6.1).
