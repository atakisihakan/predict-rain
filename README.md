# PREDICT RAIN

Predict next-day rain in Australia by training on [Kaggle data](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package) comprising 10 years of daily weather observations from many locations across Australia. 

The following models are used:
- **Logistic Regression**
- **XGBoost Classifier**
- **Random Forest Classifier**
- **Artificial Neural Network (ANN)**

Model performance is evaluated using various metrics: 
- Accuracy
- F1-score
- Confusion matrix
- ROC-AUC curve
- Precision-recall curve

For model interpretability, the following tools are utilized:
- Permutation feature importance
- SHAP values (SHapley Additive exPlanations)

\
**SELECT FIGURES**
<img src="Figures/missing_values_overview.jpg">
<img src="Figures/correlation_matrix.jpg">
<img src="Figures/predictive_power_score.jpg">
<img src="Figures/rain_tomorrow_distribution.jpg">
<img src="Figures/highly_correlated_features.jpg">
<img src="Figures/ROC_AUC_curve_xgb.jpg">
<img src="Figures/precision_recall_curve_xgb.jpg">
<img src="Figures/feature_importance_beeswarm_xgb.jpg">
<img src="Figures/feature_importance_permutation_xgb.jpg">
<img src="Figures/feature_importance_shap_xgb.jpg">
<img src="Figures/ann_training_history.jpg">