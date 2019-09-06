# Designing & Creating a Database
## Introduction/Goals
In this project, I will:

* Import data into SQLite
* Design a normalized database schema
* Create tables for the schema
* Insert data into the schema
## Data
I will be working with a file of Major League Baseball games from Retrosheet. Retrosheet compiles detailed statistics on baseball games from the 1800s through to today. The main file I will be working from game_log.csv, has been produced by combining 127 separate CSV files from retrosheet, and has been pre-cleaned to remove some inconsistencies. The game log has hundreds of data points on each game which I will normalize into several separate tables using SQL, providing a robust database of game-level statistics.

In addition to the main file, I have also included three 'helper' files, also sourced from Retrosheet:

* `park_codes.csv`
* `person_codes.csv`
* `team_codes.csv`
