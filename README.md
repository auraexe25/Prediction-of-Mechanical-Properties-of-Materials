# ML POWERED UTS Prediction of steel

## Overview

This project uses machine learning to predict the ultimate tensile strength (UTS) of steel from metallurgy-inspired synthetic data. The notebook trains and compares several regression models, then visualizes the final predicted-versus-actual UTS results.

## What’s Included

- A notebook workflow for generating, cleaning, and modeling the steel dataset.
- Feature scaling, train/validation/test splitting, and model comparison.
- A final UTS prediction model with evaluation metrics and parity plotting.
- The notebook runs fully offline and does not require downloading external files.

## Dataset

The dataset is generated inside the notebook using metallurgy-inspired rules for alloy composition, heat treatment, cooling rate, and grain size. In this version of the project, the prediction target is UTS.

## Notebook Flow

1. Generate the synthetic steel dataset.
2. Clean and prepare the features.
3. Scale the input features and the UTS target.
4. Train and compare regression models.
5. Evaluate the final model and plot predicted UTS against actual UTS.

## Run It

Open `ML_Powered_UTS_Prediction_of_Steel.ipynb` and run the cells top to bottom. If you are using a fresh environment, make sure the notebook has access to `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, and `joblib`.

## Project Files

- `ML_Powered_UTS_Prediction_of_Steel.ipynb` - main notebook for the UTS workflow.
- `steel_strength.csv` - uploaded reference dataset kept in the repository.

## Results

The final section of the notebook shows the predicted-vs-actual UTS scatter plot and the regression metrics for the selected model.

## Next Steps

- Try additional regression models or feature engineering.
- Tune hyperparameters for the final estimator.
- Extend the notebook to support other steel property targets if needed.

@Veena Sahu
