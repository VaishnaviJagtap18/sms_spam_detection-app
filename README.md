# SMS Spam Classification App

This project is a machine learning application that classifies SMS messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing techniques.

A trained ML model is deployed using **Streamlit** for interactive prediction.

## 🚀 Live Demo
https://message-spam-detection.streamlit.app/

## Internship Certificate

[📄 View Certificate](file:///C:/Users/Dell/Downloads/VAISHNAVI%20SUHAS%20JAGTAP_certificate-2.pdf)

---
## 📂 Project Structure 

```
sms-spam-app/
│
├── sms_spam_model_training.ipynb   # Model training & preprocessing
├── app.py                          # Streamlit web app
├── sms-spam(in).csv                # Dataset
├── model.pkl                       # Trained ML model
├── vectorizer.pkl                  # Text vectorizer
├── requirements.txt                # Dependencies
└── README.md
```

##  How it Works
1. SMS text is cleaned and preprocessed
2. Text is converted into numerical features using a vectorizer
3. A supervised ML classifier predicts spam or ham
4. The trained model is saved and reused in the web app
---

## 🛠 Tech Stack
- Python
- Scikit-learn
- Streamlit
- NumPy
- NLP (Text Vectorization)
---

##  How to Run Locally
```
pip install -r requirements.txt
streamlit run app.py
```

📌 Future Improvements

```
-Add model evaluation metrics
-Try different ML algorithms
-Improve text preprocessing

```






