# Longitudinal Inference Without Longitudinal Data

Part of Damian Betebenner's talks: <https://dbetebenner.github.io/talks/>

### A Copula-Based Unification of TAMP and SGP

**Damian W. Betebenner** (National Center for the Improvement of Educational Assessment)

**Henry I. Braun** (Lynch School of Education, Boston College)

Presented at the National Council on Measurement in Education (NCME) Annual Meeting, April 2026, Los Angeles, CA.

## View the Presentation

The slides are hosted via GitHub Pages at:
**[https://dbetebenner.github.io/NCME_2026_LIwLD/](https://dbetebenner.github.io/NCME_2026_LIwLD/)**

## Repository Contents

    docs/
      index.html   # Self-contained reveal.js presentation (rendered via Quarto)
      assets/
        In_Order_We_Trust.pdf   # The paper PDF (the slide QR opens it in GitHub's file viewer)
      docs/assets/
        In_Order_We_Trust.pdf   # Copy for an older link (see below)

The HTML file embeds all assets (figures, fonts, CSS, JavaScript) so no additional files are required to view the presentation.

The NCIEA Colloquium and Board decks linked to `https://dbetebenner.github.io/NCME_2026_LIwLD/docs/assets/In_Order_We_Trust.pdf`. GitHub Pages serves `docs/` as the site root, so that URL needs the copy at `docs/docs/assets/`. Keep it: copies of those decks are already in circulation.

## Abstract

This presentation demonstrates that group-level growth inference does not require student-level longitudinal linkage. Using Sklar's Theorem, we show that Braun's Trajectory Analysis of Matched Percentiles (TAMP) corresponds to the comonotonic copula and that Student Growth Percentiles (SGPc) arise as conditional quantiles under a general copula model. A sensitivity analysis across 966 longitudinal conditions, 4 datasets, and 4 content areas establishes the t-copula as a robust canonical choice (selected in 64% of cases by AIC). A minimum-distance fitting procedure over the Beta family recovers subgroup mean SGPc from cross-sectional marginals alone, with validation showing r = 0.995 and MAE = 0.40 SGPc points against linked ground truth. The precision cost of foregoing linkage (CI widening of ~2.5x) is quantifiable and manageable for large-scale assessment programs such as NAEP, TIMSS, and PISA.
