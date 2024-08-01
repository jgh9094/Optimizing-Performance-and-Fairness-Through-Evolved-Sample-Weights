# Optimizing Model Performance and Fairness Through Genetically Evolved Sample Weights

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13149100.svg)](https://doi.org/10.5281/zenodo.13149100)
[![supplemental](https://img.shields.io/badge/go_to-supplementary_material-98111e)](https://jgh9094.github.io/PSB2024-Fairness-Through-Evolved-Sample-Weights/Sup/)
[![data](https://img.shields.io/badge/go_to-data-9807FF)](https://osf.io/nx6wp/)

## Authors

- [Anil Kumar Saini](https://theaksaini.github.io/)
- [Jose Guadalupe Hernandez](https://jgh9094.github.io/)
- [Emily F. Wong](https://www.cedars-sinai.edu/research-education/research/labs/bright/members.html)
- [Jason H. Moore](https://jasonhmoore.org/)

## Overview

Link to all supplementary material: [here](https://jgh9094.github.io/PSB2024-Fairness-Through-Evolved-Sample-Weights/Sup/).
All data is available on the Open Science Framework [here](https://osf.io//).

### Abstract

> Machine learning models trained on real-world data may inadvertently produce biased predictions that negatively impact people from marginalized communities.
Biased predictions are especially problematic in healthcare settings, where these predictions can lead to underdiagnosis and misdiagnosis, exacerbating existing inequalities in healthcare access.
Reweighing is a method that mitigates bias in model predictions by assigning weight to each data sample in the training set used during model training.
In this work, we present a Genetic Algorithm (GA) for evolving these sample weights.
We use ten publicly available datasets and one medical dataset to test the effectiveness of our new approach.
Our results demonstrate that evolving sample weights through our GA approach optimizes both predictive performance (e.g., area under ROC curve) and fairness (e.g., false negative rate across groups) better than the sample weights computed using the existing methods.