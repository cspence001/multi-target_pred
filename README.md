# multi-target_pred
Utilizing a dataset of 10,000 mobile apps hosted in the GooglePlayStore, plot models identify variables determinant of application success and evaluate the relative feature importance in multiple-target regression models to optimize their prediction accuracy of application rating on a decimalized 1-5 scale.

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/multi_pred.ipynb">main analysis, model prediction</a>
<ul>
<li>Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Accuracy, and Prediction of Random Forest Regressor (RFR), Gradient Boost Regressor (GBR), Decision Tree Regressor (DTR), AdaBoost Regressor (ABR) base models </li><br>
<li>SHAP Evaluation of RFR, GBR models tuned using GridSearchCV</li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/tier_segmentation_correlation.ipynb">feature correlation</a>
<ul>
  <li>Evaluating Correlation of all Categorical Features</li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/base_linear_models.ipynb">base linear models</a>
<ul>
  <li>Linear Regression Analysis of Size, Reviews, Installs on Rating for each App Category</li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/cluster_linear_models.ipynb">tier segmented linear models</a>
<ul>
  <li>Linear Regression Analysis of Tier Segmented Size, Reviews, Installs, Type, Content Rating on Rating </li>
</ul>

<a href="https://github.com/cspence001/multiclass_pred/blob/main/app_pred/weight_variable_encoding.ipynb">weight encoded categorical feature evaluation, pairwise plots</a>
<ul>
  <li>Categorical weight-encoded Feature Evaluation using SHAP, pairwise plots </li>
</ul>



<h5>jupyter notebooks running python, pandas, numpy, matplotlib, sk.learn </h5>
