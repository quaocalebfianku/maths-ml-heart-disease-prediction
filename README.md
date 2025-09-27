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

---

## 📊 Dataset
- Source: [Framingham Heart Study Dataset (Kaggle)](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)  
- Records: ~4,000 patients  
- Features: 15 attributes including **age, BMI, cholesterol, blood pressure, smoking status, diabetes, glucose levels**  
- Target: `10-year risk of coronary heart disease (CHD)` (binary: 1 = Yes, 0 = No)  

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

3. ## 🛠️ Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Feature distributions  
   - Correlation analysis  
   - Visualization of key trends  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - ROC-AUC  

---

## 🧰 Tech Stack
- **Python**  
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`, `Jupyter Notebook`

---

## 🚀 Results
- Built models to predict **10-year CHD risk** with solid performance.  
- Identified key predictors such as **age, smoking status, blood pressure, cholesterol, and diabetes**.  
- Showcased how **mathematical concepts in ML** translate into practical healthcare applications.  

---

## 📚 References  
- [Framingham Heart Study Dataset (Kaggle)](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)  
- WHO Reports on Cardiovascular Diseases  

---
