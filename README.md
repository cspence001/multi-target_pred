# multi-target_pred
Utilizing a dataset of 10,000 mobile apps hosted in the GooglePlayStore, plot models identify variables determinant of application success and evaluate the relative feature importance in multiple-target regression models to optimize their prediction accuracy of application rating on a decimalized 1-5 scale.

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/multi_pred.ipynb">main analysis, model prediction</a>
<ul>
<li>Scatterplot Distributions of Rating v Reviews, Size, Installs by Type</li>
<li>Prediction Analysis of App Rating using Random Forest Regressor (RFR), Gradient Boost Regressor (GBR), Decision Tree Regressor (DTR), AdaBoost Regressor (ABR) base models.</li>
  <li> > Evaluating Average Error, Accuracy, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) of models </li>
  <li> > Plotting Model Predictions of Rating vs Actual Rating based on Reviews, Size, Installs </li>
  <li> > Plotting Prediction Accuracy of RFR, GBR base models and DTR, ABR base models to Test Set </li>
<li>Hyperparameter Tuning of RFR, GBR models using GridSearchCV, Feature Importance evaluation of best grid using SHAP Tree Explainer</li>
<li>Stacked Generalization ensemble (RFR, GBR, XGBR, RidgeCV estimation) comparison to RFR, GBR base model accuracy </li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/tier_segmentation_correlation.ipynb">feature correlation</a>
<ul>
  <li>Heatmap Correlation of one-hot encoded Categorical Features</li>
  <li>K-means Cluster Evaluation for binning Reviews, Size </li>
  <li>Standardized Scaling v Normalized Scaling for Reviews, Size, Installs</li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/base_linear_models.ipynb">base linear models</a>
<ul>
  <li>Linear Regression Analysis of Reviews, Size, Installs on Rating for each App Category</li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/cluster_linear_models.ipynb">tier segmented linear models</a>
<ul>
  <li>Linear Regression Analysis of Tier Segmented Reviews, Size, Installs, Type, Content Rating on Rating </li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/weight_variable_encoding.ipynb">weight encoded categorical feature evaluation, pairwise plots</a>
<ul>
  <li>Weight of Evidence (WoE) encoding, Information Value (IV) of Categorical variables (Categories, Type, Content Rating) </li>
  <li>RFR Model Evaluation of Rating Prediction based on Reviews, Size,	Installs, WoE encoded Categorical variables</li>
  <li>Evaluating Feature, Permutation Importance determined by RFR Model using SHAP TreeExplainer</li>
  <li>Pairwise Plots for Categorical Feature Evaluation using WoE-encoded Categorical variables</li>
  <li>Target Enclosed Feature Modeling based on Example Rating</li>
</ul>



<h5>jupyter notebooks running python, pandas, numpy, matplotlib, sk.learn </h5>
