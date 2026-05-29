---
layout: page
title: Day 3
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial
  isPartOf:
      url: "https://longtrec.github.io/summer_school/"
      name: "LongTREC summer school - long-read transcriptomics"
---

<img src="../assets/logos/LongTREC_logo_FINAL.png" width="200" /> <img src="../assets/logos/OSCARS.png" width="150" />

# Day 3 Agenda

## Goals
**Morning session: Differential expression and haplotype analysis**
* To learn how long-read RNA-seq can be used for differential isoform expression/usage analysis and what are the current challenges.
* To learn about specific case of expression analysis: allele-specific expression & haplotype analysis.

**Afternoon session: Single-cell transcriptomics with long reads**
* Learn the differences between bulk experiments and single-cell experiments (library preparation and data).
* Understand the different steps involved in going from Long Sequencing Reads to gene and isoform matrices.
* Learn the basics of tertiary analysis for single cell data with focus on long-read specific steps.

## Timetable

| Time | Activity | Details |
|------|---------|---------|
| 09:00 - 10:30 | Differential Expression & DIU | <u>Ana</u>: How to build your expression matrix and concept of DE analysis vs DIU. Hands-on with tappAS and IsoTools. |
| 10:30 - 11:00 | **Coffee Break** | |
| 11:00 - 12:30 | Allele-specific & Haplotype analysis | <u>Nadja</u>: Biases, limitations and pipelines for allele-specific expression. Hands-on ASE quantification and analysis. |
| 12:30 - 13:30 | **Lunch break** | |
| 13:30 - 15:00 | Single-Cell Long-Read intro & QC | <u>Eamon & Fran</u>: Library preparation overview, Preprocessing and QC for single-cell long-reads. |
| 15:00 - 15:30 | **Coffee Break** | |
| 15:30 - 17:00 | Tertiary analysis & Hands-on | <u>Eamon & Fran</u>: Filtering, QC, cell typing, gene & isoform level analysis. Pipeline overview and exploring differential isoform usage. |

## Learning Objectives

**Morning session: Differential expression and haplotype analysis**
* Understand the difficulties of assigning reads to isoforms.
* Understand biological mechanisms of allelic imbalance & different sources of bias in allele-specific expression analysis.

**Afternoon session: Single-cell transcriptomics with long reads**
* Identify and understand differences between bulk and single-cell protocols.
* Understand single-cell analysis pipeline steps (preprocessing, QC, tertiary analysis).

## Materials
* [Differential expression](../theory/day3/Differential_Expression.pdf): Slides for Join&Call, Call&Join and differential expression.
* [tappAS](../theory/day3/LongTREC_SummerSchool_tappAS.pptx): Slides for tappAS analysis.
* [Haplotype analysis](../theory/day3/Haplotype_analysis.pptx): Slides for allele-specific expression.
* [Single-cell 1](../theory/day4/Differences_bulk_single.pdf): Introductory slides about single-cell long-reads.
* [Single-cell 2](../theory/day4/Pipelines.pdf): Slides for single cell analysis pipelines.
* [Single-cell 3](../theory/day4/LongTREC_SS_EMC_Long_read_single_cell.pdf): Slides for tertiary analysis of long-reads single cell.

## Data
* [Data backup (Day 3)](https://github.com/longTREC/summer_school_data_backup/tree/main/day3/data)
* [Data backup (Day 4/Single Cell)](https://github.com/longTREC/summer_school_data_backup/tree/main/day4/data)

## Recommended Bibliography
* Bi, Yalan. et al. IsoTools 2.0: software for comprehensive analysis of long-read transcriptome sequencing data. Journal of Molecular Biology (2025). https://doi.org/10.1016/j.jmb.2025.169049
* Glinos, D.A., Garborcauskas, G., Hoffman, P. et al. Transcriptome variation in human tissues revealed by long-read sequencing. Nature (2022). https://doi.org/10.1038/s41586-022-05035-y  
* Cleary, S. and Seoighe, C. Perspectives on Allele-Specific Expression. Annual Reviews (2021). https://doi.org/10.1146/annurev-biodatasci-021621-122219
* De la Fuente, L., Arzalluz-Luque, A., Tardáguila, M., et al. tappAS: a comprehensive computational framework for the analysis of the functional impact of differential splicing. Genome Biology (2020). https://doi.org/10.1186/s13059-020-02028-w
* Gupta, P., O’Neill, H., Wolvetang, E.J., Chatterjee, A., Gupta, I., 2024. Advances in single-cell long-read sequencing technologies. NAR Genomics and Bioinformatics 6, lqae047. https://doi.org/10.1093/nargab/lqae047
* Heumos, L., Schaar, A.C., Lance, C., Litinetskaya, A., Drost, F., Zappia, L., Lücken, M.D., Strobl, D.C., Henao, J., Curion, F., Schiller, H.B., Theis, F.J., 2023. Best practices for single-cell analysis across modalities. Nat Rev Genet 24, 550–572. https://doi.org/10.1038/s41576-023-00586-w

### Back

Back to [main page](../index.md).
