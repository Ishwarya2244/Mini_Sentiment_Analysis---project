# Mini Sentiment Analysis Project

This project performs sentiment analysis on text reviews using:
- TF-IDF Vectorizer
- Logistic Regression
#Machine Learning Work Flow
1. Raw Data
We collect text reviews and their labels (sentiment: 0 or 1).
2.Train–Test Split
Data is split into training data (to learn) and testing data (to check performance).
3.Text to Numbers (TF-IDF)
Text reviews are converted into numerical form because ML models understand only numbers.
4.Model Training
Logistic Regression learns the relationship between words (features) and sentiment labels.
5.Prediction
The trained model predicts sentiment for new, unseen reviews.
6.Evaluation
Accuracy and classification report tell how well the model performed.

## Tools Used
- Python
- Pandas
- Scikit-learn

“The model achieved low accuracy due to the very small size of the dataset. With limited training samples, the model was unable to generalize patterns effectively.
However, the implementation pipeline, preprocessing steps, and model training process were successfully completed. With a larger real-world dataset, 
the performance is expected to improve significantly.”

