# ML Diabetes Classification

Supervised machine learning project for predicting the likelihood of diabetes from tabular patient data (e.g. clinical measurements and lab values).

The repository is structured like a small Python package with configuration and schema files so that you can iteratively build and experiment with classification models.

---

## Features

- End-to-end pipeline for binary classification on a diabetes dataset
- Clear separation between:
  - configuration (`config/`)
  - schema/metadata (`schema.yaml`)
  - installable package code (`setup.py`, Python modules)
- Reproducible environment via `requirements.txt`
- MIT licensed for unrestricted use and modification

---

## Project Structure

```
ML_Diabetes_Classification/
├─ config/              # Configuration files (paths, parameters, etc.)
├─ .gitignore           # Git ignore rules
├─ LICENSE              # MIT license
├─ README.md            # Project documentation (you are here)
├─ requirements.txt     # Python dependencies
├─ schema.yaml          # Data schema / feature definitions
└─ setup.py             # Package metadata and installation
```