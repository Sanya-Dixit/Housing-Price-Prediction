# 🏠 California Housing Price Prediction using Linear Regression

This project uses **Linear Regression** to predict median housing prices in California based on features like location, income, population, and more. It's built using Python and Jupyter Notebook, with data sourced from the [California Housing Dataset](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html).

---

## 📊 Project Overview

- 📁 **Dataset:** `housing.csv`
- 🧠 **Model Used:** Linear Regression
- 📈 **Target Variable:** `median_house_value`
- 🔍 **Goal:** Predict housing prices using features such as:
  - Median income
  - House age
  - Rooms and bedrooms per household
  - Latitude and longitude
  - Population, etc.

---

## 🛠️ Tech Stack

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Matplotlib & Seaborn** – for data visualization
- **Scikit-learn** – for model building and evaluation

---

## 📁 Project Structure

📦 california-housing-price-prediction/
├── California Housing price - Linear regression txclass.ipynb # Jupyter notebook with full analysis
├── housing.csv # Dataset used for training/testing
└── README.md # Project documentation

---

## 📌 Key Steps

1. **Load and explore the data**
2. **Visualize correlations between features**
3. **Preprocess the data** (handling nulls, feature scaling, encoding)
4. **Train/Test split**
5. **Train a Linear Regression model**
6. **Evaluate model performance** using:
   - Mean Squared Error (MSE)
   - R² Score
7. **Visualize predictions vs actual values**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/california-housing-price-prediction.git
cd california-housing-price-prediction
```

2. Install Required Libraries
```bash
You can use the following requirements.txt:
pandas
numpy
matplotlib
seaborn
scikit-learn
```
Install them with:
```bash
pip install -r requirements.txt
```
3. Run the Notebook
 
Open Jupyter Notebook and run:
```bash
jupyter notebook "California Housing price - Linear regression txclass.ipynb"
```


📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
Scikit-learn Documentation

UCI Machine Learning Repository – California Housing

---
