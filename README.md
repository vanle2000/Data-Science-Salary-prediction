# Data Science Salary Prediction

This project aims to predict data science salaries based on various features such as experience level, employment type, employee residence, company location, and more.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)

## Introduction
Predicting data science salaries is a common problem in the job market. This project explores the use of machine learning algorithms to forecast salaries based on factors that influence compensation.

## Dataset
The dataset used for this project includes information about data science job positions and their corresponding salaries. It contains features such as work year, experience level, employment type, job title, employee residence, remote work ratio, company location, and company size.

## Installation
1. Clone this repository to your local machine.

git clone https://github.com/your-username/data-science-salary-prediction.git
cd data-science-salary-prediction


3. Install the required Python packages using pip.

pip install -r requirements.txt


## Usage
1. Ensure you have the dataset (data.csv) in the project directory.

2. Run the main prediction script.

python predict_salary.py

3. The script will train and evaluate both Decision Tree Regressor and Random Forest Regressor models, providing insights into their predictive capabilities.

## Models
### Decision Tree Regressor
The Decision Tree Regressor is a single decision tree-based model designed to predict salaries. It constructs a tree structure where each internal node represents a decision based on a specific feature, leading to a final salary prediction in the leaf nodes.

### Random Forest Regressor
The Random Forest Regressor is an ensemble model consisting of multiple decision trees. It aggregates the predictions from individual trees to arrive at a final prediction. This approach often results in improved accuracy and generalization.

## Evaluation
The performance of the models is evaluated using the Mean Squared Error (MSE) metric on an independent test dataset. Lower MSE values indicate better predictive accuracy.

## Contributing
Contributions to this project are highly encouraged! If you have suggestions for enhancements or new features, please feel free to open an issue or submit a pull request. Your insights and contributions can help advance the project.


---
