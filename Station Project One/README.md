# Future Sales Prediction 🏷️

## Overview 🧾
Predict sales based on advertising costs using machine learning.

## Jupyter Notebook

You can view and interact with the Jupyter Notebook directly on GitHub without any installation.
[Click here](https://github.com/RozaKerobyan/Tumo-Labs-ML/blob/labs/Station%20Project%20One/future_sales_prediction.ipynb) to access it.

## **Installation & Setup**

If you want to install it, follow these steps to set up your environment and run the project.

### 1. Clone the Repository
Clone the repository to your local machine using the following command:

``` bash
git clone git@github.com:RozaKerobyan/Tumo-Labs-ML.git
```
### 2. Open `Station Station One` directory

```bash
cd Station Project One
```

### 3. Install packages 
```bash
pip install -r requirements.txt
```

### 4. Run the Project

Once the dependencies are installed, you can run the project using Jupyter Notebook. Run the following command:

``` bash
jupyter notebook
```

- This will open the Jupyter Notebook in your browser. Open the .ipynb file and run the code cells to see the results.

## Features:
- TV: Advertising cost on TV
- Radio: Advertising cost on Radio
- Newspaper: Advertising cost on Newspaper
- Sales: Units sold (target variable)

## Model:
- Linear Regression
- Training Accuracy: 0.90
- Test Accuracy (R²): 0.91
- Mean Squared Error (MSE): 2.91
- R² Score: 0.91

## Scatter Plot
This scatter plot visualizes the relationship between TV advertising costs and units sold.

![Scatter Plot](https://github.com/RozaKerobyan/Tumo-Labs-ML/blob/labs/Station%20Project%20One/scatter_plot.png)

## Pie Chart
This pie chart illustrates the distribution of advertising costs across different media.

![Pie Chart](https://github.com/RozaKerobyan/Tumo-Labs-ML/blob/labs/Station%20Project%20One/pie_chart.png)

## Summary

This project demonstrates how to predict future sales using machine learning techniques, including data preprocessing, model training, and evaluation. By following the instructions above, you can run the code both with and without Jupyter Notebook. The model's performance is evaluated with metrics such as Mean Squared Error (MSE) and R² score.
