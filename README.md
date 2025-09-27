# 🫀 Heart Disease Risk Prediction

## 📌 Description  
### 🔎 Introduction  
The World Health Organization estimates that **12 million deaths occur worldwide every year due to heart diseases**. In the United States and other developed countries, **half of all deaths are due to cardiovascular diseases (CVDs)**.  
Early prognosis of cardiovascular diseases can aid in making lifestyle decisions for high-risk patients and significantly reduce complications.  

This project aims to **identify the most relevant risk factors of heart disease and predict the overall risk** using **machine learning techniques and statistical modeling**.

---

### ❓ Problem  
The dataset comes from the **Framingham Heart Study** on residents of Framingham, Massachusetts.  
The objective is to predict whether a patient has a **10-year risk of future coronary heart disease (CHD)**.  

The dataset contains **4,000+ records** with **15 attributes**.  

---

### 📊 Features  
- **Sex**: male or female (Nominal)  
- **Age**: Age of the patient (Continuous)  
- **Current Smoker**: whether or not the patient is a current smoker (Nominal)  
- **Cigs Per Day**: number of cigarettes smoked per day (Continuous)  
- **BP Meds**: whether or not the patient was on blood pressure medication (Nominal)  
- **Prevalent Stroke**: previous stroke history (Nominal)  
- **Prevalent Hyp**: whether the patient was hypertensive (Nominal)  
- **Diabetes**: diabetes status (Nominal)  
- **Tot Chol**: total cholesterol level (Continuous)  
- **Sys BP**: systolic blood pressure (Continuous)  
- **Dia BP**: diastolic blood pressure (Continuous)  
- **BMI**: Body Mass Index (Continuous)  
- **Heart Rate**: heart rate (Continuous)  
- **Glucose**: glucose level (Continuous)  
- **10-year CHD risk**: binary (1 = Yes, 0 = No)  

---

## 🧠 Machine Learning & Math Perspective  
This project is a **Supervised Machine Learning classification task**, where the goal is to map input features (**X**) to an output label (**y**) that indicates **CHD risk**.  

Mathematically, the task is to approximate a function:  

\[
f: X \to y
\]

Where:  
- \( X = \{x_1, x_2, ..., x_n\} \) are the features (age, BMI, cholesterol, etc.)  
- \( y \in \{0, 1\} \) is the target (no risk / risk)  

We apply algorithms such as **Logistic Regression, Decision Trees, Random Forests, or Gradient Boosting** to estimate the probability:  

\[
P(y = 1 \mid X) = \frac{1}{1 + e^{-(\beta_0 + \beta_1x_1 + \cdots + \beta_nx_n)}}
\]

Performance is measured using metrics like:  
- **Accuracy**  
- **Precision & Recall**  
- **F1-score**  
- **ROC-AUC**  

---

## 🛠️ Tasks  
1. Perform **Exploratory Data Analysis (EDA)**  
2. **Preprocess the data** (encoding categorical features, handling missing values, scaling, etc.)  
3. Identify and explain the **type of ML problem**  
4. **Build and train models** to predict 10-year CHD risk  
5. **Evaluate model performance** using multiple metrics (ROC, Precision, Recall, etc.)  
6. **Perform hyperparameter tuning** for optimization  
7. Document findings in a **report (≤ 5 pages)** including:  
   - Dataset overview  
   - ML algorithms used  
   - Evaluation metrics explained  
   - Results and interpretation  

---

## 👥 Team Members  
- **Yacoba Oduro-Yeboah**  
- **Caleb Fianku Quao**  

---

## 📚 References  
- [Framingham Heart Study Dataset (Kaggle)](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)  
- WHO Reports on Cardiovascular Diseases  

---
