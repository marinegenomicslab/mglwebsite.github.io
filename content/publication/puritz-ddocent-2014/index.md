---
title: 'textitdDocent : a RADseq, variant-calling pipeline designed for population
  genomics of non-model organisms'
authors:
- Jonathan B. Puritz
- Christopher M. Hollenbeck
- John R. Gold
date: '2014-06-10'
publishDate: '2024-11-01T17:25:24.939500Z'
publication_types:
- article-journal
doi: 10.7717/peerj.431
abstract: Restriction-site associated DNA sequencing (RADseq) has become a powerful
  and useful approach for population genomics. Currently, no software exists that
  utilizes both paired-end reads from RADseq data to efficiently produce populationinformative
  variant calls, especially for non-model organisms with large effective population
  sizes and high levels of genetic polymorphism. dDocent is an analysis pipeline with
  a user-friendly, command-line interface designed to process individually barcoded
  RADseq data (with double cut sites) into informative SNPs/Indels for population-level
  analyses. The pipeline, written in BASH, uses data reduction techniques and other
  stand-alone software packages to perform quality trimming and adapter removal, de
  novo assembly of RAD loci, read mapping, SNP and Indel calling, and baseline data
  filtering. Double-digest RAD data from population pairings of three different marine
  fishes were used to compare dDocent with Stacks, the first generally available,
  widely used pipeline for analysis of RADseq data. dDocent consistently identified
  more SNPs shared across greater numbers of individuals and with higher levels of
  coverage. This is due to the fact that dDocent quality trims instead of filtering,
  incorporates both forward and reverse reads (including reads with INDEL polymorphisms)
  in assembly, mapping, and SNP calling. The pipeline and a comprehensive user guide
  can be found at http://dDocent.wordpress.com.
links:
- name: URL
  url: https://peerj.com/articles/431
---
