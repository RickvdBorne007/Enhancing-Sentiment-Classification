# Enhancing Sentiment Classification Using Engineered Text Features

## Project Overview
This repository contains the code and resources used for the master's thesis titled **"Enhancing Sentiment Classification Using Engineered Text Features: A Case Study on Amazon Food Reviews"**, submitted as part of the Data Science & Society MSc at Tilburg University.

The study investigates whether the integration of sentiment polarity, subjectivity, and structural linguistic features can improve sentiment classification models. Using a comprehensive feature engineering pipeline and multiple machine learning models (Logistic Regression, Random Forest, Gaussian Naive Bayes), the research demonstrates that engineered features significantly enhance classification accuracy.

## Language
- Python 3.9+

## Models and Techniques
- Logistic Regression
- Random Forest
- Gaussian Naive Bayes
- GridSearchCV for hyperparameter tuning
- 5-fold Cross-Validation

## Libraries and Tools
- pandas
- numpy
- scikit-learn
- matplotlib
- textblob

## Dataset
**Amazon Fine Food Reviews**  
- Source: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

## Reproduction
To reproduce the results:
1. Clone this repository
2. Install the requirements via `pip install -r requirements.txt`
3. Run `main.py` to train and evaluate the models

## Author
**Rick van den Borne**  
MSc Data Science & Society, Tilburg University  
GitHub: [RickvdBorne007](https://github.com/RickvdBorne007)

## License
This project is licensed under the terms of the MIT License — see the LICENSE file for details.

