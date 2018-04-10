# Capstone-Project-1
### Summary
My first capstone project for springboard deals with handling NBA players' statline and using them to help predict the season MVPs. Since MVPs are chosen through a process in which a handful of players are rank by sports analysts and broadcaster, the idea will be to model the way these individuals cast their votes towards choosing their candidates. In doing so, perhaps determining the next NBA season's MVP will ultimately come down to analyzing specific stats of a player during that season.


### Dataset
The dataset was retrieved from Kaggle that contain players' statlines from 1950s to 2017 NBA season that included regular and advanced stats. In addition, I web scrapped from basketball-reference.com to include the player's team win-lose percentage since I believe this is a huge reason for candidates to win.


### Approach
The approach to this problem will be to randomly sample 1800 different statlines from the 2000 season till 2017 season. Of this 1800, each season will have 100 statlines where 1 statline will be the definitive MVP for that season and the rest are all non MVPs. The goal is to develop a model using classification algorithms to classify MVPs and non MVPs by hand picking specific features. To determine the definitive MVP for the season, the player with the highest probability output by the model will be considered the definitive MVP.


### Extension
To get a more objective view on the players, unsupervised learning can be done to help seperate players in hope to finding other trends to discern MVP players.
