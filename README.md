# Project 2
Machine Learning and Neural Networks
# MLB Outcome Prediction Model 

## Objective
The function of this model is to accept historical MLB team performance stats from two teams as an input, as well as additional matchup data, and predict the outcome of who will win a specific game played between the two teams. 


## Data Source 
There exists a large amount of historical baseball data and statistics dating back to 1871. Retrosheet (https://www.retrosheet.org/gamelogs/index.html) includes team and player statistics, and will be the primary datasource for this project. 

For the purpose of this model, data from 2020 - present will be used. 

Because each team in the MLB plays 162 games in a season, there is a large sample size of recent data, making MLB an ideal candidate for Machine Learning modeling. 

## Methodology 
The dataset will ideally contain descriptive statistics on two teams for a specific head-to-head matchup. 

The features portion of the dataset may contain attributes such as: win percentage, batting average, on base percentage, earned run average, and strikeout/homerun rate. 
The target attribute of the data will be home-team win (binary 0 or 1). 
