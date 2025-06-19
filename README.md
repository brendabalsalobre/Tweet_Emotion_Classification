# Tweet Emotion Classification Project

## 🔎 Project Overview
This project applies supervised learning to classify tweets into six emotions (sadness, joy, love, anger, fear, surprise) using TF-IDF features and classic machine learning models. By transitioning from Naive Bayes to Logistic Regression, the model's accuracy improved from 84% to 90%, offering a scalable solution for detecting a variety of emotions in text. 

## 🎯 Objective
My goal with this project was to create a reproducible NLP workflow that combines text preprocessing, feature scaling, and model tuning to improve classification performance on short-form user-generated text.

## 👩🏻‍💻 Tools & Techniques
* Python (Pandas, scikit-learn)
* TF-IDF Vectorization
* MaxAbsScaler
* Multinomial Naive Bayes (initial model)
* Logistic Regression (optimized model)
* Classification Report for precision, recall, F1-score

## 📈 Performance Summary
* **Naive Bayes**: Baseline model (accuracy = 84%)
* **Logistic Regression**: Optimized model (accuracy = 90%)

## 💡Key Insights:
Here we can see that the Logistic Regression model outperforms the Naive Bayes model. The Logistic Regression model was able to capture dependencies between words and balance predictions across emotional categories. Moreover, I noticed that preprocessing decisions (especially feature scaling) were critical to performance gains.

## 📄 Dataset Info: 
* **Source**: Kaggle/Twitter Emotion Classification Dataset
* **Format**: Parquet (.parquet)



