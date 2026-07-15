# House Price Prediction using XGBoost

This repository contains a Machine Learning project that predicts house prices using the **Boston House Price Dataset** and an **XGBoost Regressor** model. 

The project includes data preprocessing, exploratory data analysis (correlation heatmaps), model training, evaluation, and visualization of predicted vs. actual prices.

---

## 📊 Dataset

The model is trained on the classic **Boston House Price Dataset**.
* **Features**: 13 numeric/categorical attributes (such as crime rate, number of rooms, pupil-teacher ratio, etc.).
* **Target**: Median value of owner-occupied homes in $1000's (`price`).

---

## ⚙️ Model & Performance

An **XGBoost Regressor** was used to train and evaluate the data. Below are the performance metrics achieved:

* **Training Set**:
  * **$R^2$ Score**: `0.973`
  * **Mean Absolute Error (MAE)**: `1.15`
* **Test Set**:
  * **$R^2$ Score**: `0.912`
  * **Mean Absolute Error (MAE)**: `1.99`

---

## 📁 Repository Structure

* `House_Price_Prediction.ipynb` — The primary Jupyter/Colab notebook containing the code.
* `sample_data/` — Configuration and sample dataset files.
* `README.md` — Project description and setup instructions.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the following libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
