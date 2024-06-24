## File Description:

`./Dataset1_SNPs_Relaxed_CHR.vcf.zip` --> Filtered SNPs of only chromosomal regions for dataset 1 

`./Dataset2_SNPs_Relaxed_CHR.vcf.zip` --> Filtered SNPs of only chromosomal regions for dataset 2

`./Dataset1_SNPs_Relaxed_LE_CHR.vcf.zip` --> Filtered SNPs in linkage equilibrium of only chromosomal regions for dataset 1

`./Dataset2_SNPs_Relaxed_LE_CHR.vcf.zip` --> Filtered SNPs in linkage equilibrium of only chromosomal regions for dataset 2

### Dataset Description: 

**Dataset 1:** field and common garden *Q. rubra* and *Q. ellipsoidalis*
**Dataset 2:** field and common garden collected *Q. rubra* (coastal, inland, and interior regions).

### Filtering Description:

For information on filtering please refer to the materials and methods and the supplemental material and methods sections in the Gomez Quijano et al., 2024 manuscript Genetic differentiation across a steep and narrow environmental gradient: Quantitative genetic and genomic insights into Lake Superior populations of *Quercus rubra*. 


#### SNP calling and filtering 

We performed variant calling on the demultiplexed trimmed reads using the standard ipyRAD v.9.93 pipeline (Eaton and Overcast, 2020). To construct the assembly, we used the Quercus rubra v.2.1 reference genome (Kapoor et al., 2023) with a clustering threshold of 0.85 and a minimum of eight samples per RAD locus; all other parameters followed the standard workflow as suggested in Eaton and Overcast (2020). 

We removed any SNPs that had not been characterized as part of a chromosomal region in the Q. rubra  v.2.1 nuclear refence genome as we identified that some of these SNPs were the same as an inserted mis-assembly region (29726880-30108053 bp in chromosome 1) of a mitochondrial sequence in the Q. lobata nuclear reference genome (Sork et al., 2022).

We then performed further SNP filtering using VCFtools (Danecek et al., 2011). To remove low-confidence genotypes, we removed sites with a Phred quality score of <20, a sequencing depth of <5 reads per genotype, a minimum mean depth of <5 reads per site, and a minor allele frequency (MAF) of <0.02. To reduce the rate of missing data, we retained individuals and sites with <50% missing data. Finally, we removed indels and retained only SNPs.

