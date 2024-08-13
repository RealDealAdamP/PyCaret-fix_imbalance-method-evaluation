# PyCaret `fix_imbalance_method` Evaluation

This repository contains a Jupyter Notebook that automates the evaluation of all PyCaret `fix_imbalance_method` options available for handling class imbalances within a dataset. 
The notebook is structured to compare different models using each method and identify which one yields the most optimal performance.

## Project Overview

Class imbalance is a common issue in machine learning, where certain classes are underrepresented in the data. 
PyCaret offers several methods to address this issue through the `fix_imbalance_method` parameter. This notebook:

- Loads a dataset containing comments labeled with different stances.
- Identifies all available methods for the `fix_imbalance_method` parameter from the PyCaret Setup function.
- Iteratively applies each method to the dataset.
- Compares model performances and ranks the top models based on accuracy, recall, precision, and f1 scores.

## Files in the Repository

- **PyCaret fix_imbalance method evaluation.ipynb**: The main Jupyter Notebook containing the code and analysis.

## Prerequisites

Ensure you have the following Python libraries installed:

- `pycaret`
- `pandas`
- `re` (part of Python's standard library)

You can install the required libraries using:

```bash
pip install pycaret pandas
