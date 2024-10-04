# Data-Analytics---Best-XI-from-T20-Wrold-Cup-2022
Pick the best XI from all teams based on T20 World Cup 2022. This team should be able to win with any other team. 

#################
1st step
****
Collect all the required data like match summary and player summary from online sources 
Clean the data using the pandas library in python. Cleaning includes removing the duplicates and null entries and transform the data into excel or CSV files. 
******

2nd step
***
Load all these files into Power BI
Filter the players based on certain criteria for different roles like Top Order Batsmen, Middle Order Batsmen, Finishers, Spinners, and Fast Bowlers
To be picked as a Top Order Batsmen, I considered the following conditions:
1. Batting Position should be less than 4
2. Average should be greater than 30
3. Innings played is greater than 3
4. Runs scored should be greater than 130
5. Strike Rate should be greater than 140

For a Middle Order Batsmen:
1. Batting position should be less than 6 and greater than 3
2. Batting Average should be greater than 40
3. Batting Strike Rate should be greater than 140
4. Boundary percentage should be greater than 40%

For a Finisher, bowling abilities should also play a crucial role. The conditions are 
1. Batting position should be less than 9 and greater than 4
2. Batting Strike Rate should be greater than 150
3. Boundary percentage should be greater than 55%
4. Bowling Economy should be less than 9
5. Total Balls faced should be greater than 25

For a Spinner:
1. The Bowling Average should be less than 25
2. Dot Ball percentage should be greater than 30
3. Bowling Economy should be less than 9
4. Wickets should be greater than 9

For a Fast Bowler:
1. Overs bowled should be greater than 10
2. Bowling Average should be less than 20
3. Dot Ball Percentage should be greater than 40
4. Economy should be less than 8.
5. Wickets should be greater than 10.

Based on the above conditions, I got a squad of 16 players. These 16 players are match winners, we can pick any 11 players from these players and they can win matches against any XI. 
