Sports Team Management System | MySQL

Project Overview
The Sports Team Management System is a database project built using MySQL to efficiently manage information about leagues, teams, players, matches, and scores. It demonstrates key SQL concepts like Joins, Views, Subqueries, Triggers, Stored Procedures, Indexes, and CTEs (WITH clause) for optimized data management and reporting.

 Database Design
Tables:
•	Leagues – Stores league information.
•	Teams – Contains team details linked to leagues.
•	Players – Holds player profiles, age, and position.
•	Matches – Records match schedules, teams, and winners.
•	Scores – Tracks goals scored by each team per match.

Key SQL Features Implemented
Joins - Combined data from multiple tables to display match details with teams and winners.
View - Created TeamPerformance view to summarize matches played and won per team.
Subquery - Used to find players from the latest winning team.
Trigger - Update_winner_after_score automatically updates the winner after score insertion.
Stored Procedure - GetPlayerCountByTeam() lists total players in each team.
Indexes - Added indexes to improve query performance on key columns.
WITH Clause - Implemented CTE RecentMatchScores to analyze recent match results.

How to Run the Project
Install MySQL on your system.
Open MySQL Workbench or any SQL client.
Copy and run the contents of SPORTS TEAM MANAGEMENT SYSTEM.sql.
Execute the sample queries to explore joins, views, triggers, and more.

Tech Stack
Database   : MySQL
Language   : SQL
Tools      : MySQL Workbench 
