# Overview

In this project I focused on analyzing various statistics from players and teams that participated in the 2023-2024 NBA playoffs. This information can be applicable to NBA coaches and managers because I anaylzed statistics that correlate with higher success within the games. Using the correlations and patterns that I determined from my proccessing NBA executives can use this information to create the best teams and lineups possible that give them the highest probabilty of winning games. 

## Data Cleaning

Looking at the raw dataset that I chose to use I found that there was no duplicates or missing/null values within the data. The only thing I recognized that was incorrect with this dataset is that a few of the player names were spelled incorrectly so I just edited those to be correct.

## Questions

There were 4 questions that I anaylzed through my research. These questions are: how does minutes per game correlate with points per game, how does player age correlate with points per game, how does scoring efficiency change with points per game, and what is the relationship between 2 point shot percentage and 3 point shot percentage.

## Question 1: How does minutes per game correlate with points per game?

![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/MPG-PPG)

Looking at this visual we can see a scatter plot that shows the correlation between minutes and points per game with points on the y-axis and minutes on the x-axis. There is a trend that shows that on average the more minutes a player receives, the more points they typically score. This is shown with the trend line where there is a clear trend upwards that proves that points increase with minutes increasing. I also calculated the R^2 value which turned out to be about 0.54 which shows a medium positive relationship and proves that there is a positve corrrelation between these 2 variables. This can be useful information to NBA managers and coaches because it shows that it is on average more beneficial to give their best players more minutes because they are most likely to score more points with those minutes and in turn help them win the game.

## Question 2: How does age correlate with points per game?

![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/AGE-PPG)

This picture shows a graph showing the correlation between age and points per game. My hypothesis before creating this visual was that a majority of the highest scorers would be between the ages of 25-30 because this is typically when a player would be in their prime hence this is where I predicted the best players to fall under. After creating this visual I noticed that there really is not a correlation at all between age and points per game and my hypothesis seemed to be false. This is also proven with the trend line which shows that there is no strong correlation as well as the r^2 value which is calculated at 0.038 which proves a very weak correlation. The 2 things that stood out to me most on this chart was that every player under the age of 20 scored under 10 points per game as well as every player over 35 scored under 15 besides one outlier. Other than that there is really no pattern or correlation between points per game and age which tells us that there is no reason to consider age when determining and predicting whether a player will be a higher scorer or not.

## Question 3: How does efficiency change with points per game?

![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/EFF-PPG1)
![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/EFF-PPG2)
![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/EFF-PPG3)


Looking at this chart we can see how efficieny changes with points per game. The dark blue line represents the players field goal percentage and as you scroll down the chart it shows the players sorted by points per game descending. There is not really a trend between efficiency and points per game. Every player that averaged 20+ points per game scored with an efficiency between 40-63% which shows that typically a high scorer will average around 50% of their shots going in. However when you look at players who averaged less than 10 points per game there is a way higher range which is 0-100% which just shows that players who average less points are just more hit and miss with their total efficiency. 
Pearson correlation coefficient (r): ≈ -0.762
R² (coefficient of determination): ≈ 0.580
What this means:There's a moderate to strong negative correlation between FG% (efficiency) and PTS (points per game) in this dataset. About 58% of the variation in scoring can be explained by FG%, but inversely — which is counterintuitive. Higher efficiency seems to be associated with lower scoring in this dataset. This suggests that players who take more shots (and score more) may be less efficient, while role players with fewer points often have higher FG% due to taking easier or more selective shots.This information can be useful to NBA coaches and managers because it shows them and gives them an idea of how efficient certain players should be so if a player does not live up to this expectation they can infer they should play them less minutes.

## Question 4: What is the relationship between 2 point and 3 point shot percentage?

![Screenshot](https://github.com/Tommy-Fugal/capstone/blob/main/2P-3P)

This graph shows us the  between 2 point percentage and 3 point percentage with the dark blue line representing 3p% and the light blue line representing 2P%. Looking at the graph we can determine that there is no noticable pattern. Consistency: From about 5 to 30 PTS, 2P% mostly fluctuates between 0.45 and 0.60, with less volatility. Lower Averages: For most PTS values, the 3P% remains in the 0.25–0.40 range, typically lower than 2P%. High Variability: At lower PTS values (<10), 3P% shows extreme spikes and drops, indicating inconsistency in 3-point shooting among low scorers. Slight Stability Beyond 20 PTS: As PTS increases past 20, 3P% stabilizes a bit but still trends lower than 2P%.Slight Decline with Higher PTS: While the trend is not steep, there is a mild downward slope toward the far right of the graph (i.e., high scorers have slightly lower 2P%). Players who score more points tend to have consistent but not superior 2P%, and their 3P% remains lower on average. This may suggest that volume scorers often take harder shots or more 3-pointers, affecting their efficiency — especially from deep. This information can prove useful to NBA coaches and managers because it gives them an insight of typically how efficient certain ranges of scorers are and what specifically they rely on for the majority of their points.

In this repository there is also a link to the file I created visuals and anaylzed data with which can be accessed by clicking the "capstone.pbix" file and accessing it through Power BI. There is also a link to the google sheet file I used to analyze data as well as a link to the raw dataset that I used with this project.

Link to Google Sheet: https://docs.google.com/spreadsheets/d/1s_1s5N6vpHy79Hd70US4o7F6JOCmXB5Xwn0WyZvVMfg/edit?usp=sharing
Link to dataset: https://www.kaggle.com/datasets/vivovinco/2023-2024-nba-player-stats
