#  Disaster Tweets Classification (LogReg + DistilBERT)

This project is part of my NLP exploration using machine learning and transformer models to classify disaster-related tweets.  
The goal is to predict whether a tweet refers to a real disaster or not.

---

## 📌 Overview

- **Dataset**: [Kaggle - Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)
- **Goal**: Binary classification (disaster or not)
- **Models used**:
  -  Logistic Regression with TF-IDF
  -  DistilBERT fine-tuned using `transformers`

---

##  Structure

- `disaster-tweets-nlp.ipynb` — Jupyter notebook with full code and results

---

##  Technologies Used

- Python, NumPy, pandas
- scikit-learn (Logistic Regression, TF-IDF)
- HuggingFace Transformers (`DistilBERT`)
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Results

| Model         | Public Score / Accuracy | Notes                              |
|---------------|--------------------------|-------------------------------------|
| Logistic Reg. | _F1-score 0.81_        | TF-IDF + basic preprocessing        |
| DistilBERT    | _F1-score 0.85_        | Pretrained transformer, fine-tuned |

---

