# RAD-seq bam files test data

This data was generated from nf-core/radseq test-data. In short fastq files ("msp_[0..9].{1,2}.fq.gz") were aligned against the reference fasta ("hsc_Chr26.fasta", defined as chromosome 26 of atlantic horseshoe crab). Alignments were made with bwa mem (v0.7.19) and then sorted with samtools (v1.22.1) into bam format. 

## File description

### Simulated Horseshoe Crab Data
- `illumina/bam/msp_[0..9].bam` &rarr; Bam files generated from simulated radseq libraries test data
- `popmap.tsv` &rarr; File describing the association of the bam file prefixes to populations. Defined populations are arbitrary. This file is required to run stacks

