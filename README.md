# Home-Credit-Default-Risk
Link : https://www.kaggle.com/c/home-credit-default-risk

#Home Credit Default Risk using LGBM


**Salient Project Features:**
> The Datasets were joined together to form an Accumulated Dataset (ADS) for both Train
  and Test to do analysis.

> Exploratory Data Analysis (EDA) was done using both univariate and multivariate
  analysis to understand the relationship and associations among the variables.

**Missing Value treatment**
> This was leveraged to reduce the dimensionality of the dataset by dropping the
  variables which had missing values greater than 50% as any imputing strategy
  used for these features would have been misleading.

> For remaining numerical features, the missing values were imputed with Median
  values as the variables were skewed and preference was given to Median value
  over Mean.

> For remaining categorical features, imputed with a constant value to identify the
  missing values. These could have been imputed with mode value but as the
  Target variable in dataset is highly imbalanced, this was avoided.

−> Anomaly and Outlier detection and treatment was done for features with counter
   intuitive values and/or having values extremely small or high.

−> Feature Engineering was applied to derive new variables based on learnings industry
  research and correlation and multivariate analysis.

−> LightGBM algorithm was used to for predicting the probabilities for defaulting after
   appropriately treating the variables, imputing and scaling the most important features.
