# E-Commerce Customer Spending – Linear Regression

Predicts a customer's **Yearly Amount Spent** from their usage data. The business question: should the company invest more in its **mobile app** or its **website**?

> 📚 **Course project:** completed while following the Udemy course *Python for Data Science and Machine Learning Bootcamp* (Pierian Data). The dataset and task come from the course.

## Data (`Ecommerce Customers`)
Avg. Session Length · Time on App · Time on Website · Length of Membership → target: **Yearly Amount Spent**

## Approach
1. Exploratory analysis with joint plots, pair plots and an `lmplot` of membership length vs. spending
2. Train/test split and **Linear Regression** (scikit-learn)
3. Evaluated with MAE, MSE and RMSE, plus a residual plot
4. Interpreted the coefficients to answer the business question

## Results

| Metric | Value |
|---|---|
| MAE | 7.23 |
| MSE | 79.81 |
| RMSE | 8.93 |

## Tech
Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter

## Run it
```bash
git clone https://github.com/Aniket1103200/Linear-regression-ecommerce-analysis.git
cd Linear-regression-ecommerce-analysis
pip install -r requirements.txt
jupyter notebook ecommerce_linear_regression.ipynb
```
