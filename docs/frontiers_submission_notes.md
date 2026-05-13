# Frontiers Submission Notes

## Target

- Journal: Frontiers in Artificial Intelligence
- Article type: Hypothesis and Theory
- Recommended section: Machine Learning and Artificial Intelligence
- Working manuscript: `paper-v5.md`
- Working PDF: `preprint/ConsciOS_v5_preprint.pdf`

## 200-word Scope Statement Draft

ConsciOS proposes a formal systems architecture for studying alignment as a property of nested control structure rather than only post-hoc behavioral correction. The paper integrates viable systems theory, active inference, affect science, hierarchical reinforcement learning, and human-in-the-loop AI alignment into a testable Hypothesis and Theory framework. Its core contribution is a three-layer controller decomposition: an embodied controller for short-horizon perception-action loops, a supervisory controller that selects among policy frames, and a meta-controller that shapes long-horizon priors and governance constraints. The proposed Resonance Engine formalizes policy selection as a weighted combination of expected utility, coherence, and cost. Interoceptive Control Signal and Time-Integrated Coherence constructs are introduced as operational hypotheses for affect-informed feedback, coherence accumulation, and complexity gating. The manuscript does not claim empirical validation; instead, it specifies falsifiable hypotheses, proposed human-subjects and simulation protocols, governance considerations, and a reproducible toy instrumentation demo. The submission fits Frontiers in Artificial Intelligence because it advances a novel, testable model for AI alignment, interpretability, and robust policy selection in hybrid human-agent and artificial-agent systems.

## Reference Check Notes

- DOI-resolved references were checked for the main DOI-bearing sources.
- The prior relevance-realization reference appeared unverifiable and was replaced with Darling, Corcoran, and Hohwy's peer-reviewed predictive-processing relevance paper.
- ArXiv records now include arXiv DOIs where available.
- The toy benchmark remains framed as illustrative instrumentation, not empirical validation.

## Frontiers Submission Checklist Notes

- Frontiers requires the submitting/corresponding author to register and log in.
- Submit both a manuscript PDF and source file.
- Figures should be uploaded individually in order, preferably TIFF/JPEG, RGB, 300 dpi, with legible text.
- The submission portal asks for author contribution, funding/payment details, ethics/data answers, and a 200-word contribution-to-the-field statement.
- Frontiers explicitly says a traditional cover letter is not provided in the submission workflow.
- Frontiers' author guidelines say data and ethics statements may be generated during submission based on portal answers, but keeping clean draft statements in the manuscript is useful for review and later consistency.
- For Hypothesis and Theory in Frontiers in Artificial Intelligence, the listed APC is A-type: CHF 2,195.

## Figure 3 Audit

- Core terms in the drawing still match the v5 manuscript: Meta-Controller, Supervisory Controller, Embodied Controller, Policy/Frame Library, Selector (Resonance Engine), Central Coherence Estimator, Coherence/ICS, TIC, Internal Constraints, External Constraints, Inputs, Outputs, Feedback, Actors, and Processes.
- The v5 manuscript removed metaphor/branding terms from Appendix C; Figure 3 already uses canonical terms, so no drawing change is required because of that edit.
- The revised `nested-control-architecture-rev5.png` updates "Prime Priors" to "Meta Priors" and clarifies the Quality Control path as a slow prior update to the Meta-Controller.
- Recommended drawing polish: text contrast is low in the PNG preview because most labels are dark gray on black/transparent background. Ensure the exported journal figure has high contrast at final size.

## Fee-Support Request Draft

I am submitting the manuscript "ConsciOS: A Viable Systems Architecture for Human and AI Alignment" to Frontiers in Artificial Intelligence as an independent researcher based in Turkey. I do not have institutional affiliation, grant funding, library open-access support, or a research budget that can cover the article publishing charge.

The listed A-type APC for this journal is CHF 2,195, which is financially prohibitive for me in the context of Turkey's exchange rate and local salary levels. The APC is approximately comparable to a full monthly salary for me, and paying it personally would create a serious financial burden.

I respectfully request the maximum fee support available, ideally a full waiver or the largest possible reduction. The manuscript is an unfunded theoretical contribution intended to serve the public research community: it proposes a falsifiable architecture for AI alignment and hybrid human-agent systems, includes open materials and reproducible toy instrumentation, and will remain available for critique and reuse. I am committed to open-access publication, but I cannot realistically proceed at the full APC without substantial assistance.

I can provide supporting documentation regarding my independent status, lack of institutional funding, location, and financial circumstances if required.

## Pre-submission Reminders

- Deposit a v5 Zenodo version before submission if the author wants the manuscript DOI to reflect the final v5 text.
- Update `CITATION.cff` and the Data Availability Statement if the v5 Zenodo DOI differs from the current public preprint DOI.
- Apply for Frontiers fee support before submission or immediately after submission; Frontiers says requests can be made before acceptance and independent researchers are eligible.
