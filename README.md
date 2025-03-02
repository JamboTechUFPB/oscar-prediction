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

Finally our model achieved the following results:

- **Precision and Recall of 0.500**: These values indicate that the model is making a notable amount of errors in both directions—misclassifying positive examples (false positives) and failing to identify positive examples (false negatives). This is likely due to the scarcity of positive instances (1s) in the dataset.

- **F1-score of 0.500**: This reflects the balanced relationship between precision and recall, showing that the model performs equally in both error directions.

- **Accuracy of 0.750**: This suggests the model is making correct predictions in the majority of cases. However, it’s worth noting that accuracy might be skewed due to the dominance of class 0.

- Remembering these results are influenced by the small sample size, as only one winner is selected per category each year. Based on our analysis, the two **most probable** candidates for winning the **97º Best Actress winner** Oscars award are **Demi Moore** and **Mikey Madison**.

**Important Note**: The model is **not capable** of accounting for variables influenced by *human bias*, and predictions are based solely on available data, which may not capture all real-world influences.

## Authors

- [@adriel1ft](https://github.com/adriel1ft)  
- [@kamilyassis](https://github.com/kamilyassis)  

## Future Ideas

- Add additional features such as gender, age, critic ratings, and news articles. This will help not only to analyze potential correlations but also to see if these features can improve the model's performance.
- Train different models to compare metrics


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
