# 🛡️ Cybercrime Detection Agent

An AI-powered Cybercrime Detection Agent that detects phishing emails, spam messages, and fraudulent transaction alerts using Machine Learning and Rule-Based Analysis.

This project was developed as part of an AI course assignment to demonstrate intelligent cybercrime detection through automated message analysis and Gmail monitoring.

---

## 🚀 Features

- Detects phishing and spam emails
- Machine Learning-based text classification (TF-IDF + Logistic Regression)
- Rule-Based phishing detection using keywords and regular expressions
- Gmail inbox monitoring using Gmail API
- Real-time Windows desktop notifications for suspicious emails
- FastAPI backend for message analysis
- Streamlit web dashboard for manual testing
- Displays confidence score and detection reasons

---

## 🛠️ Technologies Used

- Python
- FastAPI
- Streamlit
- Scikit-learn
- Pandas
- Joblib
- Gmail API
- Google OAuth 2.0
- Win11Toast
- Regular Expressions (Regex)

---

## 📂 Project Structure

```
CyberCrimeDetectAI/
│
├── model/
│   ├── classifier.pkl
│   └── vectorizer.pkl
│
├── dashboard.py
├── gmail_monitor.py
├── main.py
├── rules.py
├── test_load.py
├── README.md
└── seen_message_ids.json
```

---

## ⚙️ How It Works

1. Gmail API reads incoming emails.
2. Email subject and body are extracted.
3. Text is sent to the Machine Learning model.
4. The Rule-Based engine checks for:
   - Urgent keywords
   - Suspicious URLs
   - OTP/PIN requests
   - Banking scams
5. Both detection results are combined.
6. If suspicious, a Windows desktop notification is displayed.
7. Users can also manually test messages using the Streamlit dashboard.

---

## 🤖 Machine Learning Model

- Algorithm: Logistic Regression
- Vectorizer: TF-IDF
- Model Storage: Joblib
- Dataset: SMS Spam Collection Dataset
- Accuracy: ~98%

---

## 🔐 Gmail Integration

The project uses the Gmail API with OAuth 2.0 authentication.

The monitor continuously checks the inbox for new emails and analyzes each message automatically.

---

## 📊 Dashboard

The Streamlit dashboard allows users to:

- Paste an email or SMS
- Analyze the message
- View phishing probability
- View rule-based risk score
- See detailed detection reasons

---

## 📸 Project Demonstration

A complete demonstration video of the project is available here:

**Demo Video:** *(Add your Google Drive or YouTube link here)*

Example:

https://drive.google.com/your-demo-link

---

## 📄 Project Report

The complete project report is included in this repository.

---

## 📌 Future Improvements

- Real-time mobile SMS monitoring
- Sender reputation analysis
- Email attachment scanning
- Deep Learning models (BERT)
- Domain reputation checking
- Multi-language phishing detection

---

## 👨‍💻 Author

**Edwin Benny**

B.Tech Computer Science Engineering

AI Course Assignment

---

## 📜 License

This project was developed for educational purposes only.
