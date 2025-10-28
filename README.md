#📰 Fake News Detection Using Machine Learning

📌 Overview

This project focuses on detecting fake news using Machine Learning and Natural Language Processing (NLP) techniques.
The goal is to classify news articles as “True” or “Fake” based on their textual content.

The project uses TF-IDF for text vectorization and multiple machine learning models to compare their performance, including Logistic Regression, Decision Tree, Random Forest, and Naive Bayes.



#⚙️ Features

Preprocessing and merging of real and fake news datasets

Text vectorization using TF-IDF

Model training using multiple ML algorithms

Performance evaluation using accuracy, precision, recall, and F1-score

Visualization of model results through bar charts, ROC curves, and confusion matrices

Identification of most indicative words for fake and true news

WordCloud generation for visual insights



#🧠 Machine Learning Models Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Multinomial Naive Bayes



#📊 Evaluation Metrics

Each model is evaluated on:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

The results are compared visually using bar charts and ROC curves for better understanding.



#📂 Dataset

The dataset consists of two CSV files:

Fake.csv → Contains fake news articles

True.csv → Contains real news articles

Each dataset is labeled with a class value:

0 → Fake news

1 → True news

After merging, the combined dataset is shuffled and split into training and testing sets.



#🧰 Tech Stack

Language: Python
Libraries Used:

pandas

numpy

matplotlib

seaborn

sklearn

wordcloud



#📈 Output Visualizations

Model Performance Comparison (Bar Chart)

Confusion Matrices for each model

ROC Curves & AUC Scores

Top Indicative Words for true and fake news

WordClouds for text visualization



#💡 Insights

Logistic Regression and Random Forest often achieve the best balance between accuracy and interpretability.

TF-IDF effectively captures important textual patterns for distinguishing fake vs. true news.

Visualization of indicative words helps in understanding how models make predictions.



#🏁 Conclusion

This project demonstrates how machine learning and NLP can be used to automatically detect misinformation.
It can be further extended by:

Using deep learning models (LSTM, BERT)

Expanding the dataset

Building a web app for real-time fake news detection
