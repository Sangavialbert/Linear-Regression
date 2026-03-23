# 📊 Life Expectancy Prediction using Linear Regression

## 📌 Project Overview

This project builds a **Linear Regression model** to predict the life expectancy of countries based on socio-economic and health-related factors. The model uses historical data to understand how different variables impact life expectancy.

---

## 📂 Dataset

* Dataset: *Life Expectancy (WHO)*
* Source: Kaggle
* Features used:

  * Adult Mortality
  * Alcohol Consumption
  * GDP
  * Schooling
  * HIV/AIDS
* Target:

  * Life Expectancy

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🔄 Workflow

### 1. Data Loading

* Dataset is loaded using pandas.

### 2. Data Preprocessing

* Removed missing values using `dropna()`
* Cleaned column names using `str.strip()`

### 3. Feature Selection

* Input features:

  * Adult Mortality
  * Alcohol
  * GDP
  * Schooling
  * HIV/AIDS
* Output:

  * Life Expectancy

### 4. Train-Test Split

* 80% training data
* 20% testing data

### 5. Model Building

* Algorithm: Linear Regression
* Library: Scikit-learn

### 6. Model Evaluation

* Mean Squared Error (MSE)
* R² Score

### 7. Visualization

* Scatter plot of Actual vs Predicted values

---

## 📈 Results

* The model predicts life expectancy with reasonable accuracy.
* Key observations:

  * 📉 Adult Mortality negatively impacts life expectancy
  * 📉 HIV/AIDS reduces life expectancy significantly
  * 📈 Schooling and GDP improve life expectancy

---

## 📊 Sample Output

```
MSE: <value>
R2: <value>
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/life-expectancy-prediction.git
```

2. Navigate to the project folder:

```
cd life-expectancy-prediction
```

3. Install dependencies:

```
pip install pandas numpy matplotlib scikit-learn
```

4. Run the script:

```
python main.py
```

---

## 📌 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Handle missing values using imputation instead of dropping
* Add feature scaling
* Deploy as a web app

---

## 🤝 Contributing

Feel free to fork this repository and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.
