# NLP Preprocessing and Fake News Detection

📌 ## Objective
The objective of this project is to implement Natural Language Processing (NLP) preprocessing techniques and build a machine learning model to classify news as Fake or Real.

---

##🎯 Learning Outcomes  

Apply NLP preprocessing techniques:
- Tokenization  
- Stopword Removal  
- Stemming  
- Lemmatization  

Implement text vectorization:
- TF-IDF  
- CountVectorizer  

Build machine learning models for text classification  

Evaluate model performance using metrics  

---

##📂 Dataset  
Dataset link :- https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

Dataset used: Fake and Real News Dataset (Kaggle)  

- True.csv → Real News  
- Fake.csv → Fake News  

---

##⚙️ Technologies Used  

- Python  
- NumPy  
- Pandas  
- NLTK  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

##🔄 Workflow  

1. Data Loading  
- Load True.csv and Fake.csv files  
- Combine both datasets  

2. Data Preprocessing  
- Convert text to lowercase  
- Remove special characters  
- Tokenization  
- Stopword removal  
- Stemming (PorterStemmer)  
- Lemmatization (WordNetLemmatizer)  

3. Text Vectorization  
- TF-IDF Vectorizer (used for model training)  
- CountVectorizer (used for comparison)  

4. Model Training  
- Logistic Regression  
- Naive Bayes  
- Support Vector Machine (SVM)  

5. Model Evaluation  
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

6. Visualization  
- Confusion Matrix Heatmap  
- Model Accuracy Comparison Graph  

7. Custom Prediction  
- Predict whether input news is Fake or Real  
- Display prediction with confidence score  

---

##📊 Results  

- Achieved approximately **90–99% accuracy**  
- Best performing models: **SVM and Logistic Regression**  

---

##📁 Project Structure  

├── NLP_Assignment.ipynb
├── True.csv
├── Fake.csv
├── README.md


---

##📌 Conclusion  

This project demonstrates how NLP preprocessing and vectorization techniques can effectively classify news as Fake or Real. The use of TF-IDF and machine learning models significantly improves classification performance.

---

##📜 Undertaking  

We hereby declare that this project is our original work and has been completed as part of the academic requirement. All resources and references have been appropriately acknowledged.

##🔗 GitHub Repository  

👉 https://github.com/Sakshi2004-29/NLP-Preprocessing-and-Text-Classification

