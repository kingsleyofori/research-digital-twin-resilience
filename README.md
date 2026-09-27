# Digital Twin-Based Stochastic Energy Resilience Modelling of Cape Town Municipal Facilities
This repository contains the data-processing scripts, stochastic simulation model, resilience calculations and interactive visualisation developed for the study “Digital Twin-Based Stochastic Energy Resilience Modelling of Cape Town Municipal Facilities under Load Shedding.”

The study combines historical municipal electricity-use data with historical load-shedding records to examine electricity-disruption exposure across municipal facilities in Cape Town. A stochastic simulation approach was used to generate possible disruption conditions from the historical load-shedding record, while a digital twin environment was used to represent the facilities and their modelled resilience characteristics.

The repository is intended to support transparency and reproducibility of the research.

## Repository Contents

The repository contains the research data, analysis notebook, interactive digital twin, licensing information, and citation information used in the study.

| File                                  | What it contains                                                                                                                              | Where to find it |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| `CITATION.cff`                        | Citation information for citing this research repository and its associated study                                                             | Root directory   |
| `LICENSE`                             | MIT License governing the original code and materials in this repository                                                                      | Root directory   |
| `Loadshedding_schedule.csv`           | Historical load-shedding schedule used to represent electricity disruption conditions in the study                                            | Root directory   |
| `SmartFacility_Energy_FullNames.xlsx` | Municipal facility electricity-use dataset used for the facility energy analysis and modelling                                                | Root directory   |
| `cape_town_twin_interactive.html`     | Interactive digital twin visualisation of the municipal facilities and their modelled resilience characteristics                              | Root directory   |
| `digital_twin_study.ipynb`            | Main Jupyter Notebook containing the data preparation, analysis, stochastic modelling, resilience calculations, and supporting visualisations | Root directory   |
| `README.md`                           | Description of the study, repository structure, data sources, methods, and instructions for using the files                                   | Root directory   |

## Quick Access

Researchers interested in specific parts of the study can use the files as follows:

### 1. Want to reproduce the analysis?

Start with:

`digital_twin_study.ipynb`

The notebook contains the main analysis workflow, including data preparation, load-shedding analysis, stochastic simulation, resilience calculations, sensitivity analysis, and supporting visualisations.

### 2. Want the municipal energy dataset?

Use:

`SmartFacility_Energy_FullNames.xlsx`

This file contains the facility-level electricity-use data used in the study.

### 3. Want the load-shedding data?

Use:

`Loadshedding_schedule.csv`

This file contains the historical electricity-disruption records used to construct the disruption environment for the stochastic simulations.

### 4. Want to explore the digital twin?

Open:

`cape_town_twin_interactive.html`

The HTML file provides the interactive visualisation developed for the study. It can be opened directly in a web browser without running the Jupyter Notebook.

### 5. Want to cite the repository?

Use:

`CITATION.cff`

GitHub can use this file to provide citation information for the repository.

### 6. Want to check the usage rights?

See:

`LICENSE`

The repository's original code is distributed under the MIT License. Third-party datasets remain subject to the licensing and attribution conditions of their respective data providers.

## Recommended Starting Point

| If you are...                         | Start with...                         |
| ------------------------------------- | ------------------------------------- |
| A researcher reproducing the study    | `digital_twin_study.ipynb`            |
| Looking for the facility energy data  | `SmartFacility_Energy_FullNames.xlsx` |
| Looking for the load-shedding records | `Loadshedding_schedule.csv`           |
| Exploring the digital twin            | `cape_town_twin_interactive.html`     |
| Citing the research                   | `CITATION.cff`                        |
| Checking licensing information        | `LICENSE`                             |

