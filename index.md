---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "VALT summer school - long-read transcriptomics"
  description: "Valencia long-read transcriptomics summer school organized by LongTREC and the OSCARS project, a European Training Network on long-read transcriptomics. The course will cover the analysis of long-read RNA sequencing data, including technologies, experimental design, quality control, mapping, transcript identification and quantification, structural annotation evaluation, differential expression and haplotype analysis, and single-cell transcriptomics."

  # Keywords -> Consult EDAM:Topic
  keywords:  ""

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution"]

  # Author info
  author:
    - "@type": Organization
      name: "LongTREC"
      alternateName: "LongTREC"
      sameAs: "https://longtrec.eu/"
    - "@type": Organization
      name: "OSCARS"
      alternateName: "OSCARS"
      sameAs: "https://https://oscars-project.eu/"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Ana Conesa"
    - "@type": Person
      name: "Carolina Monzó"
    - "@type": Person
      name: "Juan Francisco Servilla"
    - "@type": Person
      name: "Pablo Atienza"
    - "@type": Person
      name: "Nadja Nolte"
    - "@type": Person
      name: "Eamon McAndrew"
    - "@type": Person
      name: "Yalan Bi"
    - "@type": Person
      name: "Tian-Yuan Liu"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://longtrec.github.io/summer_school/"
---
<img src="./assets/logos/LongTREC_logo_FINAL.png" align="centre" width="25%" height="25%">

## Course Description

Welcome to the VALT Bioinformatics Summer School on the Analysis of Long-Reads Technology Data.

We have organized a comprehensive 3-day course designed for master's students, doctoral candidates, and early career postdoctoral fellows interested in exploring the exciting world of long-read RNA sequencing. Throughout this course, you will be introduced to a diverse range of topics — from fundamental technologies and basic data processing to advanced applications including long-read transcriptomics, single-cell analysis, and many other exciting topics.

## Target Audience

This training is specifically designed for early career researchers who are:
* In the grant application phase for long-read sequencing projects
* Planning experimental design for studies centered around long-read technologies
* Looking to expand their bioinformatics toolkit with cutting-edge long-read analysis methods

## What Will You Learn?

* **Technologies & Fundamentals**
  * Comprehensive overview of different long-read sequencing technologies
  * Best practices in experimental design
  * Quality control evaluation using SQANTI-reads

* **Analysis & Applications**
  * Transcript identification and quantification using long-reads
  * Structural annotation evaluation  
  * Differential expression analysis and haplotype identification
  * RNA modifications detection with long-reads

* **Advanced Topics**
  * Single-cell and spatial transcriptomics approaches

## Workshop Schedule

### Day 1 | [Foundation Day](./pages/day1.md)

| Time          | Session                                                                                    |
|--------------|--------------------------------------------------------------------------------------------|
| 09:00 - 12:30 | **Lecture**:  <br><br> Different long-read sequencing technologies, experimental design, quality, mapping  <br><br> **Lecturers:** Ana Conesa |
| 12:30 - 13:30 | [*Lunch Break*](/assets/images/lunch.webp)                                                                               |
| 13:30 - 17:00 | **Hands-on**: <br><br> Different long-read mappers and QC evaluation with SQANTI-reads <br><br> **Lecturers:** Carol and Tian  |

### Day 2 | [Transcript Analysis Day](./pages/day2.md)

| Time          | Session                                                                                    |
|--------------|--------------------------------------------------------------------------------------------|
| 09:00 - 12:30 | **Lecture & Hands-on**: <br><br> Transcript identification and quantification using long reads <br><br> **Lecturers:** Yalan and Ana |
| 12:30 - 13:30 | [*Lunch Break*](/assets/images/lunch.webp)                                                                               |
| 13:30 - 17:00 | **Lecture & Hands-on**: <br><br> Evaluation of structural annotation using long reads RNA sequences <br><br> **Lecturers:** Pablo |

### Day 3 | [Advanced Analysis Day](./pages/day3.md)

| Time          | Session                                                                                    |
|--------------|--------------------------------------------------------------------------------------------|
| 09:00 - 12:30 | **Lecture & Hands-on**: <br><br> Differential expression and haplotype analysis using long reads <br><br> **Lecturers:** Nadja and Pablo  |
| 12:30 - 13:30 | [*Lunch Break*](/assets/images/lunch.webp)                                                                               |
| 13:30 - 17:00 | **Lecture & Hands-on**: <br><br> Single-cell transcriptomics with long reads <br><br> **Lecturers:** Eamon and Fran  |

---

### Instructors

[Ana Conesa](https://www.linkedin.com/in/ana-conesa-557b1a12/)

[Pablo Atienza](https://www.linkedin.com/in/pablo-atienza-lopez/)

[Carolina Monzó](https://www.linkedin.com/in/carolina-monz%C3%B3-944762134/)

[LongTREC Fellows](https://longtrec.eu/fellows/)

---

The source for this course webpage is [in github](https://github.com/ConesaLab/VALT_Summer_Course).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Web_course_template</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.