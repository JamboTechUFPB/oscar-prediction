# Best Actress Oscar Prediction: Analyzing the Influence of Other Awards

## Project Overview

This project explores the relationship between the **Best Actress winner** at the Academy Awards (Oscar) and the influence of other major awards. By analyzing the winners over the last decade (2014-2023), the goal is to uncover patterns and trends that can help predict this year's winner using Machine Learning. 

### Key Objectives

- Analyze the last 10 years of Best Actress Oscar winners historical.
- Examine the influence of other prestigious awards.
- Train a Logistic Regression Machine Learning (ML) model to predict this year’s Best Actress at the Oscars.

## Pipeline Diagram

![alt text](image.png)

## Awards Considered

The following major awards were analyzed to evaluate their influence on the Best Actress winner at the Oscars:

- **Golden Globes**  
- **SAG Awards**  
- **BAFTA**  
- **Critics' Choice Awards**  

## Data Structure

The dataset includes the following columns:

- **ano**: Year of the award season  
- **nome**: Name of the actress  
- **indicada_sag**: Nominated for the SAG Awards (Yes [1] /No [0])  
- **indicada_gg**: Nominated for the Golden Globe Awards (Yes [1] /No [0])  
- **indicada_os**: Nominated for the Oscar (Yes [1] /No [0])  
- **indicada_bafta**: Nominated for the BAFTA (Yes [1] /No [0])  
- **indicada_cc**: Nominated for the Critics' Choice Awards (Yes [1] /No [0])  
- **ganhou_sag**: Won the SAG Award (Yes [1] /No [0])  
- **ganhou_bafta**: Won the BAFTA (Yes [1] /No [0])  
- **ganhou_cc**: Won the Critics' Choice Awards (Yes [1] /No [0])  
- **ganhou_gg**: Won the Golden Globe (Yes [1] /No [0]) 
- **ganhou_os**: Won the Oscar (Yes [1] /No [0]) 

**Note**: The column `ganhou_os` (Won Academy Awards) is the target variable we are predicting.

## Machine Learning Models Used

For the prediction of the Best Actress winner, were employed:

- **Logistic Regression**: A simple yet effective model for binary classification, useful for predicting outcomes based on the given features.  

## Technologies Used

- **Python**: For data analysis and model training  
- **BeautifulSoup**: For web scraping  
- **Pandas**: For data manipulation  
- **Matplotlib/Seaborn**: For data visualization  

## Results

[ainda n temos results]

## Authors

- [@adriel1ft](https://github.com/adriel1ft)  
- [@kamilyassis](https://github.com/kamilyassis)  

## How to Open the Project

1. Clone the repository:  
   ```sh
   git clone https://github.com/JamboTechUFPB/oscar-prediction/
   ```
2. Navigate to the project folder:  
   ```sh
   cd oscar-prediction/
   ```

## Contribution

If you want to contribute, follow these steps:

1. Fork the repository  
2. Create a branch for your feature:  
   ```sh
   git checkout -b my-feature
   ```
3. Commit your changes:  
   ```sh
   git commit -m 'Adding new feature'
   ```
4. Push to the remote repository:  
   ```sh
   git push origin my-feature
   ```
5. Open a Pull Request, we will analyze this
