# 💻 Laptop Price Prediction

This project is a Machine Learning-based web application that predicts the price of a laptop based on key specifications such as RAM, RAM type, HDD, operating system, and more. It was developed during my Data Science Internship at **Innomatics Research Labs**.

## 📌 Project Objective

To build an ML-powered interface where users can input laptop features and receive a predicted price instantly. The goal is to simplify buying decisions and offer insights into how specifications affect pricing.

---

## 🎯 Project Highlights

- ✅ Achieved **92% R² score** using Linear Regression for accurate price prediction.
- 📊 Processed and cleaned a dataset of **~1,300 Flipkart laptop listings**.
- 🧠 Performed **10+ feature transformations** and engineered new variables.
- 🌐 Built and deployed an **interactive web app** using Streamlit for real-time predictions.
- 🛠️ End-to-end ML pipeline: Data Cleaning → EDA → Feature Engineering → Model Building → Deployment.

---

## 🚀 Features

- Predict laptop price using a **Linear Regression model**
- Clean and preprocessed real-world Flipkart dataset
- Feature Engineering and EDA performed using `Pandas`, `NumPy`, and `Matplotlib`
- Model building and evaluation using `Scikit-Learn`
- Deployed using `Streamlit` as an interactive web application

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning**  
   - Handled missing values  
   - Removed irrelevant columns

2. **Feature Engineering**  
   - Converted categorical data to numerical (Label Encoding, One-Hot Encoding)  
   - Standardized/normalized data where needed

3. **EDA (Exploratory Data Analysis)**  
   - Analyzed distribution of features  
   - Checked correlations and outliers

4. **Model Building**  
   - Trained a **Linear Regression** model  
   - Evaluated using R² Score, MAE, and MSE

5. **Web App**  
   - Built using `Streamlit`  
   - Easy user interface to input laptop specs and get instant price prediction

---

## 📊 Tech Stack

 - **Python**: Core programming language
 - **Pandas, NumPy**: Data manipulation and preprocessing
 - **Matplotlib, Seaborn**: Visualization and EDA
 - **Scikit-Learn**: Model building and evaluation
 - **Streamlit**: Web app deployment 

---

## 💼 Use Case
- 🛒 Online Retailers – To assist buyers and sellers in setting competitive prices.
- 🧑‍💻 Consumers – To evaluate laptop configurations and make informed buying decisions.
- 📊 Market Analysts – To understand pricing trends based on hardware specifications.

---

## 🖥️ How to Run Locally

```bash
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction
pip install -r requirements.txt
streamlit run app.py
```
---

## 🤝 Acknowledgements

This project was completed as part of a 3-month Data Science Internship at Innomatics Research Labs, where I gained hands-on experience working with real-world datasets and deploying ML solutions.
