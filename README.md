# Representation Learning for Tabular Data — CMPE 255 Short Story

A short story on how machine learning models learn from tables, from gradient-boosted trees and specialized deep networks to transferable and tabular foundation models such as TabPFN.

| | Link | Status |
|---|---|---|
| Medium article | <MEDIUM_URL> | 🚧 In progress |
| Slides | <SLIDES_URL> | 🚧 In progress |
| Video (10–15 min) | <YOUTUBE_URL> | 🚧 In progress |

## Paper

Jun-Peng Jiang, Si-Yang Liu, Hao-Run Cai, Qi-Le Zhou, Han-Jia Ye. **Representation Learning for Tabular Data: A Comprehensive Survey.** *IEEE Transactions on Pattern Analysis and Machine Intelligence* (TPAMI), 2026.
arXiv: [2504.16109](https://arxiv.org/abs/2504.16109) · DOI: [10.1109/TPAMI.2026.3657217](https://doi.org/10.1109/TPAMI.2026.3657217)

## Why this paper

- **Course fit:** it covers representation learning, feature handling, ensembles and evaluation, applied to the kind of data most data-mining work starts with: tables.
- **Organizing idea:** it groups models by how far they generalize:
  - *specialized*: trained for one dataset;
  - *transferable*: pre-trained, then adapted;
  - *general*: tabular foundation models that use in-context learning.
- **Central question:** why gradient-boosted trees still often win on tables, and when deep or foundation models change that.
