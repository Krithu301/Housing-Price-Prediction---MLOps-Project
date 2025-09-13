# 🏠 Housing Price Prediction - ML Ops Project

This project aims to build a regression model that predicts housing prices using machine learning techniques. The project is structured with CI/CD pipelines using GitHub Actions, follows MLOps best practices, and includes environment isolation and automated testing.

## 👩‍💻 Author
- **Name:** Ruby Mythili M  
- **Roll Number:** G24AI1001  
- **Course:** M.Tech in Data Engineering, IIT Jodhpur  

---

## 📁 Project Structure
HousingRegression/
├── data/ # Dataset CSVs
├── utils.py # Custom functions for data loading
├── regression.py # Main ML code for training and testing
├── requirements.txt # Python dependencies
└── .github/
└── workflows/
└── ci.yml # GitHub Actions CI config


---

## 🔧 Tools and Technologies

- Python 3.10
- Pandas, NumPy, Matplotlib, Scikit-learn
- GitHub Actions for CI/CD
- Jupyter Notebook for experimentation
- Conda virtual environment

---

## 📊 Model Overview

The following regression models are used:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Metrics Evaluated:
- Mean Squared Error (MSE)
- R² Score

---

## ⚙️ CI/CD with GitHub Actions

This project uses a CI pipeline to:
- Install dependencies
- Run the regression script
- Ensure all models train successfully without manual effort

✅ Successful CI Runs:  
![CI Success](.github/screenshots/ci-success.png)

---

## 🧪 Setup Instructions

### Step 1: Clone the repo
git clone https://github.com/RubyMythiliM/HousingRegression.git
cd HousingRegression

### Step 2: Create conda environment
conda create --name housing-env python=3.10 -y
conda activate housing-env
pip install -r requirements.txt

### Step 3: Run the script
python regression.py
