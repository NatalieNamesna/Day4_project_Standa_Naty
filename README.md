# THE DUNE algae project
![Static Badge](https://img.shields.io/badge/Topic-Algae%20diversity-green)
![Static Badge](https://img.shields.io/badge/Sampling%20area-Europe-blue)
![Static Badge](https://img.shields.io/badge/Methods-Metabarcoding-purple)



## Contact
Stanislav Jíra jirasta@natur.cuni.cz
Natalie Namesna 

Diversity analysis of biological soil crusts across European dune ecosystems.

## Project Overview
- **Research question:** What is the diversity of green algae in dune BSCs.
- **Study area:** Europe
- **Sampling period:** 2026-2029
- **Status:** Analysis in progress

## Repository Structure

├── Data/
│   ├── Raw/           # Original field observations (READ-ONLY)
│   └── Processed/     # Cleaned datasets
     └── Env_metadata/     # temperature, moisture data
     └── Diversity_indices/  # Diversity data
├── R/                 # Analysis scripts (run in order: 01_, 02_, 03_...)
├── Outputs/
│   ├── Figures/
│   └── Tables/
└── README.md

## Getting Started
1. Look on the project webpages: www.dunealgae.com
2. Clone this repository
3. Install R packages: "vegan", "tidyverse", "usethis"
4. Run scripts in `R/` folder in numerical order
