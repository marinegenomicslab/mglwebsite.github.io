---
title: 'Haplotyping RAD loci: an efficient method to filter paralogs and account for
  physical linkage'
authors:
- Stuart C. Willis
- Christopher M. Hollenbeck
- Jonathan B. Puritz
- John R. Gold
- David S. Portnoy
date: '2017-09-01'
publishDate: '2024-11-01T18:04:41.594642Z'
publication_types:
- article-journal
doi: 10.1111/1755-0998.12647
abstract: Next-generation sequencing of reduced-representation genomic libraries provides
  a powerful methodology for genotyping thousands of single-nucleotide polymorphisms
  (SNPs) among individuals of nonmodel species. Utilizing genotype data in the absence
  of a reference genome, however, presents a number of challenges. One major challenge
  is the trade-off between splitting alleles at a single locus into separate clusters
  (loci), creating inflated homozygosity, and lumping multiple loci into a single
  contig (locus), creating artefacts and inflated heterozygosity. This issue has been
  addressed primarily through the use of similarity cut-offs in sequence clustering.
  Here, two commonly employed postclustering filtering methods (read depth and excess
  heterozygosity) used to identify incorrectly assembled loci are compared with haplotyping,
  another postclustering filtering approach. Simulated and empirical data sets were
  used to demonstrate that each of the three methods separately identified incorrectly
  assembled loci; more optimal results were achieved when the three methods were applied
  in combination. The results confirmed that including incorrectly assembled loci
  in population-genetic data sets inflates estimates of heterozygosity and deflates
  estimates of population divergence. Additionally, at low levels of population divergence,
  physical linkage between SNPs within a locus created artificial clustering in analyses
  that assume markers are independent. Haplotyping SNPs within a locus effectively
  neutralized the physical linkage issue without having to thin data to a single SNP
  per locus. We introduce a Perl script that haplotypes polymorphisms, using data
  from single or paired-end reads, and identifies potentially problematic loci.
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/10.1111/1755-0998.12647
---
