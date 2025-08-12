#  Sentiment Analysis on Amazon Product Reviews

##  Overview
This project focuses on **Sentiment Analysis** of Amazon product reviews to determine whether a review expresses a **positive** or **negative** sentiment.  
It uses **text preprocessing**, **TF-IDF vectorization**, and machine learning models such as **Logistic Regression** and **Naive Bayes** for classification.

---

##  Dataset
We used the **Amazon Product Reviews** dataset from Kaggle.  
Download it here:  
🔗 [Amazon Product Reviews Dataset](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews)

---

##  Features
- Preprocessing of text data (stopwords removal, lemmatization, lowercasing)
- Sentiment labeling based on review scores
- Feature extraction using **TF-IDF**
- Training and evaluation of:
  - Logistic Regression
  - Naive Bayes
- Model accuracy comparison
- Visualization of most common words in positive and negative reviews

---

##  Requirements
Install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk spacy kagglehub
python -m spacy download en_core_web_sm
