# 🏠 Bangalore House Price Prediction


## 📜 Certification

I have successfully completed a **Udemy course** covering:

- Probability & Statistics
- Basic Python Programming
- Linear & Logistic Regression
- Cluster Analysis
- Deep Neural Networks
- Real-world Case Studies

📎 *Certificate of completion is attached below.*

---

## 💡 Project Overview: *"Prediction of Flat Prices in Bangalore"*

This project focuses on predicting flat/apartment prices in Bangalore using various **data preprocessing**, **feature engineering**, and **machine learning** techniques.

---

## 🧹 Data Preprocessing

Key steps in preparing the data:

- ✅ Removed unnecessary columns
- ✅ Dropped rows with missing/incomplete data
- ✅ Standardized column formats
- ✅ Removed **outliers** to improve model performance

The result: A clean and ready-to-model DataFrame.

---

## ⚙️ Feature Engineering

- Converted categorical (string) variables to numerical format using **dummy variables**.
- Handled numerical scaling implicitly via regression modeling.

---

## 🧠 Model Training

- Dataset split into **training** and **testing** sets.
- Applied **Linear Regression** as the baseline model.
- Compared performance with other models.
- Achieved **84%+ accuracy** using Linear Regression.
- Added **random constant (seed)** to maintain consistent shuffling of data.
- Chose a **low test size** to avoid overfitting.
  - (Note: Overfitting typically handled by monitoring validation loss — not used here.)

---

## 🗃️ Deployment Prep

- Created `.pkl` (pickle) and `.json` files for the model and feature inputs.
- Set up a **basic Flask server** to prepare the project for deployment.

---

## 📁 Project Structure

```bash
.
├── data/                     # Raw and cleaned dataset
├── model/                    # Saved .pkl and .json files
├── server/                   # Flask server files for deployment
├── notebooks/                # Jupyter notebooks for EDA and modeling
├── certificate/              # Udemy course certificate
└── README.md                 # Project documentation
