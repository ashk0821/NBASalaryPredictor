# NBA-salary-predictor
NBA-salary-predictor using python


We are all really big basketball fans. We all love watching and playing basketball, which is why we wanted our project to have something to do with the NBA (National Basketball Association). The objective of our project is to create a machine learning model which uses NBA player statistics from the 2021-2022 season to determine their salaries for that same season. In order to do so, we obtained two datasets, one with player statistics for the season, and the other with player salaries for the season. Since NBA players do earn very high salaries annually, instead of having our model predict the specific number for their salary, we will create brackets that each of their salaries may fall into, and then predict players' salary brackets using our model. First, we will need to clean and prep each of these datasets, and then we will be able to join them together. After that, we can determine which features will be used in our models, and will test different models on their ability to predict the salary bracket of a player accurately.

What we concluded:
After cleaning and merging the data, we were able to create a few different machine learning models to predict the salary bracket that each player falls into. We used the K-NN Classifier, Random Forest Classifier, and Support Vector Machines, to create different models. After tuning the hyperparameters for the three different models, we found that the Random Forest Classifier is the best model for our project, producing an accuracy of 0.72 when the hyperparameters were tuned such that 'max_depth' = 8 and 'n_estimators' = 41. We were hoping for an accuracy of around 0.75, and while we weren't able to reach that with any model, we have gotten pretty close. The reason that we believe our accuracy wasn't able to be higher than this, was because there are many different factors that affect a player's salary, other than just their statistics on the season. There are many other skills in the NBA, such as hustle, communication, leadership, and many more that aren't necessarily trackable, but definitely have an impact on the player's impact and value, and thus their salary. If we were able to create a model with an accuracy of 0.90 or greater, then this would be very impressive. This would make it very easy for owners of NBA teams to determine how much to pay their players based on their statistical performance. Determining a player's worth and their salary still remains a big problem in the NBA today, and we believe our model does a solid job at predicting this.