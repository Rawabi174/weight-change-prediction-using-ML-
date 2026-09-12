# Weight Change Prediction Model

A machine learning project that predicts individual weight change using lifestyle and physiological data collected from 103 participants. The notebook can be opened and run directly in **Google Colab** or **Jupyter Notebook**.

## Overview

This study aims to build a machine learning model capable of predicting weight change based on real participant data. The project focuses on:

- Building and evaluating a **regression model** that predicts the exact numerical value of weight change.
- Identifying the **most influential factors** affecting weight change, in order to guide and optimize weight management strategies.
- Improving the overall understanding of weight gain/loss dynamics to increase the precision of future predictions.

## Problem Statement

The goal of this project is to develop a machine learning model to predict weight changes based on individual lifestyle and physiological factors. Using data collected from 103 participants, the model analyzes the impact of variables such as:

- Stress levels
- Daily caloric intake
- Sleep patterns
- Exercise habits
- Basal Metabolic Rate (BMR)

This predictive tool aims to provide actionable insights that help individuals better understand and manage weight fluctuations.

## Dataset

- **Participants:** 103 individuals
- **Features:** Stress level, daily caloric intake, sleep patterns, exercise habits, BMR, and other lifestyle-related variables
- **Target variable:** Weight change (numerical, predicted via regression)

## How to Run

### Option 1: Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook file (`.ipynb`) via `File > Upload notebook`.
3. Run the cells in order from top to bottom.

### Option 2: Jupyter Notebook
1. Make sure you have Python and Jupyter installed.
2. Install the required dependencies (see below).
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook
   ```
4. Run the cells in order.

## Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

*(Update this list based on the actual libraries used in the notebook.)*

## Methodology

1. **Data preprocessing** – cleaning and preparing the participant dataset.
2. **Exploratory data analysis (EDA)** – understanding relationships between lifestyle factors and weight change.
3. **Model building** – training regression models to predict weight change.
4. **Model evaluation** – assessing model performance using standard regression metrics.
5. **Feature importance analysis** – identifying which factors most strongly influence weight change.

## Results

Two regression models were trained and compared:

- **Random Forest Regressor** achieved the best performance, with an accuracy of **92%**, indicating strong predictive power that generalizes well to the data.
- **Linear Regression** achieved poor performance, suggesting that a linear model is not well-suited to capture the relationships within this dataset.

Based on these results, the **Random Forest Regressor** is recommended as the primary model for predicting weight change.

## Future Work

- Expand the dataset with more participants for better generalization.
- Test additional regression algorithms and ensemble methods.
- Explore feature engineering to improve prediction accuracy.

## Author

*Rawabi Alhulaybi*
