# MachineLearning-ExoPlanets
Tuning the hyper-parameters of a SVM classifier model

### Assumptions and Findings

Unfortunately this dataset does not include the full dataset.  It only contains the results that were initially proposed as exoplanets and then was mostly checked for confirmed positive and negative canditates with a portion of the data still in the candidate but unconfirmed range.  

It may have  sense to remove the candidate data from the dataset then do the classification training on the confirmed and false positive data.  We could then use the model to make predictions on the candidate data.

Nevertheless, I continued using the whole dataset as is.

I tried 3 Support Vector Classification methods with various hyper-parameters and one K-nearest neighbor classifier to check which model gave the best results.

After tuning the hyperparameters the best model results came out of a Linear SVC model with C = 1000.  The resulting model scores an .89 with both the training and the testing data.
