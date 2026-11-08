AraMAData: Arabic Reading Comprehension and Multiple-Choice Question Dataset
Overview
AraMAData is a research dataset for Arabic natural language processing and educational content generation. It brings together 1,000 passages from Arabic Wikipedia, covering 15 thematic domains, and 3,000 manually authored multiple-choice questions (MCQs). Each MCQ includes one correct answer and three distractors, for 9,000 distractors in total.

The resource is intended to support research in Arabic reading comprehension, answer-aware question generation, distractor generation, subject classification, and related NLP tasks. Its research use should not be conflated with independent psychometric validation or proof of educational effectiveness in classrooms.
Dataset Summary
Property	Value
Language	Arabic (primarily written Modern Standard Arabic)
Passage source	Arabic Wikipedia
Passages	1,000
Thematic domains	15
Manually authored MCQs	3,000
Correct answers	3,000
Distractors	9,000 (three per MCQ)
Original annotation	Four Arabic-speaking volunteers
Cognitive labels	Automatically assigned heuristic labels inspired by Bloom's Taxonomy; not independently validated pedagogical ground truth


Annotation and Scope
Four Arabic-speaking volunteers manually created the MCQs, correct answers, and distractors. Their original contributions are distinct from the source passages derived from Arabic Wikipedia. Separately assigned cognitive labels were generated using heuristic rules and must not be interpreted as expert-validated measures of cognitive demand.
Data Availability
The project repository is public, but the complete AraMAData dataset has not yet been publicly released. Repository visibility does not imply that the entire dataset is available or that unrestricted downstream rights have been granted to unreleased materials.

The full dataset will be released after the passage-level source records and the applicable notices for the released components have been verified and completed. Any published dataset files and their applicable license terms will be identified explicitly at the time of release.
Attribution and Permissions
- Arabic Wikipedia passages: Passage text is reusable under the applicable Wikimedia open-content licenses, normally including CC BY-SA 4.0 for Wikipedia text, subject to attribution, modification notices, and ShareAlike requirements where applicable. See [LICENSES.md](LICENSES.md) and the Wikimedia Terms of Use. Individual author permission is not required for reuse that complies with those licenses.
- Manually authored annotations: All four original volunteer annotators have provided documented authorization for the publication, distribution, and reuse of their original contributions. Confirmation records are retained privately by the project. Their authorization should not be confused with assigning an unspecified standard Creative Commons license to the entire assembled dataset. The exact public-facing reuse terms for released files will be documented in [LICENSES.md](LICENSES.md).
- Source traceability: Per-passage references and source revision details, where verifiable, will be recorded before the full release. The included [PROVENANCE_TEMPLATE.csv](PROVENANCE_TEMPLATE.csv) is an empty schema, not a completed record of all 1,000 sources.
Reproducibility and Planned Release
The repository is intended to host the materials and notices necessary for reproducible research. Release materials will identify source data, any documented transformations, reuse notices, and the precise scope of available files. No claim is made here that the complete 1,000-passage dataset or its verified source index is already available.
Citation
If using AraMAData in academic work, cite the associated thesis or peer-reviewed dataset publication when its final bibliographic details are available. Do not infer a published version or DOI from this repository alone.
