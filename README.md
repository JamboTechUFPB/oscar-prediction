# Best Actress Oscar Prediction: Analyzing the Influence of Other Awards:

## Project Overview

This project aims to explore the relationship between the **Best Actress winner** at the Academy Awards and the influence of other major awards. By analyzing the winners over the last decade, the goal is to uncover patterns and trends that can help predict this year's winner using Machine Learning.

Key objectives:

 - Analyze the last 10 years of Best Actress Oscar winners.
- Examine the influence of other prestigious awards (SAG Awards, Golden Globes, BAFTA, and Critics' Choice Awards).
- Train a Machine Learning (ML) model to predict the winner of this year’s Best Actress at the Oscars.

## Pipeline Diagram

![alt text](image.png)
## Awards Considered

The following major awards were analyzed to evaluate their influence on the Best Actress winner at the Oscars:

- SAG Awards 
- Golden Globes
- BAFTA
- Critics' Choice Awards

# Data Structure

The dataset includes the following columns, which capture key information about each year's nominees and winners:

- ano: Year of the award season
- nome: Name of the actress
- filme: Movie the actress was nominated for
- indicada_sag: Nominated for the SAG Awards (Yes/No)
indicada_gg: Nominated for the Golden Globe Awards (Yes/No)
- indicada_os: Nominated for the Oscar (Yes/No)
- indicada_bafta: Nominated for the BAFTA (Yes/No)
- indicada_cc: Nominated for the Critics' Choice Awards (Yes/No)
- ganhou_sag: Won the SAG Award (Yes/No)
- ganhou_os: Won the Oscar (Yes/No)
- ganhou_bafta: Won the BAFTA (Yes/No)
- ganhou_cc: Won the Critics' Choice Awards (Yes/No)
- ganhou_gg: Won the Golden Globe (Yes/No) [Target Column]

Note: The column ganhou_gg (Won Golden Globe) is the target variable we are predicting.


## Machine Learning Models Used

For the prediction of the Best Actress winner, two machine learning models were employed:

- Random Forest: A robust ensemble learning model for classification tasks.
- Logistic Regression: A simple yet effective model for binary classification, useful for predicting outcomes based on the given features.

## Technologies Used

- Python: For data analysis and model training
- BeautifulSoup: For webscraping
- Pandas: For data manipulation
- Matplotlib/Seaborn: For data visualization
