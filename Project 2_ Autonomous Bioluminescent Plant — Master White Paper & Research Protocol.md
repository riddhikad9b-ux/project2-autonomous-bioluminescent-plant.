### Technical White Paper: Project 2 – Autonomous Bioluminescent Plant and Psychrophilic Research Extension

#### 1\. Executive Summary and Project Scope

The engineering of autonomous bioluminescence represents a strategic leap in synthetic biology, transitioning from instrument-dependent reporting to the realization of "living sensors." By configuring plants to emit self-sustained light, we establish a non-invasive architecture for the real-time monitoring of molecular physiology. This framework obviates the requirement for destructive sampling protocols and high-latency laboratory assays, offering a high-fidelity window into metabolic flux and stress response. Beyond its role as a diagnostic tool, this technology provides a blueprint for the bio-renewable illumination industry, capable of transforming urban landscapes into energy-autonomous ecosystems.The core of this architecture is the  **enhanced Hybrid Bioluminescence Pathway (eHBP)** . While initial iterations relied on the fungal hispidin-based pathway (oFBP), recent breakthroughs have enabled a "Hybrid Pathway" approach. This system integrates newly discovered indigenous plant hispidin synthases, which are significantly smaller and more flexible than the multi-gene fungal stacks they replace. By coupling these native plant enzymes with optimized mushroom-derived luciferase modules, we achieve sustained green emission ( \$\\lambda\_{max}\$  \~520 nm) with a signal intensity of approximately  \$3 \\times 10^{11}\$  photons/min/cm², optimized for visibility to the naked eye.

##### Project Scope: The Three Pillars

1. **Autonomous Emission:**  Leveraging the hispidin cycle to recycle caffeylpyruvic acid into caffeic acid via the hybrid module, ensuring an uninterrupted supply of luminescent precursors without exogenous intervention.  
2. **Durability:**  Establishing rigorous metabolic coupling with photosynthesis and the primary "sugar pathway" (PEP/E4P), ensuring the system is powered by the plant's internal carbon fixation.  
3. **Stress Resilience:**  Utilizing psychrophilic engineering to maintain thermodynamic stability and kinetic efficiency across extreme temperature gradients.**The "So What?" Analysis:**  The competitive advantage of this system lies in its ability to transform high-value horticulture and urban forestry into "living sensors." This provides a bio-renewable light source that simultaneously monitors environmental health (e.g., drought, pest attack). Establishing a standardized evidence framework for these complex metabolic interactions is the prerequisite for scaling these autonomous systems into global infrastructure.

#### 2\. Evidence Classification Matrix: The 9 Core Research Areas

To mitigate developmental risk and maintain data integrity across multi-gene assemblies, we employ a classification matrix that grounds our synthetic biology in verified evidence zones.| Research Area | Status | Justification (Source: PBI-21-1671, CG-21-96, EurekAlert) || \------ | \------ | \------ || **1\. Caffeic Acid Recycling** | **GREEN** | Experimentally established; CPH converts caffeylpyruvic acid to caffeic acid to maintain the FBP cycle. || **2\. Hispidin Biosynthesis Efficiency** | **GREEN** | Validated 3x efficiency increase using indigenous hispidin synthases coupled with NPGA. || **3\. ATP-Dependent Metabolic Coupling** | **BLUE** | Supported association; rapid signal decay observed with AA and OM respiratory inhibitors. || **4\. Oxygen Availability in Tissues** | **BLUE** | Supported association; eFBP signals demonstrate high sensitivity to  \$O\_2\$  partial pressure. || **5\. Heat Sensitivity (NnLuz)** | **GREEN** | Experimentally established; emission exhibits a "cliff-like drop" when ambient  \$T \> 30^\\circ C\$ . || **6\. UV-Induced Emission Spikes** | **GREEN** | Experimentally established; UV stress induces caffeic acid biosynthesis, resulting in natural signal increases. || **7\. Cold-Stress Kinetic Adaptation** | **YELLOW** | Hypothesis; while natural cold response increases signal,  *engineered*  kinetic stability at  \$T \< 10^\\circ C\$  is in development. || **8\. Genomic Stability (Multi-Gene)** | **BLUE** | Supported association; stable expression achieved in  *Nicotiana*  and  *Populus*  via TGSII stacking. || **9\. In Silico Structural Predictions** | **GREEN** | Experimentally established; AlphaFold2 accurately mapped residues forming H-bonds with  \$p\$ \-coumaroyl shikimate. |  
*Classification:*  ***GREEN***  *(Experimentally established),*  ***BLUE***  *(Supported),*  ***YELLOW***  *(Hypothesis),*  ***RED***  *(Unverified).*

#### 3\. The 7 Genuine Research Gaps for Long-Lived Bioluminescent Plants

Achieving long-term plant vitality requires resolving critical bottlenecks that lead to metabolic load or signal failure.

1. **Kinetic Quenching at Low Temperatures:**  Mesophilic enzymes lose active-site flexibility in the cold.  **Competitive Necessity:**  Enabling year-round functionality for "living cities" in temperate climates.  
2. **Thermal Degradation of NnLuz:**  Rapid unfolding of luciferase above  \$30^\\circ C\$  limits applications in tropical urban corridors.  
3. **Precursor Toxicity:**  High flux of caffeic acid is required for signal, but levels  \$\> 0.5\$  mM induce cellular inhibition.  **Impact:**  Requires "metabolic rheostats" to modulate precursor levels and prevent premature cell death.  
4. **Oxygen Diffusion Limits:**  Depth-dependent oxygen gradients in dense woody structures (e.g., Poplar trunks) limit internal autoluminescence.  
5. **Circadian-Metabolic Desync:**  Luminescence current fluctuates with the photosynthetic cycle; decoupling is necessary for peak night-time performance.  
6. **Protein Folding in Psychrophilic Variants:**  Structural stability trade-offs when "cold-active" enzymes are expressed in mesophilic plant hosts.  
7. **Post-Translational Modification Flux:**  Divergent species-specific efficiency of PPTase (NPGA) affects the activation rate of the hispidin synthase module.*These bottlenecks represent the transition point from observation to the specific experimental designs outlined in our Hypothesis Matrix.*

#### 4\. Structured Hypothesis Matrix

This matrix converts structural research gaps into an engineering roadmap for high-fidelity biological outputs.| Hypothesis | Variables | Controls | Measurement Metrics || \------ | \------ | \------ | \------ || **Sugar Pathway Dependency** | PEP/E4P availability vs. signal | Wild-Type (WT) baseline | Exogenous Carbon Source Correlation || **NnLuz Flexibility Enhancement** | P142G Mutation in Luciferase | Native  \$NnLuz\$  sequence | Kinetic Flux Maintenance Coefficient ( \$K\_m\$  at  \$10^\\circ C\$ ) || **Low-Temp CPH Efficiency** | Gly88Ser substitution in CPH | Non-mutated  \$ngarCPH\$ | \$LC-MS/MS\$  Caffeic Acid Recycling Rate || **Energy Coupling Verification** | ATP inhibition ( \$AA\$ / \$OM\$ ) | Mock-treated  \$eFBP\$  cells | Relative Light Units ( \$RLU\$ ) Decay Gradient |  
**The "So What?" Layer:**  Testing null hypotheses regarding energy dependency (e.g., ATP inhibition) confirms that the luminescence signal is an intrinsic reporter of cellular vitality. A signal drop upon respiratory inhibition proves the system's reliability as a diagnostic tool for plant metabolic health.

#### 5\. Gap 3 Extension: Cold-Night Kinetic Quenching & Psychrophilic Engineering

To ensure year-round functionality in temperate zones, we must engineer enzymes capable of catalysis at low thermal energies. Mesophilic enzymes become rigid in the cold; we therefore adopt a "flexibility-over-stability" structural logic.

##### Engineering nnLuz\_cold\_v1

Utilizing  **P142G/F145S**  mutations, we replace rigid prolines and bulky residues with Glycine and Serine. Following the structural logic of psychrophilic adaptation, the  **F145S**  mutation (Phenylalanine to Serine) reduces steric hindrance in the active site. By replacing bulky side chains with smaller groups, we reduce the  \$\\Delta G\$  of activation and increase the protein's "breathing" capacity, maintaining catalytic turnover at  \$10^\\circ C\$ .

##### Engineering ngarCPH\_cold\_v1

We employ  **Gly88Ser/Ala91Gly**  substitutions to mimic Cold-Acclimation Proteins (CAPs). These modifications ensure the recycling of caffeylpyruvic acid remains efficient during cold-night cycles, preventing precursor bottlenecks. Unlike thermophilic proteins that use salt bridges to increase rigidity, our psychrophilic variants prioritize a less compact core and neutral, tiny amino acids to lower the entropic cost of enzyme-ligand binding.

#### 6\. The 12-Stage Computational Architecture

Our  *in silico*  workflow architecture minimizes wet-lab failure rates by optimizing multi-gene assembly prior to transformation.

1. **Codon Optimization:**  Strategic sequence tailoring for  *N. tabacum*  and  *Populus*  preferences.  
2. **Structure Prediction:**  AlphaFold2 modeling of the 3D architecture of  \$BnC30H1\$  and  \$NnLuz\$ .  
3. **Ligand Docking Analysis:**  AutoDock Vina simulation of  \$p\$ \-coumaroyl shikimate binding.  
4. **Binding Free Energy Calculation:**  Quantitative affinity comparison of  \$BnC30H1\$  variants.  
5. **Hydrogen Bond Mapping:**  Identification of critical residues (Trp112, His242, Trp294, Thr298) that form specific hydrogen bonds with the  **\$p**\$  **\-coumaroyl shikimate**  ligand.  
6. **Simulated Mutagenesis:**  Assessing the flexibility impact of  **P142G/F145S**  substitutions.  
7. **Thermodynamic Stability Profiling:**  Balancing the  **Entropy/Enthalpy trade-off**  to ensure psychrophilic variants remain stable enough for host expression.  
8. **Metabolic Flux Analysis:**  Modeling the eFBP coupling to the Calvin Cycle.  
9. **Pathway Interference Prediction:**  Evaluating diversion of precursors from Lignin and Flavonoid biosynthesis.  
10. **Regulatory Element Optimization:**  Analyzing the anther-specific  **PAS promoter**  for localized marker-free expression.  
11. **Marker-Free Recombination Simulation:**  Validating Cre/loxP excision logic for genomic cleanliness.  
12. **Virtual Photometry:**  Predictive modeling of photon output per  \$cm^2\$  based on simulated flux.

#### 7\. In Silico Wet-Lab Validation Results & Recombinant Expression Protocol

Validation results indicate that the hybrid pathway approach—coupling indigenous plant hispidin synthases with the fungal module—yields a  **3x efficiency increase**  in HispS activity and an  **8x total signal increase**  over the original fungal pathway (oFBP). Plant hispidin synthases are notably smaller and have simpler biological requirements, enhancing their usability in complex stacks.

##### Recombinant Expression Protocol

* **Preparation:**  Culture  *Agrobacterium tumefaciens*  (EHA105) to an  \$OD\_{600}\$  of 0.8 in infection buffer (10 mM  \$MgCl\_2\$ , 10 mM MES, 150  \$\\mu M\$   **Acetosyringone (As)** ).  
* **Transformation:**  Leaf disc infection or BY-2 cell suspension ( \$OD\_{600}\$  0.25). Incubate in the dark for 48 hours for T-DNA integration.  
* **Selection:**  Utilize the  **PAS-driven Cre recombinase system** . Anther-specific activation triggers the marker-free excision of the HPT and Cre cassette, resulting in a clean genomic insertion.  
* **Verification:**  Quantitative RT-qPCR for the multi-gene stack and  \$LC-MS/MS\$  profiling of caffeic acid and hispidin levels to ensure metabolic flux is optimized.**Conclusion:**  This architecture enables the realization of "living cities," where roadside poplar trees function as bio-renewable light sources and continuous environmental monitors. By shifting toward an energy-driven, hybrid metabolic model, we align the future of lighting with the fundamental processes of life—photosynthesis and respiration.

