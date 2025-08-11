##Movie Hit or Flop Prediction using Machine Learning
This project focuses on predicting whether a movie will be a commercial hit or a flop before its release by using several machine learning models. The goal is to provide a tool that can help producers, investors, and marketing teams make informed decisions and reduce financial risks.

**Project Objectives**
- Collect and preprocess movie data from sources like IMDb, TMDb, and Box Office Mojo.
- Develop and train classification models, specifically Gradient Boosting, Support Vector Machine (SVM), and Random Forest, to predict if a movie will be a "Hit" or a "Flop".
- Identify the key factors that influence a movie's performance.
- Evaluate the performance of each model using metrics such as Accuracy, Precision, Recall, and F1-Score.

**Methodology**
The project follows a systematic workflow to build and evaluate the prediction models:
a. Data Collection: Gathering relevant data from various sources to be used for model training.
b. Preprocessing: Cleaning and preparing the data for analysis. This step includes handling missing values, encoding categorical features like genre and cast into a machine-readable format, and scaling      numerical features.
c. Train-Test Split: The dataset is divided into an 80% training set and a 20% testing set. The training set is used to train the models, while the testing set is used to evaluate their performance.
d. Model Training: Three classification models—Gradient Boosting, SVM, and Random Forest—are trained on the preprocessed training data.
  -Gradient Boosting: This model builds decision trees sequentially, with each new tree correcting the errors of the previous ones.
  -SVM: This classifier finds the optimal boundary (hyperplane) to separate the classes (Hit or Flop).
  -Random Forest: This model is an ensemble method that combines the results of many decision trees to make a final prediction based on a majority vote.

e. Model Evaluation: The trained models are tested on the unseen test data to assess their performance.
f. Model Comparison: The models are compared to each other to determine the best-performing one.

##Novelty and Key Modifications
A key aspect of this project is its focus on using both numerical and non-numerical features to predict movie success. Unlike previous approaches that primarily relied on revenue, budget, and ratings, this project incorporates "Alternative Factors" such as:

Cast and Director Influence: The reputation and fan following of actors and directors can significantly impact a movie's success, regardless of its budget.
Genre Impact: Certain genres, like horror or comedy, can be profitable even with lower production costs.

By incorporating these factors and using techniques like One-Hot Encoding to convert them into a machine-readable format, the model can learn deeper patterns behind a movie's success. This approach is more valuable for early-stage movie planning because it can predict potential success before revenue or rating data is available.

##Results
The models were evaluated based on their accuracy scores:

Gradient Boosting: Achieved an accuracy of 0.85. Its AUC score was 0.87.
SVM: Achieved an accuracy of 0.79. Its AUC score was 0.79.
Random Forest: Achieved the highest accuracy of 0.88.

The results indicate that the Random Forest model performed the best in predicting movie outcomes among the three models tested.
