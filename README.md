# NBA_Project

Predictive Analysis of MVP (Most Valuable Player) in the NBA Tournament       

Exploratory Data Analysis on NBA data from 1991-2022 to predict MVP for a year The Primary source of data for this project is :- https://www.basketball-reference.com/ The project contains the following files:-

mvps.csv:- This csv file contains the usable data which is scraped from the HTML pages of the mvp folder.

players.csv:- This csv file contains the usable data which is scraped from the HTML pages of the player folder.

teams.csv:- This csv file contains the usable data which is scraped from the HTML pages of the teams folder.

nicknames.csv:- This csv file contains the Team names with the abbreviations generally used for them.

player_mvp_stats1.csv:- This csv file contains the data of players.csv, teams.csv and mvps.csv

msedgedriver:- It was used to automate MS Edge for the purpose of data collection. The application may change if different browser is used.

NBA_Project.ipynb:- This notebook is the first notebook of the project. In this notebook, we are downloading the html pages, extracting the required data, and then 
saving it into their respective folder. Then we use that data to make Pandas dataframe, and then convert it into csv file.

NBA_data_cleaning.ipynb:- This notebook is the second notebook of the project. In this notebook, we clean our data and then perform some analysis on the data specially looking at the correlation of different attributes with "Share".

mvp_predict.ipynb:- It is the last notebook of the project. In this notebook, we split the data for training and testing purpose, and tried two different models for better accuracy.
