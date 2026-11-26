# Protect the Pine

**Play it:** https://umi-max.github.io/protect-the-pine/

A two-minute browser game about timing beneficial microbes to protect pine seedlings from root-rot spores. No install, no sign-up — works on phone and desktop.

## How it plays

Tap a seedling to release beneficial microbes onto its roots. They need about seven days to settle in, and protection grows as they do. Spore warnings show which tree is targeted and when the spores land. Doses are limited, so you have to decide which trees to protect, and when.

| Level | Idea it teaches |
| --- | --- |
| 1 · The Nursery Bed | A head start wins: react to long warnings in time |
| 2 · Late Season | Prevention beats reaction: warnings are too short, so protect at-risk trees in advance |
| 3 · Mixed Weather | Plan where you must, react where you can |

After each level, a short lesson explains the science in plain language, with an optional section giving the evidence for researchers.

## The science behind it

The game is based on a systematic review of microbial co-inoculation in conifers (Awan & Iqbal), which screened 430 records and included 20 primary studies. The full interactive guide is at
https://umi-max.github.io/microbial-coinoculation-conifers/

**The game model is a simplification.** Protection builds over 7 days of colonisation, the pre-inoculation window reported by Grönberg et al. (2009), up to a maximum of 74% less damage, the best suppression in the review (Yu et al., 2024). Those two findings come from different host–pathogen systems, and real outcomes vary with host, pathogen and microbes. The "damp patch" risk markers are a game mechanic, not a research finding.

## Technical notes

- A single self-contained `index.html`: inline CSS and JavaScript, no build step, no dependencies beyond Google Fonts.
- Spore attacks are randomised each play, so replays differ.
- Best stars per level are kept in the browser's `localStorage`.
- Keyboard: number keys protect trees, `S` starts the season, `P` pauses.

## Author

Hafiz U. M. Awan — forest pathology, University of Helsinki.
