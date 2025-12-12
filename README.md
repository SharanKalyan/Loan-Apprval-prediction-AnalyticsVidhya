# Loan-Apprval-prediction-AnalyticsVidhya

This notebook contains the code files for the competition hosted by #AnalyticsVidhya

The Objective is to classify wheather a customer can be approved for loan based on several parameters such as their education, No. of dependants,
previous loan status etc. 

I have Imported the data, clened and analysed the necessary data, imputed the misisng values, Visualised and have plotted all the necessary graphs to understand the data.

For predicting wheather a customer can be approved for a loan, I have used 8 Different Models, Used the ROC curve and F1 score as a metric (as the data was Imballanced).
I have taken the Ensemble of those 8 models to predict the test dataset. I was able to achieve an Roc score of ~ 0.8 for the test data. 

The major goal here is to make sure we reduce the Type 2 errors which is to avoid approving loans to the bad customers and improve the Precision of Class 1 (which is to make sure the model approves the loan for good customers) 


![image](https://user-images.githubusercontent.com/20862520/153546189-199eb395-9d64-481a-bb56-86c7838288f8.png)


![image](https://user-images.githubusercontent.com/20862520/153546808-218d69ce-4d6c-4b1f-9d3f-5ef22f036e82.png)

For more indepth understanding : https://www.analyticsvidhya.com/blog/2022/02/loan-approval-prediction-machine-learning/

