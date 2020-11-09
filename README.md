
# [Project 1: Quora-Question-Similarity: Project Overview](https://github.com/vaibhavt14/Quora-Question-Similarity) 
* It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.
* Identify which questions asked on Quora are duplicates of questions that have already been asked.
* This could be useful to instantly provide answers to questions that have already been answered.
* We are tasked with predicting whether a pair of questions are duplicates or not.  
* Optimized Logistic Regressor,Linear SVM, and XGBoost to reach the best model. 
* Performance metrics: log-loss

![](/images/class_distribution.png"Class distribution of target variable")
![](/images/questions.png "Distribution of unique and repeated")
![](/images/questions_occurence.png "question appeareance counts")


# [Project 2: Personalized-Cancer-Diagosis: Project Overview](https://github.com/vaibhavt14/Personalized-Cancer-Diagosis)
* Personalized Medicine Redefining Cancer Treatment is a real world data set from Kaggle
* Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track, because we need your help to take personalized medicine     to its full potential
* Classify the given genetic variations/mutations based on evidence from text-based clinical literature.
* Optimized Naive Bayes,Logistic Regression,Linear SVM and Random Forest Regressors to reach the best model. 

![](/images/class_distribution%20(1).png "Class features for target variable")
![](/images/histogram.png "train data for univariate analysis")

# [Project 3: Netflix-Movie-Recommendation: Project Overview](https://github.com/vaibhavt14/Netflix-Movie-Recommendation)
* The given problem is a Recommendation problem 
* Predict the rating that a user would give to a movie that he has not yet rated
* For a given movie and user we need to predict the rating would be given by him/her to the movie. 
* Applied Surprise model,SVD(Singular value decomposition),SVDpp,xgboost regressor,item-item,user-user similarity,Matrix Factorization
* Performance metrics: Minimize the difference between predicted and actual rating (RMSE and MAPE)

![](/images/distribution%20of%20ratings.png "Class distribution of target variable")
![](/images/rating_per_month.png "Rating per month")
![](/images/rating_per_movie.png "Rating per movie")

# [Project 4: FaceRecoginition-Web-App: Project Overview](https://github.com/vaibhavt14/FaceRecoginition-Web-App) 
* To classify the gender by uploading a image and model will predict the gender whether Male or Female 
* Object detection using Haar Casacade 
* For the preprocess images, we will extract features from the images, ie. computing Eigen images using principal component analysis 
* Developed web server gateway interphase in flask by rendering HTML CSS and bootstrap in the frontend and in the backend written in Python
* Optimized Linear SVM algorithm using GridsearchCV to reach the best model
* Integrating the machine learning model to Flask App.
* Built a client facing API using flask

![](/images/test.jpg "Gender prediction")

[Click here](http://169.63.212.53:8085/)

