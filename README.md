# Designing-and-Creating-a-Normalized-Database-using-SQLite3-and-Pandas
I worked with a file of [Major League Baseball](https://en.wikipedia.org/wiki/Major_League_Baseball) games from [Retrosheet](http://www.retrosheet.org/). Retrosheet compiles detailed statistics on baseball games from the 1800s through to today. The main file I worked from `game_log.csv`, has been produced by combining 127 separate CSV files from retrosheet, and has been pre-cleaned to remove some inconsistencies. The game log has hundreds of data points on each game which I normalized this data into several separate tables using SQL, providing a robust database of game-level statistics.

In addition to the main file, there are three 'helper' files, also sourced from Retrosheet:

- `park_codes.csv`
- `person_codes.csv`
- `team_codes.csv`

These three helper files in some cases contain extra data, but will also make things easier as they will form the basis for three of the normalized tables.

Included is a `game_log_fields.txt` file from Retrosheet which explains the fields included in our main file, which will be useful to assist in the EDA. 

## Getting Started

Download or View the Jupyter [notebook](https://github.com/arjunchndr/Designing-and-Creating-a-Normalized-Database-using-SQLite3-and-Pandas/blob/master/Designing%20and%20Creating%20a%20Normalized%20Database%20using%20SQLite3%20and%20Pandas.ipynb) if you have all the dependencies listed below.

## Built With

* [Anaconda](https://www.anaconda.com/download/) - Distribution pre-installed with Python and its associated packages
  * [Python 3.6.3](https://www.python.org/downloads/) 
  * [Pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) 
  * [Jupyter 5.1.0](http://jupyter.org/install.html)
  * [SQLite3](https://www.sqlite.org/download.html)
    * [How To Download & Install SQLite](http://www.sqlitetutorial.net/download-install-sqlite/)

