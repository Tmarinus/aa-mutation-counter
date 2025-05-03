##Alanine-scan
Python scripts for alanine scanning of NGS data. Used in publication by R. C. Prins, programmed by T. Marinus [1]. 
Cells were grouped in halo size, DNA library prep was performed per group with an unique bar code. Goal of this script was to analyse the mapped sam/bam file and find all amino acids that are mutated into Alanine.

#### vcf_to_fasta
Script to convert vcf file to fasta. Given variant call format file and reference fasta, convertion can be done.

#### fastq_size_splitter
Preprocessing script to split fastq files depending on read read length.

#### sam_to_codon
Main script for alanine scanning. Reads a sam file and generates a xlsx output file of where alanine (or other if specified) mutations were found. 


[1] R. C. Prins, T. Marinus, E. Dafni, I. Yacoby, and S. Billerbeck, “Alanine-scanning of the yeast killer toxin K2 reveals key residues for activity, gain-of-function variants, and supports prediction of precursor processing and 3D structure,” Nov. 22, 2024, bioRxiv. doi: 10.1101/2024.11.22.624868.
