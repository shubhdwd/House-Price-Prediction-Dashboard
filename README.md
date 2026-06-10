# 🏠 Bengaluru House Price Prediction Dashboard

A Machine Learning project that predicts house prices in Bengaluru based on property features such as area type, location, total square feet, number of bathrooms, balconies, and BHK. The project includes data preprocessing, exploratory data analysis (EDA), model comparison, and an interactive GUI built with CustomTkinter.

---

## 🚀 Features

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* 🏗️ Feature Engineering
* 🔄 One-Hot Encoding of Categorical Variables
* 🤖 Comparison of Multiple Machine Learning Models

  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
* 📈 Model Evaluation using R² Score, MAE, RMSE, and MSE
* 💾 Export of the Best Trained Model
* 🖥️ Interactive CustomTkinter Dashboard for Price Prediction

---

## 📂 Project Structure

```text
├── HousePricePrediction.ipynb
├── dashboard.py
├── Bengaluru_House_Data(1).csv
├── Bengaluru_House_Cleaned.csv
├── Bengaluru_House_Encoded.csv
├── House_Price_Prediction_Model.pkl
├── model_columns.pkl
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* CustomTkinter

---

## 📚 Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Data Cleaning
5. Feature Engineering
6. Encode Categorical Variables
7. Correlation Analysis
8. Train-Test Split
9. Train Multiple Regression Models
10. Compare Model Performance
11. Select the Best Model
12. Save the Trained Model
13. Predict House Prices through a GUI Dashboard

---

## 📈 Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

The best-performing model is selected based on evaluation metrics and used for prediction.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/bengaluru-house-price-prediction.git
cd bengaluru-house-price-prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Dashboard

```bash
python dashboard.py
```

---

## 📊 Dataset

The project uses the Bengaluru Housing dataset, which contains information such as:

* Area Type
* Availability
* Location
* Total Square Feet
* BHK
* Bathrooms
* Balconies
* Price

---

## 🎯 Future Improvements

* Hyperparameter tuning for improved accuracy
* Web deployment using Flask or Streamlit
* Interactive map-based location selection
* Advanced feature engineering
* Real-time property data integration

---

## 👨‍💻 Author

**Shubh Dwivedi**

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
