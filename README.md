# Wine Quality Prediction using Linear Regression

This repository contains the Jupyter Notebook code for building a linear regression model to predict wine quality. The model uses various physicochemical features as input to predict the quality of the wine.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Predicting the quality of wine based on physicochemical properties is a challenging yet important problem. In this project, we implement a linear regression model to predict wine quality using a set of input features. Linear regression is a versatile algorithm that establishes a linear relationship between the input features and the target variable.

## Dataset

The dataset used for training and evaluating the model is available in the `data` directory. The dataset contains the following columns:

- `fixed acidity`: The fixed acidity of the wine.
- `volatile acidity`: The volatile acidity of the wine.
- `citric acid`: The citric acid content in the wine.
- `residual sugar`: The amount of residual sugar in the wine.
- `chlorides`: The chloride content in the wine.
- `free sulfur dioxide`: The amount of free sulfur dioxide in the wine.
- `total sulfur dioxide`: The total amount of sulfur dioxide in the wine.
- `density`: The density of the wine.
- `pH`: The pH value of the wine.
- `sulphates`: The sulphates content in the wine.
- `alcohol`: The alcohol content in the wine.
- `quality`: The target variable, i.e., the quality of the wine.

## Requirements

Make sure you have the following dependencies installed before running the Jupyter Notebook:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib

You can install these dependencies using the following command:

```bash
pip install jupyter pandas numpy scikit-learn matplotlib
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/wine-quality-prediction.git
cd wine-quality-prediction
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Wine_Quality_Prediction.ipynb
```

3. Follow the steps outlined in the notebook to load the dataset, preprocess the data, build the linear regression model, train the model, make quality predictions, and evaluate the model's performance.

## Results

After running the Jupyter Notebook, you will have a trained linear regression model that can predict wine quality based on physicochemical features. The notebook will also display and visualize various evaluation metrics to assess the model's predictive accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute the code as per the terms of the license.
