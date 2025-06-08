# 🏡 House Price Prediction with Linear Regression

A hands-on machine learning project to predict house prices based on features like living area, bedrooms, and bathrooms. Built using Python and shared on LinkedIn to showcase my journey in data science and ML 🎯

**🔗 LinkedIn Post**  
[Check out my project announcement and insights](https://www.linkedin.com/posts/sumansekhar-sahoo_machinelearning-python-datascience-activity-7337366989473988608-k2Hp?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFbWbFkBBD_ckmIB0-Z1ZAk25yadMwBisI0)

---

## 📁 Project Structure
├── train.csv                  
├── house\_price\_prediction.py  
├── README.md                  
├── requirements.txt            
└── visuals/                   
└── actual\_vs\_predicted.png



---

## 🚀 Overview

- **Objective**: Predict house sale prices using a Linear Regression model.
- **Dataset**: Kaggle's "House Prices: Advanced Regression Techniques" (`train.csv`).
- **Features Used**:
  - `GrLivArea`: Above grade living area (sq ft)
  - `BedroomAbvGr`: Number of bedrooms
  - `FullBath`: Number of full bathrooms
- **Target**: `SalePrice`

---

## 💡 Key Features

- **Data Cleaning**: Handled missing values with mean imputation.
- **Exploratory Data Analysis (EDA)**: Visualized relationships between features and target.
- **Model Training**: Trained a Linear Regression model using scikit-learn.
- **Evaluation**: Assessed performance using Mean Squared Error (MSE) and R² score.
- **Visualization**: Generated scatter plot comparing actual vs predicted prices for interpretability.

---

## 🛠️ Tech Stack

| Library         | Use Case                         |
|------------------|----------------------------------|
| `pandas`         | Data loading & manipulation      |
| `numpy`          | Numerical operations             |
| `matplotlib`     | Plotting and visualization       |
| `seaborn`        | Statistical visualizations       |
| `scikit-learn`  | Machine learning & evaluation     |

---

## 📥 Getting Started

1. **Clone the repository**  
   
   git clone https://github.com/SumanSekhar-Sahoo/House-Price-Prediction.git
   cd House-Price-Prediction


2. **Install dependencies**

   
   pip install -r requirements.txt
   

3. **Download dataset**

   * Get `train.csv` from Kaggle's [House Prices competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
   * Place it in the repo root directory

4. **Run the script**

   
   python house_price_prediction.py
   

5. **View results**

   * Printed MSE & R² in terminal
   * A scatter plot comparing actual vs predicted prices will be displayed or saved to `visuals/`

---

## 📈 Sample Output


Mean Squared Error: 1.97e+09

R² Score: 0.72

![Figure_1](https://github.com/user-attachments/assets/c6fd081a-094f-4b29-a8ef-ff965dbe85bd)

(Actual values may vary depending on data split)



---

## ✅ Next Steps & Improvements

* Add more advanced features and feature engineering
* Experiment with regularized regression (Ridge, Lasso), tree-based models (Random Forest, XGBoost)
* Deploy model as a web app using Flask, FastAPI, or Streamlit

---

## 📬 Connect & Collaborate

Suman Sekhar Sahoo

* 📘 [LinkedIn Project Announcement](https://www.linkedin.com/posts/sumansekhar-sahoo_machinelearning-python-datascience-activity-7337366989473988608-k2Hp?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFbWbFkBBD_ckmIB0-Z1ZAk25yadMwBisI0)
* 💻 [GitHub Repository](https://github.com/SumanSekhar-Sahoo/House-Price-Prediction)

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more details.



---

