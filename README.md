# Awesome Phylogenetics

This is a curated list of awesome phylogenetic estimation and downstream inference tools.
With these resources we want to help you to find the tools for your specific system, analysis, and research questions.

##### Table of Contents

* [Software Suites](#software-suites)
* [Tree Estimation](#tree-estimation)
* [Network Estimation](#network-estimation)
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

## Tree Estimation

## Network Estimation

### Summary-Statistic Methods
Tools that infer networks from abstract data summaries (*e.g.,* quartet concordance factors or allele frequencies) rather than full trees or alignments. Generally fast and scalable to phylogenomic datasets.

* [SNaQ](https://juliaphylo.github.io/SNaQ.jl/stable/) - A Julia package that infers level-1 networks from concordance factors using composite likelihood under a network coalescent model.
* [TreeMix](https://speciationgenomics.github.io/Treemix/) - Uses genome-wide allele frequency data to model population splits and subsequent migration/gene-flow events.

### Locus tree Methods

[SpeciesNetwork](https://github.com/zhangchicool/speciesnetwork) - A BEAST 2 package that can infer phylogenetic networks from multilocus gene trees *or* sequence data using a birth-hybridization network prior.
[PhyloFusion](https://github.com/husonlab/splitstree6) - A part of SplitsTree thats a set of input trees and constructs a tree-child network. The output network then displays all input trees.

### Sequence/Site Methods

* [PhyNest](https://github.com/sungsik-kong/PhyNEST.jl) - A high-performance Julia package that infers level-1 phylogenetic networks directly from DNA sequence alignments. It uses a composite likelihood framework based on quartet site patterns under the network multispecies coalescent.

## Community


### Talk


## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](./contributing.md) to get started.
