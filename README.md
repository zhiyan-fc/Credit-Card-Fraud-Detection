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


## Outline
<b>1. Understanding data</b>    
1.1 Gather Sense of Data      
    a) loading the data    
    b) EDA    
     
<b>2. Preprocessing data and modeling</b>  
2.1 Scalling    
2.2 Splitting data    
2.3 Naive Classifier    
2.4 Undersampling    
    a) Logistic Regression    
    b) Random Forest    
    c) Neural Network      
2.5 Oversampling     
    a) Logistic Regression     
    b) Random Forest     
    c) Neural Network      

<b>3. Prediction Evaluation</b>  
3.1 Comaprison models using Undersampling     
3.2 Comparison models using Oversampling     

<b>4. Conclusion</b>  
