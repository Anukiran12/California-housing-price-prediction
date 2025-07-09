#  California Housing Price Prediction

This project applies a **Linear Regression** model to predict median house prices across California using the [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html). It is designed as a foundational machine learning project for aspiring data analysts or data scientists.


##  Project Objectives

- Understand and explore a real-world regression dataset
- Perform exploratory data analysis (EDA) and feature interpretation
- Train a Linear Regression model using scikit-learn
- Evaluate model performance with R², MAE, and MSE
- Interpret feature impacts on housing prices

##  Key Steps & Workflow

1. **Data Loading and Exploration**
   - Loaded dataset via `scikit-learn.datasets`
   - Explored distributions using histograms and `.describe()`

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature correlations using a heatmap
   - Identified high-impact features like `MedInc`, `Latitude`, `Longitude`

3. **Data Preprocessing**
   - Handled missing values (none present)
   - Performed train-test split using `train_test_split`

4. **Model Training**
   - Trained a Linear Regression model on the training set
   - Printed model coefficients for interpretation

5. **Model Evaluation**
   - Used Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score
   - Achieved R² ≈ 0.57 on the test set

6. **Conclusion**
   - Interpreted model results
   - Outlined potential improvements (e.g., trying other models like Random Forest)

##  Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook


##  Results Summary

- **R² Score:** ~0.57
- **MAE:** ~0.53
- **Most impactful feature:** `MedInc` (Median Income)


## What I Learned

- How to structure and complete an end-to-end ML project
- How to evaluate and interpret a regression model
- Importance of feature relationships (correlation & multicollinearity)
- Basics of model deployment and presentation

##  Project Structure

```bash
california-housing-price-prediction/
│
├── california_housing.ipynb       # Main Jupyter Notebook
├── House_Price_Prediction.html    # HTML export (optional)
└── README.md                      # This file

