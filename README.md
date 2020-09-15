# Credit-Card-Fraud-Detection

In this notebook, we used various predictive models to detect fraud transactions.
We started with an exploratory data analysis, and we found our data was a very imbalanced dataset with 0.17% of fraud transactions.     

We created a naive prediction model and proved that using an accuracy metric was misleading. F1 score, AUC, precision, and recall should be the proper metrics for evaluating the model performance in this case.          
            
Two techniques were used in balanced the datasets:
1) undersampling and 
2) upsampling     

Three predicitve models were built using the balanced dataset.
1) Logistic Regression method
2) Random Forest Regression method
3) Neural Network

At the end, we used the test dataset from the original data to compare the performance. Instead of using accuracy, F1 score, confusion matrix, AUC, precision and recall are used to compare the performance of the model prediction.
