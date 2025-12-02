# BCAI-Group6

This repository contains the analysis code and figures for a study on how well a simple deep neural network can predict human choices in a category-based painting selection task under different risk structures.

Participants first learned a set of artists during an exploration phase and then completed multiple test rounds. In each test round, 20 paintings were shown and participants had to select 4 paintings, ideally all from the same artist. Two reward conditions were analysed:

- **Hc (High-risk)** – bonus concentrated on perfect 4/4 matches  
- **Lc (Low-risk)** – bonus available for both 3/4 and 4/4 matches  

Only data from the **Hc** and **Lc** groups in the **2019** and **2025** student cohorts are used here.

---

## Repository structure

```text
.
├── data/      # Preprocessed behavioural data and processing scripts
├── figs/      # All figures used in the manuscript
├── model/     # Model training & evaluation scripts
└── README.md  # This file
```