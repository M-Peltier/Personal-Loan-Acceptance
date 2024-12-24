# Personal-Loan-Acceptance
A campaing that the bank ran last year for liability customers customers showed a healthy conversion rate of over %9 success. 
This has encouraged the retail marketing department to devise smarter campaigns with better target marketing.
The goal is to use k-NN to predict whether a new customer will accept a loan offer. This will serve as a 
basis for a new campaign.
The file universalBank.csv contains data on 5000 customers. The data include customer demographic information,
the customers relationship with the bank, and the customer response to the last personal loan campaign.
Among these 5000 customers, only 480(=%9.6) accepted the personal loan that was offered to them in the 
earlier campaign. Data was partitioned into training and validation sets
1. Consideration of the following customer was applied  'Age': 40, 'Experience' : 10, 'Income': 84, 'Family' : 2, 'CCAvg': 2, 'Education_1': 0, 'Education_2': 1,'Education_3': 0,'Mortgage': 0, 'Securities Account': 0, 'CD Account': 0, 'Online': 1, 'Credit Card': 1
  Performed a k-NN classification with all predictors except ID and ZIP code using k = 1.
  transformed categorical predictors with more than two categories into dummy variables first.
  Specified the success class as 1 (loan acceptance), and use the default cutoff value of 0.5.
  HOW WAS THIS CUSTOMER CLASSIFIED?
2. The best choice of K that balances between overfitting and ignoring predictor information is shown.
3. Confusion matrix  shown for the validation data that results from using the best k.
4. New customer used to classify the customer using the best k
5. Next repartitioned the data, into training, validation and test sets. Applied the k-NN method with the k chosen from above.
   compared the confusion matrix of the test set with that of the training and validation sets. Commented on the differences and reasons.

