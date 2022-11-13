
# Datasets used in Sugihara et al. 2022

## Genotypes of rice RILs for association analysis

[The VCF file](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/10_RIL_VCF/N19_imputed_SNP_filtered.vcf.gz) includes the genotypes of the two parental rice cultivars Hitomebore and Moukoto and their 249 recombinant inbred lines (RILs). This VCF file was generated based on [the Os-Nipponbare-Reference-IRGSP-1.0 reference genome](https://rapdb.dna.affrc.go.jp/download/irgsp1.html) published in [Kawahara et al. (2013)](https://doi.org/10.1186/1939-8433-6-4). The sample ID prefix "N19_" in the VCF can be repalced to "RIL #" (e.g. N19_058 -> RIL #58).

## Hitomebore genome sequence

- [Hitomebore genome sequence (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/00_Hitomebore_genome/Os_Hitomebore_v1.0.fasta.gz)

## Reconstructed Pik trees

- [Pik-1 nucleotide sequences (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/20_Pik_trees/Pik-1_aln_seq.fasta) aligned with [MAFFT](https://doi.org/10.1093/molbev/mst010)
- [Pik-2 nucleotide sequences (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/20_Pik_trees/Pik-2_aln_seq.fasta) aligned with [MAFFT](https://doi.org/10.1093/molbev/mst010)
- [Pik-1 tree](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/20_Pik_trees/Pik-1_aln_seq.treefile) recontructed with [IQ-TREE](https://doi.org/10.1093/molbev/msaa015)
- [Pik-2 tree](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/20_Pik_trees/Pik-2_aln_seq.treefile) recontructed with [IQ-TREE](https://doi.org/10.1093/molbev/msaa015)

## *Magnaporthe oryzae* genome sequences and anontations

### Genome sequences

- [O23 genome sequence (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/O23_v1.0.fasta.gz)
- [TH3o genome sequence (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/32_TH3o/TH3o_v1.0.fasta.gz)
- [d44a genome sequence (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/33_d44a/d44a_v1.0.fasta.gz)

### RNA-seq during barley infection

- [Gene expression of O23 at 24 hours after barley infection (GTF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/RNA-seq/O23_24h.gtf)
- [Gene expression of O23 at 48 hours after barley infection (GTF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/RNA-seq/O23_48h.gtf)
- [Gene expression of TH3o at 24 hours after barley infection (GTF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/32_TH3o/annotations/RNA-seq/TH3o_24h.gtf)
- [Gene expression of TH3o at 48 hours after barley infection (GTF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/32_TH3o/annotations/RNA-seq/TH3o_48h.gtf)

### Transposable elements (TEs)

- [Sequences of TEs (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/TE/transposon.fasta) curated in [Chuma et al. (2011)](https://doi.org/10.1371/journal.ppat.1002147)
- [Annotation of TEs of O23 genome (GFF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/TE/O23_TE.gff3)
- [Sequences of LTRs of retrotransposons (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/TE/LTR.fasta) curated in [Chuma et al. (2011)](https://doi.org/10.1371/journal.ppat.1002147)
- [Annotation of LTRs of O23 genome (GFF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/TE/O23_LTR.gff3)

### Gene annotation trasfered from 70-15 to O23
- [Gene annotation trasfered from 70-15 to O23 (GFF)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/annotations/70-15_to_O23.gff3)

## Genotypes of *M. oryzae* F1 progeny for association analysis

[The CSV file](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/40_TH3o_x_O23/O23_v1.0.Chr-SNP_ctng-PA.rrBLUP.csv) includes the genotypes of the 144 F1 progeny derived from a cross between the *M. oryzae* isolates TH3o and O23. The genotypes were generated based on [the O23 reference genome](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/30_Mo_genome/31_O23/O23_v1.0.fasta.gz). The genotypes "0" or "1" in the file represent the genotypes derived from O23 or TH3o, respectively.

## Dataset of AVR-Mgk1

- [Nucleotide seuqnece of AVR-Mgk1 (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/50_AVR-Mgk1/AVR-Mgk1.nt.fasta)
- [Amino acid seuqnece of AVR-Mgk1 (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/50_AVR-Mgk1/AVR-Mgk1.aa.fasta)
- [Predicted protein structure of AVR-Mgk1 (PDB)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/50_AVR-Mgk1/AVR-Mgk1_AlphaFold2.pdb) using [AlphaFold2](https://doi.org/10.1038/s41586-021-03819-2)
- [Global alignment between AVR-Mgk1 and AVR-PikD](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/50_AVR-Mgk1/AVR-Mgk1_AVR-PikD_global-alignment.txt) using [the Needleman-Wunsch algorithm](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&PROG_DEF=blastn&BLAST_PROG_DEF=blastn&BLAST_SPEC=GlobalAln&LINK_LOC=BlastHomeLink)
- [Structure-based alignment between AVR-Mgk1 and AVR-PikD](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/50_AVR-Mgk1/AVR-Mgk1_AVR-PikD_TM-align.txt) using [TM-align](https://zhanggroup.org/TM-align)

## Dataset of AVR-PikD_O23

- [Nucleotide seuqnece of AVR-PikD_O23 (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/60_AVR-PikD_O23/AVR-PikD_O23.nt.fasta)
- [Amino acid seuqnece of AVR-PikD_O23 (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/60_AVR-PikD_O23/AVR-PikD_O23.aa.fasta)

## Effector sequences used in TRIBE-MCL
- [Effector sequences of Magnaporthe oryzae (FASTA)](https://github.com/YuSugihara/Sugihara_et_al_2022/blob/master/70_TRIBE-MCL/Mo_Effectors.faa) based on [Petit-Houdenot et al. (2020)](https://doi.org/10.1094/MPMI-03-20-0052-A)
