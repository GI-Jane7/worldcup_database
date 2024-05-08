# 💻 PROJECT: WORLDCUP DATABASE
## Goal:
Create a Bash script that enters information from World Cup games into PostgreSQL, then query the database for useful statistics.
A worldcup database project required for Relational Database Certification on FreeCodeCamp.


## Database Creation
Dataset: [Games.csv](https://github.com/GI-Jane7/worldcup_database/blob/main/Games.csv)

Tables: 
* Games: Indicates all matches and scores produced by each team( winner and opponent) using the team_id as identifier.
* Teams: All the team that played in the matches.

Added appropriate constraints(primary keys and foreign keys)


## Automating data Insertion and Querying with SQL
Created a bash script that reads the games.csv data and uses SQL query commands to insert the data automatically into the tables that was previously created.

Took the constraints into consideration when creating the Bash script to insert all winner and opponent teams individually into the 'teams' table and then into 'games' table based on the team_id created.

Database dump after data Insertion: 





