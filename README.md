# IPL Data Analytics Dashboard (Power BI)
## Project Objective

The aim of this project is to analyze player performance, team outcomes, and toss impact in the Indian Premier League (IPL) using historical match data. The dashboard highlights key KPIs like top batsmen, best death-over bowlers, strike rate trends, team success, and the role of toss in match outcomes..

## Dataset

<a href = "https://www.kaggle.com/datasets/manasgarg/ipl">IPL Data</a>

## Key Questions (KPIs)

-Who are the Top 10 batsmen in IPL history based on total runs?

-How do the Top 10 batsmen rankings change when filtered by year?

-Who are the best death-over bowlers (lowest economy rate in overs 16–20)?

-How does a player’s strike rate vary across seasons?

-Which teams have the most IPL titles (wins) and which have the most runner-up finishes?

-What is the overall toss impact % in IPL history?

-Does winning the toss significantly improve a team’s chances of winning?

-How do KPIs change when filtering by Year, Team, or Player?

## Process

1.Data Collection → Downloaded Kaggle IPL dataset (matches.csv, deliveries.csv).

2.Data Cleaning (Python Pandas) →

Removed null values and duplicates.

Normalized player and team names.

Created calculated columns: Runs by Batsman, Death Economy Rate, Strike Rate, Wins/Runner-up flags.

3.Feature Engineering →

Added year column from match date.

Aggregated stats at Player, Team, and Season levels.

4.Data Import → Exported cleaned datasets (batsman_stats.csv, bowler_stats.csv, team_stats.csv) and loaded into Power BI.

5.Dashboard Creation → Used DAX for KPIs (Strike Rate, Death Economy, Toss Impact).

6.Visualization → Built interactive visuals and slicers.

## Project Insights

-Top Scorers: Consistently dominated by players like Virat Kohli, Rohit Sharma, and David Warner.

-Death Over Specialists: Bowlers like Bumrah and Bravo stand out with strong death-over economy.

-Player Trends: Strike rate trends show peak years for certain players (e.g., Dhoni’s strong finishes).

-Team Performance: MI and CSK dominate in both wins and runner-up finishes.

-Toss Impact: Toss matters (~44–47% impact) but does not guarantee a win.

## Dashboard
<img width="1118" height="627" alt="Screenshot 2025-09-30 163418" src="https://github.com/user-attachments/assets/e50b3d55-f663-4f09-bbb4-9ff095fa391b" />


