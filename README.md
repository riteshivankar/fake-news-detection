
## 📰 Fake News Detection using Machine Learning

A machine learning project that detects whether a news article is **real or fake** using natural language processing (NLP) techniques and classification algorithms. This project demonstrates how to preprocess text, vectorize using TF-IDF, and train multiple models for accurate predictions.

---

### 🔍 Features

* Binary classification: **Real vs. Fake** news detection
* NLP text cleaning and preprocessing
* TF-IDF vectorization for text features
* Multiple ML models: Logistic Regression, KNN, Decision Tree, etc.
* Evaluation using accuracy, F1-score, confusion matrix
* Manual testing interface for real-time prediction

---

### 🧠 Tech Stack

* Python 🐍
* Scikit-learn ⚙️
* Pandas & NumPy 🧮
* TfidfVectorizer for text features
* Jupyter Notebook (for interactive development)

---

### 📁 Dataset

Uses two labeled datasets:

* `fake.csv` — Fake news articles
* `true.csv` — Real news articles
  Both contain `title`, `text`, and `date` fields.

---

### 📊 Model Pipeline

1. Load & merge datasets
2. Assign labels (`0 = fake`, `1 = real`)
3. Clean and preprocess text
4. Split data into train/test sets
5. Vectorize text using `TfidfVectorizer`
6. Train multiple classifiers
7. Evaluate performance
8. Test with manual examples

---

### ✅ How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script:

   ```bash
   jupyter notebook Fake\ News\ Detection.ipynb
   ```

---

### 📌 Future Enhancements

* Integrate deep learning models like LSTM or BERT
* Deploy via Flask or Streamlit
* Add real-time news scraping for live prediction

---

### 🤝 Contributions

Contributions are welcome! Feel free to fork the repo and submit a PR for improvements.

