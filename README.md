# AraMAData: An Arabic Dataset for Educational NLP and Multiple-Choice Question Generation

## Overview

**AraMAData** is an Arabic-language dataset developed to support research in Natural Language Processing (NLP), particularly reading comprehension, question answering, automatic question generation, distractor generation, and text classification.

The dataset comprises **1,000 passages collected from Arabic Wikipedia**, covering **15 thematic domains**, including science, history, education, culture, and social studies.

It contains **3,000 manually authored multiple-choice questions (MCQs)**. Each question is associated with a source passage, one correct answer, and three plausible distractors, resulting in **9,000 manually constructed distractors**.

AraMAData provides a structured resource for investigating Arabic educational content generation, language understanding, and automated assessment methods.

## Dataset Characteristics

| Characteristic | Description |
|---|---|
| Language | Arabic |
| Source | Arabic Wikipedia |
| Source passages | 1,000 |
| Thematic domains | 15 |
| Multiple-choice questions | 3,000 |
| Correct answers | 3,000 |
| Distractors | 9,000 |
| Distractors per question | 3 |
| Annotation method | Manual annotation by four Arabic-speaking volunteers |
| Cognitive labels | Automatically assigned using heuristic rules based on Bloom's Taxonomy |

## Annotation and Cognitive Labels

The multiple-choice questions, correct answers, and distractors were manually constructed by four Arabic-speaking volunteer annotators.

In addition to the manually authored annotations, AraMAData includes cognitive labels derived from Bloom's Taxonomy.

These cognitive labels were assigned using an automated rule-based procedure rather than independent manual assessment by educational experts. They should therefore be considered **heuristic indicators of cognitive demand**, not validated pedagogical ground-truth annotations.

The dataset is intended primarily for Arabic NLP research. Its use in operational educational assessment would require additional pedagogical and psychometric validation.

## Research Applications

AraMAData supports research on several Arabic NLP tasks, including:

- **Reading comprehension and question answering:** investigating the relationship between passages, questions, and correct answers.
- **Automatic question generation:** generating questions conditioned on Arabic source passages.
- **Distractor generation:** developing and evaluating methods for producing plausible but incorrect multiple-choice alternatives.
- **Text classification:** categorizing Arabic passages according to thematic domains.
- **Educational NLP:** studying automated assessment-content generation and related language-processing methods.

These applications describe the intended research uses of the resource and do not imply that every task has undergone comprehensive experimental or educational validation.

## Data Availability and Licensing

### Current Availability

A public repository has been established at:

https://github.com/lafkiar/AraMAData

However, **the complete AraMAData dataset has not yet been publicly released**.

The repository currently serves as a resource for project information, dataset documentation, and preparation for future dissemination.

### Data Provenance and Attribution

The source passages were collected from Arabic Wikipedia and subsequently selected and preprocessed for the construction of the dataset.

Wikipedia-derived material remains subject to the applicable source licensing and attribution requirements, including Creative Commons Attribution–ShareAlike conditions where applicable.

Passage-level provenance records, source attribution information, and preprocessing details are being finalized to support transparent and compliant redistribution.

### Volunteer-Contributed Annotations

The dataset's manually authored annotations were created with the participation of four Arabic-speaking volunteers.

All four contributors have provided documented authorization for the publication and redistribution of their original annotations.

The applicable licensing terms for these annotations and their compatibility with the source material will be specified in the dataset's licensing documentation before the complete public release.

### Licensing and Redistribution Policy

The licensing documentation is being finalized to distinguish the conditions applicable to:

- Arabic Wikipedia-derived source passages;
- manually authored questions, answers, and distractors;
- the assembled AraMAData resource.

The planned documentation will include:

- **`PROVENANCE.csv`** — source attribution and passage-level provenance records.
- **`LICENSES.md`** — applicable licenses and redistribution conditions.

These files will be provided or updated once the relevant information has been verified.

The complete dataset will be released only after the applicable licensing, attribution, and redistribution requirements have been addressed.

**The public availability of this repository does not imply unrestricted access to, or redistribution rights for, the complete dataset.**

## Reproducibility and Future Release

AraMAData was developed to support reproducible research on Arabic question generation and multiple-choice assessment.

The planned public release will be accompanied by documentation describing the dataset structure, provenance, applicable licenses, and conditions for reuse.

The repository will be updated as the documentation and release process progress.
