*****************
File descriptions
*****************
fifa_2018_results.csv - FIFA World Cup 2018 result
past_results.csv - past competitions result, including past FIFA results
players_scores.csv - player's performance score (measures based on offensive and defensive KPIs) for the 2017/2018 club season, 
including Premier League, La Liga, UEFA, Super league, etc. Player's score are calculated based on tournaments, one might have more 
than one performance score. Scraped from www.whoscored.com
sofifa.csv - the team's performance rating calculated by sofifa.com. The ratings were collected yearly since 2010, and improved to 
monthly collection on 2013. 

***************
Data dictionary
***************

fifa_2018_results.csv
---------------------
date: date of match
game: type or phase of match
home_team: who the home team is
away_team: who the away team is
home_result: home score
away_result: away score
home_penalty: home penalties score
away_penalty: away penalties score
stadium: stadium of match
city: city where stadium located
lat: latitude of the stadium location
long: longitude of the stadium location
country: hosting country

past_results.csv
----------------
date: date of match
home_team: who the home team is
away_team: who the away team is
home_score: home score
away_score: away score
tournament: competition name
city: city where the match is
country: hosting country

players_scores.csv
-----------------
nationality: player's nationality
player: player's name
club: player's club
age: player's age
Apps: player's appearance, the starts and the bracketed number is sub appearances
Mins: minutes played
Goals: total goals
Assists: total assists
Yel: yellow card
Red: red card
SpG: shots per game
PS: pass success percentage (%)
AerialsWon: Aerial duels won per game
MotM: Man of the match
Rating: overall rating

sofifa.csv
----------
datestats: date when the ratings were collected
countrystats: team (country)
overall: overall rating of the team
attack: attack rating of the team
midfield: midfield rating of the team
defense: defense rating of the team
bu_speed: build up speed rating
bu_passing: build up passing rating
bu_positioning: build up positioning rating
cc_crossing: chance creation crossing rating
cc_passing: chance creation passing rating
cc_shooting: chance creation shooting rating
cc_positioning: chance creation positioning rating
aggression: tactical defence aggression rating
pressure: tactical defence pressure rating
avg_age: average age of the players in the team