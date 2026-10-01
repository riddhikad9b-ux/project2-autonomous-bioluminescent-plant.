# Autonomous Bioluminescent Plant (Project 2 - Research Lab v2)

## Author
**RIDDHIKA D**  
Email: `riddhika.d9b@gmail.com`

---

## Overview
**Project 2 — Research Lab v2** is an advanced computational biology and metabolic engineering suite designed to optimize, simulate, and validate the **Fungal Bioluminescence Pathway (FBP)** for stable autonomous expression in higher plants. 

This repository houses a comprehensive **21-stage computational pipeline**, covering baseline pathway stabilization, metabolic Flux Balance Analysis (FBA), 3D canopy ray-tracing, and an extensive **Gap 3 Research Extension** focused on psychrophilic enzyme engineering for cold-night (8 °C) performance.

---

## Pipeline Architecture & Stages

### Baseline Engineering & Simulation (Stages 1–12)
- **Stages 1–3:** FBP core gene cluster retrieval, codon optimization, and GC-content harmonization for plant expression.
- **Stages 4–6:** Protein homology modeling, active-site structural prediction for fungal luciferase (`nnLuz`) and caffeoylpyruvate hydrolase (`CPH`).
- **Stages 7–9:** Metabolic pathway integration via Flux Balance Analysis (FBA) to assess ATP draw and precursor drain.
- **Stages 10–12:** Spatial canopy photon flux distribution modeling and multi-layered leaf ray-tracing simulations.

### Gap 3 Research Extension — Psychrophilic Optimization (Stages 13–21)
- **Stages 13–15:** Ortholog identification and active-site flexibility scoring via Gly/Ser residue enrichment indices.
- **Stages 16–18:** Loop remodeling (`nnLuz_cold_v1` & `ngarCPH_cold_v1`) and Arrhenius thermal activity modeling.
- **Stage 19:** Low-temperature FBA flux balance confirming sustained photon emission at 8 °C.
- **Stage 20:** Formulation of testable hypotheses and automated white paper generation.
- **Stage 21:** Wet-lab assay protocol simulation, recombinant expression roadmap, and statistical validation reporting.

---

## Repository Structure
```text
project2_fbp/
├── data/
│   └── processed/
│       ├── extension_gap3_manifest.json
│       └── stage21_validation_report.json
├── results/
│   └── tables/
│       └── stage21_wet_lab_validation_plan.csv
├── WHITE-PAPER_PROJECT2.md
├── WHITE-PAPER_PROJECT2_GAP3_EXTENSION.md
└── README.md

```

---

## Key Findings & Validation

* **Cold-Night Luminescence:** Engineered variants `nnLuz_cold_v1` (`P142G / F145S`) and `ngarCPH_cold_v1` (`Gly88Ser / Ala91Gly`) maintain $>35\text{--}44\%$ of peak catalytic activity under 8 °C cold-night conditions.
* **Metabolic Stability:** FBA simulations verify continuous auto-luminescence ($1.2 \times 10^{11}$ photons/min/cm$^2$) without inducing severe carbohydrate starvation or systemic metabolic collapse.

---

## Usage & Execution

Open the complete research notebook (`Autonomous Bioluminescent Plant – Project 2 – Research Lab v1.ipynb`) in Google Colab and run cells sequentially from Stage 1 through Stage 21 to replicate all structural models, simulations, and validation outputs.

---

## License & Citation

This project is developed for academic research and synthetic biology exploration. Please credit the author (**RIDDHIKA D**) if utilizing this codebase or documentation.

```

---


```
