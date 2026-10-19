# DFT Investigation of Anionic Dye and Heavy-Metal Adsorption on a Brushite–Banana-Peel Biocomposite

**Project Duration:** April 2026 – June 2026  
**Researcher:** Dr. Erum Hasan  
**Research Areas:** Computational Chemistry, Density Functional Theory (DFT), Environmental Chemistry, Molecular Modeling, and Adsorption Studies

## 1. Project Overview

This project investigates the adsorption of selected anionic dyes and heavy-metal ions on a modeled brushite–biomass composite inspired by banana-peel-based adsorbent materials.

A brushite cluster was constructed from its crystal structure and combined with cellulose, hemicellulose, and lignin to represent the mineral and major structural components of the modeled biocomposite.

The molecular structures were initially constructed and inspected in Avogadro. Preliminary geometry optimization was performed using xTB, followed by vibrational frequency calculations to assess the optimized structures. Subsequently, density functional theory (DFT) calculations were carried out using ORCA.

The same general computational workflow was applied to the investigated dye and metal-ion systems. Electronic properties, including HOMO–LUMO distributions and molecular electrostatic potential (MEP) maps, were visualized using VESTA. Geometrical structures were visualized using BIOVIA Discovery Studio.

The overall objective is to investigate molecular-level interactions between the modeled biocomposite and selected environmental pollutants.

## 2. Research Objectives

- Construct a brushite cluster derived from its crystal structure.
- Develop a composite model incorporating brushite, cellulose, hemicellulose, and lignin.
- Optimize and refine molecular geometries using xTB.
- Perform vibrational frequency calculations to assess the nature of the optimized structures.
- Conduct DFT calculations using ORCA.
- Investigate interactions between the modeled composite and selected anionic dyes.
- Study the interactions of Pb²⁺, Cu²⁺, and Al³⁺ ions with the modeled composite.
- Analyze frontier molecular orbitals and molecular electrostatic potential distributions.
- Visualize and compare optimized geometries and pollutant–composite structures.
- Evaluate adsorption-related properties using the calculated results and appropriate reference systems.

## 3. Computational Methodology

### Step 1: Brushite Cluster Construction

A cluster model was constructed from the crystal structure of brushite. This cluster was used as the mineral component of the modeled composite.

### Step 2: Biocomposite Model Construction

The brushite cluster was combined with molecular models of three major structural components of banana peel:

- Cellulose
- Hemicellulose
- Lignin

These components were used to construct a brushite–biomass composite model for investigating pollutant interactions at the molecular level.

### Step 3: Preliminary Geometry Optimization Using xTB

The initial molecular structures were prepared and inspected using Avogadro. Preliminary geometry optimization was subsequently performed using xTB to refine the structures before further calculations.

### Step 4: Vibrational Frequency Analysis

Frequency calculations were performed to evaluate the optimized structures. Structures were selected for subsequent calculations after obtaining frequency results without negative frequencies, according to the project's validation criterion.

For rigorous confirmation of a local minimum, the frequency calculation must correspond to the optimized geometry at the same computational level. Imaginary vibrational modes should be assessed using the frequency output and calculation settings.

### Step 5: DFT Calculations Using ORCA

The refined structures were subjected to DFT calculations using ORCA.

The computational workflow was applied to the modeled composite and the investigated pollutant systems. The resulting output files were used for subsequent electronic-structure analysis and interpretation.

The exact DFT functional, basis set, charge, multiplicity, solvation model, and convergence settings will be documented from the original computational input files.

### Step 6: HOMO–LUMO Analysis

Frontier molecular orbital analysis was performed using the results of the electronic-structure calculations.

HOMO and LUMO distributions were visualized using VESTA from suitable volumetric data generated or converted from the computational outputs.

This analysis can help interpret the spatial distribution of frontier orbitals and investigate possible electronic contributions to molecular interactions.

Where appropriate, the HOMO and LUMO energies can be used to calculate the frontier orbital energy gap:

**HOMO–LUMO gap = E(LUMO) − E(HOMO)**

The numerical orbital energies and energy gap should be reported from the calculated results.

### Step 7: Molecular Electrostatic Potential (MEP) Analysis

Molecular electrostatic potential maps were prepared using VESTA and suitable calculated electrostatic-potential data.

MEP visualization helps identify regions of relatively positive and negative electrostatic potential around the modeled structures. These distributions can support the interpretation of possible interaction sites between pollutant species and the composite model.

MEP maps should be interpreted alongside the molecular geometry, charge distribution, and other relevant computational results.

### Step 8: Geometrical Visualization

Optimized molecular geometries and modeled composite–pollutant structures were visualized using BIOVIA Discovery Studio.

These figures support the examination and presentation of molecular arrangements, interatomic distances, and possible interactions between the modeled adsorbent and pollutant species.

### Step 9: Dye and Metal-Ion Investigations

The general computational workflow was applied to the selected anionic dyes and the following metal ions:

- Lead (Pb²⁺)
- Copper (Cu²⁺)
- Aluminum (Al³⁺)

The calculated structures and electronic properties were examined to investigate their interactions with the modeled composite.

Adsorption strengths should be compared using appropriately defined adsorption energies and consistent reference calculations rather than geometry or orbital figures alone.

## 4. Systems Investigated

| Component | Description |
|---|---|
| Mineral component | Brushite-derived cluster |
| Biomass components | Cellulose, hemicellulose, and lignin |
| Adsorbent model | Brushite–biomass composite |
| Heavy-metal ions | Pb²⁺, Cu²⁺, and Al³⁺ |
| Organic pollutants | Selected anionic dyes |
| Structure construction | Avogadro |
| Preliminary geometry refinement | xTB |
| Main electronic-structure calculations | ORCA DFT |
| Frontier orbital and MEP visualization | VESTA |
| Geometrical visualization | BIOVIA Discovery Studio |

## 5. Software and Tools

### Avogadro
Used for molecular structure construction, initial visualization, and geometry inspection.

### xTB
Used for preliminary geometry optimization and structural refinement before further calculations.

### ORCA
Used for DFT calculations and vibrational frequency analysis, along with the generation of electronic-structure results.

### VESTA
Used to visualize HOMO–LUMO distributions and molecular electrostatic potential maps from compatible volumetric data.

### BIOVIA Discovery Studio
Used to visualize optimized molecular geometries and prepare structural figures of the modeled systems.

## 6. Repository Structure

```text
banana-peel-adsorption-dft/
│
├── README.md
│
├── structures/
│   ├── brushite_cluster/
│   ├── cellulose/
│   ├── hemicellulose/
│   ├── lignin/
│   ├── composite_model/
│   └── pollutant_species/
│
├── xtb/
│   ├── input_files/
│   └── output_files/
│
├── orca/
│   ├── input_files/
│   └── output_files/
│
├── results/
│   ├── optimized_geometries/
│   ├── frequency_analysis/
│   ├── homo_lumo/
│   ├── mep/
│   └── adsorption_analysis/
│
├── figures/
│   ├── geometrical_structures/
│   ├── homo_lumo/
│   └── mep/
│
└── analysis/
```

This is a proposed directory structure. Folders can be created as the corresponding input files, output files, results, and figures are organized.

## 7. Results and Analysis

The computational outputs can be organized into the following categories:

- Optimized molecular and composite geometries
- Vibrational frequency results
- Total electronic energies
- HOMO and LUMO energies and orbital distributions
- HOMO–LUMO energy gaps
- Molecular electrostatic potential maps
- Interatomic distances and structural parameters
- Adsorption energies, where the required reference calculations are available
- Comparative analysis of the investigated dyes and metal ions

Numerical results and conclusions should be included after verification against the original ORCA and xTB output files.

## 8. Reproducibility

This repository is intended to document the computational methodology, molecular structures, supporting input files, analysis, and research findings.

To facilitate reproducibility, the following information will be added where available:

- Software names and versions
- DFT functional and basis set
- Molecular charge and spin multiplicity
- Geometry optimization and frequency settings
- Solvation model and convergence criteria
- Computational input and output files
- Energy definitions and reference calculations
- Analysis procedures and visualization data

Only files that can be shared without violating publication, collaboration, or data-sharing restrictions will be uploaded.

## 9. Scientific Scope and Limitations

This study provides a computational investigation of pollutant interactions with a modeled brushite–biomass composite.

The molecular model represents selected components of a complex biomass-based material and does not necessarily capture every structural or chemical feature of experimentally prepared banana peel.

Computational adsorption energies, orbital distributions, and MEP maps can provide insight into molecular interactions. However, claims about actual adsorption capacity, removal efficiency, or experimental performance require appropriate supporting evidence and, where possible, experimental validation.

Meaningful comparisons of adsorption energies require consistent energy definitions, compatible reference states, and careful treatment of charge, solvation, and computational settings.

## 10. Researcher

**Dr. Erum Hasan**

Research interests:

- Computational Chemistry
- Density Functional Theory
- Molecular Modeling
- Computational Drug Discovery
- Adsorption and Environmental Remediation
- Nanomaterials and Electronic-Structure Analysis

