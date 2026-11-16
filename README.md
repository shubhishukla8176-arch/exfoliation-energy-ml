# Machine Learning Prediction of Exfoliation Energy in 3D Bulk Crystals

### MASC 520 Project

## About the Project

Exfoliation energy is an important property when studying layered materials because it gives an idea of how much energy is required to separate layers from a bulk crystal.

In this project, I aim to use machine learning to study how the chemical composition and crystal structure of bulk materials are related to their exfoliation energy.

The main focus is to understand whether information about the 3D crystal structure can improve predictions beyond what can be achieved using chemical composition alone.

## What I Plan to Investigate

The project will compare three different ways of representing materials:

1. **Composition-based features:** Information about the elements present in a material and their properties.
2. **Structure-based features:** Information about the crystal structure, such as lattice geometry, volume and atomic arrangements.
3. **Combined features:** A combination of chemical composition and structural information.

By comparing these approaches, I hope to understand the contribution of each type of information to the prediction of exfoliation energy.

## Dataset

The data will be obtained from **JARVIS-DFT**, a database maintained by the National Institute of Standards and Technology (NIST).

The dataset will be inspected and processed to identify suitable materials with available exfoliation energy values and the corresponding crystal structures.

## Approach

The work will follow these main steps:

1. Collect and inspect the relevant data from JARVIS-DFT.
2. Clean and prepare the dataset.
3. Generate chemical composition descriptors.
4. Extract relevant crystal structure descriptors.
5. Develop and compare machine learning models.
6. Evaluate model performance using appropriate metrics.
7. Analyse the results to understand the importance of composition and structural features.

## Tools and Libraries

The project will mainly use Python and the following libraries:

- Pandas and NumPy for data handling.
- Matminer and Pymatgen for material descriptors.
- Scikit-learn for machine learning.
- XGBoost, if suitable for the dataset.
- Matplotlib for visualisation.
- SHAP, where appropriate, for model interpretation.

## Expected Outcome

The goal is to compare the predictive performance of composition-based, structure-based and combined models. This comparison should help clarify how much additional predictive information crystal structure provides when estimating exfoliation energy.

