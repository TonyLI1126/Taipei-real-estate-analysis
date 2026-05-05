# Taipei-real-estate-analysis
Taipei Real Estate Price Prediction: Advanced Statistical Modeling (Log-Regression, PCA, HCA) using SAS &amp; R.

#  Taipei Real Estate Market Analysis

##  Project Overview
This project focuses on predicting house prices per unit area in the **Xindian District of New Taipei City**. By leveraging a dataset of 414 historical transactions, the study aims to identify the most significant environmental and temporal predictors of real estate value using advanced statistical modeling.

##  Methodology
The analysis followed a rigorous statistical pipeline:
1. **Exploratory Data Analysis (EDA)**: Conducted in **SAS** to assess data distribution, identify outliers, and check for multicollinearity.
2. **Variable Selection**: Compared **Backward, Forward, and Stepwise** selection methods.
3. **Model Optimization**: Implemented a **Log-transformation** of the target variable to address heteroscedasticity and non-normality.
4. **Multivariate Analysis**: Performed in **R** using **Principal Component Analysis (PCA)** and **Hierarchical Clustering (HCA)** to segment the market.
5. **Non-linear Insights**: Used **Generalized Additive Models (GAM)** to visualize spatial price trends.

##  Key Technical Features
- **Software**: SAS (Statistical Analysis System), R
- **Key Libraries (R)**: `mgcv`, `ggplot2`, `FactoMineR`
- **Modeling Techniques**: Multiple Linear Regression, Log-Linear Models, PCA, HCA

##  Key Findings
- **Predictive Accuracy**: The final optimized model achieved an **Adjusted $R^2$ of 67.63%**.
- **MRT Proximity**: Distance to the nearest MRT station is a critical negative predictor of price.
- **Commercial Impact**: Every additional convenience store in the vicinity significantly increases the property value.
- **Clustering**: Market segmentation revealed distinct price clusters based on longitude and proximity to high-density commercial areas.

## 📁 Repository Structure
- `/scripts`: SAS programs and R Markdown scripts.
- `/report`: Full technical report in PDF format (`TAIPEI_projet.pdf`).
- `/data`: Dataset description and metadata.
