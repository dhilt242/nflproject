
## Analysis of Fourth Down decisions in NFL football games

# Problem Statement

The following analysis attempts to take datasets of NFL football games from 2009 to 2018 from Kaggle and Armchairanalysis.com to find factors that determine whether a play on fourth down is more likely to be successful based on historical play-by-play data.


# Executive Summary

The analysis uses two datasets consisting of data points collected for each play in NFL season games describing various characteristics such as type of play, result of play, field position, time data, probability data, team data and player data. Both datasets were scraped from the official NFL website. The Kaggle database is used as primary data source for the analysis, whereas the Armchairanalysis.com database is a secondary source and is exclusively used to augment the primary database with weather and game condition data.

The goal of the analysis is twofold. The first part consists of analysing the data to identify factors that influence the effectiveness of the conversion of a fourth down play based on historical data. The potential factors analyzed are field position, home advantage, play selection and weather conditions. This would also help in the second part of the analysis by pinpointing potential factors that could be used for predictive purposes. 

The second portion of the analysis is to find a model that accurately predicts the outcome of a fourth down play based on features that were identified by the previous step. Given that the model requires a binary classification, logistic regression and KNN are used for modeling and their results compared with the help of accuracy metrics. 
The first model was optimized using a grid search, whereas the second was used with its standard settings for its hyper parameters.

# Conclusion

The first part of the analysis did not result in any major findings that could explain the success or failure of a fourth down play. Most factors showed a very even distribution of success versus failure, regardless of which factors were used to differentiate. Consequently, both models proved to be only slightly better than the base line in terms of correctly predicting the outcome of a fourth down play. 

Going forward, it would make sense to use some feature engineering to improve the performance of the models, given that the factors in their existing form provide very little differentiation. Another avenue of analysis would be to incorporate advanced analytics data points such as expected points and winning probabilities.
