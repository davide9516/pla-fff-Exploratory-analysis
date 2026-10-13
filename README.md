# Exploratory analysis for PLA-based composites processed by FFF

This repository contains the experimental dataset and Python notebooks associated with the manuscript.

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
