# titanic_survival_prediction
This is the famous kaggle competition problem of predicting the survivors of titanic.

I took the training and test datasets from kaggle. I applied all the classification algorithms but the best result came from gradient boosting classifier with an accuracy of 
around 87% the first time but the last time I checked, it was around 84% on my pc. The submitted prediction had an accuracy of 77% on Kaggle however.

In the data pre-processing step, I removed the name and cabin columns. I made a new column initially called family which was a combination of SibSp and Parch columns. Then I made a new column called family size which had 3 categories namely small, medium and large. I made this column using the family column and then deleted the family column. I trained the model on this dataset but the accuracy was coming around 74%. So, I performed some more EDA and decided to remove the fare column and the accuracy improved drastically.

Credits: Campusx
