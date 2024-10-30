The R script (.Rmd) for the analysis of the metagenomes of the samples included in this project contains:
1. Read filtering and processing. Includes removal of host (wheat) reads, normalization, and binning of reads by k-mer coverage.
2. Sample coverage based on sequence diversity.
3. Coassembly.
4. Functional annotation.
5. Functional analysis.

In addition, manually generated files "MAGS_info.txt" and "DESeq_KEGG_subset.txt" are provided.

The file "Track_Reads.txt" contains the surviving reads dugring the multiple filtering and processing steps.

The file "Contigs_stats.txt" contains the statistics of the coassembly.

For plotting the nonpareil curves, the "samples_nonpareil.txt" file and the required .npo files are provided under nonpareil directory.

The file "RAxML_bipartitions.MAG_FNAs" contains the generated phylogeny of MAGs.

