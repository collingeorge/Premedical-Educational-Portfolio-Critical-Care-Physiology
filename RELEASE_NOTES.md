# 2026.10-rc2 - educational review candidate

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Revised 27 October 2026 after the rc1 PRs were merged.

This pass corrects newly identified source and software defects and deliberately narrows unsupported clinical/methodological content. Earlier versions remain recoverable in Git history. See PUBLICATION_REVIEW.md for the precise scope and limitations, PROVENANCE.md for author statements, and RELEASE_MANIFEST.json for current-file hashes.

The candidate is not a clinical protocol, validated controller, systematic/scoping review certification, or legal opinion. No repository visibility change is included.

## Applied example set — 28 October 2026
Added 42 topic-specific male/female case pairs, a local copy of the shared anesthesia-options set, two levels of source mapping and an explicit verification standard. The profiles are entirely synthetic; the source checks are scoped and do not certify clinical validity. Existing clinical/manuscript text and PDF exports are preserved.


## 28 October 2026 — Integrated ICU/CTICU workups

Added a companion for all 42 topics/84 synthetic profiles covering diagnostic alternatives, pain/sedation, airway/breathing, pressure/perfusion, renal/metabolic issues, conditional laboratory/imaging choices and reassessment. Twenty lab categories and seven nonlaboratory categories explain indications, questions, decision implications and limitations. These are authored educational applications, not standing orders or validated protocols. Existing case text, manuscripts, PDFs and code are retained.


### Procedure-organized narrative examples

Added 18 paired worked examples (36 synthetic profiles) in four procedure/condition groups. Replaced the 42 original scenario question lists with worked interpretations, retaining their topics, vignettes and interpretation boundaries. Existing manuscripts and code are unchanged. The new material is additive except for this requested conversion from questions to explanatory examples. Pasted generic targets and palliative absolutes were qualified rather than adopted as universal rules.


### CTICU visual decision trees

Added one original Mermaid decision tree to each of the 18 paired procedure/condition examples. Each tree connects assessment, illustrative differential branches, investigations, conditional care and reassessment. Urgent care can proceed in parallel; branches may coexist. The comfort-focused example follows goals and symptoms. Existing narratives and citations remain; diagrams add no doses, device settings or universal targets and are not validated treatment algorithms.


### Public-source clinical care and equipment examples

Added 11 worked laboratory examples, pain/sedation and airway/intubation/extubation workflows, respiratory-support and ventilator-mode comparisons, and 19 equipment explanations. Linked all 18 procedure pairs to relevant sections and added navigation from the 42-topic ICU supplements. Each teaching item links to public clinical or official device sources, with source type, conditional recommendations and review limits stated. Existing decision trees, case narratives, manuscripts and code are retained.


### Clinical knowledge versus guideline recommendations

Checked and classified 27 scoped recommendation groups, recording source strength, location and population. Labeled the 11 laboratory examples, 19 equipment entries, 18 procedure pairs and 42 ICU topic pairs as appropriate: guideline/consensus guidance, general clinical knowledge, context-dependent practice and/or synthetic example. Clarified the ARDS recruitment wording, NIV population limits and preventive post-extubation NIV eligibility. Retained narratives and diagrams; removed the implication that the authored reasoning format standardizes a clinical regimen.


## 29 October 2026 — Portfolio presentation and reading path

Added a concise reader’s guide, explicit AI-assistance/authorship scope and review-status notes. Linked the portfolio home and corrected navigation wording. This presentation pass preserves substantive manuscripts, casebooks, code and existing exports. Repository visibility is unchanged.


## November 2026 — accuracy and governance review

5 November 2026. Accuracy fixes made after an independent review of the ICU/CTICU casebooks and source registers. Every case remains synthetic, and no doses were added.

- **Citation identities rechecked.** The following were confirmed through publisher, PubMed and society index records:
  - MCSHEM (Interventional Cardiology Clinics 2026; PMID added)
  - MODES (Wattley and Camporota, J Intensive Care Soc 2026; full title added)
  - TRANSPLANT (Trinh et al., Thorac Surg Clin 2022;32(2):185-195; PMID added)
  - the SSC 2026 publisher correction (Intensive Care Med 2026;52(6):1411-1413)
  - the PADIS 2025 DOI
  - the IABP review's first author (Gillespie)
  - the BTF 2020 decompressive-craniectomy update (Hawryluk et al.)
- **SSC 2026.** Added the Critical Care Medicine co-publication DOI.
- **Paired-case consistency.** Corrected the paired-case context lines in the laboratory and pain/airway examples to match the 18-pair procedure casebook. This fixes the sex/case swaps for the heart-transplant, Impella, limb-revascularization, valve and aortic examples. Examples that are not among the 18 pairs are now labeled as additional synthetic examples.
- **Integrated workups.**
  - ICU-01-05 rows were rewritten for a patient not yet on mechanical support, and the AHA 2020 fulminant myocarditis statement was added.
  - The differential in ICU-04-02 and ICU-04-12 is now ventricle-neutral (LV/RV, prosthesis, tamponade, rhythm), and VALVE was added.
  - The ICU-04-07 airway row was replaced with one that fits the case.
  - ICU-01-04 now cites the EAST 2016 blunt thoracic trauma pain guideline in place of the cardiac-surgery sources.
  - "MAZE" now reads "Cox-Maze".
  - Row-level evidence labels are clarified.
- **INTEGRATED_WORKUP_AUDIT.json.** Each case now records all eight domains, including treatment/medication and other requirements. Earlier versions recorded only six while claiming eight. The two new sources are added to the JSON.
- **Currency.**
  - Added the ESICM 2025 circulatory shock and hemodynamic monitoring guideline (Monnet et al.), the ESICM 2023 ARDS guideline and the 2024 Global ARDS definition.
  - Marked the 2017 ATS/ESICM/SCCM guideline's PEEP, recruitment and ECMO questions as superseded by ATS 2024. Its low-tidal-volume/PBW and prone recommendations are retained.
  - Added a KDIGO 2026 draft note to the bibliography and the laboratory examples.
  - Noted the 2025 ESC/EACTS valve guideline as a European comparator.
  - Driving-pressure wording now cites Amato et al. 2015 and gives the commonly cited figure of about 15 cm H2O as an association, not a target.
  - Corrected the HEMO title (cardiogenic shock).
- **Pain and airway.**
  - Added the PADIS 2018 conditional suggestion for a neuropathic agent with opioids after cardiovascular surgery (G06 scope updated).
  - RSI strength labels are now attributed to the SCCM guideline summary.
