# Mini bioinformatics project: PCA on genotypes

This repo contains the code from this video:
[https://youtu.be/-PCKK_nwFdA](https://youtu.be/-PCKK_nwFdA)

If you somehow end up publishing a paper based on this type of project, you should cite this original paper it was inspired by: [https://www.nature.com/articles/nature07331](https://www.nature.com/articles/nature07331)

## Preview VCF on 42basepairs

* [Preview variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=variants)
* [Subsample variants](https://42basepairs.com/browse/s3/1000genomes/release/20110521?file=ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz&preview=subsample&loci=22%3A16000000-16100000)


## Download data files on the command line

```bash
# Download from 42basepairs
curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz"

curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz.tbi"

curl -O "https://42basepairs.com/download/s3/1000genomes/release/20110521/phase1_integrated_calls.20101123.ALL.panel"

# or use "wget" instead of "curl -O" if you don't have curl.
```

## Colab notebook:

[https://colab.research.google.com/drive/1o24ZfqDoBEwvRSx_Br1u7edPPXLLx4w7?usp=sharing](https://colab.research.google.com/drive/1o24ZfqDoBEwvRSx_Br1u7edPPXLLx4w7?usp=sharing)
