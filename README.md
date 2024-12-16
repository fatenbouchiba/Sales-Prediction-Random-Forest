# Sales Prediction using Random Forest

This project demonstrates how to use **Random Forest** machine learning algorithm to predict sales based on advertising expenditures in three different media channels: TV, Radio, and Newspaper.

The dataset used in this project contains information about the advertising budget and the corresponding sales figures, and the goal is to predict sales based on the given advertising budget.

## Dataset

The dataset used in this project is the **Advertising.csv** dataset, which can be downloaded from [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv). 

### Features:
- **TV**: Advertising budget spent on TV (in thousands of dollars)
- **Radio**: Advertising budget spent on Radio (in thousands of dollars)
- **Newspaper**: Advertising budget spent on Newspaper (in thousands of dollars)
- **Sales**: Actual sales figures (in thousands of units sold)

## Models Used
This project uses the **Random Forest Regressor** algorithm to predict sales based on the advertising budget in TV, Radio, and Newspaper. The model is trained and evaluated, and its performance is assessed using various metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Project Structure

Sales-Prediction-Random-Forest/ 
├── data/ 
│ └── Advertising.csv # The dataset used for training the model
├── notebooks/
│ └── sales_prediction.ipynb # Jupyter notebook with the code for training, evaluation, and visualization
├── images/
├── README.md # Project description 
└── .gitignore # File to exclude unnecessary files from version control
### Requirements

You need the following Python libraries to run this project:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
