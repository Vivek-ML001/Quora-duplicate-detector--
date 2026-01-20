# Quora Duplicate Question Detector

🔗 **Live App:** [https://quora-duplicate-detector-5.onrender.com/](https://quora-duplicate-detector-5.onrender.com/)

A machine learning powered web application that detects whether two questions are **duplicate / semantically similar** or **different**. Built using **Streamlit** and deployed on **Render**.

---

##  Features

*  Detects semantic similarity between two questions
*  Machine Learning based prediction
*  Web interface using Streamlit
*  Cloud deployment on Render
*  Proper dependency management using `requirements.txt`

---

##  How It Works

1. User enters two questions
2. Text preprocessing is applied:

   * Lowercasing
   * Stopword removal
   * Tokenization
   * Cleaning
3. Feature extraction is performed
4. Similarity distance is calculated
5. ML model predicts:

   * **Duplicate** ✅
   * **Not Duplicate** ❌

---

## Tech Stack

| Layer           | Technology      |
| --------------- | --------------- |
| Frontend        | Streamlit       |
| Backend         | Python          |
| ML Model        | Scikit-learn    |
| NLP             | NLTK / distance |
| Deployment      | Render          |
| Version Control | Git & GitHub    |

---

##  Project Structure

```
quora-duplicate-detector/
│
├── app.py              # Main Streamlit app
├── helper.py           # Helper functions
├── model.pkl           # Trained ML model
├── vectorizer.pkl      # Text vectorizer
├── requirements.txt    # Dependencies
├── README.md           # Project documentation
└── .gitignore
```

---

##  Installation (Local Setup)

```bash
git clone https://github.com/your-username/quora-duplicate-detector.git
cd quora-duplicate-detector
pip install -r requirements.txt
streamlit run app.py
```

---

##  requirements.txt

```
streamlit
scikit-learn
nltk
numpy
pandas
beautifulsoup4
bs4
distance
```

---

##  Deployment

Deployed using **Render Cloud Platform**

Steps:

1. Push project to GitHub
2. Connect GitHub repo to Render
3. Select **Web Service**
4. Add build command:

   ```bash
   pip install -r requirements.txt
   ```
5. Add start command:

   ```bash
   streamlit run app.py
   ```
6. Deploy 🚀

---

## 🧪 Example Use Case

**Input:**
Q1: What is machine learning?
Q2: Explain machine learning.

**Output:**
✅ Duplicate Question
<img width="1870" height="1004" alt="image" src="https://github.com/user-attachments/assets/ae749166-fa0a-4e02-a93c-d6d7be4675ca" />


---

## Disclaimer

This model is trained on limited data and may not be 100% accurate. Predictions should be considered as probabilistic, not absolute.

---

##  Author

**Vivek Kumar**
B.Tech Machine Learning Student
AI/ML Developer

---

##  License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

⭐ If you like this project, give it a star on GitHub 
