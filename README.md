# ✈️ Travel Package Purchase Prediction

This project applies classification modeling and data analysis to help the tourism company **"Visit With Us"** identify potential customers for a newly introduced **Wellness Travel Package**. By predicting likely buyers before contact, the company can improve marketing efficiency, reduce wasted efforts, and better tailor travel offerings to customer profiles.

---

## 🧠 Context

"Visit With Us" offers five travel packages (Basic, Standard, Deluxe, Super Deluxe, King). However, only 18% of past customers purchased any package, and marketing was done randomly, without insights from existing data. The company is now launching a **Wellness Tourism Package** aimed at travelers looking for health and lifestyle enhancement.

To support this, the goal is to use last year's customer data to:
- **Predict which customers are likely to purchase**
- **Improve marketing strategies**
- **Tailor offerings based on customer demographics and behavior**

---

## 🎯 Objective

To build a classification model that can:
- Predict whether a customer will buy the new package
- Inform business decisions and marketing strategies
- Support policy makers in targeting efforts

---

## 📊 Key Insights & Conclusions

- ✅ **SVM with RBF kernel outperformed all other models**, achieving a **recall score of 0.69**, making it ideal for catching the most potential buyers.
- 🔑 **Passport holders are more likely to buy travel packages** — the company should design international packages to target them.
- 🧑‍💼 Customers in **high-income roles like AVP/VP are less likely to buy**; instead, tailor premium short-term packages for them.
- 🌆 Customers from **Tier 2 cities are underrepresented** — marketing should be expanded there.
- 📞 Customers who were **followed up more often were more likely to convert** — follow-up frequency is a key factor.
- 💰 **Match packages to customer income** — avoid offering luxury packages to low-income clients.
- 👥 **Younger and single customers** are more likely to buy — create incentives to attract couples, families, and older customers.

---

## 🧪 Methods Used

- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- Classification Models:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - **Support Vector Machine (SVM with RBF kernel)** ✅ Best Model
- Confusion Matrix, Precision, Recall, F1-score
- Feature Importance Analysis

---

## 🧭 Data Ethics & Considerations

- The model was designed to **maximize recall**, ensuring we identify as many true buyers as possible.
- **Customer data was anonymized** and used strictly for modeling and strategic purposes.
- Recommendations are tailored to income and behavior data to avoid mis-targeting or over-promising.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib, Seaborn
- Jupyter Notebook

---


## 📎 Notebook

View the full notebook for detailed EDA, modeling, and conclusions:  
[`Travel-Package-Purchase-Prediction.ipynb`](Travel-Package-Purchase-Prediction.ipynb)

---

## 💡 Future Improvements

- Perform hyperparameter tuning on SVM for even better recall
- Explore ensemble methods and boosting algorithms
- Build a scoring system to rank customers based on purchase probability
- Include additional behavioral features (website visits, call times)

---

*Project by [Your Name] — Data Science Portfolio*

