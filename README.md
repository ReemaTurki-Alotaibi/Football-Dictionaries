****⚽ Football Squad Data****

This project provides a simple Python script to analyze historical football squad data. The dataset includes player-level information such as name, position, club, country, and international appearances.

**📋 Dataset Overview**
Each player is represented with the following attributes:


Field	Description
number	Player's shirt number
position	Player's position (e.g., GK = Goalkeeper, MF = Midfielder, FW = Forward)
name	Full name of the player
date_of_birth	Date of birth and age at the time
caps	Number of international appearances (if available)
club	Club the player played for during that year
country	Player's nationality
club_country	Country where the club is based
year	The year the player was part of the national squad

**🧠 Features**

**1. Convert Player Data to Dictionaries**
Converts raw list data into structured dictionaries for easier access and processing.


convert_players_to_dict(players_list)

**2. Group Players by Position**
Organizes players by their playing position (e.g., Goalkeepers, Midfielders).


group_players_by_position(players_list)

**3. Group Players by Country and Position**
Creates a nested structure grouping players by nationality and then by position.


group_players_by_country_and_position(players_list)

**✅ Example Output**
The script prints pretty-formatted output of:

A list of players as dictionaries

Players grouped by position

Players grouped by country and position

Additionally, basic test cases are included to ensure function correctness.

**🧪 Testing**
The script includes basic assertions to validate:

Proper conversion to dictionary format

Correct grouping by position and country

Integrity of specific player data


test_all_functions()

**📌 Notes**
Some entries may have missing data (e.g., missing player number or caps).

The dataset is a mix of multiple squads from various years and countries.

Designed for educational and practice purposes in data structuring and grouping.
