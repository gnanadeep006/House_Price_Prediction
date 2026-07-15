This directory includes a few sample datasets to get you started.

*   `california_housing_data*.csv` is California housing data from the 1990 US
    Census; more information is available at:
    https://docs.google.com/document/d/e/2PACX-1vRhYtsvc5eOR2FWNCwaBiKL6suIOrxJig8LcSBbmCbyYsayia_DvPOOBlXZ4CAlQ5nlDD8kTaIDRwrN/pub

*   `mnist_*.csv` is a small sample of the
    [MNIST database](https://en.wikipedia.org/wiki/MNIST_database), which is
    described at: http://yann.lecun.com/exdb/mnist/

*   `anscombe.json` contains a copy of
    [Anscombe's quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet); it
    was originally described in

    Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American
    Statistician. 27 (1): 17-21. JSTOR 2682899.

    and our copy was prepared by the
    [vega_datasets library](https://github.com/altair-viz/vega_datasets/blob/4f67bdaad10f45e3549984e17e1b3088c731503d/vega_datasets/_data/anscombe.json).

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
