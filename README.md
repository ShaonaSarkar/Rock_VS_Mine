# Rock vs Mine Prediction using Logistic Regression  

This project is a **Machine Learning model** that predicts whether an object detected by a sonar signal is a **Rock (R)** or a **Mine (M)**. It is built using **Logistic Regression** and demonstrates how supervised learning can be applied in sonar-based object classification.  

The dataset used is the **Sonar Dataset** from the UCI Machine Learning Repository. It contains 208 samples with 60 numerical features, each representing the strength of a sonar signal at different frequencies. The target variable has two classes: **R (Rock)** and **M (Mine)**.  

---

## 📌 Project Workflow  
1. **Data Preprocessing** – Load the dataset, explore statistics, and separate features & labels.  
2. **Train-Test Split** – Divide the dataset into training and testing sets (90-10 split with stratification).  
3. **Model Training** – Train a Logistic Regression model using Scikit-Learn.  
4. **Evaluation** – Measure accuracy on both training and test data.  
5. **Prediction System** – Input custom sonar readings and classify as **Rock** or **Mine**.  

---

## ✨ Features  
- End-to-end implementation of Logistic Regression.  
- High accuracy on both training and test data.  
- Interactive prediction system for real-time testing.  
- Beginner-friendly ML workflow.  

---

## 🛠️ Technologies Used  
- Python  
- NumPy  
- Pandas  
- Scikit-Learn  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/rock-vs-mine.git
   cd rock-vs-mine
