# PROJECT BY: SYEDA UMAIMA TAMKEEN

## Project Summary: Twitter Sentiment Analysis Using NLP and Machine Learning

This project presents a complete Twitter sentiment analysis system capable of classifying tweets into **Positive**, **Negative**, or **Neutral** categories. It leverages both rule-based sentiment scoring (TextBlob and VADER) and supervised machine learning classifiers to detect the underlying sentiment of short-form texts. Visual dashboards and evaluation metrics provide insight into model performance and classification trends.

---

## Techniques Implemented:

- **Text Preprocessing**  
  - Lowercasing, punctuation removal, and whitespace cleanup  
  - Tokenization and lemmatization using NLTK  
  - Stopword removal and regular expression filtering

- **Rule-Based Sentiment Classification**  
  - TextBlob for polarity scoring and sentiment thresholds  
  - VADER SentimentIntensityAnalyzer for compound score classification  

- **Vectorization for Machine Learning**  
  - TF-IDF vectorizer using top 5000 weighted features  

- **Supervised Machine Learning Models**  
  - Logistic Regression, Support Vector Machine (SVM), Naive Bayes, and Random Forest classifiers  
  - Train-test split and 5-fold cross-validation for model evaluation  

- **Data Visualization & Evaluation**  
  - Accuracy and cross-validation score plots using matplotlib  
  - Confusion matrix heatmap using seaborn  
  - Classification report showing precision, recall, and F1-score  

---

## Evaluation Metrics:

- **Accuracy Score**: Accuracy of each ML model on test data  
- **Cross-Validation Mean Score**: Generalization capability across training folds  
- **Classification Report**: Precision, recall, and F1-score for all three sentiment classes  
- **Confusion Matrix**: Visualized correctness of model predictions for each sentiment category  

---

## Results & Insights:

- Logistic Regression consistently achieved the highest accuracy on mock Twitter data  
- Rule-based methods like VADER were effective for short, expressive texts  
- Neutral sentiments were more difficult to classify compared to subjective expressions  
- Visual dashboards helped confirm balanced performance across classes

---

## Strengths:

- Dual-layer sentiment system combining rule-based and ML-based approaches  
- Clean modular code with extensibility for real-time Twitter API integration  
- Effective text preprocessing and token normalization pipeline  
- Compatible with larger datasets or real-world tweet collections with minimal modification  

---

## Conclusion:

This Twitter sentiment analysis project offers a practical, scalable solution for classifying public opinion and social media content. The combination of NLP preprocessing, rule-based scoring, and machine learning classifiers ensures high accuracy and adaptability. The system fulfills all core project requirements and can be enhanced further with real-time streaming or deep learning models like LSTM or BERT.
