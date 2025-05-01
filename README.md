
# 📩 SMS Spam Detection App

A web-based application built using **Streamlit** and **Machine Learning** to detect whether an SMS message is **Spam** or **Not Spam**. The model uses NLP techniques with **NLTK** for text preprocessing and a trained ML classifier for prediction.

---

## 🚀 Features

- User-friendly interface built with **Streamlit**
- Real-time SMS classification
- Text preprocessing using:
  - Lowercasing
  - Tokenization
  - Stopword removal
  - Stemming
- Machine Learning model trained on a labeled SMS dataset
- Visual output: "Spam" or "Not Spam"

---

## 🧠 Tech Stack

- **Python 3.x**
- **Streamlit**
- **NLTK**
- **Scikit-learn**
- **Pickle** (for saving vectorizer and model)

---

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/sms-spam-detection.git
cd sms-spam-detection
```

2. Install the dependencies:

```bash
pip install streamlit nltk scikit-learn
```

3. Download NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

4. Make sure `vectorizer.pkl` and `model.pkl` are in the project directory.

---

## ▶️ Running the App

```bash
streamlit run app.py
```

Replace `app.py` with your actual Python filename if it's different.

---

## 📂 Files

- `app.py`: Main Streamlit app
- `vectorizer.pkl`: Trained TF-IDF vectorizer
- `model.pkl`: Trained ML model (e.g., Naive Bayes)
- `README.md`: Project documentation

---

## 📊 Model Training (Not included in this repo)

The model was trained using a labeled dataset of SMS messages, with preprocessing and feature extraction done using TF-IDF. The final classifier was saved using `pickle`.

---

## 🙋‍♂️ Author

**Aromal**  
*Feel free to connect or contribute!*
