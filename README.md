# iplDataAnalysis
Indian Premium League Data Analysis

The core objective of this project is to showcasae the utlization of Apache Spark for data analysis. 
We will also use 

	1. Databricks
	2. SQL Analytics
	3. Amazon S3 (Simple Storage Service)

Python Libraries utilized.

1. pandas :	Clean and prepare data (e.g., handling missing values), Create new features (e.g., veteran status), Perform data analysis (e.g., finding top scorers)
2. numpy : 	Perform numerical computations (if needed for feature engineering or analysis)
3. matplotlib.pyplot :	Create basic visualizations (plots) to explore data
4. seaborn :	Create advanced statistical visualizations to understand data relationships




						==========================================================
								    ABOUT THE PROJECT
						=========================================================


**Indian Premier League** (IPL) is a professional Twenty20 cricket tournament featuring world-class players, intense regional rivalries, and high-voltage matches attracting a massive global audience. The dataset contains
data from 2008-2017 distributed over 5 different tables stored on a public Amazon S3 bucket.

**Table details**
The IPL data contains 5 tables offering insights into the matches, players, and teams. Here's a quick overview of each:

1. Ball_by_Ball.csv: This table dives deep into every ball bowled in a match. It includes details like the match ID, over number, who's batting and bowling, runs scored, and dismissal information (if any).

2. Match.csv: This table focuses on the broader match details. You'll find information like the match ID, date, season year, teams playing, venue, toss winner, and ultimately, who emerged victorious.

3. Player.csv: This table provides basic player information, including their unique ID, name, date of birth, batting style (left-handed or right-handed), bowling skill (if applicable), and their nationality.

4. Player_match.csv: This table links players to specific matches. It contains details like the match ID, player ID, along with information specific to that match, such as the player's role (batsman, bowler, etc.), their team, and their performance statistics.

5. Team.csv: This table keeps track of the teams. It includes a unique team ID, an external identifier (for linking with other datasets potentially), and the team's full name.

By combining data from these tables, one can analyze various aspects of the IPL, like player performance across matches, team strategies, and overall trends throughout the seasons.


