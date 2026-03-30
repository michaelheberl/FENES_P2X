# Power-to-X III Project Supplementary Code  
**Techno-economic site analysis of Ammonia, Methanol and Kerosene Production in South Africa, Chile and Germany**

---

## Overview

This repository contains the supplementary code developed primarily for the **Power-to-X III (P2X3) project** (https://fenes.oth-regensburg.de/projekte/p2x-phase-iii). The codebase was extended with additional models specifically created for the associated scientific publication (DOI), which builds upon and integrates results from the project.

The repository provides techno-economic energy system models for the production of:
- Ammonia  
- Methanol  
- Kerosene  
- Methane  

across multiple international locations with varying renewable energy potentials and infrastructure conditions.
The models represent different production pathways and infrastructure scenarios, enabling comparative analysis across regions and development stages.

---

## Methodology

All energy systems are modeled using the open energy modelling framework (https://oemof.org/).

- Inputs parameters are in xlsx
- Energy system components and configurations are defined within Jupyter Notebooks  
- System optimization and calculations are performed within these notebooks  
- Results are exported to csv for further analysis  

---

## Repository Structure

The repository is organized hierarchically by:

### 1. Energy Carrier (Top-Level Folders)
Each main directory represents one energy carrier:
- `ammonia/` (Ammoniak)
- `methanol/` (Methanol
- `kerosene/` (Fischer Tropsch)
- `methane/` (Methane)

---

### 2. Geographic Locations (Subfolders)

Within each energy carrier, models are structured by location:

- **Germany**
  - Leuna  
  - Memmingen  
  - Höchst  

- **High renewable potential regions**
  - Patagonia (Chile)  
  - South Africa  

---

### 3. Scenario Variants (Model Folders)

Each location contains multiple model variants representing different infrastructure conditions:

- **Greenfield scenarios**
  - No pre-existing infrastructure  
  - Fully newly developed systems  

- **Brownfield scenarios**
  - Existing infrastructure partially available  
  - Different expansion levels depending on scenario  

The specific configuration and expansion stage can be inferred from the folder naming.

---

## Model Structure

All models follow a consistent implementation approach to ensure comparability.
Each individual model folder (i.e., scenario) contains:

- **Jupyter Notebook (`.ipynb`)**
  - Defines the full energy system  
  - Follows a consistent structure across all models  
  - Includes system setup, parameterization, optimization, analysis and visualization

- **Database (`.xlsx`)**
  - Location-specific  
  - Scenario-specific (Greenfield / Brownfield level)  
  - Contains input parameters and assumptions  

- **Results (`.csv`)**
  - Contains all computed model outputs  
  - Includes techno-economic indicators and system parameters  

---

## Citation

If you use this code, please cite the associated publication.

---
