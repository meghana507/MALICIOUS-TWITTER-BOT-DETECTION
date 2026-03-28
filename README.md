# Malicious Twitter Bot Detection

## 📌 Project Overview
This project detects malicious Twitter bots using Machine Learning techniques. 
The model analyzes user profile data and tweet-related features to classify whether an account is a bot or not.

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📊 Features Used
- followers_count
- friends_count
- listedcount
- favourites_count
- statuses_count
- verified
- bot_word_frequency (engineered feature)
- URL presence (engineered feature)

---

## 🧠 Feature Engineering
- Extracted bot-related word frequency from text
- Created URL detection feature
- Improved model performance using additional features

---

## 🤖 Model Used
- Logistic Regression

---

## 📈 Results
- Accuracy: XX%
- Precision: XX%
- Recall: XX%
- ROC-AUC Score: XX

---

## 📂 Dataset
- Add your dataset here OR provide link

---

## 🚀 How to Run
1. Open the notebook (twitter_bot_detection.ipynb)
2. Install required libraries:
   pip install -r requirements.txt
3. Run all cells
4. Upload dataset when prompted

---

## 📌 Future Improvements
- Try advanced models (Random Forest, XGBoost)
- Improve feature engineering
- Use NLP techniques for better text analysis
