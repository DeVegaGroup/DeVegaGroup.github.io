---
layout: default
title: Tools & Repos
nav_order: 5
---

# Open Software and Data

We develop and release analysis code that supports our work. Much of this code is released as public repositories linked to specific papers, theses, or project analyses. Some repositories are reusable workflows, while others are study-specific but still provide transparent and reusable implementations of our methods.

## Genome assembly and assembly QC

### [HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens](https://github.com/DeVegaGroup/HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens)
Scripts used in the haplotype-aware chromosome-level assembly and downstream analysis of *Urochloa decumbens*. The repository supports analyses such as assembly assessment, comparative genomics, ancestry inference, repeat annotation, and structural characterisation of a complex polyploid forage grass genome.

**Linked paper**
- Ryan C, Fraser F, Irish N, Barker T, Knitlhoffer V, Durrant A, Reynolds G, Kaithakottil G, Swarbreck D, De Vega JJ. 2025. *A haplotype-resolved chromosome-level genome assembly of Urochloa decumbens cv. Basilisk resolves its allopolyploid ancestry and composition.* G3.

### [Assembly-and-analysis-Urochloa-humidicola-genome](https://github.com/DeVegaGroup/Assembly-and-analysis-Urochloa-humidicola-genome)
A project repository for the assembly and analysis of *Urochloa humidicola*. It contains scripts used in genome assembly, downstream comparative analysis, and interpretation of genome composition in a highly polyploid tropical forage species.

**Linked preprint**
- De Vega J, Durrant A, Irish N, Barker T, Jauregui RN. 2025. *A haplotype-complete chromosome-level assembly of octoploid Urochloa humidicola cv. Tully reveals multiple genomic compositions and evolutionary histories in the species.*

### [Basecall2Assembly](https://github.com/DeVegaGroup/Basecall2Assembly)
A Snakemake workflow for Oxford Nanopore long-read assembly starting from raw ONT data. The pipeline is designed to take raw sequencing output through preprocessing and into genome assembly.

**What it is useful for**
- Moving from raw ONT data to a draft assembly
- Standardising long-read assembly steps across projects
- Reproducible preprocessing and assembly execution

### [QCPipeline](https://github.com/DeVegaGroup/QCPipeline)
A QC workflow for genome assemblies. This repository provides a standardised framework for evaluating assembly quality and comparing alternative assemblies or parameter sets.

**What it is useful for**
- Assembly quality control
- Rapid comparison of candidate assemblies
- Reproducible reporting of assembly metrics

## Introgression, ancestry, and structural variation

### [introgressions_by_relative_depth](https://github.com/DeVegaGroup/introgressions_by_relative_depth)
This repository implements two alignment-based methods for introgression detection in hybrids and allopolyploids. These methods were developed to characterise ancestry mosaics and chromosomal imbalances using sequence alignment information rather than relying entirely on donor-specific marker panels.

The two core approaches are:

- **Relative Coverage (RC)**: a read-depth-based metric to identify ancestry shifts and introgressed genomic segments
- **Relative Averaged Alignment (RAA)**: an alignment-based metric for inferring subgenome composition and recombination patterns

**Linked paper**
- Higgins J, Osorio-Guarín JA, Olave-Achury C, Toloza-Moreno DL, Enriquez A, Di Palma F, Yockteng R, De Vega JJ. 2023. *Characterizing subgenome recombination and chromosomal imbalances in banana varietal lineages.* Annals of Botany.


## Image analysis and phenotyping

### [SeedClassifier](https://github.com/DeVegaGroup/SeedClassifier)
A seed image classification and segmentation repository built around flatbed-scanned seed images from common wildflower species. The repository compares AI and non-AI segmentation pipelines, evaluates more than 20 classifiers based on extracted seed features, tests CNN classification from single-seed images, and explores open-set recognition using mock seed mixtures containing unseen taxa.

**What it is useful for**
- Benchmarking seed-image segmentation methods
- Comparing classical classifiers and deep-learning approaches
- Testing classification robustness when unknown taxa are present
  
## GWAS, population genomics, and predictive modelling

### [KDJ-CBeans](https://github.com/DeVegaGroup/KDJ-CBeans)
Scripts accompanying our common bean study on determinacy and photoperiod sensitivity. The repository is organised into assembly-related scripts, GWAS scripts, and population structure scripts.

**Linked paper**
- Denning-James KE, Chater C, Cortés AJ, Blair MW, Peláez D, Hall A, De Vega JJ. 2025. *Genome-wide association mapping dissects the selective breeding of determinacy and photoperiod sensitivity in common bean (Phaseolus vulgaris L.).* G3.

### [Kate_PhD_2025_fork](https://github.com/DeVegaGroup/Kate_PhD_2025_fork)
A broader PhD repository extending the common bean work beyond the published GWAS paper. In addition to the scripts included in `KDJ-CBeans`, this repository includes further material for thesis chapters on population structure, climate-related analyses, phenotyping, chromosome coverage, appendices, and associated supporting analyses.

**What it is useful for**
- Common bean population structure analyses
- Trait dissection and follow-up analyses beyond the published paper
- A wider project-level view of the computational work behind the PhD

### [Compare_machine_learning_models](https://github.com/DeVegaGroup/Compare_machine_learning_models)
A Python repository comparing machine-learning models with linear models in common bean datasets. It includes scripts for genotype conversion, repeated cross-validation, and visualisation of model performance.

**What it is useful for**
- Benchmarking predictive models
- Comparing ML and linear baselines
- Preparing genotype matrices for downstream prediction analyses

## Transcriptomics and regulatory inference

### [TF-regulatory-network-inference](https://github.com/DeVegaGroup/TF-regulatory-network-inference)
An analysis repository for transcriptional regulatory network inference and regulon enrichment analysis. It was used to identify transcription factor regulons and connect gene-expression patterns to biomass-related metabolism in Miscanthus.

**Linked paper**
- De Vega JJ, Peel N, Purdy SJ, Hawkins S, Donnison I, Dyer S, Farrar K. 2021. *Differential expression of starch and sucrose metabolic genes linked to varying biomass yield in Miscanthus hybrids.*

### [rnaseq_starch_notebook](https://github.com/DeVegaGroup/rnaseq_starch_notebook)
An R notebook repository containing the RNA-seq analysis for Miscanthus hybrids with contrasting starch, sucrose, and biomass phenotypes. The repository includes the executable notebook, input objects, annotation resources, and generated outputs.

**Linked paper**
- De Vega JJ, Peel N, Purdy SJ, Hawkins S, Donnison I, Dyer S, Farrar K. 2021. *Differential expression of starch and sucrose metabolic genes linked to varying biomass yield in Miscanthus hybrids.*

### [rnaseq_drought_notebook](https://github.com/DeVegaGroup/rnaseq_drought_notebook)
An R notebook repository for differential expression analysis under drought, control, and waterlogging conditions in Miscanthus. It provides a transparent, fully reproducible analysis of transcriptional responses to contrasting water regimes across bioenergy grass genotypes.

**Linked paper**
- De Vega JJ, Teshome A, Klaas M, Grant J, Finnan J, Barth S. 2021. *Physiological and transcriptional response to drought stress among bioenergy grass Miscanthus species.*

## Disease resistance genomics and Musa resources

### [Carolina_PhD_2025](https://github.com/DeVegaGroup/Carolina_PhD_2025)
A thesis-linked repository containing scripts used in chapters 2 and 3 of a PhD on Musa disease-resistance diversity and response to Fusarium TR4 infection. The README indicates that the repository covers:

- Musa diversity genotypic characterisation
- de novo assemblies
- annotation pipeline
- NLR ortholog clustering and NLR architecture
- Musa NLRome characterisation
