**EVALUATING THE PERFORMANCE OF 3 REGRESSION MODELS ON BIKE SHARE PREDICTION FOR SEOUL, SOUTH KOREA.**

**Methodology Summary**

Clean the data: 
    
    replace categorical data points to numerical data-points 
    
    categorizing date to month, e.g. 1/12/17 will be 12, and so on
    
    data shuffling of rows  to improve geenralizability and reduce bias 

Data split: Train, test, validation (ensure random state)

Create models: 
    
    Decision Tree regressor
    
    Polynomial Regressor
    
    Dummy model

Fit models to data, use model to predict, get each model's performance 
    
    Regression performance metrics: MSE, R squared, RMSE, MAE, Accuracy of prediction (compare all models)

Hyperparameter tuning to see which parameter values maximize performance for each model 
    
    DecisionTree : max depth
    
    Polynomial: Degree order 

Cross Validation (for model generalization) to make sure our performance is the same across splits of the data 


**COMPARING ALL MODELS AT THEIR IDEAL PARAMETER VALUES**
![image](https://user-images.githubusercontent.com/98823082/182159701-a0204e73-01f4-431c-9bab-08ac4976ccbc.png)
