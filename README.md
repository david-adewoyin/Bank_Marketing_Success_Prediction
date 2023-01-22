# Bank Marketing Campaigns Success Prediction
Data Science project to  predict the success of a bank telemarketing campaigns, the aim is to predict if the client will subscribe to a term deposit.

- performed exploratory data analysis to gather insights on the datasets.
- provided recommendations to improve the success of future campaigns.
- used oversampling and undersampling techniques to increase the size of the minority class for model building.
- optimized Logistic Regression, Random Forest and LightGBM Classifiers using GridsearchCV to reach the best model.
- created external [tableau dashboard](https://public.tableau.com/views/BankTelelemarketingSuccessAnalysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) for visualization.

## Data Cleaning and EDA

- converted target column into numeric
- reduced the feature space of the education feature by recategorization
- plotted various univariate and bivariate plots to gather insights on success
- performed Hypothesis testing to test the significance of certain months high performance

![image](https://user-images.githubusercontent.com/57121852/213601225-53d33388-c831-4462-907d-bd7d0412ddd6.png)  
### Tableau Dashboard
![Dashboard 1](https://user-images.githubusercontent.com/57121852/213937143-2f2a2748-65d3-4525-9a0e-ad629e869957.png)


## Model Performance
We evaluated our models using a combination of recall and the F1 score. Though the logistic regression model has the highest recall, the poor f1 score made us go with the LightGBM model as our model of choice.

|               	| Precision 	| Recall	| F1 score 	|
|---------------	|--------	|-----------	|----------	|
| Logistic      	| 0.19  	| 0.80     	| 0.307 	|
| Random Forest 	| 0.28   	| 0.73     	| 0.407   	|
| LightGBM      	|  0.28      	|    0.75       	|   0.411     	|

