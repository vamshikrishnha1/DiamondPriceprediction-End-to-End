
# Diamond Price Prediction
****Project Prediction link**** : http://diamondpriceprediction-env.eba-vm75z7kj.eu-north-1.elasticbeanstalk.com/predict

![Diamond](https://us.123rf.com/450wm/naphotos/naphotos1201/naphotos120100082/11825706-blue-diamond.jpg)


## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Task Performed](#Task-Performed)
- [Methodology](#methodology)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Run Locally](#Run-Locally)
- [Contributing](#contributing)


## Introduction

Diamonds are valued based on several attributes such as carat weight, cut, color, and clarity. This project aims to create a model that predicts diamond prices, allowing sellers and buyers to make informed decisions.

## Dataset

The dataset used for this project is sourced from kaggle.The dataset was preprocessed to handle outliers, missing values, and categorical variables.

There are 10 independent variables (including `id`):
* The goal is to predict `price` of given diamond (Regression Analysis).
* `id` : unique identifier of each diamond
* `carat` : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
* `cut` : Quality of Diamond Cut
* `color` : Color of Diamond
* `clarity` : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
* `depth` : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
* `table` : A diamond's table is the facet which can be seen when the stone is viewed face up.
* `x` : Diamond X dimension
* `y` : Diamond Y dimension
* `x` : Diamond Z dimension

Target variable:
* `price`: Price of the given Diamond.

## Task Performed:
1. Data Cleaning
2. Exploratory Data Analysis
3. Data Preprocessing and feature engineering
4. Model training
5. Pickelizing model
6. Creating flask app for model
7. Deploying it in AWS 

## Methodology

1. **Data Preprocessing:** Cleaning the dataset, handling missing values, and converting categorical variables into numerical representations.

2. **Exploratory Data Analysis (EDA):** Exploring the data to understand distributions, correlations, and potential patterns between diamond features and prices.

3. **Feature Engineering:** Creating new features or transformations that might enhance the predictive power of the model.

4. **Modeling:** Building and training machine learning models to predict diamond prices. Experimenting with regression algorithms such as Linear Regression, Random Forest, and Gradient Boosting.

## Exploratory Data Analysis

During the EDA phase, we conducted various analyses, including:

- Distribution of diamond prices.
- Correlations between diamond attributes and prices.
- Visualization of key features' impact on price.

## Feature Engineering

Based on our EDA, we engineered some additional features such as price per carat, which could potentially provide the model with more relevant information.

## Modeling

We used various regression algorithms to train our model on the dataset. The models were evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score to assess predictive performance.

## Results

Our best-performing model achieved an R-squared score of 93%, indicating its ability to accurately predict diamond prices. The most influential features for price prediction were found to be [list_top_features_here].

## Conclusion

Predicting diamond prices is a complex task due to the interplay of multiple factors. This project demonstrates that machine learning models can provide valuable insights into diamond pricing. However, further refinement and fine-tuning are necessary to achieve even more accurate predictions.


## Run Locally

Clone the project

```bash
  gh repo clone vamshikrishnha1/DiamondPricePrediction
```

Install dependencies

```bash
  pip install -r requirements.txt
```
Training model 

```bash
  python src\pipelines\traning_pipeline.py
```

Start the server

```bash
  python application.py
```


## Tech Stack

**Client:** Flask

**Server:** Python, Machine Learning, Statistics, Oops


## Support

For support, email vamshikrishna.bodige@outlook.com.


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bodige/)




## Authors

- [@VamshiKrishnaBodige](https://github.com/vamshikrishnha1)

