# Frankel_Freedman_Tseng_OpenData_Ecosphere

## Sex-specific costs of melanization in a widespread butterfly species

Data accompanying:

> Frankel, W., Freedman, M., Tseng, M. (2026). Sex-specific costs of melanization in a widespread butterfly species. *Ecosphere*.

**Authors:** Wendy Frankel<sup>1</sup>, Micah Freedman<sup>2,3</sup>, Michelle Tseng<sup>1</sup>

**Affiliations:**

<sup>1</sup>Departments of Botany and Zoology, Biodiversity Research Centre, University of British Columbia, Vancouver, Canada
<sup>2</sup>Department of Botany, Biodiversity Research Centre, University of British Columbia, Vancouver, Canada
<sup>3</sup>Current address: Department of Ecology & Evolutionary Biology, University of Toronto, Toronto, Canada

*Corresponding author: Michelle Tseng, <tsengm@mail.ubc.ca>*

---

## Repository Structure

- `data/` — Input and processed datasets used in the analyses.

## Data Files and Column Descriptions

### 1. `Lab-monarch-data-for-archiving-Ecosphere.csv`

- **Monarch_ID** — unique identifier for individual monarch butterflies
- **Plant_ID** — unique identifier for individual milkweed plants
- **Milkweed_species** — species of milkweed tested (A = *Asclepias*, G = *Gomphocarpus*)
- **Monarch_family** — lineage of individual monarchs
- **Monarch_sex** — monarch sex (male, female)
- **Caterpillar_proportion_black** — proportion of black colouration on 5th instar caterpillar (see Methods for details)
- **Adult_percent_black** — percentage of black on the adult monarch forewing
- **Adult_wingsize_mm2** — size of adult forewing, in mm²
- **Adult_wing_measured** — which wing was measured (left, right)
- **Wing_aspect_ratio** — forewing length divided by forewing width
- **Milkweed_cardenolide_category** — cardenolides were not measured in this study; plant species were classified into low/medium/high cardenolide categories based on previous literature (see Discussion for details)
- **Monarch_development_time_days** — number of days from first instar to eclosion
- **Monarch_growth_rate** — wing size divided by development time
- **Experiment_type** — greenhouse or lab

### 2. `Monarch-greenhouse-data-for-archiving-Ecosphere.csv`

- **Monarch_ID** — unique identifier for individual monarchs
- **Temperature_treatment** — cold = 22°C/16°C day/night; warm = 32°C/26°C day/night
- **Monarch_family** — lineage of individual monarchs
- **Monarch_sex** — monarch sex (male, female)
- **Caterpillar_proportion_black** — proportion of black colouration on 5th instar caterpillar (see Methods for details)
- **Adult_percent_black** — percentage of black on the adult monarch forewing
- **Adult_wingsize_mm2** — size of adult forewing, in mm²
- **Adult_wing_measured** — which wing was measured (left, right)
- **Wing_aspect_ratio** — forewing length divided by forewing width
- **Monarch_development_time_days** — number of days from egg lay to pupation
- **Monarch_growth_rate** — wing size divided by development time
- **Experiment_type** — greenhouse or lab

## Citation

If you use this repository, please cite:

> Frankel, W., Freedman, M., Tseng, M. (2026). Sex-specific costs of melanization in a widespread butterfly species. *Ecosphere*.
