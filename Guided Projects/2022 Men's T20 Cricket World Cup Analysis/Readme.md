# Selecting the Best Cricket Team 
The task at hand is to select a team of 11 players that have the maximum likelihood winning a cricket match. Subject matter knowledge will be utilised to inform decision making.
The targets of the match is to reduce and keed the maximum score that the opposing team can make to under 150 in 20 balls of the match. And we are targeting at least 6 wickets to slowdown the team's ascent. The team selection will be done based on the following conditions:

## 1. Openers 
These individuals must possess the following statistics for a constituting a good opening play:
1. Batting Average : Average Runs Scored in an inning > 30
2. Strike Rate : Number of runs scored per 100 balls > 140
3. Innings Batted > 3
4. Boundary % : Percentage of runs cored using boundries > 50
5. Batting Position : Order in which the batter played < 4

## 2. Anchors/ Middle Order
These players acome into play when the openers have played badly and thus require good scoring skills to boost up the score
1. Batting Average > 40
2. Strike Rate > 125
3. Innings Batted > 3
4. Avg. Balls faced > 20
5. Batting Position > 2

## 3. Finisher/ Lower Order Anchor
These are aggressive players that hover around all rounders and are required to boost up team score in case all the others re batted out
1. Batting Average > 25
2. Strike Rate > 130
3. Innings Batted > 3
4. Avg. Balls Faced > 12
5. Batting Position > 4
6. Innings Bowled > 1

## 4. All Rounder/ Lower Order Batsman
These are primarily for bowling but can pull their weight in batting as well
1. Batting Average > 15
2. Strike rate > 140
3. Innings Batted > 2
4. Batting Position > 4
5. Innings Bowled > 2
6. Bowling Economy : Average Runs allowed per over < 7
7. Bowling Strike Rate : Averge number of balls required to take a wicket < 20

## 5. Specialist Fast Bowlers
These are supposed to be the bowlers that can take out wickets quickly to reduce the opposing team's scorig potential
1. Innings Bowled > 4
2. Bowling Economy < 7
3. Bowling Strike Rate < 16
4. Bowling Style : "Fast"
5. Bowling Average : Number of runs allotted per wicket < 20
6. Dot Ball % : Percentage of dot balls balled > 40

# Data Collection 
