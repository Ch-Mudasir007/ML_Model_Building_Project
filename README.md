# Predicting Solubility of Compounds using Molecular Descriptors

## Introduction
This project aims to build predictive models for estimating the solubility of various compounds based on their molecular descriptors. The dataset includes key features such as the logarithm of the partition coefficient between n-octanol and water (MolLogP), molecular weight (MolWt), number of rotatable bonds (NumRotatableBonds), and the proportion of aromatic atoms (AromaticProportion). The target variable is the logarithm of the aqueous solubility (logS).

## Data Description
The dataset consists of the following columns:
- **MolLogP**: Logarithm of the partition coefficient between n-octanol and water.
- **MolWt**: Molecular weight of the compound.
- **NumRotatableBonds**: Number of rotatable bonds in the molecule.
- **AromaticProportion**: Proportion of aromatic atoms in the molecule.
- **logS**: Logarithm of the aqueous solubility.

## Objectives
The main objectives of this project are:
1. To preprocess the data for model building.
2. To build and evaluate two predictive models: Linear Regression and Random Forest Regressor.
3. To compare the performance of these models and discuss their benefits in predicting solubility.

## Methodology

### 1. Reading the Data
The dataset is read into a pandas DataFrame for further processing.
```python
## Benefits and Applications
Predictive models for solubility can significantly accelerate the process of drug discovery and
development by providing quick and accurate estimations of compound solubility. This can help in
the selection of viable drug candidates and optimization of formulations.

## Conclusion
This project demonstrates how molecular descriptors can be used to build effective predictive models
for solubility. By comparing Linear Regression and Random Forest Regressor, we can select the best
model for predicting the solubility of new compounds.
