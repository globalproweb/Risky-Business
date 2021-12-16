# Risky Business: Analysis Summary 
# Ensemble Learning

## Background
 In this Ensemble Learners analysis I  compare two ensemble algorithms to determine which algorithm results in the best performance. I  train a Balanced Random Forest Classifier and an Easy Ensemble classifier . For each algorithm, I  complete the folliowing steps:

1. Train the model using the training data.
2. Calculate the balanced accuracy score from sklearn.metrics.
3. Display the confusion matrix from sklearn.metrics.
4. Generate a classication report using the imbalanced_classification_report from imbalanced-learn.

   ## Ananlysis 

In my analysis, Easy Ensemble Classifier accuracy score is better than Balanced Random Forest Classifier score: 
Balanced Random Forest Classifier = 0.8132747944289335
Easy Ensemble Classifier = 0.9329562348163458
Easy Ensemble Classifier has the best  recall score and the best the best geometric mean score. 

   ## The Top three features are 

 '% of Total Principal received to date.  "total_rec_prncp"
 '% of Total Interest  received to date.   "total_rec_int',
 '% of Last Payment amount                  :last_pymnt_amnt"

  # Credit Risk Resampling Techniques

In this session I look at 3 models using the quarterly data from LendingClub and Calculate the following balanced accuracy scores:  Naive overampling balanced accuracy model,  SMOTE balanced accuracy model  and SMOTEEN balanced accuracy model. In my analysis, all 3 models yields the same  balanced accuracy score and Gemetric score:
Original data set's balanced accuracy score = 0.9543211898288821
-------------------------------------------------------------------
Naive overampling balanced accuracy score = 0.9946414201183431 
SMOTE balanced accuracy score = 0.9946414201183431 
SMOTEEN balanced accuracy score = 0.9946414201183431 


