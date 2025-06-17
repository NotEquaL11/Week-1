# Week-1
# 💧 Water Quality Prediction Using Machine Learning

This project uses supervised machine learning to predict the quality of water based on various physicochemical properties.

## 🚀 Overview

- Predicts whether a water sample is **safe** or **unsafe** for drinking.
- Uses features like pH, turbidity, conductivity, chlorides, etc.
- Built using Python, Scikit-learn, Pandas, and optionally deployed with Streamlit.

## 🧠 Models Used

- Logistic Regression
- Random Forest
- XGBoost
- SVM

## 📊 Dataset

- Source: UCI or Kaggle
- Format: `.csv` with labeled water samples

## 🛠️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/NotEquaL11/water-quality-prediction.git
cd water-quality-prediction

# 2. Install requirements
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook notebooks/Water_Quality_Analysis.ipynb

# 4. (Optional) Launch the Streamlit app
streamlit run app/streamlit_app.py

