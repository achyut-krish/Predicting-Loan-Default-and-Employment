# Predicting Loan Default and Employment

<b>Predict whether someone will default on their loan as well as if they are employed.</b>

The original csv dataset can be found at: https://www.kaggle.com/kmldas/loan-default-prediction.

This prediction model uses the <b>K-Nearest Neighbors (KNN)</b> method to classify a new test-row as employed/unemployed and default/pay-off. The entire dataset from the link above contains 10,000 rows of data... 9,000 are used for training and 1,000 are used for testing. 

<b>The greatest accuracy, upwards of 70%, is achieved when using k=7.</b>

Please note that the ratios of emp : ue and default : pay-off are not 1 : 1. Therefore, the prediction accounts for this by undervaluing the majority class in the voting process. For instance, if the number of employed people is twice that of unemployed people in the dataset, the employed "vote" will carry 0.5 weight. 

The notebook in this repository walks the reader through the process of understanding the data, cleaning the data, describing the data, and finally predicting with the data. 
