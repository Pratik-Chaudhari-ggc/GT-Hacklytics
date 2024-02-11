# GT-Hacklytics
Our team's submission repo for the 2024 GT Hacklytics

## Our Team
- Pratik Chaudhari
- Cody Ledford
- Manu Achar
- Jacobi Miller

### Notebook for Live Testing Code
- dtc-notebook.ipnb

# Predicting American Football Outcomes

- Our project leverages historic data from numerous sources (linked below) in order to feed a predictive model that will determine the outcome of a football game based on plays made in the game.

## Our approach
In order to create a model that would predict the outcome of a football game properly and accurately, we engaged in the following activities:

- Identify datasources that would supply us with historic football statistics, including but not limited to play-by-play data, and per-game performance.

- Identify key fields in the datasets that preliminarily be the best for the analysis and feeding to the model.

- Clean the dataset to remove missing and non-important values, such as columns that are full of 0s and such.

- Identify the teams that were in the Superbowl, and create subsets of our season data to better analyze 

- Aggregate the historic datasets into one main dataset that can be used for training.

- Use an additional cleaned dataset with current data to test and determine the accuracy of our model.

- Utilize a decision tree model that would take in our cleaned and created datasets in effort train the model.

- Create a dataset that could be used to verify the accuracy of the model, and as a result, determine the effectiveness of our application.

## Points of Struggle
- Finding the proper datasets that contained all of the data that we were looking to capture for our problem.

- Merging of datasets

- Determining how to use PCA for feature selection

- Improving the accuracy of the model.

## How would we improve this model
- We would include additional sets of data for attempts to make the model more accurate, since it would have more data and potentially be able to recognize the most important features easier.

- Refine our filtering of the data - this would ensure that we only have quality inputs that would influence the decision making power of our model.

# Outcomes of the Analysis and Model
- Using the chosen play-by-play data from 2018 - 2022 NFL Football seasons for training, and the 2023 season our model was able to predict the outcome of a game accurately 65% of the time with top 25% of loadings based on absolute cumulative sum.

- With more data for further training, we believe that our model could be used to accurately determine the outcome of games in real-time as the game progresses.

## Dataset Sources
- [Play by Play Datasets](https://nflsavant.com/about.php)
- [Scores and Winners by Game](https://www.pro-football-reference.com/years/)
- [NFL Team Stats](https://www.kaggle.com/datasets/cviaxmiwnptr/nfl-team-stats-20022019-espn)
- [List of Super Bowl Champions](https://en.wikipedia.org/wiki/List_of_Super_Bowl_champions)