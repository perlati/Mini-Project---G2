# Mini-Project---G2

# Sales Prediction Using Machine Learning

This project implements a sales prediction model using Python. It demonstrates practical AI and data science concepts such as data preprocessing, visualization, model training, and evaluation. The goal is to predict sales based on input features using a regression approach.

## Features

- **Data processing** with `pandas` and `numpy`  
- **Data visualization** using `matplotlib` and `seaborn`  
- **Feature scaling** and **missing value imputation** with `StandardScaler` and `SimpleImputer`  
- **Machine learning model** using `LinearRegression` from scikit-learn  
- **Model evaluation** using R² score (`r2_score`)  
- **Train/test split** to assess model generalization  

## Requirements

Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Open `sales_g2.ipynb` in **Visual Studio** or **Jupyter Notebook**.  
2. Execute the notebook cells in order.  
3. The notebook will:
   - Load and clean the dataset  
   - Visualize data distributions and correlations  
   - Split the data into training and testing sets  
   - Train a linear regression model  
   - Evaluate performance using the R² metric  
   - Display plots showing predicted vs actual sales  

## Project Structure

```
sales_g2.ipynb       # Main notebook containing all code and output
data/                # (Optional) Folder for CSV data files if external input is used
models/              # (Optional) Saved model outputs
```

## Example Output

- Correlation heatmap of numerical features  
- Scatter plot of predicted vs actual sales  
- R² score printed as model accuracy  

## Concepts Demonstrated

- Data preprocessing  
- Linear regression model training  
- Evaluation and visualization of model results  
- Use of Python ML libraries for automation and insight  

