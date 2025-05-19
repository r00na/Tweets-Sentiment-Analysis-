# Tweet Sentiment Analysis 💬

This project is a **Sentiment Analysis** system that classifies tweets as **Positive 😊** or **Negative 😠** using machine learning techniques. The model is built with `Logistic Regression` and trained on a labeled dataset of tweets.


## 📁 Dataset

- CSV file: `tweet_data.csv`
- Columns used:
  - `text`: The content of the tweet
  - `target`: Sentiment label (`1` = Positive, `0` = Negative)

## 🛠️ Features & Libraries

- **Preprocessing**: Stopwords removal, lemmatization, punctuation & link cleaning 
- **Visualization**: WordCloud for positive and negative tweets
- **Modeling**: Logistic Regression, Cross-Validation (KFold) 
- **Evaluation**: Accuracy, Precision, Recall, F1 Score 


## 🔄 Workflow

1.  **Read CSV**  
2.  **Remove duplicates**
3.  **Clean tweets**: URLs, hashtags, mentions, stopwords, lemmatization
4.  **Remove empty entries**
5.  **Split data**: Train/Test
6.  **Train model**: Logistic Regression + TF-IDF Vectorizer
7.  **Evaluate**: Cross-validation + Final test accuracy
8.  **Predict custom tweets** with confidence levels

---

## Sample Prediction

```python
tweet = "I absolutely love the new update! It makes everything so much easier to use. Well done team!"
````

* **Prediction**: Positive ✅
* **Confidence**: 90.85% 🔥


## 📊 Evaluation Metrics

* Accuracy 
* Precision 
* Recall 
* F1 Score 

