# Autonomous Bioluminescent Plant (Project 2 — Research Lab v2)

## 📌 Project Overview

**Project 2 — Research Lab v2** is a rigorous, multi-stage computational research pipeline designed to engineer and evaluate autonomous bioluminescent plant systems using the Fungal Bioluminescence Pathway (FBP). Building upon foundational modeling (Stages 1–12), this repository incorporates a specialized research extension (**Gap 3: Cold-night kinetic quenching and psychrophilic enzyme engineering**, Stages 13–21) to mitigate catalytic stalling at low temperatures (4–10 °C).

## 🧬 Pipeline Architecture & Stages

### Baseline Pipeline (Stages 1–12)
* **Stages 1–4:** Sequence sanitization, structural template alignment, and master manifest generation (`sanitized_fbp_sequences.fasta`).
* **Stages 5–8:** Enzyme flexibility analysis, psychrophilic mutant variant design, and metabolic Flux Balance Analysis (FBA).
* **Stages 9–12:** Canopy ray-tracing simulations, Monte Carlo sensitivity analysis, and baseline white paper generation (`WHITE-PAPER_PROJECT2.md`).

### Gap 3 Research Extension (Stages 13–21)
* **Stages 13–15:** Ortholog verification, sequence conservation alignment, and structural flexibility propensity indexing.
* **Stages 16–17:** Active-site loop remodeling (`nnLuz_cold_v1` and `ngarCPH_cold_v1`) and in silico kinetic evaluation at 8 °C.
* **Stages 18–19:** Temperature-performance Arrhenius curve construction and cold-night FBA metabolic consequence integration.
* **Stages 20–21:** Experimental hypothesis formulation, wet-lab assay simulation, and final extension white paper generation (`WHITE-PAPER_PROJECT2_GAP3_EXTENSION.md`).

## 📁 Repository Structure

```text
project2_fbp/
├── data/
│   └── processed/
│       ├── sanitized_fbp_sequences.fasta
│       ├── master_project_manifest.json
│       ├── extension_gap3_manifest.json
│       ├── stage4 through stage19 report JSONs
│       └── stage21_validation_report.json
├── results/
│   └── tables/
│       ├── stage5_alignment_summary.csv
│       ├── enzyme_flexibility_analysis.csv
│       ├── psychrophilic_mutant_variants.csv
│       ├── metabolic_fba_simulations.csv
│       ├── canopy_ray_tracing_simulations.csv
│       ├── monte_carlo_sensitivity_analysis.csv
│       ├── stage13_psychrophilic_orthologs.csv
│       ├── stage14_alignment_conservation.csv
│       ├── stage15_flexibility_propensity.csv
│       ├── stage16_loop_mutation_candidates.csv
│       ├── stage17_kinetic_evaluation.csv
│       ├── stage18_temperature_performance.csv
│       ├── stage19_cold_night_fba.csv
│       └── stage21_wet_lab_validation_plan.csv
├── WHITE-PAPER_PROJECT2.md
└── WHITE-PAPER_PROJECT2_GAP3_EXTENSION.md
```

## 🚀 Installation & Execution

Clone the repository and set up your working environment in Google Colab or a local Python environment:

```bash
# Clone the repository
git clone https://github.com/riddhikad9b-ux/project2-autonomous-bioluminescent-plant.git
cd project2-autonomous-bioluminescent-plant

# Ensure required libraries are installed
pip install pandas numpy biopython matplotlib
```

To run individual stages or inspect output metrics, load the processed CSV tables directly from `results/tables/` or execute the Colab notebook blocks.

## 📊 Key Results & Findings

1. **Catalytic Rescue at Low Temperatures:** Introduction of glycine hinge mutations ($\text{P142G}$, $\text{F145S}$) into `nnLuz_cold_v1` successfully relieves cold-night catalytic quenching, yielding $\ge 36.1\%$ relative activity at 8 °C compared to severe baseline inactivation ($\le 10\%$).
2. **Stromal Recycling Efficiency:** `ngarCPH_cold_v1` maintains high recycling efficiency at 8 °C ($2.80\text{ s}^{-1}$ $k_{\text{cat}}$), stabilizing continuous auto-luminescence without triggering severe carbohydrate starvation.
3. **Photon Emission Flux:** Integrated cold-night FBA confirms a sustainable photon emission rate of $1.2 \times 10^{11}\text{ photons/min/cm}^2$ under 8 °C ambient conditions.

## 👤 Author

* **RIDDHIKA D**
* GitHub: [`riddhikad9b-ux`](https://github.com/riddhikad9b-ux)
* Email: `riddhika.d9b@gmail.com`