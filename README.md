**Movie Hit or Flop Prediction using Machine Learning**

[cite_start]This project focuses on predicting whether a movie will be a commercial hit or a flop before its release by using several machine learning models[cite: 6]. [cite_start]The goal is to provide a tool that can help producers, investors, and marketing teams make informed decisions and reduce financial risks[cite: 8].

### Project Objectives

* [cite_start]Collect and preprocess movie data from sources like IMDb, TMDb, and Box Office Mojo[cite: 10].
* [cite_start]Develop and train classification models, specifically Gradient Boosting, Support Vector Machine (SVM), and Random Forest, to predict if a movie will be a "Hit" or a "Flop"[cite: 11, 13].
* [cite_start]Identify the key factors that influence a movie's performance[cite: 14].
* [cite_start]Evaluate the performance of each model using metrics such as Accuracy, Precision, Recall, and F1-Score[cite: 15].

### Methodology

The project follows a systematic workflow to build and evaluate the prediction models:

1.  [cite_start]**Data Collection**: Gathering relevant data from various sources to be used for model training[cite: 38, 39].
2.  [cite_start]**Preprocessing**: Cleaning and preparing the data for analysis[cite: 35, 36]. [cite_start]This step includes handling missing values, encoding categorical features like genre and cast into a machine-readable format, and scaling numerical features[cite: 55, 57, 58].
3.  [cite_start]**Train-Test Split**: The dataset is divided into an 80% training set and a 20% testing set[cite: 101, 104, 106]. [cite_start]The training set is used to train the models, while the testing set is used to evaluate their performance[cite: 102, 105].
4.  [cite_start]**Model Training**: Three classification models—Gradient Boosting, SVM, and Random Forest—are trained on the preprocessed training data[cite: 59].
    * [cite_start]**Gradient Boosting**: This model builds decision trees sequentially, with each new tree correcting the errors of the previous ones[cite: 60, 66].
    * [cite_start]**SVM**: This classifier finds the optimal boundary (hyperplane) to separate the classes (Hit or Flop)[cite: 61, 66, 222].
    * [cite_start]**Random Forest**: This model is an ensemble method that combines the results of many decision trees to make a final prediction based on a majority vote[cite: 66, 87, 88].
5.  [cite_start]**Model Evaluation**: The trained models are tested on the unseen test data to assess their performance[cite: 27, 64].
6.  [cite_start]**Model Comparison**: The models are compared to each other to determine the best-performing one[cite: 23].

### Novelty and Key Modifications

[cite_start]A key aspect of this project is its focus on using both numerical and non-numerical features to predict movie success[cite: 44, 45, 51]. [cite_start]Unlike previous approaches that primarily relied on revenue, budget, and ratings[cite: 281, 282], this project incorporates "Alternative Factors" such as:

* [cite_start]**Cast and Director Influence**: The reputation and fan following of actors and directors can significantly impact a movie's success, regardless of its budget[cite: 288, 292].
* [cite_start]**Genre Impact**: Certain genres, like horror or comedy, can be profitable even with lower production costs[cite: 289, 293].

[cite_start]By incorporating these factors and using techniques like One-Hot Encoding to convert them into a machine-readable format, the model can learn deeper patterns behind a movie's success[cite: 51, 52]. [cite_start]This approach is more valuable for early-stage movie planning because it can predict potential success before revenue or rating data is available[cite: 297, 302].

### Results

The models were evaluated based on their accuracy scores:

* [cite_start]**Gradient Boosting**: Achieved an accuracy of 0.85[cite: 153, 215, 217]. [cite_start]Its AUC score was 0.87[cite: 168].
* [cite_start]**SVM**: Achieved an accuracy of 0.79[cite: 155, 250]. [cite_start]Its AUC score was 0.79[cite: 167].
* [cite_start]**Random Forest**: Achieved the highest accuracy of 0.88[cite: 151, 265, 268].

[cite_start]The results indicate that the Random Forest model performed the best in predicting movie outcomes among the three models tested[cite: 151].
