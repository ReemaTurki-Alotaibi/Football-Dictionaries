# Football Squad Data

This project contains data about football players and their respective clubs. The dataset includes information on the player's number, position, name, date of birth, caps (appearances), club, country, club's country, and the year they were part of the squad.

## Description

The dataset consists of several football players from different countries, grouped by their position and country. The goal of this project is to work with this data and provide various groupings and analyses.

### The data contains the following columns:
- **number**: The player's number on the team.
- **position**: The player's position (e.g., GK for Goalkeeper, FW for Forward, MF for Midfielder).
- **name**: The player's full name.
- **date_of_birth**: The player's date of birth.
- **caps**: The number of international appearances the player has made.
- **club**: The player's club at the time.
- **country**: The player's country of origin.
- **club_country**: The country where the player's club is based.
- **year**: The year the player was part of the squad.

## Features

This project includes several functions for manipulating the data:

1. **Convert to Dictionary**: Converts the list of player data into a list of dictionaries, where each player is represented as a dictionary with appropriate keys (e.g., 'name', 'position').
   
2. **Group by Position**: Groups the players by their position (e.g., Goalkeepers, Forwards, Midfielders).

3. **Group by Country and Position**: Groups the players first by their country, and then by their position (e.g., Grouping players from Argentina and then by their positions).
