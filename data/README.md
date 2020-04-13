# data

The dimensions of the original dataset (`nba_social_power`) were 100 observations and 63 variables. However, we are using a reduced version of the full dataset (`nba_social_power_mod`) for analysis, which only includes 95 observations and 15 variables. The number of observations decreased because we decided to remove players who did not have Twitter handles.

Below is the data dictionary describing the 15 variables we have decided to use in our analysis.

Data Dictionary:

PLAYER_NAME: Player's name (categorical)

TEAM_ABBREVIATION: Abbreviation for the team the player is on (categorical)

AGE: Player age (quantitative)

W_PCT: Percentage of games played won (quantitative)

OFF_RATING: Player offensive rating calculated using the formula - Offensive Production Rating = (Points Produced / Individual Possessions) x OAPOW × PPG + FTM/FT * 3pt% + FG%  (quantitative)

DEF_RATING: Player defensive rating -  Defensive Player Rating = (Players Steals * Blocks) + Opponents Differential = 1/5 of possessions - Times blown by + Deflections * OAPDW (Official Adjusted Players Defensive Withstand) (quantitative)

NET_RATING: Average of the offensive/defensive rating (quantitative)

AST_RATIO: Assists-to-turnovers ratio (quantitative)

REB_PCT: Total rebounds (quantitative)

USG_PCT: Usage percentage, an estimate of how often a player makes team plays (quantitative)

PIE: Player impact factor, a statistic roughly measuring a player's impact on the games that they play that's used by nba.com (quantitative)

SALARY_MILLIONS: Salary in millions (quantitative)

TWITTER_FOLLOWER_COUNT_MILLIONS: Number of Twitter followers (quantitative)

TWITTER_HANDLE: Twitter handle (categorical)

PTS: Points scored (quantitative)

