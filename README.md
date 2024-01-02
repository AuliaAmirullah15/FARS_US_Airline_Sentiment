# FARS_US_Airline_Sentiment
Trainings of Machine Learning Models for Fatality Analysis Reporting System and US Airline Sentiment Analysis

I trained different Machine Learning models to identify the correlation between potential parameters that could lead to severe injury and death in the US car accidents. Some of the models that I trained are:
1. Random Forest
2. Logistic Regression
3. TPOT (to choose the best model based on the available cleaned datasets)

Additionally, I harnessed the power of hyperparameter tuning and grid search cross validation techniques before training the models to choose the mostr relevant parameters that could lead to severe injury and death due to car accidents. 

Meanwhile, I trained models for sentiment analysis based on US Airline Sentiment datasets and harnessed NLTK for different purposes such as text cleaning before channeling them through Machine Learning models and word tokenization. Through this project, I put the whole process into an automated pipeline which results in a clearer and neater codes and structure for the analysis. Some of the models are:
1. Random Forest
2. Logistic Regression
3. SVM
4. Naive Bayes
5. Decision Tree
6. Ensembled Approach (Bagging) to reduce variance within a noisy dataset that leads to improved model accuracy
7. Bidirectional LSTM on IMDB

I evaluated the precision, accuracy, recall and f1-score using confusion matrix with balanced and imbalanced datasets (only for experiments and curiosity). 


