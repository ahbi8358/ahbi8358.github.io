---
title: Software and data
description: "dsc-read-bench (Can AI read a DSC curve?): a solo entry to the 2026 OSI Hackathon for the Physical Sciences & Mathematics. Code, data and write-up."
permalink: /software/
---
# Software and data

## dsc-read-bench: Can AI read a DSC curve?

<p class="meta">October 2026 · Solo entry to the 2026 Open Scientific Intelligence (OSI) Hackathon for the Physical Sciences &amp; Mathematics (formerly the LLM Hackathon for Applications in Materials Science and Chemistry) · Code MIT, data and figures CC BY 4.0 · <a href="https://github.com/ahbi8358/dsc-read-bench">Repository</a> · <a href="https://github.com/ahbi8358/dsc-read-bench/blob/v1.0-submission/writeup.pdf">One-page write-up (PDF)</a></p>

A benchmark of synthetic differential scanning calorimetry (DSC) curves whose right answers are known by construction, with a scorer and an error report for each AI reader. The repository holds the curve generator, the test set, the readers, the scorer and the write-up.

**Disclosures.** I designed the test set and the scoring and trained no model. I built the code, the README, the write-up and the video script with an AI coding assistant (Claude, Anthropic), the same provider as the models tested; the error model was written with the assistant, and I chose what it reports. The specification, generator, renderer, an 8-curve pilot and the API checks predate the event (tag v0.1-pre-event, October 20, 2026); the rest was built during the two days. The submitted state is tag v1.0-submission.
