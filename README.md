# Customer Response Prediction for Marketing Campaigns

## 📌 Project Overview
This project analyzes customer data from a marketing campaign with the goal of identifying behavioral patterns and predicting whether a customer will respond positively to a campaign.

The analysis combines exploratory data analysis (EDA) with a machine learning classification model to support data-driven decision-making in marketing strategies.

---

## 📊 Dataset
The dataset contains demographic, behavioral, and purchasing information for customers, including:
- Income and age
- Household composition
- Purchase behavior across different channels
- Historical campaign responses

---

## 🔍 Exploratory Data Analysis
The EDA process includes:
- Data inspection and cleaning (missing values, duplicates, irrelevant columns)
- Feature engineering (e.g. age and total spending)
- Visual analysis of spending patterns and customer behavior
- Comparative analysis between customers who responded and those who did not

---

## 🤖 Machine Learning Model
- **Problem type:** Binary classification
- **Target variable:** `Response`
- **Model used:** Logistic Regression
- **Preprocessing:** Standard scaling and train-test split
- **Evaluation metrics:** Precision, recall, F1-score, and confusion matrix

The model was chosen for its interpretability and suitability for binary classification problems in a business context.

---

## 📈 Key Findings
- Customers with higher income and total spending tend to show a higher probability of responding to marketing campaigns.
- Purchase frequency and channel usage also play an important role in customer response.
- The model provides a practical way to segment customers based on their likelihood of response.

---

## 🚀 Potential Business Application
This model can be used to:
- Prioritize customers with higher response probability
- Optimize marketing campaign targeting
- Reduce operational costs by focusing on high-potential segments
- Support personalized marketing strategies

---

## ⚠️ Limitations and Future Work
- The dataset presents class imbalance, which may affect prediction performance.
- More advanced models or resampling techniques could improve results.
- Additional behavioral or temporal features could enhance predictive power.

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## 👤 Author
Adrián Leandro Vega
