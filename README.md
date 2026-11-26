# Protect the Pine

**Play it:** https://umi-max.github.io/protect-the-pine/

A two-minute browser game. Disease creeps along a young pine's roots — plant helper microbes in its path, but give them time to grow. No install, no sign-up; works on phone and desktop.

## How it plays

1. **See a spore cloud** at the tip of a root — disease is about to get in.
2. **Tap the + on that root** to plant helper microbes. A green ring fills as they grow.
3. **Block the disease.** If the ring is full when the disease arrives, it is stopped. If the helpers are still growing, they get overrun and the disease reaches the trunk.

It opens with a guided practice round, then two short levels. The pine has three hearts; each attack that reaches the trunk costs one.

## The science behind it

The game is based on a systematic review of microbial co-inoculation in conifers (Awan & Iqbal), which screened 430 records and included 20 primary studies. Full interactive guide:
https://umi-max.github.io/microbial-coinoculation-conifers/

The core idea — helpers must be established before the pathogen arrives — reflects Grönberg et al. (2009): in Scots pine, pre-inoculating harmless *Rhizoctonia* 168 hours (7 days) before the pathogen suppressed it, whereas simultaneous inoculation let the pathogen win root sites.

**It is a simplified game.** Seconds stand in for days, and blocking disease at one spot on a root is a visual metaphor, not a literal mechanism.

## Technical notes

- A single self-contained `index.html` (inline SVG, CSS and JavaScript); no build step.
- Keyboard: number keys 1–5 plant helpers on roots left to right.

## Author

Hafiz U. M. Awan — forest pathology, University of Helsinki.
