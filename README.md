[![DOI](https://zenodo.org/badge/791817342.svg)](https://zenodo.org/doi/10.5281/zenodo.11078557)
# NBA Player Analysis

To execute the Exercise1.ipynb using Python 3.12, the follwing components are required:  
- **Python 3.12**: This serves as the foundational programming language for our work. It is available for download and installation from the official Python website.  
- **Jupyter Notebook**: This environment facilitates the execution of your code. It can be installed via pip (pip install notebook) or obtained through Anaconda.  
- **Required Libraries**: Ensure that all necessary Python libraries, such as pandas and matplotlib as specified in our project, are installed. These can be acquired via pip (e.g. pip install pandas).  
- **Data Files**: Our notebook relies on CSV files, which should either reside in the same directory as your notebook or be accessible from its location.  
- **Integrated Development Environment (IDE) or Text Editor**: Tools such as Jupyter, PyCharm, Sublime Text, or Visual Studio Code are suitable for viewing and editing .ipynb files.

## Re-used dataset
The NBA Player Analysis project is based on a dataset published [on Kaggle](https://www.kaggle.com/datasets/harisbeslic/nba-player-data-by-game-from-1949-to-2019/data). Out of the original 28 csv files, this project makes use of the following three.
- `players.csv`: One row corresponds to one player. For each player his player id (for reference in other files) name, full name, position, height, weight, birth date, birth place, retirement status, player url, his or her current team, all teams he or she played for and additional comments on that player is provided. The player url is meant as postfix to the basketball-reference.com website (e.g. https://www.basketball-reference.com/players/a/ackerdo01.html).
- `teams.csv`: One row corresponds to one team. For each team its team id (for reference in other files), team name, name abbreviation, years since founding, total games participated, total games won, total games lost, win percentage of all games played, number of championship wins, other names, team url postfix for te basketball-reference.com website and activity status are provided.
- `player_data_per_36_min.csv`: This file holds statistics of a unique player per row. Each row  has its own id for reference, player_id (corresponds to id attribute in players.csv file), years of the seasons the player was active in the nba, total games in the nba, total games started, number of minutes played, and 21 different statistics. Explanation of the statistics column names can be found in the ESPN NBA [Sortable Statistics Glossary](http://www.espn.com/editors/nba/glossary.html).


Contact person: Tobias Raidl (e11717659@student.tuwien.ac.at)
