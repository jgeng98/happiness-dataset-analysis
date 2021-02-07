# World Happiness Report Analyses

## Background and Introduction
The purpose of this project was to do some exploratory data analyses using data from the [World Happiness Report](https://www.kaggle.com/unsdsn/world-happiness/data) found on Kaggle.

The data was reorganized to contain the following variables: 
 

| Variable      | Description                          |
| ------------- | ------------------------------------ |
| Country       | Country name                         |
| Region        | Region of the world                  |
| GDPperCap     | Economic production                  |
| TrustGov      | Trust in government                  |
| Family        | Family support                       |
| Freedom       | Perceived freedom                    |
| HealthLifeExp | Perceived health and life expectancy |
| Generosity    | Perceived generosity                 |
| Year          | Year of survey                       |

## Objective

The aim of these analyses was to answer the following questions, separated into their own sections:

1. Scores by Region in 2019
    - Describe the distributions of the six scores by region in 2019.
    - How strong is the association between each score and region?
    - Does this association vary amongst the scores or do they all follow a similar pattern?

2. Predicted Happiness Score
   - Compute the happiness score for each country in every year (found by summing up the 6 scores).
   - For each year, which country had the minimum and maximum happiness score in every region? 
   - After plotting the minimum and maximum happiness scores for each region over the 5 years, does it appear that they change much over time?
   - Describe the associations between each of the 6 scores and the earlier computed happiness score.

3. Happiest Countries Over Time
    - Which 10 countries have the highest average happiness scores over the 5 years?
    - Which 10 countries have the largest positive change in happiness score from 2015 to 2019?