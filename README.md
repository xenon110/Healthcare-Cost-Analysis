# 🏥 Medical Cost Personal Dataset - Kaggle Project

![Kaggle](https://img.shields.io/badge/Kaggle-Medical%20Cost-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Predicting **medical insurance costs** based on personal attributes using machine learning models. This project follows **data preprocessing, exploratory analysis, feature engineering, model building, and evaluation** to achieve the best predictive performance.

---

## 📖 Project Overview

The **Medical Cost Personal Dataset Analysis** project aims to predict **medical insurance charges** based on factors like age, BMI, smoking habits, and more. By using **machine learning models**, we can identify key factors affecting insurance costs and help insurers build better pricing strategies.

### **Workflow:**
- Data Cleaning & Preprocessing 🧹
- Exploratory Data Analysis (EDA) 📊
- Feature Engineering 🛠
- Model Building & Evaluation 🤖

---

## 📂 Dataset Information

The dataset is provided by **Kaggle**:  
🔗 [Medical Cost Personal Dataset](https://www.kaggle.com/datasets)

### **Features:**
| Feature   | Description |
|-----------|------------|
| `age` | Age of the individual |
| `sex` | Gender (`male` / `female`) |
| `bmi` | Body Mass Index (BMI) |
| `children` | Number of children covered by health insurance |
| `smoker` | Smoking status (`yes` / `no`) |
| `region` | Residential area (`northeast`, `northwest`, `southeast`, `southwest`) |
| `charges` | Medical insurance cost (Target Variable) |

---

## 🛠 Installation & Setup

1️⃣ **Clone the repository**  
```sh
git clone https://github.com/your-username/Medical-Cost-Prediction.git
cd Medical-Cost-Prediction
```

2️⃣ **Install required dependencies**  
```sh
pip install -r requirements.txt
```

3️⃣ **Run the Jupyter Notebook**  
```sh
jupyter notebook medical-cost-personal-datasets.ipynb
```

---

## 🔍 Data Analysis & Processing

1. **Exploratory Data Analysis (EDA):**
   - Visualizing distributions of insurance charges
   - Identifying correlations between features
   - Checking for missing values and outliers
2. **Feature Engineering:**
   - Encoding categorical variables (e.g., `sex`, `smoker`, `region`)
   - Creating BMI categories
   - Handling outliers (if any)
3. **Splitting Data:**
   - Train-Test split (80%-20%)

---

## 🤖 Machine Learning Models Used

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**

📈 **Model Evaluation Metrics:**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score (R²)

---

## 🚀 Results & Insights

- **Smoking** has the highest impact on medical charges.
- **BMI** and **age** are strong predictors of medical costs.
- **Random Forest & XGBoost** gave the best performance with **lowest errors and highest accuracy**.

---

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets)
- Machine Learning Algorithms Documentation

---

## 🤝 Contributions

Feel free to **fork** this repository, improve the model, or try new techniques! Pull requests are welcome. 🚀

