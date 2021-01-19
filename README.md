# 66DaysOfData
66DaysOfData Challenge

This is a very simple challenge. There are only two requirements:

1. Learn data science for a minimum of 5 minutes per day for 66 days straight (consistency)
2. Share what you will be working on each day on the platform of your choice using #66DaysOfData (accountability)


#Day 1

  Thesedays, I have studied to understand several machine learning algorithms.
  The algorithm I reviewed today is Decision Tree which is intuitive and understandable.
  ​
  ★Pros and Cons
  ★Parameter of Decision Tree
  ★Visualization by Graphviz(Iris data)
  ★Overfitting
  ★GridSearchCV
  ★Practice(Human Activity Recognition from UCI Machine Learning Repository)

#Day 2

  Yesterday, I experienced the simplest classification algorithm called Decision Tree.
  Likewise Decision Tree, Ensemble Learning is one of the famous algorithm of classification and it shows the outstanding performance in structured data classification. Moreover, It is a technique to derive more accurate final predictions by generating multiple classifiers and combining their predictions.
  As far as I see the Ensemble is sort of collective intelligence, and it leads the Ensemble to diverse utilization.
  ​
  ★ Ensemble Learning - Voting, Bagging, Boosting
  ★ Voting - Hard Voting, Soft Voting
  ★ Bagging(Boostrap Aggregating) - Random Forest
  ★ GridSearchCV
  ★ Boosting - AdaBoost(Adaptive boosting)
  ★ Boosting - GBM(Gradient Boosting Machine) - GradientBoost
​
  ★Datasets I used
  1. breaset cancer prediction
  2. Human Activity Recognition

#Day 3

  XGBoost generally exhibits better predictive performance than other machine learning in classification.
  Although it's based on GBM, in the spotlight for solving problems such as slow performance time and lack of overfitting regulations, which are disadvantages of GBM.

  The strongest strength of LightGBM is only taking less time than XGBoost is.
  Furthermore the predictive performance of XGBoost and LightGBM is not much different.
  The only drawback is that overfitting is easy to occur when it applied to small datasets.

  ★ Boosting - XGBoost(eXtra Gradient Boost)
  (Python wrapper XGBoost,  sklearn wrapper XGBoost)
  ★ Boosting - LightGBM 
  (Python wrapper LightGBM,  sklearn wrapper LightGBM)

  ★Dataset I used
  breaset cancer prediction

#Day 4

  ★ I played with the 'Santander Customer Satisfaction Data' from the Kaggle.
  To solve the problem, I used XGBoost and LightGMB algorithms. They represented only a slight difference. However, LightGBM was much faster.
  ​
  ★Dataset I used​
  'Santander Customer Satisfaction Data'
  
#Day 5

  I analyzed the 'Credit Card Detection Data' from the Kaggle to be intimate the algorithms that I studied so far.
  ​
  ★ UnderSampling, OverSampling
  ★ boost_from_average - parameter of LightGBM
  ★ StandardScale by StandardScaler from sklearn
  ★ LogScale by numpy
  ★ Removing outliers by IQR
  ★ SMOTE (oversampling)
  ​
  ★Dataset I used
  'Credit Card Detection Data'
  ​
  ★ Algorithms I used
  LogisticRegression, LightGBM
 
#Day 6

  ★ Stacking Ensemble has something in common with Bagging and Boosting in that it combines several individual algorithms to produce predictive results.
  ★ Basic Stacking model
  
#Day 7

  ★ Stacking Ensemble based on CV set
  ★ CV set-based stacking model uses the predicted result datasets based on cross-validation when creating datasets for the final meta-model to improve overfitting.
  ​
  Step 1 - For each model, you generate data for training/testing for the meta-model based on the resulting values from which the original training/test data is predicted.
  ​
  Step 2 - Combine all the training data generated by each individual models in the form of stacking and it's going to be a final training datasets for the meta-model.
  Likewise, Combine all the test data generated by each individual models in the form of stacking and it's going to be a final test datasets for the meta-model.
  The meta-model is learned based on the final generated training datasets and the label data of the original training data.
  Finally, it predicts the final generated test datasets and evaluates it based on label data from the original test data.
  
#Day 8

  ★ Read about Battery thermal management system.
  ★ Reviewed the Decision Tree that I studied last week.
  ★ Searched past Kaggle competitions to get familiar with classification.
  ★ Started the 'Santander Product Recommendation'.
  
#Day 9

  ★ EDA with the 'Santander Product Recommendation' which I started yesterday.
  I read datasets, drew basic statistics. Furthermore, I also tried visualizing a single variable with bar graph.
  But, its not easy to predict 7 products. I should search datasets more delicately.
  
  ★ Reviewed the Ensemble Learning that I studied last week.
  ★ Made Voting Classifier out of Logistic Regression and KNN.
  
  ​
  ★Dataset I used
  Wisconsin Breast Cancer Datasets
  Santander Product Recommendation
