# 🏠 Bangalore House Price Prediction

This project involves predicting flat/apartment prices in Bangalore using real-world housing data. The focus is on building a clean data pipeline and developing a robust regression model for accurate price prediction.

---

## 🔧 Project Workflow

### 1. 📊 Data Preprocessing
- Removed unnecessary columns
- Dropped rows with missing/incomplete data
- Standardized formats in all relevant columns
- Removed outliers that could distort analysis
- Final cleaned DataFrame prepared for modeling

### 2. ⚙️ Feature Engineering
- Converted categorical variables into numerical using **dummy variables**
- Ensured model-ready input format

### 3. 🧠 Model Building
- Split data into training and testing sets
- Applied **Linear Regression** as the primary model
- Compared it with other models — **Linear Regression** gave the best result with **84%+ accuracy**
- Added a random seed to ensure reproducible data shuffling
- Used a low test size to minimize overfitting

### 4. 🗃️ Model Export & Deployment Setup
- Created `.pkl` and `.json` files for saving the model and feature metadata
- Set up a **Flask server** to serve predictions for deployment

---

## 🧰 Tech Stack & Libraries

- **Python**: pandas, numpy, matplotlib, seaborn
- **Scikit-learn**: model training and evaluation
- **Flask**: web server for model deployment

---

## 📁 Folder Structure

```bash
.
├── data/            # Raw and cleaned datasets
├── model/           # Pickle and JSON model files
├── server/          # Flask app files for serving predictions
├── notebooks/       # Jupyter notebooks for EDA and modeling
└── README.md
