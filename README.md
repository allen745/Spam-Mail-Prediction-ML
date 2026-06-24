# 📩 Spam Mail Prediction using Machine Learning

## 📌 Project Overview

This project is a **Spam Mail Detection System** that classifies messages into:

- ✅ Ham Mail (Normal Message)
- 🚨 Spam Mail (Unwanted Message)

The model uses **Machine Learning with Logistic Regression** and Natural Language Processing techniques to identify spam messages.

Project Pipeline:

```
Data Collection
        ↓
Data Preprocessing
        ↓
Text Feature Extraction
        ↓
Train Test Split
        ↓
Logistic Regression Model
        ↓
Model Evaluation
        ↓
Spam Prediction System
```

---

# 🎯 Objective

Build a machine learning model that can automatically detect whether an email/message is:

```
0 → Spam Mail

1 → Ham Mail
```

---

# 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-Learn
- TF-IDF Vectorizer
- Logistic Regression

---

# 📂 Project Structure

```
Spam-Mail-Prediction/

│
├── Spam Mail Prediction.py
│
├── mail_data.csv
│
├── README.md
│
└── requirements.txt

```

---

# 📊 Dataset Information

Dataset contains SMS/email messages with two columns:

| Column | Description |
|-|-|
| Category | Spam or Ham label |
| Message | Email/SMS content |


Dataset Size:

```
5572 Messages
2 Columns
```

---

# 🔎 Data Preprocessing

Steps performed:

### Handling Missing Values

Replaced null values with empty strings.

---

### Label Encoding

Converted categories:

```
Spam → 0

Ham → 1
```

---

# 🧠 Text Feature Extraction

Machine learning models cannot directly understand text.

So text data is converted into numerical vectors using:

## TF-IDF Vectorizer

Features are created based on the importance of words in messages.

---

# 🤖 Machine Learning Model

## Logistic Regression

Used because:

- Binary classification problem
- Fast training
- Good performance for text classification


---

# 🔄 Model Training


Dataset split:

```
Training Data : 80%

Testing Data  : 20%
```


Model:

```
Logistic Regression
```

---

# 📈 Model Performance


## Training Accuracy

```
96.76%
```


## Testing Accuracy

```
96.68%
```

---

# 🚀 Spam Prediction System

The project includes a real-time prediction system.

Example:

Input:

```
Congratulations! You won a free prize. Click now
```

Output:

```
🚨 Spam Mail
```


Input:

```
Are we meeting today at 5 PM?
```

Output:

```
✅ Ham Mail
```

---

# ▶️ How to Run Project


Clone repository:

```bash
git clone <your-repository-link>
```


Install dependencies:

```bash
pip install -r requirements.txt
```


Run:

```bash
python "Spam Mail Prediction.py"
```

---

# 📦 Requirements

```
pandas
numpy
scikit-learn
```

---

# 📌 Machine Learning Workflow

```
Raw Email Data

      ↓

Data Cleaning

      ↓

Label Encoding

      ↓

TF-IDF Feature Extraction

      ↓

Logistic Regression Training

      ↓

Prediction

      ↓

Spam / Ham Classification
```

---

# 👨‍💻 Author

**Allen Christian**

Machine Learning Project 🚀
