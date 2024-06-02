
# *Platynothrus peltifer* haplotype-specific analyses

Steps followed to perform MDS analyses and explore evolutionary dynamics of the two diverging haplotypes (alleles) in an asexually reproducing mite:

1. **MDS Analyses**: For detailed steps on performing MDS analyses, please check [MDS](https://github.com/merrbii/Ppr_hap_divergence/blob/main/MDSing.md).
2. **Diversity Analysis**: For information on overall as well as nucleotide diversity at synonymous/nonsynonymous sites, please check [here](https://github.com/merrbii/Ppr_hap_divergence/blob/main/calculateDiversity.md).
3. **Omega Calculation**: To calculate omega using HyPhy, please check the [evolutionary rates pipeline](https://github.com/merrbii/Ppr_hap_divergence/blob/main/calculate_omega.md).
4. **SFS Profiles**: Please use the following [script](https://github.com/merrbii/Ppr_hap_divergence/blob/main/src/get_sfs_profiles.sh) that processes a VCF file to extract, count, and sort unique genotypes. It then formats the results and saves them to an output file that can be used to produce bar plots in R, for instance.
