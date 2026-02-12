# Simple Linear Regression — Hours Studied vs Marks

## 📌 Project Overview
This project demonstrates an end-to-end implementation of Simple Linear Regression using Python and scikit-learn. The goal is to analyze the relationship between the number of hours studied and the marks obtained by students, and build a model capable of predicting marks based on study hours.

## 📊 Problem Statement
We want to predict student marks using a single feature:
- **Independent Variable (X):** Hours Studied
- **Dependent Variable (Y):** Marks Obtained

The model learns the relationship between these variables and predicts marks for unseen data.

## 🧮 Mathematical Concept
Simple Linear Regression follows the equation:

```
y = mx + b
```

Where:
- **y** → Predicted Marks
- **x** → Hours Studied
- **m** → Slope (Regression Coefficient)
- **b** → Intercept (Bias Term)

## 📂 Dataset
The dataset contains 30 observations showing how study time impacts marks.

**Dataset Columns:**
- Hours_Studied
- Marks

## ⚙️ Workflow
1. **Data Loading & Exploration**
    - Load dataset using pandas
    - Inspect structure and data types
2. **Data Preparation**
    - Separate features (X) and target variable (Y)
3. **Train-Test Split**
    - 80% Training Data
    - 20% Testing Data
4. **Model Training**
    - Train model using LinearRegression from scikit-learn
5. **Prediction**
    - Predict marks using test data
6. **Visualization**
    - Compare actual vs predicted values using scatter plots
7. **Model Evaluation**
    - Evaluate model performance using:
        - MAE (Mean Absolute Error)
        - MSE (Mean Squared Error)
        - RMSE (Root Mean Squared Error)
        - R² Score (Coefficient of Determination)

## 📈 Visualization Output
The model generates a scatter plot comparing:
- Actual marks
- Predicted marks

This helps visually understand model performance.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 🚀 How To Run
**Step 1: Clone Repository**

**Step 2: Install Dependencies**

pip install pandas numpy scikit-learn matplotlib


**Step 3: Run Notebook**

Open the notebook file and run all cells.

## 📁 Project Structure
```
.
├── data.csv
├── simple_linear_regression.ipynb
└── README.md
```

## 📌 Key Learning Outcomes
- Understanding regression fundamentals
- Implementing train-test split correctly
- Evaluating regression models using multiple metrics
- Visualizing regression performance properly

## 🔮 Future Improvements
- Add cross-validation
- Compare with other regression models
- Introduce noisy or real-world datasets
- Deploy model using Flask or Streamlit

## 📜 License
This project is created for educational and learning purposes. Feel free to use and modify.
