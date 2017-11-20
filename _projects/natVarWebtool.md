---
layout: project
title: '<i>A. thaliana</i> natural variation webtool'
description: Gene- and site-wise analysis of sequence and geograpic diversity based on the 1001 genomes dataset
---

### Hamm MO, Wright RC  

_currently in development_

This web app and open source software package for the R programming language was built to facilitate exploration of the naturally occuring sequence diversity for your favorite gene or gene family.  

The 1001 genomes dataset was collected with the intention of genome scale analyses, such as genome wide association studies, in which a particular phenotype is quantified for all of the accessions and sequence variants that are associated with phenotypic variation are identified. In [my recent work](https://dx.doi.org/10.1534/genetics.117.300092), I have utilized this rich dataset in a different manner to measure the effects of coding sequence variation on protein functional variation and phenotypic variation. This work has expanded the sequence-function-phenotype map for the auxin-signaling F-box gene family, and this web app will facilitate similar analysis other genes, gene families, and genomic regions.

Tabs within the webtool will help you: 
1. calculate nucleotide diversity for a set of genes,
2. plot the nucleotide diversity of missense and synonymous variants,  
![](/software/divPlot.png){:height="100%" width="100%"}   
3. map accessions containing variants in a gene or set of genes,
![](/software/map.png){:height="100%" width="100%"}   
4. identify variants/accessions by interacting with these plots, and 
5. download data for selected sets of variants/accessions.

We are currently testing this tool by creating summaries of the natural variation in the nuclear auxin response pathway, and plan to publish this tool and our analysis in early 2018. 


