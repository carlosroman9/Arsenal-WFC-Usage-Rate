# Arsenal-WFC-Usage-Rate Analysis

Over the past year, women's soccer has significantly increased in popularity in the sports world. 
The FC Barcelona Women's team broke a world record for fan attendance in women’s soccer; reaching a capacity of 91,648 fans at the Camp Nou, the home stadium of FC Barcelona's Men’s team. 

Though viewership is rising, female soccer players are still relatively unknown, and I wanted to highlight women’s players and their performances. I wanted to produce a visualization that would show the top performing players. 
For this project, I selected to focus on the Arsenal Women’s team to analyze their player performances for the 2020/2021 season based on “usage rate,” and “positive rate.” I extracted JSON data from an open source data repository called “Stats Bomb.” 

I was inspired to pursue this project because of my interest in human performance and personnel recruitment. I also became interested in this type of analysis because of Brentford FC, a London based soccer club playing in England’s highest soccer division; the Premier League. Until two seasons ago, they were playing second in a second division league, but after embracing a data driven approach to player recruitment they achieved promotion and have stayed in Premier League since. 

What is “usage rate? And “positive rate?”
Usage rate is a term that is used in basketball statistics. It is a formula that calculates the percentage of actions a player takes when they are in possession of the ball (whether the outcome was positive or negative). In the scope of this project, I have only selected to include a player’s passes, shots, and dribbles in the calculation. Overall, I calculated each player’s usage rate by adding their individual totals in passes, shots, and dribbles by the team’s (all the players combined) shots, passes and dribbles. The positive rate is the same formula, but only counting completed passes and successful dribbles. 

Technology: Python, JSON, SQLITE, Microsoft SQL Server
Data Source
https://github.com/statsbomb/open-data
