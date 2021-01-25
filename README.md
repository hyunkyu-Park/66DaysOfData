# 66DaysOfData
66DaysOfData Challenge
----------------------
Blog  
https://blog.naver.com/pbh6020
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


  ㆍ I solved 3 algorithm problems from Basic Mathematics. I don't know why the answer rate of the questions that I find difficult is so high.  
  But the funny thing is that the questions I thought was easy has low answer rate.  
  ㆍ Reviewed the Random Forest that I studied last week.  
  ㆍ I attempted to visualize the data of 'Santander Product Recommendation' but Its not easy as much I expected.  
  I want to see how much the each product changes depending on the date.


  ㆍDataset I used  
  Human Activity Recognition  
  Santander Product Recommendation

__Day 11__

  ㆍ Following yesterday, I tried to solve 3 algorithm questions from basic mathematics.  
  Solved 2 problems, but failed to solve last one. Its so annoying. If an error occurs and I correct it and resubmit, another error will occur.  
  I am gonna try again tomorrow. Give me luck!  

  ㆍ Reviewed the GBM(Gradient Boost Machine) that I studied last week.
  
__Day 12__

  ㆍ Unfortunately, I failed to solve the algorithm question that I couldn't solve yesterday again...  
  So I decide not to solve that question right now. I jumped to the next question!  
  As a result, I finished two more questions and tried one question. They are last 3 questions of Basic Mathematics 1.  
  That means, I am ready to start Basic Mathematics 2!!! WoW~  

  ㆍ Reviewed the XGBoost(eXtra Gradient Boost) that I studied last week.  
  ㆍ Looked over about the 'Dimension Reduction'. There are several ways to simplify dimensions such as PCA, LDA, SVD, NMF  
  ㆍ Looked over about the 'Clustering'. From the basic clustering method named 'K-means Algorithm' to the 'Mean Shift', 'GMM', 'DBSCAN', they are all fascinating.
  
__Day 13__

  Fortunately, I got an interview request from the 'AIQ' and interviewed for almost an hour and a half last night.  
  Although it was an interview to join the team, it was a fun and informative place of knowledge, contrary to worries.  
  We talked about platforms of several entertainment companies, such as 'Big Hit's Weverse', 'Naver's Vlive', and 'NC SOFT's Universe',  
  and their own unique business items for co-creating platform between fandom and artists.

  ㆍ Anyway, I joined the club and had a first meeting. One of the members brought up the topic of hills climbing, one of the hyperparameter optimization methods.  
  Two other members explained fundamentals of probability.

  ㆍ After the theoretical part, we also talked about ai techniques used in start-up companies.  
  It was super interesting and inspired me. I began to think every moment about how can we use Ai in reality.  
  I have a meeting with the professor of the group tomorrow, and I'm looking forward to it badly.
 
__Day 14__

  ㆍ I looked up news and videos about 'weverse' and 'Universe' this morning.  
  I have come up with my own answers to the emergence of new platforms, the differences between each platform, and the direction of expansion of the business structure.  
  At the meeting with the professor, I suggested 4 solutions, and I heard that three of them are already being projected by other startups.  
  To be honest, I felt very despondent.  
  However, professor told me that your proposals came out in only two days, and It means I have potential insight If it overlaps with a project already in progress.  
  I was so grateful. I felt so lucky to be a member of his team.

  ㆍ Reviewed the LightGBM that I studied last week.

__Day 15__

  I had a fender-bender today. I was totally exhausted because it was my first car accident.  
  I literally considered whether to do study or not. However, 66 Days of Data challenge encourage me to study.  
  I do appreciate to #KenJee. 

  ㆍ Made 2 base line codes with XGBoost and LightGBM of the Santander Customer Satisfaction from the Kaggle  
  ㆍ I learned 2 important things while making base line codes.  
   >ㆍ If the number of columns is high, there is a possibility of overfitting.  
   >ㆍ Using test datasets as evaluation datasets of XGBoost can cause of increasing the chance of overfitting.
