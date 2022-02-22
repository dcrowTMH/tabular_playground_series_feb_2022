# Machine learning skills practice
## Kaggle Competition - Tabular Playground Series Feb 2022
Data: https://www.kaggle.com/c/tabular-playground-series-feb-2022/data

Purpose for repository:

Aimed to practice the workflow and skill for machine learning that I have learnt.

Objective for the competition:

Train the model with incompleted DNA sequences data & predict the target bacteria in test set

Current Progress: 19/02/2022 Submitted k-fold & depth adjustment work better, PCA is not working at this moment

Next milestone: obtain experience from others notebook & try with other technique and model

#### Result

17/02/2022 First trial (XGBoost): Score = 0.90366, Rank = 701

18/02/2022 Second trial (XGBoost) : Score = 0.91611, Rank = 720 (Accuracy was increased)

19/02/2022 Third trial (XGBoost with higher lambda & alpha): Score = 0.90005, Rank = NA

19/02/2022 Fourth trial (XGBoost with 100 lambda & alpha): Score = 0.82967, Rank = NA

19/02/2022 Fifth trial (XGBoost with no gamma + Second trial regularization): Score = 0.91781, Rank = 724

21/02/2022 Sixth trial (XGBoost with 10-fold & depth adjusted): Score = 0.94448, Rank = 679

22/02/2022 Seventh trial (XGBoost with 5-fold & PCA): Score = 0.86250, Rank = NA

22/02/2022 Eighth trial (XGBoost with 5-fold & features amount PCA): Score : 0.87796, Rank = NA

https://www.kaggle.com/dcrowd/xgboost-model-first-comp-keep-improving
