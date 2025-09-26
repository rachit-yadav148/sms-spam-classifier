# 📧 SMS / Email Spam Classifier  

A simple **machine learning web app** built with **Streamlit** that classifies text messages (SMS/Email) as **Spam** or **Not Spam**.  

---

## 🚀 Features  
- Preprocesses text using:  
  - Lowercasing  
  - Tokenization (NLTK)  
  - Stopword removal  
  - Stemming (Porter Stemmer)  
- Transforms text using **TF-IDF Vectorization**  
- Classifies using **Multinomial Naive Bayes**  
- Interactive web interface with **Streamlit**  
- Deployable on **Heroku** / **Render** / any cloud  

---

## 🧠 Model  
The model is trained on a labeled dataset of SMS/Email messages using:  
- **Vectorizer:** TF-IDF (`TfidfVectorizer`)  
- **Classifier:** Multinomial Naive Bayes (`MultinomialNB`)  

Both vectorizer and model are stored as pickled files (`vectorizer.pkl`, `model.pkl`).  

---



