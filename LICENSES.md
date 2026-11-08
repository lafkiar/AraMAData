# AraMAData: Provenance, Attribution and Reuse Permissions

**Current status:** Pre-release documentation. The complete dataset has **not** yet been publicly released. This notice describes the existing permissions and the source-license obligations; it does not invent a standard license grant for unreleased files.

## 1. Arabic Wikipedia-derived passages

AraMAData passages originate from Arabic Wikipedia. Wikimedia textual content is generally reusable under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**, subject to the license applicable to the particular content/version and any special notices.

Compliant reuse normally requires:

- Attribution to the original contributors, for example by linking to the source article and its edit history;
- A link to the applicable license and retention of attribution/license notices;
- Disclosure of modifications made to the source text, including preprocessing where relevant;
- Compliance with ShareAlike obligations when sharing adapted material, where applicable.

Official references:

- [Wikimedia Terms of Use](https://foundation.wikimedia.org/wiki/ToU)
- [CC BY-SA 4.0 license summary](https://creativecommons.org/licenses/by-sa/4.0/)
- [CC BY-SA 4.0 legal code](https://creativecommons.org/licenses/by-sa/4.0/legalcode)

The project does not claim copyright ownership over the underlying Wikipedia text. No separate individual permission from Wikipedia contributors is necessary for reuse that complies with applicable Wikimedia licenses.

## 2. Original volunteer-authored annotations

Four Arabic-speaking volunteers manually authored the question, answer, and distractor annotations. All four have provided **authorization for publication, distribution, and reuse of their original annotations**. The confirmation records are maintained privately; no personal correspondence is published in this repository.

These permissions are **already obtained**, not permissions that the project is still seeking. The public release documentation will specify the scope of the permissions available to downstream users for the particular released files. At present **no additional standard license is asserted here for the entire assembled resource**; do not assume that a CC license has already been applied to the annotations merely because the Wikipedia passages carry one.

## 3. Assembled dataset

AraMAData combines Wikipedia-derived passages with separately authored annotations. Source text and annotations may carry different obligations. Any public release will identify the applicable conditions for the actual files made available, rather than treating repository publicity or contributor consent alone as an unrestricted blanket license.

## 4. Passage-level provenance

Each released passage should be associated with a source article URL and, where available, an exact Wikipedia revision identifier, an extraction date, a description of modifications, and the verified source license. `PROVENANCE_TEMPLATE.csv` provides the required **column structure only** and contains no verified passage-level records yet.

## 5. Current availability

The repository currently documents the project and the planned release. The complete dataset is not yet publicly available. The exact distribution conditions and source-attribution notices will be published alongside the complete release, following verification of the supporting information.

*This document is a factual project notice, not a replacement for legal review of exceptional source material or of the precise wording of the existing contributor permissions.*
