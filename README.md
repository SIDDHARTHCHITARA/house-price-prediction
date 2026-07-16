# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques on the California Housing dataset. It covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

The objective is to build a regression model that accurately predicts house prices based on various housing features.

---

## 📂 Dataset

- **Dataset:** California Housing Dataset
- **Source:** Scikit-learn (`fetch_california_housing`)

The dataset contains information such as:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🚀 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. House Price Prediction

---

## 🤖 Model Used

- XGBoost Regressor

---

## 📊 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
## 📈 Results

The XGBoost Regressor achieved strong performance on the California Housing dataset.

**Test Set Performance**
- **R² Score:** 0.8413
- **Mean Absolute Error (MAE):** 0.3075

The model demonstrates good predictive performance for estimating house prices on unseen data.
---

## 📁 Project Structure

```text
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/SIDDHARTHCHITARA/house-price-prediction.git
```

### 2. Navigate to the project folder

```bash
cd house-price-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open **House_Price_Prediction.ipynb** and run all cells.

---
## 📷 Project Output

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

### Actual vs Predicted House Prices

![Prediction Plot](images/prediction_plot.png)

---
## 📈 Future Improvements

- Hyperparameter Tuning
- Model Comparison
- Feature Engineering
- Streamlit Web Application
- Flask/FastAPI Deployment
- Docker Support

---

## 👨‍💻 Author

**Siddharth Chitara**

- B.Tech, Civil Engineering
- Indian Institute of Technology (IIT) Patna

GitHub:
https://github.com/SIDDHARTHCHITARA

---

## ⭐ If you found this project useful, consider giving it a Star.
