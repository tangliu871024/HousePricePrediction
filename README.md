# Predict House Price

Data: https://www.kaggle.com/competitions/home-data-for-ml-course

The goal is to predict the sale price of each house based on the given information. 
The considered error in this case is the RMSE between the log of the prediction and the true value. Log is taken in order to deal with the tail of the distribution of the sale price.  


## Keep in mind
- How much correlation there is among the input variables? Depending on the type of models used, the extent of correlation may have different implications.
- Are there any further processing needed for the features, be it normalization, categorization of continuous variables etc.
- How balanced is the output label? And does it have some implications for the evaluation metrics?
- What approaches are used to avoid overfitting?
- If the models selecetd have hyperparameters, how are these hyperparameters tuned?
- What are typical metrics to evaluate the performance of the models, and how to interpret the outcome of these metrics?
- What explainability methods can be used to understand the model? 

  
