# Awesome Phylogenetics

This is a curated list of awesome phylogenetic estimation and downstream inference tools.
With these resources we want to help you to find the tools for your specific system, analysis, and research questions.

##### Table of Contents

* [Software Suites](#software-suites)
* [Tree Estimation](#tree-estimation)
* [Network Estimation](#network-estimation)
* [Integrated Pipelines](#integrated-pipelines)
* [Community](#community)
  * [Talk](#talk)
* [Contribution](#contribution)


## Software Suites

Many Phylogenetic tools perform a multitude of functions, or contain many different utilities.

* [RevBayes](https://revbayes.github.io/) – An incredibly flexible, syntax-driven platform for Bayesian phylogenetic inference and macroevolutionary analysis. Uses an interactive modeling language (Rev) to let users build and customize highly complex probabilistic models from scratch.
* [IQ-TREE](https://iqtree.github.io/) - A lightning-fast, user-friendly maximum likelihood program for phylogenomic inference. Features an advanced ultra-fast bootstrap approximation, automated model selection (ModelFinder), and specialized routines for analyzing complex partition schemes.
* [PhyloNet](https://phylogenomics.rice.edu/html/phylonet.html) - A powerful command-line software package for reconstructing and evaluating phylogenetic networks. Offers diverse inference methods (parsimony, likelihood, and MCMC) alongside tools for network comparison and data simulation.
* [BEAST/BEASTX](https://beast.community/index.html) - A powerful Bayesian MCMC software package focused on molecular dating and evolutionary analysis of time-structured nucleotide and amino acid sequences. Highly optimized for phylodynamics, epidemic tracking, and ancestral state reconstruction.
* [BEAST2](https://www.beast2.org/) - A modular, redesigned framework for Bayesian phylogenetic analysis that relies on a flexible XML structure. Designed for extensibility, it allows users to dynamically install third-party packages for complex birth-death models, multispecies coalescent analyses, and total-evidence dating.
* [ASTER](https://github.com/chaoszhang/ASTER) - A suite of high-performance, quartet-based tools for large-scale species tree inference under the multispecies coalescent.

## Tree Estimation

### Likelihood/Bayesian Sequence-to-Tree 
Standard, site-independent methods that infer phylogenetic trees directly from multiple sequence alignments  using traditional substitution models using a Likelihood or Bayesian approach.

* [RaXML-ng](https://github.com/amkozlov/raxml-ng) - A highly optimized, maximum likelihood engine engineered for massive, genome-scale datasets.
* [PhyML](https://github.com/stephaneguindon/phyml) - A highly efficient maximum likelihood program that has specialized structural/protein modeling and the ability to calculate fast parametric branch support (aLRT/aBayes).
* [FastTree](https://morgannprice.github.io/fasttree/) - An fast maximum likelihood approximation tool built to infer massive phylogenies in a fraction of the time and memory of standard ML engines.
* [PhyloBayes](https://pbil.univ-lyon1.fr/software/phylobayes/) - A Bayesian method that implements the site-heterogeneous CAT mixture models, making it a standard for suppressing long-branch attraction artifacts in ancient alignments and deep-scale phylogenomics.

## Coalescent & Summary-Tree Methods

* [BUCKy](https://pages.stat.wisc.edu/~ane/bucky/index.html) - A Bayesian concordance analysis program that uses gene tree posteriors to estimate the species tree topology.
* [ASTRAL](https://github.com/chaoszhang/ASTER) - A summary method for inferring species trees from a set of gene trees by efficiently maximizing the total number of shared quartet trees found across the input.
* [Tree-QMC](https://github.com/molloy-lab/TREE-QMC) -  A quartet-based summary tool that employs a unique weighted quartet max-cut approach to infer species trees from a collection of gene trees. 
* [SVDQuartets](https://www.asc.ohio-state.edu/kubatko.2/software/SVDquartets/) - A method that uses It uses algebraic statistics (singular value decomposition of site-pattern flattening matrices) to infer species trees directly from sequence alignments.


## Network Estimation

### Summary-Statistic Methods
Tools that infer networks from abstract data summaries (*e.g.,* quartet concordance factors or allele frequencies) rather than full trees or alignments. Generally fast and scalable to phylogenomic datasets.

* [SNaQ](https://juliaphylo.github.io/SNaQ.jl/stable/) - A Julia package that infers level-1 networks from concordance factors using composite likelihood under a network coalescent model.
* [TreeMix](https://speciationgenomics.github.io/Treemix/) - Uses genome-wide allele frequency data to model population splits and subsequent migration/gene-flow events.
* [NANUQ+](https://cran.r-project.org/web/packages/MSCquartets/vignettes/NANUQplus.html) - A quartet-based framework for inferring level-1 phylogenetic networks under the Network Multispecies Coalescent (NMSC). This appraoch first estimates the tree of blobs and systematically resolves the multifurcations into hybrid cycles.

### Locus tree Methods

* [SpeciesNetwork](https://github.com/zhangchicool/speciesnetwork) - A BEAST 2 package that can infer phylogenetic networks from multilocus gene trees *or* sequence data using a birth-hybridization network prior.
* [PhyloFusion](https://github.com/husonlab/splitstree6) - A part of SplitsTree thats a set of input trees and constructs a tree-child network. The output network then displays all input trees.

### Sequence/Site Methods

* [PhyNest](https://github.com/sungsik-kong/PhyNEST.jl) - A high-performance Julia package that infers level-1 phylogenetic networks directly from DNA sequence alignments. It uses a composite likelihood framework based on quartet site patterns under the network multispecies coalescent.

## Integrated Pipelines

* [PhyloSuite](http://phylosuite.jushengwu.com/) - A comprehensive, GUI-driven platform that integrates a complete multi-locus phylogenetic workflow.

## Community


### Talk


## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](./contributing.md) to get started.
