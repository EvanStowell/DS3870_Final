# DS3870_Final
## Authors: Evan S, Joey G, Ryan S, Jack V

## Notes:
### Data summary + link
NBA data
Link: https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats?select=Advanced.csv

### Data cleaning
Data Needed:
  - Player Season
  - Player Totals
  - Team Summaries (for W/L totals)
  - Player Award Shares
  - End of Season Teams (Voting) for 1st team

Data Cleaning
- Get rid of data before 1980 and 2025,
- Add a column for different awards of that year ( 0 or 1 ) for player,
- If a player has more than one instance in a year- remove that player’s season entirely
- Add team wins / any other team stat
- For roty df
	- Filter only players with 1 year of experience

### EDA


### Models
#### MVP
- Regression (linear or logistic)
- Features
    Team wins,
    Typical per game stats (fg%, points, rebounds, assists, etc),
    Age / experience,
- Go back and find the best MVP season ever (run only on MVP winners)
#### DPOY
- Trees
- Features
	- Typical per game defensive stats
	- Team points allowed per game
#### ROTY
- Logistic Regression
- Only keep where the player experience is 1 for training
- Features
	- Typical per game stats - fg%, points, rebounds, assists, etc
	- Minutes played
#### 1ST Team
- Regression (linear or logistic) or trees by position- 2 guards, 3 forwards/centers
- Features: Similar to mvp


### Results
Share results for each prediction/method
Predict current season awards after

