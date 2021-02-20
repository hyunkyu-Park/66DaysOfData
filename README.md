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
  I literally considered whether to do study or not. However, 66 Days of Data challenge encouraged me to study.  
  I do appreciate to #KenJee. 

  ㆍ Made 2 base line codes with XGBoost and LightGBM of the Santander Customer Satisfaction from the Kaggle  
  ㆍ I learned 2 important things while making base line codes.  
   >- If the number of columns is high, there is a possibility of overfitting.  
   >- Using test datasets as evaluation datasets of XGBoost can cause of increasing the chance of overfitting.

__Day 16__

  I was trapped in a maze while EDA of 'Santander Product Recommendation' last week.  
  I decided to approach the problem in different way. So, I drew a whole forest instead of cutting down single tree and started to make Base Line codes first.  
  It seemed work! Now, I am doing data preprocessing.
  
  ㆍSolved one question of Basic Mathematics 2 from Baekjoon Online Judge (acmicpc.net), Korean-style 'Leetcode'.  
  ㆍSummarize Complexities of Algorithm. Time Complexity and Space Complexity

__Day 17__
  
  ㆍWhile solving the problem related to prime number algorithms, I studied the Eratosthenes' sieve and uploaded on my github algorithm repository.  
  ㆍadvanced the base line codes.  
  ㆍHad a zoom-meeting with team members of 'Marvus' company and AIQ(Emotional AI Research Team) for R&D.
  
__Day 18__

  ㆍSummarized the contents of the yesterday's meeting. Additional research on emotional recognition.  
  ㆍSearched and read articlesㆍresearch about  learning analytics.
  
__Day 19__

  ㆍSolved 2 algorithm questions about Goldbach's conjecture and Bertrand's postulate.  
  Those are so challenging and I could think about the time complexity once again.  
  ㆍEven though I didn't understand everything, I read the R&D article about Lightweight Deep Learning.  
  I am going to summarize this article as soon as possible.
 
__Day 20__

ㆍI had a study meeting with AIQ members, and we discussed about Bayes rule and Naive Bayes classifier.  
The concept was not as difficult as I thought it would be. Because we tried to apply the theory with Covid 19 diagnosis, I guess.  
 After that, one of our member reviewed articles MIT Solan article - emotional AI explained and Financial Times article - How AI is getting an emotionally intelligent robot.  Every topics were so fascinating such as 'Where does computer function?', 'What is emotion AI', 'Concerns'.  
 We conducted the company review in the third order. Company 'Affectiva' is a software company that builds artificial intelligence that understands human emotions, cognitive states, activities and the objects people use, by analyzing facial and vocal expressions. The company spun out of MIT Media Lab and created the new technology category of Artificial Emotional Intelligence. We scanned how they collect the whole data, discussed Business Scalability in automobile sector, Media field, and Biometric research. It was literally constructive time.  
Lastly, other member brought new topic for storytelling time. We talks about what would have happend if AI had been applied in Storytelling time. Today's topic was drug discovery through AI in the movie named 'The return'.

__Day 21__

  ㆍI studied one of optimization methods called 'Hill climbing'. The crucial point of this method is that it does not guarantee that you find the absolute best solution.  
  Moreover, there is an problem with the hill climbing that we can easily get stucked in a good but not optimal solution(Local optima).  
  So, the simple hill climbing solution where we only go upwards is often called to be a greedy method which greedily optimizes the short term gain and  
  refuses to incur some temporary loss even if it would lead to better long-term gain.

  ㆍanother key terminology: Simulated annealing Instead of only allowing changes that improve the solution (go uphill),  
  some changes that make it worse (go downhill) are also allowed with some probability.  Concept word  'Temperature' is important point in Simulated annealing.  
  Simulated annealing is quite similar to Greedy search in that the optimization process is moving towards better solution.  
  However, Simulated annealing accepts both better solutions and worse solutions.

  ㆍIf we change the temperature higher in Simulated annealing, the algorithm takes all new solutions.  
  On the other hand, low temperature as close as 0 only accepts new solutions when they are better than the current one.
  
__Day 22__

  ㆍ Finally, I completed algorithm questions of the 'basic mathematics 2'. Wow!  
  Especially, the answer rate of the last question is almost 20%, so I bit worried. However, I didn't give up and I made it. I am proud of myself today.  
  ㆍ The next algorithm problem will be recursive function.

  ㆍ We were supposed to make our AI song my using open API, but Its not easy to make what we want.  
  So, we changed our plan that AI to read the poem by 'Aleksandr Sergeevich Pushkin'.  
  ㆍ The poem 'What though life conspire to cheat you' is profound and beautiful. We used 3 open API from 'Voiceful', 'AWS', and 'Naver'.  
  It was pretty interesting and the funny thing is that reading poem with English by AI was a bit disappointing but with Korean was pretty natural and represented emotions.  

__Day 23__

  ㆍ I re-opened my jupyter notebook for 'Santander product recommendation competition' of Kaggle.  
  I just finished data preprocessing last time, so I tried to figure out feature engineering.  
  ㆍ Created the columns for machine learning model  training. I am going to use 'customer variables', 'variables based on dates', and 'lag-1' variable in baseline codes.  
  ㆍReplace missing values with -99 when using derived variables.  
  ㆍ'lag-1' variable is a variable that will be used as the current customer's data whether they held the product a month ago.  
  Later, I will make several variables such as 'lag-2', 'lag-3' to see if these are effective.

__Day 24__

  ㆍI have tried to follow the books that I bought in last Christmas. Fortunately😂, however, I have a lot of things to do such as study, research, meeting etc.  
  Hence, I could not open the book named 'machine learning perfect guide' ever since I studied classification algorithms.  
  But today, I reopened  the book and started Regression section.
  ㆍ The core of machine learning regression is finding Optimal Regression coefficients based on given features and determination value data.  
  ㆍRegularization refers to applying penalty values to regression coefficient to solve the overfitting problem of general linear regression.  
  ㆍCreating a optimal regression model means creating the model in which sum of the residuals of the entire data is minimal.  
  At the same time, it means to find the optimal regression coefficient where the sum of the error values can be minimal.  
  ㆍUsually, when calculating the sum of errors, you take the absolute value and add it(Mean Absolute Error), or you take the square of the error value and add it(RSS, Residual Sum of Square). In other words, the error^2 = RSS  
  ㆍFinding regression coefficients with minimum RSS through training is a key point in machine learning-based regression.

__Day 25__

  ㆍ I heard that brute-force search algorithm questions are interesting.  
  I can understand a little bit what it means, however, It's so awkward solving algorithm with barely thinking time complexity. 

  ㆍ Also, I studied 'Gradient descent' and 'Stochastic gradient descent'.  
  I know it is very critical concept in machine learning and important in Neural networks which are the basis of Deep learning as well.  
  Hence, I implemented both of them myself. Implementing it myself really helped me understand the concept of Gradient descent.

  ㆍAs I implement myself, I also realize that the disadvantage of gradient descent.  
  The disadvantage of it is that it takes a very long time to perform because it repeatedly updates the value for minimizing the cost function for all learning data.  
  To improve this issue, Stochastic gradient descent does not calculate the value at which is updated with full input data, but rather uses only some data to calculate the value at which w is updated, ensuring a faster rate than gradient descent.
  
__Day 26__

  ㆍ I read the Linear Regression part of chapter 3 - Machine Learning from Building AI. The chapter introduces funny phrases from twitter.  
  When fundraising: it's AI  
  When recruiting: it's machine learning  
  When implementing: it's linear regression  
  In fact, I think this phrases become so popular because there is an element of truth in it.😁  
  ㆍ They also explains the types of machine learning. Supervised learning, Un-supervised learning, and Reinforcement learning.  
  The funny thing is that the way introduces these concepts are quite similar everywhere.  
  If I may exaggerate, I have seen the examples of guessing apartment price and classifying dogs and cats over 3 times. lol

__Day 27__

  ㆍHad third meeting with AIQ members. We discussed about the basic concept of machine learning, Linear Regression and the nearest neighbor method.  
  ㆍConducted  the company review. Today's company was acryl-Jonathan. Jonathan offers various services and they opened their own AI platform last December.  
  Big data collection and Analysis tool: Jonathan-Datascope  
  Data annotation tool: Jonathan-Marker  
  Deep learning library: Jonathan-Intelligence  
  AI development and operational maintenance tool: Jonathan-Flightbase  
  Chatbot solution and management tool: Bots  
  ㆍIn early days of the start-up, collected data from research institutes and universities were relatively inexpensive, but it was not easy to for start-up to purchase. Morever, the data is not valid for a long time, so they thought a lot about it in this area and eventually collected data in one by one. Currently, distributed data crawling engines are used to collect information including the data that other data robots cannot collect.

  SWOT

  Strength  
  ㆍ It is used in a variety of areas, including health insuarance, finance, public, IT, education.  
  ㆍ Have all necessary technology and business operations within the framework of AI, such as NLP, Emotion detection, and Data crawling  
  ㆍ Increasing number of R&D assignments by government, not just businesses, every year  
  Weakness  
  ㆍ The platform, Jonathan, was unveiled in the second half of the 20th year, but the MAU has yet to meet expectations.  
  Opportunity  
  ㆍ As the government's startup support policy is activated every year, it is expected to receive a lot of support.  
  ㆍ NLP and Emotion Detection have clear marketability and customer needs as well as clear objectives.  
  ㆍ AI is rapidly gaining market share in education, which used to be an unwavering market  
  Threat  
  It is a great advantage to have and know all the necessary technologies of AI, but as it is now said to be Narrow AI, it is often tried to achieve the highest efficiency with one or two algorithms rather than using various AI algorithms. I don't know if they can survive the competition with these companies.

  ㆍWhile storytelling, discussed what are the differences between Face-verification vs Face-recognition and studied the triplet loss function that the great method to train hyper-parameter for Neural network in face-recognition.

__Day 28__

  ㆍProf.Henny of the AIQ aksed me to introduce the Bert in NLP to the members. So I decided to find information of NLP today.  
  Key points I studied  
  ㆍ What is Natural Language Processing?  
  ㆍ Word embedding  
  ㆍ Markov Chains and RNN in Language Model, LM  

__Day 29__

  ㆍStudied basic algorithms called 'built in functions', 'itertools', 'heapq'. I am going to implement 'bisect' and 'collections tomorrow'
  ㆍFollowing yesterday, I tried to understand Attention model, self-attention model, and multi-head self attention model.  
  These are necessary concepts to understand bert. What is bert, and why does bert has been developed. The more I study NLP, I think there is a lot of potential.  
  ㆍStarted to make my presentation for NLP, bert and to organize that I am going to speech.

__Day 30__

  ㆍI believe I have done the most today since I started blogging. First, I have finished python built-in functions called bisect, collections, and math following yesterday. In addition, studied two-pointer algorithm which means the algorithm that processes two point positions when a list needs to be accessed sequentially.  
  ㆍ Started to learn SQL and experienced at the 'BigQuery Console'.  
  ㆍ In my Kaggle project, I separated the data for cross-validation and reviewed my Baseline codes. I think I am ready to start model training.
  
__Day 31__

  ㆍI studied other basic algorithms, Calculating interval sums and Permutation-Combination, that useful in coding test. Also, solved several SQL questions, but, unfortunately, I couldn't study new concept of SQL such as 'logical operators', 'LIKE', and 'IN' etc.😂  
  ㆍIn Kaggle challenge, I chose 'XGBoost' as a model for learning in base codes. In addition, I tried to make cross-validation, however, evaluation way is so unfamiliar. Hence, I barely understand even though I spent more than 2 hours.
  
__Day 32__

  ㆍToday, I searched the general processing of Natural Language Processing.  
  Data preprocessing -> Create a word set -> One-Hot Encoding -> Word Embedding -> Learning Model Configuration -> Model training -> Save the model  
  ㆍProcedure of Data preprocessing.  
  Generate Token - > Morpheme Analysis -> tag part of speech -> refine data  
  
__Day 33__

  ㆍ Following yesterday, I did a detailed data survey of NLP. There are 4 major steps in Data preprocessing and 3 steps in Creating a word set.  
  ㆍ Procedure of Creating a word set  
  Indexing the words -> Figure out words frequency -> Word Representation in Text Data  
  ㆍThere are several methods for word representation in text data such as 'One-Hot Vector', 'N-gram', 'Bag of Words', 'Word2Vec', 'LSA', 'Glove'  
  
 ![1 1](https://user-images.githubusercontent.com/68415173/107762157-f12d3000-6d6f-11eb-951e-77622480ccd9.png)

__Day 34__

  ㆍI was confused relationship between one-hot Vector and Word Embedding. Because some people say 'Vectorizing is the word embedding' and others say 'Word embedding is the techniques for compressing words'. and now I know that It is a method to overcome the limitations of simple vectorization.  
  ㆍAfter understanding the concept, I made a powerpoint to explain it to AIQ members.  

![1](https://user-images.githubusercontent.com/68415173/107849005-8f39fc80-6e3b-11eb-8a9f-0d4ea19dfcc8.png)

__Day 35__

  ㆍSearched Definition and Concept of the Word Embedding and found the limits of the Word Embedding as well.  
  ㆍStudied 'RNN' and 'Transformer, which are the foundations of the 'Bert'.  
  ㆍRNN -> RNN + Attention -> Transformer(Attention is all you need).  
  ㆍStarting tomorrow, I will participate in the 'AI tutor R&D using artificial intelligence' with the 'Ministry of Trade, Industry and Energy' as a coordinator of AIQ. Although it is a short time of a week, I will participate so that I can experience many things and have a positive impact.  
  (I would like to thank the professor once again for giving me a good opportunity)  

![임명장](https://user-images.githubusercontent.com/68415173/107876388-16a17180-6f09-11eb-94c7-0f4e3f6d8619.png)

__Day 36__

  ㆍ Along with the Marvrus, we outlined the RFP development of ai tutoring system for the task support of teaching instructors in a non-face-to-face learning environment organized by the Ministry of Commerce, Industry and Energy. It is not possible to describe the details, but it is interesting that data can be handled from a numerical improvement and a business perspective.

__Day 37__

  ㆍDraw the outline of Application of R&D performance and expected effects.  
  ㆍOutlined 'Expanded the R&A to Areas and measures to utilize key technology performance'.  
  ㆍCreate the DataBase ERD.

__Day 38__

   I couldn't post yesterday because I was too busy.  
   ㆍI investigated the evaluation criteria and datasets in various fields of deep learning.  
   I looked into it hard, but I was a little sad that the agenda was revised at the meeting late at night.

__Day 39__


  Today, there were two big things: Samsung mentoring and natural language processing announcement.  
  ㆍI met the two Samsung experts(They were called 'expert Ma', 'expert Cha'). One is a programmer and the other is data analyst.  
  They gave insperation and shared their life lessons to the participated mentees. I feel glad having such a meaningful time with good people.  
  ㆍAs a matter of fact, I was not worried about my presentation that much. However, It was harder that I thought it would be. I usually keep observing people's facial expressions and change the style of presentation continuously. However, doing a presentation on zoom was not as simple as general presentation. I should practice presentation assuming that I can't get feedback.

__Day 40__

  ㆍAlong with the Marvrus, I filled Quantitative Target Items of the RFP development of AI tutoring system for the task support of teaching instructors in a non-face-to-face learning environment organized by the Ministry of Commerce, Industry and Energy.  Among other several sources in the world, Traffic lights at Pearl Dew University in the U.S. were the most helpful.  
  ㆍI have been participating with two 'AIQ' members. They are really hardworking and helpful, but I felt that it was really difficult to play the role of a middle bridge with the company this time.

__Day 41__

  ㆍHad meeting with AIQ members and invited CEO 'Kim Joseph'. We shared the idea of 'Working with text' and 'overfitting'. It was very informative to talk more about cross-validation.  
  ㆍRight after theoretical themes, we also shared companies research as always. Today's topic was related to Health system and crowd funding. In addition, our invited guest is CEO of Health system company, so he taught us examples of ai applications in healthcare.  
  ㆍThe rfp submission date is almost near, so I finished it with my team members and had a meeting with the the Marvrus whole day.
