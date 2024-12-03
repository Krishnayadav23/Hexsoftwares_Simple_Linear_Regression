# Hexsoftwares_Simple_Linear_Regression
# Simple Linear Regression on Housing Prices

This project demonstrates a simple linear regression model applied to the **Boston Housing Dataset**. The model predicts house prices based on key features such as the number of rooms and percentage of lower-income population.

---

## 📋 **Project Overview**

- **Objective**: Predict housing prices using a simple linear regression model.
- **Dataset**: [Boston Housing Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#boston-house-prices-dataset).
- **Key Features Used**: 
  - **RM**: Average number of rooms per dwelling.
  - **LSTAT**: Percentage of lower-income population.

---

## 🚀 **Project Workflow**

1. **Data Collection**: Loaded the dataset from OpenML.
2. **Data Preprocessing**:
   - Checked for missing values.
   - Normalized the data using `StandardScaler`.
3. **Model Building**: Implemented a linear regression model.
4. **Evaluation**: Assessed performance using Mean Squared Error (MSE) and R² Score.
5. **Visualization**:
   - Correlation heatmap.
   - Residual and scatter plots for model analysis.

---

## 🛠️ **Technologies Used**

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-Learn

---

## 📊 **Results**

- **Mean Squared Error (MSE)**: _[31.243290601783638]_  
- **R² Score**: _[0.5739577415025857]_

---

## 📈 **Visualizations**

- Correlation heatmap of features.
- Actual vs. Predicted prices scatter plot.
- Residual plot for error analysis.

---

## 📝 **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Hexsoftwares_HousingPrices.git
   cd Hexsoftwares_HousingPrices
