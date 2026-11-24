# R code for the Bachelor thesis

**Stable Resampling for Confidence Intervals in CRISPR-Barcoded Clonal Fitness
Screens: A Comparison with Published Estimates**

Horty Katé Nango, Bachelor thesis, Biomathematics,
Koblenz University of Applied Sciences (RheinAhrCampus Remagen), 2026.

## Data

The analyses use the count files published by Eirew et al. (2022):

- Article: Eirew, P. et al. Accurate determination of CRISPR-mediated gene
  fitness in transplantable tumours. *Nature Communications* 13, 4534 (2022).
  https://doi.org/10.1038/s41467-022-31830-2
- Data: https://doi.org/10.5281/zenodo.6584802 (CC BY 4.0)

The data are not included in this repository. Download them from Zenodo and
set the data folder at the beginning of each script.

## Scripts

| File | Content | Thesis section |
|---|---|---|
| `EDA_all_PDX.R` | Exploratory analysis of the 184 count files | 3.3.1 |

Further scripts will be added.

## Requirements

R (version 4.5.2) with the packages `data.table`, `knitr` and `rmarkdown`.
