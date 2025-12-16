# Industrial Data Science Course Material
This repository contains the course material for an Industrial Data Science course.

[//]: # TODO - This material is still work in progress (expected to be ready to be released in january/february 2026).

You can find the latest version of the course material at https://noxthot.github.io/ws25_industrial_datascience_manuscript/.

## Citing this manuscript
[![DOI](https://zenodo.org/badge/1035638412.svg)](https://zenodo.org/badge/latestdoi/1035638412)

[//]: # TODO - update
Right now, this is a draft version of the course material.
Once ready (expected to be in january/february 2026), it will be properly published and licenced.

If you use this material, please cite it by using the [citation information](./CITATION.cff).

## Content
- Time series
- Data imputation
- Clustering
- Classification
- Regression
- Batch and Stream Processing
- Exploratory Data Analysis
- Predictive Maintenance


## Setup
`uv` is used to manage the virtual environment and dependencies.

Then install the dependencies with:
```bash
uv sync --dev
```

## Local preview
To preview the manuscript locally, run:
```bash
uv run quarto preview
```
