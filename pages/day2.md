---
layout: page
title: Day 2
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial
  isPartOf:
      url: "https://longtrec.github.io/summer_school/"
      name: "LongTREC summer school - long-read transcriptomics"
---

<img src="../assets/logos/LongTREC_logo_FINAL.png" width="200" /> <img src="../assets/logos/OSCARS.png" width="150" />

# Day 2 Agenda

## Goals
* Gain an overview of the challenges of transcript identification and the variety of computational methods.
* Gain practical proficiency in the identification of known and novel transcript isoforms, as well as quality control of transcriptomes using tools like `IsoTools` and `SQANTI3`.
* Understand how to create structural annotations using an evidence-driven approach that integrates long-read sequencing data.
* Gain practical experience in deriving isoform-resolved functional annotations and drawing biological conclusions through visualization and exploration.

## Timetable

| Time          | Activity                | Details                                                                                                                                       |
| --------------------- | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 09:00 - 09:20 | Transcript Identification         | <u>Yalan & Ana</u>: Give an overview of basic concepts and the space of transcript identification and quantification tools (reference-reliant vs. de novo vs. quantification only)                                                                                                     |
| 09:20 - 09:40 | IsoTools Theory                   | <u>Yalan</u>: Overview of theory and concepts of IsoTools algorithm and functionalities                                                                                                                |
| 09:40 - 10:30 | IsoTools Practice                 | <u>Yalan</u>: Applying IsoTools to identify and quantify both known and novel transcripts, investigating results                                                                                           |
| 10:30 - 11:00 | Coffee Break                      |                                                                                                                                                                   |
| 11:00 - 11:30 | SQANTI3 Theory                    | <u>Pablo</u>: Motivate why we need transcriptome quality control and filter, and introduce SQANTI3 concepts like structural categories                                                                                           |
| 11:30 - 12:20 | SQANTI3 Practice                  | <u>Pablo</u>: Applying SQANTI3 to perform quality control, filtering, and rescue on a custom transcriptome                                                                      |
| 12:30 - 13:30 | Lunch break                       |                                                                                                                                                                   |
| 13:30 - 15:00 | Structural Annotation Evaluation Theory | <u>Pablo</u>: How long-read sequencing integrates into structural genome annotation and its evaluation (ab initio predictions, identification of alternative splicing). |
| 15:00 - 15:30 | Coffee Break                      |                                                                                                                                                                   |
| 15:30 - 16:00 | Functional Annotation Theory      | <u>Pablo</u>: How to map functions (from public databases or predictors) to isoform-resolved sequences        |
| 16:00 - 16:50 | Functional Annotation Practice    | <u>Pablo</u>: Utilizing IsoAnnotLite to obtain isoform-resolved annotations and visualization of results |
| 16:50 - 17:00 | Summary                           | Questions                                                                                                                                                         |

## Learning Objectives
* Students should be able to understand common problems for transcript identification and quantification.
* Students should be able to apply tools to identify and quantify transcript isoforms.
* Students should be able to understand how long-read sequencing integrates in the structural genome annotation workflow.
* Students should be able to use long-read sequences to validate gene models and assess performance
* Students should be able to functionally annotate transcript models and evaluate annotation results.

## Materials
* [Transcript identification](../theory/day2/Transcript_Identification.pdf)
* [Transcript identification quantification](../theory/day2/Transcript_identification_quantification_theory.pptx)
* [Isotools](../theory/day2/IsoTools_theory.pptx)
* [SQANTI3](../theory/day2/SQANTI3.pdf)
* [Functional annotation](../theory/day2/Functional_Annotation.pdf)

## Data
* [Data backup](https://github.com/longTREC/summer_school_data_backup/tree/main/day2/data)

## Recommended Bibliography
* Monzó, C., Liu, T. & Conesa, A. Transcriptomics in the era of long-read sequencing. Nature Reviews Genetics (2025). [https://doi.org/10.1038/s41576-025-00828-z](https://doi.org/10.1038/s41576-025-00828-z)
* Bi, Yalan, et al. "IsoTools 2.0: software for comprehensive analysis of long-read transcriptome sequencing data." Journal of Molecular Biology (2025): 169049. [https://doi.org/10.1016/j.jmb.2025.169049](https://doi.org/10.1016/j.jmb.2025.169049)

### Back

Back to [main page](../index.md).
