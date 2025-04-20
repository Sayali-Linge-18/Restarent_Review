# Restarent_Review
# 🍽️ Restaurant Review Sentiment Analysis

A machine learning project that analyzes restaurant reviews and classifies them as **positive** or **negative** using **Natural Language Processing (NLP)**.

---

## 📁 Dataset
- **File:** `a1_RestaurantReviews_HistoricDump.tsv`
- **Columns:**
  - `Review`: Text review from a customer
  - `Liked`: Sentiment label (1 = Positive, 0 = Negative)

---

## 🛠️ Tech Stack
- Python
- pandas
- scikit-learn
- CountVectorizer (for text feature extraction)
- Logistic Regression (classification model)
- Pickle (for model saving)

---

## 🚀 How It Works

1. Load and preprocess data
2. Convert text to numerical features using **CountVectorizer**
3. Split data into training and testing sets
4. Train a **Logistic Regression** model
5. Evaluate with accuracy score
6. Save the model for reuse

---

## 📊 Result
- **Accuracy Achieved:** `75%` on the test set
- **Model saved as:** `sentiment_model.pkl`

---

## 💡 Future Improvements
- Add text cleaning (stopwords, punctuation)
- Use TF-IDF or Word Embeddings
- Try other ML models like SVM or Random Forest
- Deploy using Flask or Streamlit

---

## 👨‍💻 Author
[Your Name Here]
