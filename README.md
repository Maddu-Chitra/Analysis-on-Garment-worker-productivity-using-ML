Project Overview:- This is our Regression Project where we analyzed the Garments Worker Productivity dataset to identify factors that affect worker performance in a garment factory.
                  We applied multiple ML models to predict productivity and compared their effectiveness.

Objective:- To predict the  actual productivity of workers.

Dataset:-
Source: Garments Worker Productivity Dataset (2015, 1197 observations)
Features include: department, team size, work-in-progress (WIP), overtime, idle time, incentives, day, quarter, etc.

Technical Approach:-
Data Cleaning: Missing values imputed, categorical features encoded.
Exploratory Data Analysis (EDA): Boxplots, heatmaps, time-series plots.
Modeling: Linear Regression, KNN, Decision Tree, Random Forest, Bagging, Boosting, XGBoost, Neural Networks.
Evaluation Metrics: MAE, MAPE, accuracy scores.

Results:-
Top Factors: Department, team size, and WIP were the strongest drivers of productivity.
Least Impact: Incentives and style changes.
Best Model: XGBoost achieved the best performance (MAE = 0.0803, MAPE = 0.1501).
Productivity peaks in Quarter 1 and gradually declines later.
