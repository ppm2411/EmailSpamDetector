# EmailSpamDetector

This project builds a machine learning-based email spam classifier that automatically detects whether an incoming message is spam or not. The system uses natural language processing techniques and classification algorithms to distinguish between spam and ham (legitimate) emails.

## 🧠 Model Performance

## 📊 Confusion Matrix

|                        | Predicted: Ham (0)     | Predicted: Spam (1)     |
|------------------------|------------------------|--------------------------|
| Actual: Ham (0)        | True Negatives (TN): 800 | False Positives (FP): 96 |
| Actual: Spam (1)       | False Negatives (FN): 17 | True Positives (TP): 121 |

### ✅ Interpretation

- **800** ham emails were correctly predicted as ham.
- **96** ham emails were incorrectly predicted as spam.
- **121** spam emails were correctly predicted as spam.
- **17** spam emails were incorrectly predicted as ham.

> Overall Accuracy: **89.07%**  
> Precision: **55.76%**

## 🔍 Key Features

- Email content preprocessing using NLP techniques
- Feature extraction with **TF-IDF vectorization**
- Model training using **Logistic Regression**
- Evaluation using confusion matrix, precision, and accuracy

## 🛠️ Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK / spaCy (for optional preprocessing)
- Jupyter Notebook

## 📁 Use Cases

- Email service providers
- Anti-spam modules in messaging apps
- Inbox management automation
