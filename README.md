# Sales Prediction using Machine Learning

This project uses a dataset containing advertising budgets and sales data to build a predictive model using Linear Regression. The goal is to predict sales based on TV, Radio, and Newspaper advertisement spending.

---

## Dataset

- **Source**: [Kaggle - Advertising.csv](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Columns**:
  - `TV`: Advertising spend on TV (in thousands of dollars)
  - `Radio`: Advertising spend on Radio
  - `Newspaper`: Advertising spend on Newspaper
  - `Sales`: Sales generated (in thousands of units)

---

## Project Steps

1. **Data Loading**: Load the CSV file using Pandas.
2. **Exploratory Data Analysis**:
   - Use `pairplot` to visualize relationships.
   - Use `heatmap` to understand feature correlations.
3. **Data Preprocessing**:
   - Check for missing values.
   - Split the data into features and target.
4. **Model Building**:
   - Train a Linear Regression model using `scikit-learn`.
5. **Evaluation**:
   - Calculate Mean Squared Error (MSE) and R² Score.
   - Visualize actual vs predicted sales using scatter plot.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / VS Code

---

## How to Run

1. Clone this repository or download the notebook and CSV file.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Sales_Prediction_Notebook.ipynb
   ```

---

## Output

### Actual vs Predicted Sales Plot
Below is the visualization showing:
- Pairplot of advertising features and sales
- Correlation heatmap
- Actual vs Predicted Sales scatter plot

![Sales Prediction Output](https://i.postimg.cc/3kyd4N1V/sales-prediction.png)



- **Mean Squared Error**: ~2.4 (example)
- **R² Score**: ~0.89 (example)

---

## Author

**Anusha**  
First-year Computer Science Engineering Student
