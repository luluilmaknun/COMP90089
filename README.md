# Mortality Predictive Analysis on Acute Pancreatitis in Intensive Care Unit Patients - MIMIC-IV Dataset

Author: Group 5 of COMP90089
- Danlan Chen [1288528]
- Edoardo de Duro [1497010]
- Muhan Guan [1407870]
- Lulu Qurotaini [1328810]

## Project Overview

Acute Pancreatitis (AP) is a severe inflammation of the pancreas and it is one of the most common causes for hospitalization admission in the USA (Lee \& Papachristoum, 2019). Despite the mortality caused by AP having recently decreased, this disease remains a cause of death in ICU departments (1\%-5\%; Krishna et al., 2017). Particularly, the mortality rate seems to be higher in subgroups characterized by unclear clinical and laboratory risk factors (Vege, 2022). Here, we use MIMIC-IV (Jonson et al, 2020) database to predict mortality and identify the strongest predictors of death due to AP.

## Dataset

The project utilizes the MIMIC-IV (Medical Information Mart for Intensive Care) dataset, a comprehensive source of ICU patient data. Access to the dataset is required for running the analysis. You can obtain the dataset from the official MIMIC website (https://physionet.org/content/mimic-iv/). Please ensure that you have the necessary permissions and adhere to ethical guidelines when working with patient data.

## Dependencies

The project runs on Python `>3.9`. Make sure you have the following Python libraries installed:

```
numpy==1.26.1
```

You can install the dependencies using `pip`:

```bash
pip install -r requirements.txt
```

## Project Structure

* `dataset/`: This directory should contain the cohort dataset extracted from MIMIC-IV, you may not be able to see the files due to privacy constraint.
* `exploratory/`: Jupyter notebooks for data exploration, preprocessing.
* `predictive_analysis/`: Jupyter notebooks for predictive analysis, including feature engineering, modeling, and evaluation.
* `clustering_analysis/`: Jupyter notebooks for clustering analysis, including feature engineering, modeling, and evaluation.
* `results/`: Store the trained models, evaluation metrics, and visualizations generated during the analysis.
