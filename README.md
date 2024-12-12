# baseball-postseason
## A machine learning project for Stat 486 about predicting postseason success in the MLB from regular season data.

This repository contains scripts to process data for a pre-defined list of teams. This list of teams includes every team which has made the postseason since 1995.
Curated data is saved in applicalbe .pkl files.
It also contains scripts to create, train, and evaluate models. There are three such scripts.
The first script (team_model.ipynb) trains a model based on collective team data during each game in a season.
The second script (player_model.ipynb) trains a model based on season-average player statistics for each team. The model takes three distinct inputs: batting statistics, pitching statistics, and fielding statistics.
The third script (combined_model.ipynb) trains a model using the class probability predictions from the previous two models to refine predictions.
The best model predictions from the first two models are saved to .csv files.

The information used here was obtained free of
     charge from and is copyrighted by Retrosheet.  Interested
     parties may contact Retrosheet at 20 Sunset Rd.,
     Newark, DE 19711.
