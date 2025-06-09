# 💄 Sentiment Analysis for Small Business Growth — Beauty Industry Case Study

This project explores how deep learning can help small beauty businesses understand customer feedback at scale. Using Amazon product reviews from the Beauty category, we trained and compared machine learning models to classify customer sentiment and gain actionable insights.

---

## 🎯 Project Objective

To build a sentiment classification system that predicts whether a product review is **positive** or **negative**, with a focus on helping small beauty businesses monitor and improve customer satisfaction.

---

## 🧾 Dataset

- **Source**: [Amazon Beauty Product Reviews Dataset](https://nijianmo.github.io/amazon/index.html)
- **Category**: Beauty
- **Preprocessing**: 
  - Text cleaning (stopwords, punctuation, lowercase, etc.)
  - Tokenization and padding
  - Sentiment labeling based on review ratings

---

## 🧠 Models Compared

| Model                 | Accuracy     |
|-----------------------|--------------|
| Logistic Regression   | 89.7%        |
| **LSTM Neural Network** | **93.5%**  |

- LSTM outperformed traditional models, capturing context and sequential dependencies in customer language.

---

## 🧩 Model Interpretability

To understand **why** the model made certain predictions, we used:

### 🟢 LIME (Local Interpretable Model-agnostic Explanations)

- Highlights which words influenced a prediction
- Improves trust and transparency in AI systems

#### Example LIME Output:
- Words like **"love", "perfect", "smooth"** increased positive sentiment score
- Words like **"dry", "burn", "fake"** flagged negative reviews

---

## 🛠️ Tech Stack

- `Python`
- `TensorFlow / Keras`
- `scikit-learn`
- `LIME`
- `NLTK`, `spaCy`, `NumPy`, `Pandas`
- `Matplotlib`, `Seaborn`

---

## 💡 Key Learnings

- Deep learning models (like LSTM) can significantly outperform classical ML when dealing with natural language.
- LIME is a powerful tool for explaining black-box predictions to non-technical stakeholders.
- Preprocessing text well is just as important as model selection.

---

