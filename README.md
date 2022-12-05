# Credit_Risk_Analysis

# Overview of the analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques to train and evaluate models with unbalanced classes. imbalanced-learn and scikit-learn libraries are used to build and evaluate models using resampling. Some other libraries and algorithm used to build and evaluate these models are:
  
  
  1.imbalanced-learn 
  2.scikit-learn
  3.RandomOverSampler
  4.SMOTE algorithm
  5.ClusterCentroids
  6.BalancedRandomForestClassifier
  7.EasyEnsembleClassifier(bias reduction model)
  
  # Purpose:
  
  1.Explain how a machine learning algorith is used in data analytics.
  2.Create training and test groups from a given data set.
  3.Implementing the logistic regression,random forest and support vector machine algorithms.
  4.Interpret the results of the logistic regression, random forest and support vector machine algorithms.
  5.Compare the advantages and disadvantages of each supervised learning algorithm.
  6.Determine which supervised learning algorithm is best used for a given data set ar scenario.
  7.Use ensemble and resampling techniques to improve model performance.
  
  
  # Resukts:
  
  The results fro the 6 machine learning models including their respective balanced accuracy, precision and recall scores are as follows:
  
  # Random Oversampling
  ![Screen Shot 2022-12-05 at 4 18 56 PM](https://user-images.githubusercontent.com/55648656/205754947-9aa21323-fe38-4645-a860-5c94e8fd79af.png)
1. Balanced Accuracy: 0.6533977140416822
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .65/.67

# SMOTE Oversampling
![Screen Shot 2022-12-05 at 4 25 19 PM](https://user-images.githubusercontent.com/55648656/205755923-e2a030ce-a16c-466b-a888-ba172865d631.png)
1.Balanced Accuracy: 0.6512291961274883
2.Presicion : The precision is low fro High-risk loans and high fro Low-risk loans.
Recall: High/Low risk = .65/.66

# Undersampling

![Screen Shot 2022-12-05 at 4 41 37 PM](https://user-images.githubusercontent.com/55648656/205758485-40815202-9b42-4558-ab85-4f2abc691365.png)
1.Balanced Accuracy: 0.6512291961274883
2.Precison: The precision is low for High-risk loans and is high fro Low-risk loans.
3.Recall: High/Low risk = .65/.40

# Combination Under-Over Sampling
![Screen Shot 2022-12-05 at 4 44 27 PM](https://user-images.githubusercontent.com/55648656/205758903-f5536870-e934-4e04-9a94-62a897dbd783.png)
1. Balaned Accuracy: 0.5109523751969091
2. Precision: The precision is low for High-risk loans and is high fro Low-risk loans.
3. Recall: high/Low risk = .69/.60

# Balaned Random Forest Classifier

![Screen Shot 2022-12-05 at 4 52 37 PM](https://user-images.githubusercontent.com/55648656/205760195-846fc9bc-eee2-4251-8d06-1885d8452bb0.png)
1. Balanced Accuracy: 0.7844011748069183
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk= 0.68/0.89


# EasyEnsemble Classifier

![Screen Shot 2022-12-05 at 4 56 30 PM](https://user-images.githubusercontent.com/55648656/205760868-bc4e1558-cd31-4cfe-8ca4-a3b0cb2dd4ab.png)

1. Balanced Accuracy: 0.7877672625306695
2. Precision: The Precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk= 0.67/0.91

Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and1 is closest to 1 is the best machine learning model. For the credit card data set, the SMOTE Oversampling is the best model to choose with Precision and recall score closer to 1 to choose for further credit card analysis.
