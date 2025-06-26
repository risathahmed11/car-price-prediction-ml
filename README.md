# car-price-prediction-ml
A supervised machine learning project predicting car prices using regression models.

# car-price-prediction-ml

A supervised machine learning project to predict car prices using regression algorithms in Python, developed as part of the CMP6202 module on Artificial Intelligence and Machine Learning.

---

##  Problem Statement

Accurately estimating car prices is a significant challenge in the automotive industry due to variables such as mileage, fuel type, brand, and age. This project addresses the problem by applying supervised machine learning techniques to predict car prices based on real-world data.

---

## Solution Overview

This project explores the effectiveness of regression models for price prediction. Using data preprocessing, feature engineering, and model evaluation, I trained and tested machine learning algorithms to build a predictive model.

---

##  Project Structure

car-price-prediction-ml/
├── data/
│ └── car_price_prediction.csv
├── notebooks/
│ └── car_Prediction.ipynb
├── reports/
│ └── Car Price Prediction Report.pdf
├── README.md
└── LICENSE


---

## Technologies & Tools

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**: 
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – visualization  
  - `scikit-learn` – regression models, preprocessing, metrics
- **Models**: 
  - Linear Regression  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
- **Evaluation Metrics**: RMSE, MAE, R² Score

---

## Results

- Achieved **71%** grade in the academic evaluation.
- Gradient Boosting produced the most accurate price predictions.
- Identified top predictive features: `year`, `mileage`, `engineSize`, and `brand`.

---

##  How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/risathahmed11/car-price-prediction-ml.git
   cd car-price-prediction-ml


Open the Jupyter Notebook:
1. jupyter notebook notebooks/car_Prediction.ipynb
Make sure dependencies are installed:
pip install -r requirements.txt  # (Create this if needed)


What I Learned
Hands-on application of regression techniques.

Practical use of real-world datasets.

Feature correlation analysis and model evaluation.

Building end-to-end machine learning pipelines.

Keywords
Machine Learning, Car Price Prediction, Regression, Python, Scikit-learn, Jupyter Notebook, Supervised Learning, AI, Automotive Data

License
This project is licensed under the MIT License.
