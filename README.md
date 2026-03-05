Simple Linear Regression From Scratch

A Python implementation of Simple Linear Regression built from scratch without using machine learning libraries such as scikit-learn. The project demonstrates how regression models work internally by implementing the mathematical concepts and optimization logic manually.

Linear regression is a fundamental supervised learning algorithm used to model the relationship between a dependent variable and an independent variable by fitting a straight line to the data.

Project Overview

This project implements a Simple Linear Regression model from scratch using Python and NumPy. The objective is to understand how machine learning algorithms work internally instead of relying on high-level libraries.

The model learns the relationship between input features and target values and predicts outcomes using the learned linear equation.

Features

Implementation of Simple Linear Regression from scratch

Uses NumPy for numerical computations

Demonstrates model training and prediction

Helps understand the mathematical foundation of regression

Beginner-friendly machine learning project

Project Structure
simple-linear-regression-from-scratch
│
├── start_01.ipynb        # Jupyter notebook implementation
├── requirements.txt      # Project dependencies
├── dataset.csv           # Sample dataset (if included)
└── README.md             # Project documentation
Installation

Clone the repository:

git clone https://github.com/parthTyagi-tech/simple-linear-regression-from-scratch.git

Navigate into the project folder:

cd simple-linear-regression-from-scratch

Install dependencies:

pip install -r requirements.txt
Usage

Run the notebook or Python script to train the model:

jupyter notebook start_01.ipynb

The notebook demonstrates:

loading the dataset

computing regression parameters

training the model

making predictions

Algorithm Explanation

The regression model follows the equation:

y = β0 + β1x

Where:

x = independent variable

y = predicted value

β0 = intercept

β1 = slope

The algorithm calculates optimal parameters to minimize prediction error and generate accurate predictions.

Technologies Used

Python

NumPy

Jupyter Notebook

Matplotlib (if used for visualization)

Learning Outcomes

Through this project you will learn:

How regression algorithms work internally

Mathematical intuition behind linear models

Model training and prediction without ML libraries

Core machine learning concepts

Author

Parth Tyagi

GitHub:
https://github.com/parthTyagi-tech
