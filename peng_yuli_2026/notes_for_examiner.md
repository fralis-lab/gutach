# Notes for the examiner (not part of the report)

Thesis: Yuli Peng, KAUST, "Development of Rapid Point-of-Care Diagnostics for Viral Infectious Diseases using Lateral Flow Platforms" (228 pp., Sept 2026).

## 1. Points in the thesis that matter for the grade

1. **Novelty is moderate.** Every nanobody is taken from the literature. No discovery, no affinity maturation, no format engineering, even though the thesis itself identifies affinity/avidity as the bottleneck (monomeric ALX-0171 is ~150x weaker than the trimer; DD7 does not bind DENV1 NS1). The obvious experiment (trimeric ALX-0171) was not done. The real contribution is assay engineering, above all oriented conjugation (AviTag/BirA, SpyTag/SpyCatcher, streptavidin-AuNP) and the biotin-4-fluorescein finding that streptavidin loses biotin-binding capacity when coupled to carboxyl-AuNPs.
2. **Sensitivity is mostly below commercial tests.** RSV: 100 ng/mL vs 5 ng/mL for the commercial kit she benchmarked herself. Coronavirus spike: ~250 ng/mL. Dengue NS1 in serum: 200 ng/mL to 1 ug/mL effective after mandatory 20x dilution. Only the Zika assay (1 ng/mL in urine, 20 ng/mL in serum) is competitive. SARS-CoV-2 assay does not detect the Delta variant (framed as "low cross-reactivity with variants", which is a euphemism).
3. **No clinical samples anywhere.** Spiked simulated/commercial matrices only; inactivated virus only in Chapter 2.3.
4. **No statistics.** LODs are naked-eye reads of single strips (see Figs. 13, 21, 31, 32, 42, 43). Replicate numbers are not given except "duplicate" in 3.1. Chapter 1 explicitly demands standardised, statistically defined LODs, so this is an internal inconsistency you can point to without being unfair.
5. **Stability of the dengue assay failed.** After 4 weeks: loss of LOD in buffer and urine, false positive in diluted serum. Honestly reported, but it is a failed result.
6. **Chapter 2.1 (RPA-LFA) is very thin.** Plasmid DNA only, no reverse transcription, nonspecific products in all no-template controls, LOD 8x10^3 copies (2–3 orders worse than literature). Reads like a side project; could be argued it belongs in an appendix.
7. **Shared first authorship and collaborator contributions.** Zika (published) and dengue (in prep) are co-first with Atheer Alqatari (Arold/Grünberg labs). Per the authorship statement, BLI kinetics, mass photometry and the avidity analysis in the Zika paper were done and written by collaborators; her part is GST-nanobody expression, all LFA work and the manuscript. In dengue, purification and BLI were done by the collaborator. Worth probing at the defense.
8. **Over-claims in Chapter 2.3** (the published coronavirus paper): abstract says "highly sensitive", "clinically relevant diagnostic cut-off values" (never substantiated in the text), "long shelf life" (4 weeks tested). Claim "first nanobody-based sandwich LFA observable by the naked eye" contradicts her own Table 1 (Doerflinger 2016 norovirus, fully nanobody-based colorimetric; Fatima 2014).
9. **Factual error:** chikungunya virus listed under Flaviviridae (p. 117); it is an alphavirus. Plus the cross-reference/citation errors listed in Section 4 of the report (refs 57/62 misplaced on p. 30; "Table 2" for Table 5 on p. 81; MERS virus "on SARS-CoV-2 strips" on p. 109; periplasmic vs cytoplasmic contradiction pp. 120/126; DD7/DD9 roles reversed on p. 131; Table 8 without units; residual "Figure S2.7" in Appendix Discussion 2).
10. **Unexplained artefact:** in the dengue assay the control-line intensity rises with antigen concentration (p. 134). If the control line depends on the analyte it is not a valid control. Good defense question.

## 2. Points for you to take care of

- **Examples not received.** You mentioned uploading earlier Gutachten as style examples; only the thesis zip arrived. The report uses a generic structure (summary / merit / rigour / presentation / revisions / defense questions / recommendation). Send the examples and I will re-cut it to your usual format.
- **KAUST form.** KAUST usually sends the external examiner a form with a yes/no recommendation on whether the dissertation is acceptable for defense and a box for the written evaluation. The report is written so that Sections 1–4 go into the evaluation box and Section 7 answers the recommendation. Check the exact outcome categories on the form (typically pass / pass with minor revisions / pass with major revisions / fail) and align the last sentence.
- **Section 6 (defense questions) is optional.** Delete it if the form does not ask for it; keep the questions for yourself.
- **Placeholders:** name, affiliation, date, signature.
- **WhatsApp to Dominik.** Fine as background, but keep it one-directional: ask for his ranking, do not tell him your verdict before the report is submitted, and do not cite his opinion in the report. KAUST expects the external assessment to be independent, and Dominik is a co-author on every chapter.
- **Thesis PDF is not committed to the repo** (candidate's document, 21 MB). It stays in the upload folder.

## 3. How to shift the tone later

**Harder ("major revisions"):**
- Change Section 5 items 3 and 4 into conditions: replicate strips (n >= 3, independent batches) with a defined LOD criterion for every LFA; move Chapter 2.1 to an appendix or drop it; repeat the dengue stability test.
- In Section 7 replace "conceptual novelty is moderate" with "the conceptual contribution is limited to assay optimisation with published binders", and recommend acceptance "after major revisions".

**Softer ("pass"):**
- Merge Section 5 into Section 4 as "editorial corrections"; drop items 3 and 4.
- In Section 3(b) delete the sentence about falling short of her own standard.
- In Section 7 add a sentence on productivity (two ACS Synth Biol papers, review, two protocol papers, one manuscript in prep) and recommend acceptance without conditions.

## 4. WhatsApp to Dominik (German, informal)

Short version:

> Hi Dominik, ich sitz gerade am Gutachten für Yulis Thesis. Bevor ich mich festlege: Wie würdest du sie im Vergleich zu euren anderen Doktoranden einordnen – oberes Drittel, Mittelfeld? Und wie eigenständig war sie im Labor, vor allem bei den Teilen mit den Kollaborateuren (BLI, Massenphotometrie, Dengue)? Kurze ehrliche Einschätzung reicht mir, bleibt unter uns. Danke dir!

Even shorter:

> Hi Dominik, sitze am Gutachten für Yuli. Ganz ehrlich und unter uns: Wo würdest du sie im Vergleich zu euren anderen PhDs einordnen, und wie selbstständig war sie? Zwei Sätze reichen mir. Danke!
