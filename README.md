## NBA Draft Regression Analysis.ipynb
Notebook outlining the methods of analysis, interpretations, and conclusions. The main goal of this analysis is to look at how biometric information
and player contribution in box-score statistics can be projected onto the draft. The final schema used is as follows:

| Variable | Description |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------|
| player_height |  Player height (cm) |
| player_weight | Player weight (kg) |
| draft_number | Draft position (1-82) |
| gp | Games played per season |
| pts | Points per game |
| reb | Rebounds per game |
| ast | Assists per game |
| net_rating | Net rating - team's point differential per 100 possessions while player is on the floor |
| oreb_pct | Offensive rebound percentage - percentage of available offensive rebounds a player grabbed while on the floor |
| dreb_pct | Defensive rebound percentage - percentage of available defensive rebounds a player grabbed while on the floor |
| usg_pct | Usage percentage - percentage of team plays used by a player while on the floor |
| ts_pct | True shooting percentage - measure of shooting efficiency that takes into account field goals, 3-point field goals, and free throws |
| ast_pct | Assist percentage - percentage of teammate field goals a player assisted while on the floor |

**Note: all variables are career averages** 

The original dataset can be found [here](https://www.kaggle.com/justinas/nba-players-data).
