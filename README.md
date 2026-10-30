# Can Machine Learning Support the Inverse Design of Sustainable PLA-Based Composites for Fused Filament Fabrication with Limited Data? An Exploratory Analysis

**Davide Renzi¹†, Daniela Fico²†, Elisabetta Monaldo¹*, Roberto Vergallo³*, Sonia Marfia¹, Carola Esposito Corcione²**

¹ Department of Civil, Computer Science and Aeronautical Technologies Engineering, Roma Tre University, Rome (RM), 00146, Italy

² Department of Engineering for Innovation, University of Salento, Monteroni di Lecce (LE), Italy

³ Pegaso Digital University, Department of Information Science and Technology, Naples (NA), Italy

† These authors contributed equally to this work.

* Corresponding authors: Elisabetta Monaldo and Roberto Vergallo.

## Overview

This repository contains the experimental dataset and Python notebooks accompanying the article identified above, accepted for publication in Materials Today Communications.

## Repository structure

- `dataset/`: experimental dataset used for the predictive analyses.
- `notebooks/`: Jupyter notebooks implementing the two predictive strategies.

## Predictive strategies

- `strategy_A.ipynb`: hybrid classification-regression strategy.
- `strategy_B.ipynb`: double-classification strategy.

## Requirements

The analyses were developed using Python 3.12.13.

Main packages:
- numpy
- pandas
- matplotlib
- scikit-learn
- imbalanced-learn
- openpyxl

Install the required packages with:

```bash
pip install -r requirements.txt
```

## Reproducibility

To reproduce the analyses, open the notebooks contained in the `notebooks/` folder and run them from the beginning.

The dataset is provided in the `dataset/` folder. The notebooks use relative paths to load the data.

## Notes

This repository is provided in anonymized form for peer review. A complete public version will be released upon acceptance of the manuscript.
