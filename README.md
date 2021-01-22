# 66DaysOfData
66DaysOfData Challenge
----------------------

This is a very simple challenge. There are only two requirements:

1. Learn data science for a minimum of 5 minutes per day for 66 days straight (consistency)
2. Share what you will be working on each day on the platform of your choice using #66DaysOfData (accountability)


__Day 1__

  Thesedays, I have studied to understand several machine learning algorithms.
  The algorithm I reviewed today is Decision Tree which is intuitive and understandable.
  
  ㆍ Pros and Cons  
  ㆍ Parameter of Decision Tree  
  ㆍ Visualization by Graphviz(Iris data)  
  ㆍ Overfitting  
  ㆍ GridSearchCV  
  ㆍ Practice(Human Activity Recognition from UCI Machine Learning Repository)  

__Day 2__

  Yesterday, I experienced the simplest classification algorithm called Decision Tree.  
  Likewise Decision Tree, Ensemble Learning is one of the famous algorithm of classification and it shows the outstanding performance in structured data classification.
  Moreover, It is a technique to derive more accurate final predictions by generating multiple classifiers and combining their predictions.
  As far as I see the Ensemble is sort of collective intelligence, and it leads the Ensemble to diverse utilization.
  
  ㆍ Ensemble Learning - Voting, Bagging, Boosting  
  ㆍ Voting - Hard Voting, Soft Voting  
  ㆍ Bagging(Boostrap Aggregating) - Random Forest  
  ㆍ GridSearchCV  
  ㆍ Boosting - AdaBoost(Adaptive boosting)  
  ㆍ Boosting - GBM(Gradient Boosting Machine) - GradientBoost  
  
  ㆍ Datasets I used  
  1. breaset cancer prediction  
  2. Human Activity Recognition  

__Day 3__

  XGBoost generally exhibits better predictive performance than other machine learning in classification.
  Although it's based on GBM, in the spotlight for solving problems such as slow performance time and lack of overfitting regulations, which are disadvantages of GBM.

  The strongest strength of LightGBM is only taking less time than XGBoost is.
  Furthermore the predictive performance of XGBoost and LightGBM is not much different.
  The only drawback is that overfitting is easy to occur when it applied to small datasets.

  ㆍ Boosting - XGBoost(eXtra Gradient Boost)  
  (Python wrapper XGBoost,  sklearn wrapper XGBoost)  
  ㆍ Boosting - LightGBM   
  (Python wrapper LightGBM,  sklearn wrapper LightGBM)  

  ㆍ Dataset I used  
  breaset cancer prediction  

__Day 4__

  ㆍ I played with the 'Santander Customer Satisfaction Data' from the Kaggle.  
  To solve the problem, I used XGBoost and LightGMB algorithms. They represented only a slight difference. However, LightGBM was much faster.  
  
  ㆍ Dataset I used  
  'Santander Customer Satisfaction Data'  
  
__Day 5__

  I analyzed the 'Credit Card Detection Data' from the Kaggle to be intimate the algorithms that I studied so far.
  
  ㆍ UnderSampling, OverSampling  
  ㆍ boost_from_average - parameter of LightGBM  
  ㆍ StandardScale by StandardScaler from sklearn  
  ㆍ LogScale by numpy  
  ㆍ Removing outliers by IQR  
  ㆍ SMOTE (oversampling)
  
  ㆍ Dataset I used  
  'Credit Card Detection Data'  
  
  ㆍ Algorithms I used  
  LogisticRegression, LightGBM  
 
__Day 6__

  ㆍ Stacking Ensemble has something in common with Bagging and Boosting in that it combines several individual algorithms to produce predictive results.  
  ㆍ Basic Stacking model  
  
__Day 7__

  ㆍ Stacking Ensemble based on CV set  
  ㆍ CV set-based stacking model uses the predicted result datasets based on cross-validation when creating datasets for the final meta-model to improve overfitting.  
  
  Step 1 - For each model, you generate data for training/testing for the meta-model based on the resulting values from which the original training/test data is predicted.
  
  Step 2 - Combine all the training data generated by each individual models in the form of stacking and it's going to be a final training datasets for the meta-model.
  Likewise, Combine all the test data generated by each individual models in the form of stacking and it's going to be a final test datasets for the meta-model.
  The meta-model is learned based on the final generated training datasets and the label data of the original training data.
  Finally, it predicts the final generated test datasets and evaluates it based on label data from the original test data.
  
__Day 8__

  ㆍ Read about Battery thermal management system.  
  ㆍ Reviewed the Decision Tree that I studied last week.  
  ㆍ Searched past Kaggle competitions to get familiar with classification.  
  ㆍ Started the 'Santander Product Recommendation'.  
  
__Day 9__

  ㆍ EDA with the 'Santander Product Recommendation' which I started yesterday.  
  I read datasets, drew basic statistics. Furthermore, I also tried visualizing a single variable with bar graph.  
  But, its not easy to predict 7 products. I should search datasets more delicately.  
  
  ㆍ Reviewed the Ensemble Learning that I studied last week.  
  ㆍ Made Voting Classifier out of Logistic Regression and KNN.  
  
  
  ㆍ Dataset I used  
  Wisconsin Breast Cancer Datasets  
  Santander Product Recommendation  
  
 __Day 10__
 
   I decided to post the algorithm problems that I solve every day as well from Baekjoon Online Judge (acmicpc.net). Its a Korean-style 'Leetcode'


  ㆍI solved 3 algorithm problems from Basic Mathematics. I don't know why the answer rate of the questions that I find difficult is so high.  
  But the funny thing is that the questions I thought was easy has low answer rate.  
  ㆍ Reviewed the Random Forest that I studied last week.  
  ㆍ I attempted to visualize the data of 'Santander Product Recommendation' but Its not easy as much I expected.  
  I want to see how much the each product changes depending on the date.


  ㆍDataset I used  
  Human Activity Recognition  
  Santander Product Recommendation

__Day 11__

  ㆍFollowing yesterday, I tried to solve 3 algorithm questions from basic mathematics.  
  Solved 2 problems, but failed to solve last one. Its so annoying. If an error occurs and I correct it and resubmit, another error will occur.  
  I am gonna try again tomorrow. Give me luck!  

  ㆍ Reviewed the GBM(Gradient Boost Machine) that I studied last week.
