# FIFA-Simulator

Simulate tournament of players based on strength level





## How to use program

Run using `python tournament.py <csvfile>`



## How it works

The program will read the CSV file and convert the team names and respective strength values into a dictionary. This dictionary will act as a roster for the tournament. 



**Program ONLY accepts rosters of base 2 (2,4,8,16,etc.)**



The roster of players will go through a tournament where each round the probability of a team winning is based on how much of a difference Team A's strength to Team B's strength is. There is an element of randomness to this as just like in real life, no team will always win every time. 



This tournament wlil be executed N times, the code specifies N to be a default of 1000.



After 1,000 simulations take place, the data is analyzed and the program will return the statistical information regarding each team's probability of winning a tournament based on the performances during the simulations. 
