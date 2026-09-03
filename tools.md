---
layout: default
title: Datasets and tools
nav_order: 5
---

# Datasets and tools

We develop and release **research software, genome assemblies and annotations, population-genomic datasets, breeding and mapping populations, phenotyping resources and reproducibility workflows** for crop evolutionary genomics and breeding.

Where possible, sequence data are deposited in **ENA/NCBI**, released variant datasets in **EVA**, phenotype and imaging datasets in public repositories, and research software in **GitHub and/or Zenodo**.

Different links on this page refer to different levels of the underlying research resource:

- a **BioProject or ENA study** normally contains the underlying raw sequence reads;
- an **assembly accession** identifies a particular genome assembly;
- **EVA** provides released and reusable variant datasets;
- **Dataverse/Figshare/Zenodo** records may contain phenotypes, variants, assemblies, annotations or software;
- **supplementary tables** frequently contain accession metadata, phenotype matrices, pedigrees, marker genotypes and mapping results that are not deposited elsewhere;
- **GitHub repositories** may contain either reusable tools or publication-specific reproducibility code.

For reuse, please cite the **associated publication** and, where appropriate, the **sequence accession, dataset DOI or software release**.


- [Quick reference of papers, datasets and code — and where to find it](#quick-reference-of-papers-datasets-and-code--and-where-to-find-it)
- [Tools and reusable workflows](#tools-and-reusable-workflows)
- [Genome assemblies and annotations](#genome-assemblies-and-annotations)
- [Genetic diversity, association and mapping populations](#genetic-diversity-association-and-mapping-populations)
- [Phenotyping and image datasets](#phenotyping-and-image-datasets)
- [Transcriptomic datasets](#transcriptomic-datasets)

---

# Quick reference of papers, datasets and code — and where to find it

This section is deliberately redundant. It provides the fastest route from a publication to the corresponding sequence data, code, phenotypes, supplementary tables and other reusable resources.

- **2026**
  - **Seed species classification**
    - **Paper:** [Integrating machine learning, deep learning, and image analysis for seed species classification](https://doi.org/10.1002/aps3.70072)
    - **Code:** [SeedClassifier / SeedAnalyser](https://github.com/DeVegaGroup/SeedClassifier)
    - **Phenotypes:** seed images and derived quantitative image features associated with the study
    - **Tables / data:** trained models, model evaluations and supporting information accompanying the paper
  - **Spittlebug resistance in *Urochloa***
    - **Paper:** [Integrating image-based phenotyping and GWAS to map resistance to spittlebug nymphs in interspecific Urochloa grasses](https://doi.org/10.1093/g3journal/jkag101)
    - **Raw reads:** [ENA PRJEB109285](https://www.ebi.ac.uk/ena/browser/view/PRJEB109285)
    - **Phenotypes:** [Harvard Dataverse DOI 10.7910/DVN/EGUVHA](https://doi.org/10.7910/DVN/EGUVHA)
    - **Tables / data:** supplementary genotype, phenotype and GWAS datasets
  - ***Urochloa humidicola* cv. Tully genome**
    - **Paper:** [A haplotype-complete chromosome-level assembly of octoploid Urochloa humidicola cv. Tully reveals multiple genomic compositions and evolutionary histories in the species](https://doi.org/10.1093/g3journal/jkag033)
    - **Raw reads:** [ENA PRJEB90424](https://www.ebi.ac.uk/ena/browser/view/PRJEB90424)
    - **Code:** [Assembly-and-analysis-Urochloa-humidicola-genome](https://github.com/DeVegaGroup/Assembly-and-analysis-Urochloa-humidicola-genome)
    - **Tables / data:** [assembly and annotation GCA_965614515.2](https://www.ebi.ac.uk/ena/browser/view/GCA_965614515.2) · supplementary genome analyses

- **2025**
  - **Guinea grass diversity-panel GWAS**
    - **Paper:** [Genome-wide association study of a Guinea grass (*Megathyrsus maximus*) diversity panel reveals the genetic basis of agronomic and nutritional traits](https://doi.org/10.1186/s12870-025-08007-2)
    - **Raw reads:** [ENA PRJEB97636](https://www.ebi.ac.uk/ena/browser/view/PRJEB97636)
    - **Phenotypes:** agronomic, biomass and nutritional traits; genotype-level BLUEs/BLUPs
    - **Tables / data:** Supplementary Materials 1–2
  - **Napier grass global diversity and progeny**
    - **Paper:** [Whole-genome resequencing of a global collection of Napier grass (*Cenchrus purpureus*) to explore global population structure and QTL governing yield and feed quality traits](https://doi.org/10.1093/g3journal/jkaf113)
    - **Raw reads:** [ENA PRJEB73794](https://www.ebi.ac.uk/ena/browser/view/PRJEB73794)
    - **Phenotypes:** yield, agronomic and feed-quality measurements
    - **Tables / data:** [EVA SNP dataset PRJEB88573](https://www.ebi.ac.uk/eva/?eva-study=PRJEB88573) · Supplementary Tables 1–10
  - **Common-bean determinacy and photoperiod GWAS**
    - **Paper:** [Genome-wide association mapping dissects the selective breeding of determinacy and photoperiod sensitivity in common bean (*Phaseolus vulgaris* L.)](https://doi.org/10.1093/g3journal/jkaf090)
    - **Raw reads:** [ENA PRJEB81566](https://www.ebi.ac.uk/ena/browser/view/PRJEB81566)
    - **Code:** [KDJ-CBeans](https://github.com/DeVegaGroup/KDJ-CBeans)
    - **Phenotypes:** growth habit, determinacy and photoperiod response
    - **Tables / data:** supplementary population, phenotype and GWAS outputs
  - ***Urochloa decumbens* cv. Basilisk genome**
    - **Paper:** [A haplotype-resolved chromosome-level genome assembly of Urochloa decumbens cv. Basilisk resolves its allopolyploid ancestry and composition](https://doi.org/10.1093/g3journal/jkaf005)
    - **Raw reads:** [ENA PRJEB73762](https://www.ebi.ac.uk/ena/browser/view/PRJEB73762)
    - **Code:** [HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens](https://github.com/DeVegaGroup/HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens)
    - **Tables / data:** [assembly and annotation GCA_964030465.3](https://www.ebi.ac.uk/ena/browser/view/GCA_964030465.3) · supplementary genome analyses

- **2024–2023**
  - **Banana morphology, fruit-quality and yield GWAS**
    - **Paper:** [Genome-wide association analyses using multilocus models on bananas (*Musa* spp.) reveal candidate genes related to morphology, fruit quality, and yield](https://doi.org/10.1093/g3journal/jkae108)
    - **Raw reads:** [ENA PRJEB62882](https://www.ebi.ac.uk/ena/browser/view/PRJEB62882)
    - **Phenotypes:** morphology, fruit-quality and yield traits
    - **Tables / data:** AGROSAVIA germplasm `COL004` · supplementary GWAS and phenotype datasets
  - **Banana subgenome recombination and chromosomal imbalance**
    - **Paper:** [Characterizing subgenome recombination and chromosomal imbalances in banana varietal lineages](https://doi.org/10.1093/aob/mcad192)
    - **Raw reads:** [ENA PRJEB62882](https://www.ebi.ac.uk/ena/browser/view/PRJEB62882)
    - **Code:** [RAA/RC](https://github.com/DeVegaGroup/introgressions_by_relative_depth) · [Structural-diversity-in-banana-cultivars](https://github.com/jjdevega/Structural-diversity-in-banana-cultivars)
    - **Tables / data:** supplementary ancestry, introgression and chromosome-structure analyses
  - ***Urochloa* genomic composition and cytogenomics**
    - **Paper:** [Complex polyploid and hybrid species in an apomictic and sexual tropical forage grass group: genomic composition and evolution in *Urochloa* (*Brachiaria*) species](https://doi.org/10.1093/aob/mcab147)
    - **Raw reads:** [NCBI PRJNA771228](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA771228)
    - **Tables / data:** accession, cytogenetic, repeat, k-mer and genome-composition datasets in Supplementary Tables S1–S10

- **2022**
  - **Vietnamese rice — genomic regions selected during breeding**
    - **Paper:** [Genomic regions and candidate genes selected during the breeding of rice in Vietnam](https://doi.org/10.1111/eva.13433)
    - **Raw reads:** [ENA PRJEB36631](https://www.ebi.ac.uk/ena/browser/view/PRJEB36631)
    - **Tables / data:** Supplementary Tables S1–S13 with population-genomic signals, selected regions and candidate genes
  - ***Urochloa* population structure and genetic diversity**
    - **Paper:** [Diverged subpopulations in tropical *Urochloa* (*Brachiaria*) forage species indicate a role for facultative apomixis and varying ploidy in their population structure and evolution](https://doi.org/10.1093/aob/mcac115)
    - **Raw reads:** [NCBI PRJNA513453](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA513453)
    - **Tables / data:** 111-accession population, ancestry and population-structure supplementary datasets
  - **Liborino common-bean germplasm**
    - **Paper:** [Genotype Selection, and Seed Uniformity and Multiplication to Ensure Common Bean (*Phaseolus vulgaris* L.) var. Liborino](https://doi.org/10.3390/agronomy12102285)
    - **Phenotypes:** multi-site agronomic and adaptation measurements
    - **Tables / data:** 44-accession passport dataset in Supplementary Table S1 and associated seed/field supplements

- **2021**
  - **Vietnamese native-rice diversity and GWAS panel**
    - **Paper:** [Resequencing of 672 Native Rice Accessions to Explore Genetic Diversity and Trait Associations in Vietnam](https://doi.org/10.1186/s12284-021-00481-0)
    - **Raw reads:** [ENA PRJEB36631](https://www.ebi.ac.uk/ena/browser/view/PRJEB36631)
    - **Phenotypes:** 20 traits across 672 accessions
    - **Tables / data:** Supplementary Tables S1–S11 with accession metadata, population assignments, diversity statistics, GWAS results and functional SNP annotation
  - **Potato multi-environment late-blight population**
    - **Paper:** [Global multi-environment resistance QTL for foliar late blight resistance in tetraploid potato with tropical adaptation](https://doi.org/10.1093/g3journal/jkab251)
    - **Phenotypes:** [CIP Dataverse DOI 10.21223/P3/JJJQV0](https://doi.org/10.21223/P3/JJJQV0) · [DOI 10.21223/6TRC9T](https://doi.org/10.21223/6TRC9T)
    - **Tables / data:** [diploid-coded VCF](https://doi.org/10.6084/m9.figshare.12786398) · [tetraploid-coded VCF](https://doi.org/10.6084/m9.figshare.12789383) · Tables S1–S4 with pedigree, BLUEs, PBLUPs and GBLUPs
  - ***Urochloa ruziziensis* reference genome + aluminium-tolerance/apomixis family resource**
    - **Paper:** [A new genome allows the identification of genes associated with natural variation in aluminium tolerance in Brachiaria grasses](https://doi.org/10.1093/jxb/eraa469)
    - **Paper:** [A Parthenogenesis Gene Candidate and Evidence for Segmental Allopolyploidy in Apomictic Brachiaria decumbens](https://doi.org/10.1534/genetics.116.190314)
    - **Raw reads:** [NCBI PRJNA437375](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA437375)
    - **Phenotypes:** aluminium tolerance and reproductive-mode phenotypes from the shared BRX 44-02 × CIAT 606 family
    - **Tables / data:** [assembly GCA_003016355](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_003016355/) · [genome/annotation Zenodo](https://doi.org/10.5281/zenodo.3941963) · family genotypes, markers, linkage maps and phenotype datasets in the supplementary tables
  - **Sugarcane CC 01-1940 genome**
    - **Paper:** [Unraveling the Genome of a High Yielding Colombian Sugarcane Hybrid](https://doi.org/10.3389/fpls.2021.694859)
    - **Raw reads:** [NCBI PRJNA713858](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA713858)
    - **Tables / data:** [assembly GCA_020102875.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_020102875.1/) · WGS `JAIOJY000000000` · supplementary annotation and comparative-genomics data
  - ***Miscanthus sacchariflorus* genome**
    - **Paper:** [Draft genome assembly of the biofuel grass crop *Miscanthus sacchariflorus*](https://doi.org/10.12688/f1000research.44714.1)
    - **Raw reads:** [PRJNA435476](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA435476) · [PRJNA679435](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA679435)
    - **Tables / data:** WGS `JADQCR000000000` · [genome FASTA, GFF3 annotation and anchoring files](https://doi.org/10.5281/zenodo.4270235)
  - ***Miscanthus* drought transcriptomics**
    - **Paper:** [Physiological and transcriptional response to drought stress among bioenergy grass *Miscanthus* species](https://doi.org/10.1186/s13068-021-01915-z)
    - **Raw reads:** [E-MTAB-9354](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-9354)
    - **Code:** [Zenodo DOI 10.5281/zenodo.3950495](https://doi.org/10.5281/zenodo.3950495) · [analysis site](https://joseja.github.io/miscanthus_drought_rnaseq/)
    - **Tables / data:** differential-expression and functional-analysis supplements
  - ***Miscanthus* starch/sucrose and biomass transcriptomics**
    - **Paper:** [Differential expression of starch and sucrose metabolic genes linked to varying biomass yield in *Miscanthus* hybrids](https://doi.org/10.1186/s13068-021-01948-4)
    - **Raw reads:** [NCBI PRJNA639832](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA639832)
    - **Code:** [R code](https://doi.org/10.5281/zenodo.3834007) · [analysis repository](https://github.com/jjdevega/miscanthus_starch_rnaseq) · [co-expression repository](https://github.com/jjdevega/miscanthus_transcriptional_regulatory_coexpression_network)
    - **Phenotypes:** biomass-related phenotypes
    - **Tables / data:** expression, differential-expression and network-analysis supplements
  - ***Urochloa* drought transcriptomics**
    - **Paper:** [Physiological and transcriptional responses of tropical forage grasses to drought stress](https://doi.org/10.3389/fpls.2021.637956)
    - **Raw reads:** [ENA PRJEB41722](https://www.ebi.ac.uk/ena/browser/view/PRJEB41722)
    - **Phenotypes:** physiological drought-response measurements
    - **Tables / data:** differential-expression, pathway and GO analyses

- **2020**
  - ***Miscanthus sinensis* chromosome-scale genome and population variation**
    - **Paper:** [Genome biology of the paleotetraploid perennial biomass crop *Miscanthus*](https://doi.org/10.1038/s41467-020-18923-6)
    - **Raw reads:** [genomic reads PRJNA346689](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA346689) · transcriptomic reads `PRJNA575573` and `SRP017791`
    - **Code:** [Miscanthus-genome](https://github.com/miscanthus-paper/Miscanthus-genome)
    - **Tables / data:** genome, annotation and variation resources through Phytozome · Source Data · Supplementary Data · four-cross genetic map
  - **Red-clover diversity panel**
    - **Paper:** [Population structure and genetic diversity in red clover (*Trifolium pratense* L.) germplasm](https://doi.org/10.1038/s41598-020-64989-z)
    - **Raw reads:** [ENA PRJEB30826](https://www.ebi.ac.uk/ena/browser/view/PRJEB30826)
    - **Phenotypes:** survival, flowering, vegetative growth and environmental variables
    - **Tables / data:** 75 accessions / 640 plants · candidate-selection, population, phenotype and geographic tables

- **2019**
  - ***Lolium perenne* physical genome resource and European GWAS panel**
    - **Paper:** [Integrating a newly developed BAC-based physical mapping resource for *Lolium perenne* with a genome-wide association study across a *L. perenne* European ecotype collection identifies genomic contexts associated with agriculturally important traits](https://doi.org/10.1093/aob/mcy230)
    - **Raw reads:** [BAC sequencing BioProject PRJNA475227](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA475227)
    - **Phenotypes:** 716 genotypes from 90 European accessions evaluated for agronomic traits
    - **Tables / data:** [LpBAC5000](https://doi.org/10.20391/dfb05330-7485-444f-a475-8310bee5d510) · [physical maps](https://doi.org/10.20391/bb56e6d7-8913-4bd7-8167-2b7e4c01382b) · [BAC-end database](https://doi.org/10.20391/61921116-ddd0-4d85-b0fd-e0d734bc63c8) · Supplementary Table S2 accession geography

- **2016**
  - ***Urochloa* apomixis / aluminium-tolerance F1 family**
    - **Paper:** [A Parthenogenesis Gene Candidate and Evidence for Segmental Allopolyploidy in Apomictic *Brachiaria decumbens*](https://doi.org/10.1534/genetics.116.190314)
    - **Paper:** [A new genome allows the identification of genes associated with natural variation in aluminium tolerance in Brachiaria grasses](https://doi.org/10.1093/jxb/eraa469)
    - **Phenotypes:** reproductive mode and aluminium tolerance in the same BRX 44-02 × CIAT 606 segregating family
    - **Tables / data:** GBS genotypes, segregation classes, linkage maps, phenotype datasets and candidate-region analyses

- **2015**
  - **Red-clover reference genome**
    - **Paper:** [Red clover (*Trifolium pratense* L.) draft genome provides a platform for trait improvement](https://doi.org/10.1038/srep17394)
    - **Raw reads:** [ENA PRJEB9186](https://www.ebi.ac.uk/ena/browser/view/PRJEB9186)
    - **Tables / data:** [genome and annotation files on Zenodo](https://doi.org/10.5281/zenodo.17232) · BAC ends `HR235466–HR298279` · Supplementary Table 5 sequencing-library information

---

# Tools and reusable workflows

## LegumeDiscovery

**LegumeDiscovery** provides an entry point for discovering and navigating curated legume breeding datasets and analysis-ready resources generated through our work on crop improvement.

The aim is to make breeding data easier to **find, interpret and reuse**, connecting germplasm, experiments, environments and traits with harmonised phenotype datasets and downstream analyses.

Activities around these datasets include:

- curation and harmonisation of breeding-trial data;
- consistent trait definitions and metadata;
- integration of multi-site and multi-season experiments;
- generation of analysis-ready phenotype matrices;
- genotype quality control and imputation;
- quantitative-genetic analyses;
- genomic prediction and association analyses.

**Resource:** [DeVegaGroup on GitHub](https://github.com/DeVegaGroup)

---

## autoBLUEs/BLUPs

**autoBLUEs/BLUPs** automates mixed-model analysis of replicated and multi-environment phenotyping experiments to generate genotype-level **BLUEs** — best linear unbiased estimates — and **BLUPs** — best linear unbiased predictions.

The workflow provides a reproducible bridge between raw experimental observations and downstream analyses including:

- GWAS;
- genomic prediction;
- genotype ranking and selection;
- multi-environment trial analysis;
- estimation of genetic and environmental effects;
- genotype × environment analysis;
- comparison of traits across experiments, seasons and locations.

**Resource:** [DeVegaGroup on GitHub](https://github.com/DeVegaGroup)

---

## SeedAnalyser

**SeedAnalyser** is our computer-vision and machine-learning framework for extracting quantitative information from scanned seeds and classifying seed species.

**Code:** [SeedClassifier](https://github.com/DeVegaGroup/SeedClassifier)

The repository includes:

- ImageJ macros;
- OpenCV-based segmentation;
- Cellpose-based segmentation;
- extraction of seed dimensions and image-derived features;
- comparison of conventional image-analysis pipelines;
- classical machine-learning classifiers;
- deep-learning / ResNet classification;
- trained models;
- model evaluation;
- open-set classification experiments.

**Paper:** [Integrating machine learning, deep learning, and image analysis for seed species classification](https://doi.org/10.1002/aps3.70072).

---

## Relative Averaged Alignment and Relative Coverage

We developed two alignment-based approaches for identifying ancestry changes and introgressed chromosome segments:

- **Relative Averaged Alignment (RAA)**
- **Relative Coverage (RC)**

**Code:** [introgressions_by_relative_depth](https://github.com/DeVegaGroup/introgressions_by_relative_depth)

**Paper-specific analyses:** [Structural-diversity-in-banana-cultivars](https://github.com/jjdevega/Structural-diversity-in-banana-cultivars)

**Paper:** [Characterizing subgenome recombination and chromosomal imbalances in banana varietal lineages](https://doi.org/10.1093/aob/mcad192).

**Sequence data:** [ENA PRJEB62882](https://www.ebi.ac.uk/ena/browser/view/PRJEB62882).

---

## Basecall2Assembly

**Basecall2Assembly** is a Snakemake workflow for moving from raw Oxford Nanopore Technologies sequence data towards a genome assembly.

- **Repository:** [Basecall2Assembly](https://github.com/DeVegaGroup/Basecall2Assembly)
- **Archived release:** [Zenodo DOI 10.5281/zenodo.15005311](https://doi.org/10.5281/zenodo.15005311)

---

## QCPipeline

**QCPipeline** provides a reproducible workflow for quality control and evaluation of genome assemblies.

**Repository:** [QCPipeline](https://github.com/DeVegaGroup/QCPipeline)

It complements **Basecall2Assembly** and the project-specific assembly workflows distributed with our genome publications.

---

# Genome assemblies and annotations

This section contains reference genomes, chromosome-scale assemblies, draft genomes, structural and functional annotations, and physical genome resources.

Population-level genetic diversity datasets derived from these or related studies are listed independently below.

---

## *Urochloa humidicola* cv. Tully — haplotype-complete octoploid genome

A haplotype-resolved chromosome-scale reference for the octoploid tropical forage grass *Urochloa humidicola* cv. Tully.

- **Raw sequence data:** [ENA PRJEB90424](https://www.ebi.ac.uk/ena/browser/view/PRJEB90424)
- **Genome assembly and annotation:** [GCA_965614515.2](https://www.ebi.ac.uk/ena/browser/view/GCA_965614515.2)
- **Code:** [Assembly-and-analysis-Urochloa-humidicola-genome](https://github.com/DeVegaGroup/Assembly-and-analysis-Urochloa-humidicola-genome)
- **Paper:** [A haplotype-complete chromosome-level assembly of octoploid *Urochloa humidicola* cv. Tully reveals multiple genomic compositions and evolutionary histories in the species](https://doi.org/10.1093/g3journal/jkag033)
- **Supplementary data:** genome assembly, comparative-genomics and subgenome analyses accompanying the paper.

The analysis repository contains workflows for long-read assembly, scaffolding, read mapping, assembly assessment, BUSCO, KAT, dot plots, orthology, phylogenomics and analysis of chromosome/subgenome composition.

---

## *Urochloa decumbens* cv. Basilisk — haplotype-resolved allotetraploid genome

A chromosome-level haplotype-resolved assembly of the apomictic allotetraploid *Urochloa decumbens* cv. Basilisk.

- **Raw sequence data:** [ENA PRJEB73762](https://www.ebi.ac.uk/ena/browser/view/PRJEB73762)
- **Genome assembly and annotation:** [GCA_964030465.3](https://www.ebi.ac.uk/ena/browser/view/GCA_964030465.3)
- **Code:** [HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens](https://github.com/DeVegaGroup/HaplotypeAwareChromosomeLevelAssemblyUrochloaDecumbens)
- **Paper:** [A haplotype-resolved chromosome-level genome assembly of *Urochloa decumbens* cv. Basilisk resolves its allopolyploid ancestry and composition](https://doi.org/10.1093/g3journal/jkaf005)
- **Supplementary data:** assembly, ancestry, repeat and comparative-genomics analyses accompanying the paper.

The repository contains workflows for assembly, ancestry clustering, BUSCO, Merqury, repeat analysis, genome-composition plots, dot plots and synteny.

---

## *Urochloa ruziziensis* CIAT 26162 — reference genome and annotation

A reference genome for diploid *Urochloa ruziziensis* CIAT 26162 developed to support comparative genomics and mapping of natural variation in tropical forage grasses.

- **BioProject:** [NCBI PRJNA437375](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA437375)
- **Genome assembly:** [GCA_003016355](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_003016355/)
- **Genome and annotation archive:** [Zenodo DOI 10.5281/zenodo.3941963](https://doi.org/10.5281/zenodo.3941963)
- **Paper:** [A new genome allows the identification of genes associated with natural variation in aluminium tolerance in Brachiaria grasses](https://doi.org/10.1093/jxb/eraa469)
- **Supplementary data:** genome sequence, chromosome anchoring, structural annotation, functional annotation and mapping analyses.

The associated BRX 44-02 × CIAT 606 family is listed separately in the population section.

---

## *Miscanthus sinensis* DH1 — chromosome-scale reference genome

A chromosome-scale reference genome for *Miscanthus sinensis*, assembled into its 19 chromosomes and used for comparative, evolutionary and population-genomic analyses.

- **Genome-sequencing BioProject:** [NCBI PRJNA346689](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA346689)
- **Transcriptomic BioProject:** `PRJNA575573`
- **Additional transcriptomic study:** `SRP017791`
- **Genome, annotation and variation resources:** Phytozome
- **Code:** [miscanthus-paper/Miscanthus-genome](https://github.com/miscanthus-paper/Miscanthus-genome)
- **Paper:** [Genome biology of the paleotetraploid perennial biomass crop *Miscanthus*](https://doi.org/10.1038/s41467-020-18923-6)
- **Supplementary data:** Source Data and extensive Supplementary Data accompanying the paper.

A four-cross genetic map containing 4,298 uniquely assigned markers was used in validating and anchoring the chromosome-scale assembly.

---

## *Miscanthus sacchariflorus* cv. Robustus 297 — draft genome and annotation

A draft genome resource for the bioenergy grass *Miscanthus sacchariflorus* cv. Robustus 297.

- **Genome-sequencing BioProject:** [NCBI PRJNA435476](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA435476)
- **Assembly/annotation BioProject:** [NCBI PRJNA679435](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA679435)
- **WGS accession:** `JADQCR000000000`
- **Genome, annotation and anchoring files:** [Zenodo DOI 10.5281/zenodo.4270235](https://doi.org/10.5281/zenodo.4270235)
- **Paper:** [Draft genome assembly of the biofuel grass crop *Miscanthus sacchariflorus*](https://doi.org/10.12688/f1000research.44714.1)

The Zenodo archive includes genome FASTA, chromosome-anchored sequence, GFF3 gene annotation, functional annotation and AGP anchoring information.

---

## Sugarcane hybrid CC 01-1940 — chromosome-level genome and annotation

A chromosome-level genome assembly of the high-yielding Colombian sugarcane hybrid CC 01-1940.

- **BioProject:** [NCBI PRJNA713858](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA713858)
- **Genome assembly:** [GCA_020102875.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_020102875.1/)
- **WGS accession:** `JAIOJY000000000`
- **Paper:** [Unraveling the Genome of a High Yielding Colombian Sugarcane Hybrid](https://doi.org/10.3389/fpls.2021.694859)
- **Supplementary data:** structural and functional annotation, comparative genomics and associated analyses.

---

## *Lolium perenne* P226/135/16 — BAC physical map and genome-sequence resource

A physical genome and BAC-sequence resource connecting the *Lolium perenne* genome with genetic mapping and association analyses.

- **BioProject:** [NCBI PRJNA475227](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA475227)
- **BioSample:** `SAMN09382314`
- **SRA study:** `SRP150420`
- **LpBAC5000:** [DOI 10.20391/dfb05330-7485-444f-a475-8310bee5d510](https://doi.org/10.20391/dfb05330-7485-444f-a475-8310bee5d510)
- **Physical maps:** [DOI 10.20391/bb56e6d7-8913-4bd7-8167-2b7e4c01382b](https://doi.org/10.20391/bb56e6d7-8913-4bd7-8167-2b7e4c01382b)
- **BAC-end database:** [DOI 10.20391/61921116-ddd0-4d85-b0fd-e0d734bc63c8](https://doi.org/10.20391/61921116-ddd0-4d85-b0fd-e0d734bc63c8)
- **BAC-end GenBank accessions:** `MJ032229–MJ424519`
- **Paper:** [Integrating a newly developed BAC-based physical mapping resource for *Lolium perenne* with a genome-wide association study across a *L. perenne* European ecotype collection identifies genomic contexts associated with agriculturally important traits](https://doi.org/10.1093/aob/mcy230)

Important supplementary resources include marker sequences, SNP positions, BAC-library statistics, complete FPC/LTC physical maps and genome-coverage statistics.

The associated 716-genotype European GWAS panel is listed separately below.

---

## Red clover (*Trifolium pratense*) — draft genome and annotation

A draft reference genome and gene annotation for red clover.

- **Raw sequence libraries and assembly:** [ENA PRJEB9186](https://www.ebi.ac.uk/ena/browser/view/PRJEB9186)
- **Genome FASTA and annotation:** [Zenodo DOI 10.5281/zenodo.17232](https://doi.org/10.5281/zenodo.17232)
- **BAC-end sequences:** `HR235466–HR298279`
- **Paper:** [Red clover (*Trifolium pratense* L.) draft genome provides a platform for trait improvement](https://doi.org/10.1038/srep17394)
- **Supplementary Table 5:** shotgun sequencing libraries used for the reference assembly.

---

# Genetic diversity, association and mapping populations

This section contains crop diversity panels, germplasm collections, GWAS populations, breeding populations and segregating families.

The ordering is intended to make the larger crop-population resources easy to find first.

---

## Vietnamese native-rice diversity panel

A whole-genome resequencing resource comprising **672 Vietnamese native rice accessions**, developed for analysis of crop diversity, population structure, trait association and genomic regions affected by breeding.

### Data

- **Whole-genome resequencing:** [ENA PRJEB36631](https://www.ebi.ac.uk/ena/browser/view/PRJEB36631)
- **Paper:** [Resequencing of 672 Native Rice Accessions to Explore Genetic Diversity and Trait Associations in Vietnam](https://doi.org/10.1186/s12284-021-00481-0)
- **Selection paper:** [Genomic regions and candidate genes selected during the breeding of rice in Vietnam](https://doi.org/10.1111/eva.13433)

### Particularly reusable supplementary tables

- **Table S1:** accession identities, National Genebank numbers, local names, collection locations, sequencing/mapping statistics and population assignments.
- **Table S2:** comparative dataset of 3,635 rice varieties.
- **Table S3:** phenotypic measurements for 20 traits across the 672 accessions.
- **Table S4:** phenotype definitions and abbreviations.
- **Table S5:** phenotype summary statistics and population comparisons.
- **Table S6:** nucleotide diversity by subpopulation.
- **Table S7:** GWAS results and reported QTL.
- **Table S8:** genes associated with QTL.
- **Table S9:** IRRI accessions.
- **Table S10:** definitions of the SNP datasets used in the analyses.
- **Table S11:** functional annotation of the SNP set.

The later selection study adds **Supplementary Tables S1–S13** describing selected genomic regions, population-genomic statistics and candidate genes.

---

## Banana diversity panel — population structure, introgression and GWAS

A whole-genome resequencing panel of cultivated bananas used for studies of ancestry, subgenome recombination, chromosomal imbalance and agronomic-trait association.

### Data

- **Whole-genome sequence data:** [ENA PRJEB62882](https://www.ebi.ac.uk/ena/browser/view/PRJEB62882)
- **Germplasm collection:** AGROSAVIA collection, MGIS `COL004`
- **Introgression code:** [introgressions_by_relative_depth](https://github.com/DeVegaGroup/introgressions_by_relative_depth)
- **Analysis repository:** [Structural-diversity-in-banana-cultivars](https://github.com/jjdevega/Structural-diversity-in-banana-cultivars)

### Papers

- [Characterizing subgenome recombination and chromosomal imbalances in banana varietal lineages](https://doi.org/10.1093/aob/mcad192)
- [Genome-wide association analyses using multilocus models on bananas (*Musa* spp.) reveal candidate genes related to morphology, fruit quality, and yield](https://doi.org/10.1093/g3journal/jkae108)

The same genomic panel can be reused for:

- ancestry inference;
- population structure;
- introgression;
- chromosome imbalance;
- structural diversity;
- association mapping.

Phenotypes covering morphology, fruit quality and yield are supplied through the GWAS paper and its supplementary datasets.

---

# Legume populations

## Red clover diversity panel

A diversity resource designed to characterise population structure, adaptation and useful genetic variation across European and Asian red clover germplasm.

### Population

- **75 accessions**
- 70 natural populations/ecotypes and five commercial varieties
- **640 individual plants** originally sampled

### Data

- **GBS:** [ENA PRJEB30826](https://www.ebi.ac.uk/ena/browser/view/PRJEB30826)
- **Paper:** [Population structure and genetic diversity in red clover (*Trifolium pratense* L.) germplasm](https://doi.org/10.1038/s41598-020-64989-z)

### Supplementary resources

The supplementary spreadsheets contain:

- SNP statistics;
- accession-level heterozygosity;
- AMOVA;
- outlier loci and candidate genes;
- genotype–environment associations;
- survival;
- flowering;
- plant architecture;
- geographic and climate groupings;
- commercial-variety metadata.

Particularly useful tables include:

- **Table S4:** candidate loci showing signatures of selection.
- **Table S6:** survival/mortality.
- **Table S7:** vegetative-growth phenotypes.
- **Table S8:** geographic/climatic grouping.
- **Table S9:** commercial-variety metadata.

---

## Common bean diversity panel — determinacy and photoperiod

A whole-genome resequencing panel used to dissect selection for growth habit, determinacy and photoperiod sensitivity.

### Data and code

- **Whole-genome sequence data:** [ENA PRJEB81566](https://www.ebi.ac.uk/ena/browser/view/PRJEB81566)
- **Analysis repository:** [KDJ-CBeans](https://github.com/DeVegaGroup/KDJ-CBeans)
- **Paper:** [Genome-wide association mapping dissects the selective breeding of determinacy and photoperiod sensitivity in common bean (*Phaseolus vulgaris* L.)](https://doi.org/10.1093/g3journal/jkaf090)
- **Phenotypes and GWAS results:** supplementary material accompanying the paper.

---

## Liborino common-bean germplasm panel

A collection of **44 Liborino-type common bean accessions** used for germplasm characterisation, adaptation, yield evaluation and participatory selection.

- **Paper:** [Genotype Selection, and Seed Uniformity and Multiplication to Ensure Common Bean (*Phaseolus vulgaris* L.) var. Liborino](https://doi.org/10.3390/agronomy12102285)
- **Supplementary Table S1:** passport information for the 44 accessions.
- **Supplementary Figure S1:** seed-coat patterns.
- **Supplementary Figure S2:** days to harvest for locally adapted accessions.

No separate public sequence BioProject was identified for this experiment; the primary reusable resources are the germplasm metadata and multi-site phenotype datasets published with the article.

---

# Temperate grasses and bioenergy crops

## *Lolium perenne* European ecotype GWAS population

A European ryegrass diversity population consisting of:

- **716 diploid genotypes**
- from **90 accessions / collection sites**
- phenotyped over two years;
- genotyped using a custom *Lolium* Infinium SNP array.

### Resources

- **Paper:** [Integrating a newly developed BAC-based physical mapping resource for *Lolium perenne* with a genome-wide association study across a *L. perenne* European ecotype collection identifies genomic contexts associated with agriculturally important traits](https://doi.org/10.1093/aob/mcy230)
- **Supplementary Table S2:** geographical collection sites for the GWAS accessions.
- **Supplementary Methods S4–S5:** field and analytical-chemistry phenotyping protocols.
- **Supplementary Table S1:** map positions and SNP/marker sequences connecting association signals with the BAC resource.
- **Associated physical-genome BioProject:** [NCBI PRJNA475227](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA475227)

The BioProject contains the BAC/genome-sequence resource; the GWAS population genotype and phenotype information is supplied primarily through the publication and supplementary datasets.

---

## *Miscanthus* diversity, admixture and mapping populations

The *Miscanthus sinensis* genome study also generated substantial population-genomic and mapping resources.

### Data

- **Reference-genome reads:** [NCBI PRJNA346689](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA346689)
- **Genome, annotation and variation resources:** Phytozome
- **Code:** [miscanthus-paper/Miscanthus-genome](https://github.com/miscanthus-paper/Miscanthus-genome)
- **Paper:** [Genome biology of the paleotetraploid perennial biomass crop *Miscanthus*](https://doi.org/10.1038/s41467-020-18923-6)
- **Population and mapping outputs:** Source Data and Supplementary Data accompanying the paper.

The analyses cover *M. sinensis*, *M. sacchariflorus*, interspecific admixture and the evolutionary origin of *M. × giganteus*.

A four-cross genetic map with 4,298 uniquely assigned markers provides an additional family-based mapping resource.

---

## Potato TON multi-environment breeding population

A **380-genotype tetraploid potato breeding panel** from the International Potato Center, evaluated for late-blight resistance across multiple environments.

### Phenotypes

- [CIP Dataverse DOI 10.21223/P3/JJJQV0](https://doi.org/10.21223/P3/JJJQV0)
- [CIP Dataverse DOI 10.21223/6TRC9T](https://doi.org/10.21223/6TRC9T)

### Genotypes

- **Diploid-coded VCF:** [Figshare DOI 10.6084/m9.figshare.12786398](https://doi.org/10.6084/m9.figshare.12786398)
- **Tetraploid-coded VCF:** [Figshare DOI 10.6084/m9.figshare.12789383](https://doi.org/10.6084/m9.figshare.12789383)

### Supplementary tables

- **Table S1:** population assignments and parentage of 380 genotypes.
- **Table S2:** genotype BLUEs for rAUDPC by environment.
- **Table S3:** pedigree BLUPs.
- **Table S4:** genomic BLUPs.

**Paper:** [Global multi-environment resistance QTL for foliar late blight resistance in tetraploid potato with tropical adaptation](https://doi.org/10.1093/g3journal/jkab251).

This is a particularly reusable breeding dataset because field data, genotype calls and derived BLUE/BLUP values are all publicly available.

---

# Tropical forage-grass populations

## Guinea grass (*Megathyrsus maximus*) diversity and GWAS panel

A diversity panel of **124 genebank accessions** used to investigate the genetic basis of agronomic, biomass and nutritional traits.

- **Whole-genome sequencing:** [ENA PRJEB97636](https://www.ebi.ac.uk/ena/browser/view/PRJEB97636)
- **Paper:** [Genome-wide association study of a Guinea grass (*Megathyrsus maximus*) diversity panel reveals the genetic basis of agronomic and nutritional traits](https://doi.org/10.1186/s12870-025-08007-2)
- **Supplementary Material 1:** phenotype and association-analysis resources.
- **Supplementary Material 2:** additional methods and results.

Traits include plant architecture, flowering, biomass production, protein, fibre and digestibility.

---

## Napier grass (*Cenchrus purpureus*) global diversity collection and progeny

A global resequencing resource containing **450 Napier grass genotypes** sampled from international germplasm and breeding collections.

The study also includes **109 open-pollinated progeny** from 14 maternal genotypes.

### Data

- **Raw whole-genome sequence data:** [ENA PRJEB73794](https://www.ebi.ac.uk/ena/browser/view/PRJEB73794)
- **Released SNP dataset:** [EVA PRJEB88573](https://www.ebi.ac.uk/eva/?eva-study=PRJEB88573)
- **Paper:** [Whole-genome resequencing of a global collection of Napier grass (*Cenchrus purpureus*) to explore global population structure and QTL governing yield and feed quality traits](https://doi.org/10.1093/g3journal/jkaf113)

### Supplementary datasets

- **Table 1:** accession metadata and phenotype information.
- **Table 2:** detailed trait performance.
- **Table 3:** PCA results.
- **Table 4:** chromosome-level SNP statistics.
- **Table 5:** population/admixture assignments.
- **Table 6:** interspecific hybrids.
- **Tables 7–10:** marker-trait associations and candidate regions.

---

## *Urochloa* 111-accession population-genomic panel

A multispecies tropical-forage panel designed to investigate how reproductive mode, hybridisation and genome composition influence population structure.

### Data

- **RNA-seq / population sequence data:** [NCBI PRJNA513453](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA513453)
- **Paper:** [Diverged subpopulations in tropical *Urochloa* (*Brachiaria*) forage species indicate a role for facultative apomixis and varying ploidy in their population structure and evolution](https://doi.org/10.1093/aob/mcac115)
- **Supplementary data:** accession, SNP, population-structure, ancestry and genetic-diversity analyses.

The resource includes **111 genetically distinct accessions** and supports analyses of:

- species relationships;
- genetic differentiation;
- admixture;
- reproductive mode;
- subpopulation structure.

---

## *Urochloa* genomic-composition and cytogenomic collection

A broad germplasm characterisation resource integrating taxonomy, genome composition, cytogenetics, repetitive-DNA analysis and whole-genome sequencing.

### Data

- **Germplasm panel:** 362 accessions.
- **Whole-genome sequencing:** nine representative accessions.
- **WGS BioProject:** [NCBI PRJNA771228](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA771228)
- **Paper:** [Complex polyploid and hybrid species in an apomictic and sexual tropical forage grass group: genomic composition and evolution in *Urochloa* (*Brachiaria*) species](https://doi.org/10.1093/aob/mcab147)

### Supplementary datasets

- **Table S1:** accessions, genome composition, growth habits and geographic distributions.
- **Table S2:** sequencing data for the nine WGS accessions.
- **Tables S3–S4:** genome-specific candidate sequences and probes.
- **Tables S7–S10:** repeat, k-mer, genome-specific sequence and transposable-element analyses.

---

## *Urochloa* apomixis and aluminium-tolerance F1 mapping family

The apomixis and aluminium-tolerance studies use the **same interspecific BRX 44-02 × CIAT 606 family** and are therefore presented here as a single reusable genetic resource.

### Population

- approximately **169 F1 progeny**
- sexual *U. ruziziensis* BRX 44-02 × apomictic *U. decumbens* CIAT 606 cv. Basilisk

The population has been used to study both:

- reproductive mode and the apospory-specific genomic region;
- natural variation in aluminium tolerance.

### Genome and sequence resources

- **Reference-genome BioProject:** [NCBI PRJNA437375](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA437375)
- **Reference assembly:** [GCA_003016355](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_003016355/)
- **Genome and annotation archive:** [Zenodo DOI 10.5281/zenodo.3941963](https://doi.org/10.5281/zenodo.3941963)

### Apomixis paper

[A Parthenogenesis Gene Candidate and Evidence for Segmental Allopolyploidy in Apomictic *Brachiaria decumbens*](https://doi.org/10.1534/genetics.116.190314)

Reusable supplementary resources include:

- GBS sequencing depth;
- marker and primer information;
- marker genotype scores for the family;
- marker segregation classes;
- linkage-map markers;
- comparative positions relative to foxtail millet;
- reproductive-mode phenotypes.

### Aluminium-tolerance paper

[A new genome allows the identification of genes associated with natural variation in aluminium tolerance in Brachiaria grasses](https://doi.org/10.1093/jxb/eraa469)

Reusable supplementary resources include:

- aluminium-tolerance phenotypes;
- genetic markers and association/mapping results;
- candidate genomic regions;
- genome structural and functional annotation.

Together, the two studies make this one of the more extensively characterised *Urochloa* segregating families.

---

## *Urochloa* spittlebug-resistance F1 population

A breeding population of **339 interspecific F1 hybrids** used to dissect resistance and tolerance to *Aeneolamia varia* spittlebug nymphs.

### Data

- **RAD-seq:** [ENA PRJEB109285](https://www.ebi.ac.uk/ena/browser/view/PRJEB109285)
- **Image-phenotyping dataset:** [Harvard Dataverse DOI 10.7910/DVN/EGUVHA](https://doi.org/10.7910/DVN/EGUVHA)
- **Paper:** [Integrating image-based phenotyping and GWAS to map resistance to spittlebug nymphs in interspecific *Urochloa* grasses](https://doi.org/10.1093/g3journal/jkag101)
- **Supplementary resources:** genotype, phenotype and association-analysis outputs.

The combination of genomic data and thousands of plant images makes this both a mapping-population dataset and an independently reusable computer-vision resource.

---

# Phenotyping and image datasets

## *Urochloa* spittlebug plant-damage image collection

A high-throughput image dataset generated from experimentally phenotyped *Urochloa* plants challenged with spittlebug nymphs.

- **Image dataset:** [Harvard Dataverse DOI 10.7910/DVN/EGUVHA](https://doi.org/10.7910/DVN/EGUVHA)
- **Associated RAD-seq:** [ENA PRJEB109285](https://www.ebi.ac.uk/ena/browser/view/PRJEB109285)
- **Paper:** [Integrating image-based phenotyping and GWAS to map resistance to spittlebug nymphs in interspecific *Urochloa* grasses](https://doi.org/10.1093/g3journal/jkag101)

The collection can be reused independently for development and benchmarking of quantitative plant-damage and computer-vision methods.

---

## Seed image-analysis and classification resources

Resources associated with **SeedAnalyser** include seed images, quantitative image descriptors, trained models and model-evaluation code.

- **Code and models:** [SeedClassifier](https://github.com/DeVegaGroup/SeedClassifier)
- **Paper:** [Integrating machine learning, deep learning, and image analysis for seed species classification](https://doi.org/10.1002/aps3.70072)
- **Supporting data:** supplementary information accompanying the publication.

The repository supports reuse of segmentation, feature extraction, classical machine learning and deep-learning components independently of the complete pipeline.

---

# Transcriptomic datasets

## *Miscanthus* drought-response transcriptomics

RNA-seq data examining physiological and transcriptional responses to drought across *Miscanthus* material.

- **RNA-seq:** [ArrayExpress/BioStudies E-MTAB-9354](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-9354)
- **Archived R analysis:** [Zenodo DOI 10.5281/zenodo.3950495](https://doi.org/10.5281/zenodo.3950495)
- **Analysis site:** [miscanthus_drought_rnaseq](https://joseja.github.io/miscanthus_drought_rnaseq/)
- **Paper:** [Physiological and transcriptional response to drought stress among bioenergy grass *Miscanthus* species](https://doi.org/10.1186/s13068-021-01915-z)
- **Supplementary datasets:** phenotype/model outputs, differential-expression analyses and pathway/function analyses.

---

## *Miscanthus* biomass, starch and sucrose transcriptomics

A transcriptomic resource linking expression of starch- and sucrose-metabolism genes with variation in biomass yield.

- **RNA-seq:** [NCBI PRJNA639832](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA639832)
- **Archived R code:** [Zenodo DOI 10.5281/zenodo.3834007](https://doi.org/10.5281/zenodo.3834007)
- **Analysis repository:** [miscanthus_starch_rnaseq](https://github.com/jjdevega/miscanthus_starch_rnaseq)
- **Co-expression analyses:** [miscanthus_transcriptional_regulatory_coexpression_network](https://github.com/jjdevega/miscanthus_transcriptional_regulatory_coexpression_network)
- **Paper:** [Differential expression of starch and sucrose metabolic genes linked to varying biomass yield in *Miscanthus* hybrids](https://doi.org/10.1186/s13068-021-01948-4)

Supplementary resources include phenotype measurements, normalised expression values, differential-expression statistics, functional annotations and regulatory/network analyses.

---

## *Urochloa* drought-response transcriptomics

A transcriptomic experiment examining drought responses in contrasting *Urochloa* hybrid genotypes.

- **RNA-seq:** [ENA PRJEB41722](https://www.ebi.ac.uk/ena/browser/view/PRJEB41722)
- **Paper:** [Physiological and transcriptional responses of tropical forage grasses to drought stress](https://doi.org/10.3389/fpls.2021.637956)
- **Supplementary resources:** physiological measurements, differential-expression results, pathway analyses and GO analyses.

---

# Reuse and cite!
