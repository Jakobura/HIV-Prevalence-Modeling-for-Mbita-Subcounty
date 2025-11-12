# HIV-Prevalence-Modeling-for-Mbita-Subcounty
Project Background
Mbita Sub-County, Homa Bay County, Kenya, has one of the highest HIV prevalence rates in the country. Public health authorities face challenges due to sparse sub-county data. This project applied machine learning to predict HIV prevalence (%) using socio-demographic, behavioral, health-service, and environmental features, supporting data-driven planning for HIV prevention.

Research Problem
Develop a predictive model for HIV prevalence using features such as population density, education levels, poverty rate, male circumcision rate, condom use, HIV testing coverage, and health facility density. The aim was to identify key determinants of HIV prevalence and provide actionable insights for targeted interventions.


Tools & Technologies

Python: pandas, NumPy, scikit-learn, Matplotlib, Seaborn, joblib


Machine Learning Models: Random Forest regression with hyperparameter tuning


Data Visualization: Scatter plots, correlation matrices, bar charts for feature importance


Methodology

Data Preparation: Generated a synthetic dataset reflecting plausible sub-county feature distributions; handled missing values, normalized features, and split into training/testing sets.


Exploratory Data Analysis: Examined distributions and correlations; identified relationships between features and HIV prevalence.


Model Training & Evaluation: Built and tuned Random Forest model; evaluated using MAE, RMSE, and R² metrics.


Feature Importance Analysis: Identified key predictors of HIV prevalence, including male circumcision, poverty rate, and female education levels.


Key Findings

Higher male circumcision and female education levels correlate with lower HIV prevalence.


Poverty and low health-service coverage are associated with higher prevalence.


Behavioral factors like condom use and HIV testing frequency significantly impact prevalence predictions.


Random Forest model achieved strong predictive performance and highlighted actionable features for targeted interventions.


Recommendations & Impact

Prioritize interventions in areas with high poverty and low male circumcision.


Promote HIV testing and condom-use awareness programs.


Allocate resources efficiently based on model predictions.


Extend the model to incorporate GIS or temporal data for improved precision.


Conclusion
Machine learning effectively predicts HIV prevalence at the sub-county level, enabling data-driven decision-making for public health planning. Insights from this project support targeted HIV prevention strategies in high-risk regions.

