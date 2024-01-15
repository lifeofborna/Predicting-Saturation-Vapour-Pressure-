# Saturation Vapour Pressure Prediction using Random Forest Regressor

In this notebook, we will build a regression-based machine-learning model for predicting saturation vapour pressure. 

This notebook, originally set up in Google Colab, highlights linear regression and random forest models made by Borna. Detailed elements such as hyperparameter tuning and key parameter identification are omitted here but detailed in the accompanying report, which also explores other developed models by others in my team.

The final evaluation reveals that Borna's hyperparameter-tuned random forest model achieved a top 20% ranking on Kaggle. This was accomplished by prioritizing interpretability, with a minimal 1-3% gap in accuracy compared to the first-place entry, which employed a complex stack of models including neural networks, random forest, XGBoost, etc., to gain a slight edge in accuracy but less interpretability.

For a more detailed analysis check the accompanying report. 

## Problem Significance

Understanding saturation vapour pressure and its prediction is crucial for various reasons:

- **Aerosol Formation:** Approximately half of the aerosol particles in the atmosphere are formed through the New Particle Formation (NPF) process, where vapours condense into atmospheric aerosol particles. NPF plays a significant role in atmospheric dynamics and composition.

- **Health and Climate Impact:** NPF has direct implications for both human health and global climate change. Aerosols, resulting from NPF, are closely associated with air pollution, which is a severe health issue affecting nearly the entire global population, as stated by the World Health Organization (WHO).

- **Climate Cooling:** According to the Intergovernmental Panel on Climate Change (IPCC) report (Section 2.1.1), human activities, primarily the emission of aerosols, contribute to global cooling in the range of 0.0°C to 0.8°C. This cooling effect is crucial for balancing the warming caused by greenhouse gases. Accurate modeling of NPF is essential to reduce uncertainties in climate predictions.

- **Computational Challenges:** Predicting molecular properties, like saturation vapour pressure, is computationally intensive and often requires resource-intensive quantum chemistry simulations on supercomputers. However, the vast number of atmospherically relevant molecules necessitates faster and more efficient methods, such as the regression models explored in this competition.

## Repository Contents

- **Code:** This repository contains the Python code for our random forest regressor implementation and data preprocessing seen in the solution folder.

- **Report:** You can find a comprehensive report detailing our approach, methodology, and results in the root directory.

- **Data:** The 'data' used for this project can be found in the solution part.

- **Resources:** Additional resources and references related to saturation vapour pressure and NPF modeling can be found at https://www.nature.com/articles/s41597-023-02366-x. 

