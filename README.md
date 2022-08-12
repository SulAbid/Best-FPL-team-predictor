
# Predicting best FPL team using ML

In this project we will create try to predict the most valuable FPL squad that will get the highest points average using ML.



## Datasets

#### In this project we will use the following Datasets :

1-`cleaned_players.csv`

2-`cleaned_merged_seasons.csv` 

## Data dictionary

1-`cleaned_players.csv`



| Variable          | Discription                                                                                           |
|-----------------|-------------------------------------------------------|
| first_name	                | The first name of a player                                                             |
| second_name	    |                 The second name of a player                             |
| goals_scored |   The number of scored goals in the season                                     |
| assists            | The number of assists deliverd in the season                                                    |
| total_points           | The total number of FPL points collected in the season                                                         |
| minutes             | The number of minutes that a player played                                                      |
| goals_conceded               | Number of goals conceded in the season                                                        |
| creativity              | Used as a guide to identify the players most likely to supply assists.                                                 |
| influence   | Evaluates the degree to which a player has made an impact on a single match or throughout the season             |
| threat     | A value that examines a player's threat on goal                                                   |
| bonus  | The number of bonus points achieved by a player in the season                                                |
| bps           | An index that takes the actions of a player in a match & returns a number to determine if he deserve a bonus or not. |
| ict_index | An index that combines influence,creativity and threat to help to give a verdict on FPL assets.                                                  |
| clean_sheets	         | The number of matches ended without concededing any goal.                                                |
| red_cards          | The number of red car a player recived for the whole season.                                                 |
| yellow_cards          | The number of yellow car a player recived for the whole season.                                                 |
| selected_by_percent          | The percentage of FPL users selecting a certain player.                                                 |
| now_cost          | The last updated price for a player.                                                 |
| element_type          | The position of a player (GK for Goalkeepers , DEF for defenders , MID for midfielders , FWD for the attackers).                                                 |

2-
`cleaned_merged_seasons.csv`


| Variable          | Discription                                                                                           |
|-----------------|-------------------------------------------------------|
| season_x	                | the football season (eg. 2019-20 )                                                             |
| name	    |                 The  name of a player                             |
| position |   position of a player (GK,DEF,MID,FWD)                                   |
| team_x            | The team that a player plays for .                                                    |
| transfers_balance	         | The diffrence between transfers_in and transfers_out.                                                |
| transfers_in | The number of FPL users who bought a player in certain GW.                                                  |
| transfers_out	         | The number of FPL users who sold a player in certain GW.                                                |
| was_home          | If the player team was playing in their home (True or False)                                                 |
| GW          | The number of the gameweek .                                                 |
| own_goals          | The number of goals scored by a player on his own team during a single GW.                                                 |
| penalties_missed          | Missed penalties during the GW.                                                 |
| penalties_saved          | Saved penalties during the GW (for Goalkeepers).                                                 |
| saves          | The number of saves a GK did in the GW.                                                 |
| team_a_score          | The score of the away team.                                                 |
| team_h_score          | The score of the home team.                                                 |
| opp_team_name          | The opponent team name.                                                 |



## Libraries 

- Pandas
- Numpy
- Scikit learn
- Matplotlib
- Json
- Requests

