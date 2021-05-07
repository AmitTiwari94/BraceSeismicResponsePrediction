# BraceSeismicResponsePrediction

This project's objective is to predict the nonlinear seismic response of structural braces using Machine Learning.

Numerical modeling of different structural materials that have highly nonlinear behaviors has always been a challenging problem in engineering disciplines. Experimental data is commonly used to characterize this behavior. This study aims to improve the modeling capabilities by using state of the art Machine Learning techniques, and attempts to answer several scientific questions: (i) Which ML algorithm is capable and is more efficient to learn such a complex and nonlinear problem? (ii) Is it possible to artificially reproduce structural brace seismic behavior that can represent real physics? (iii) How can our findings be extended to the different engineering problems that are driven by similar nonlinear dynamics? To answer these questions, the presented methods are validated by using experimental brace data. In this work, I have implemeneted a Python notebook that performs Data Preprocessing, Data Normalization, Feature Selection, Data Modeling and Evaluation on the experimental brace data.

Enlisted below are the techniques used in this project for modeling the data.

Data Collection: Extracted papers from previous research carried out in this area from 1976-2019.
Data Preprocessing: Data Cleaning, Imputing missing values, Data Normalization using min-max and z-score.
Data Visualization: Heatmap
Feature Selection: Boruta, Recursive Feature Elimination, Feature importance using F-score, SHAP
Data Modeling: Linear Regression, Decision Tree, Support Vector Machines, Bagging Regression, Gradient Boosting Regression.
Data Evaluation: Pearson Correlation, RMSE, MAE.
