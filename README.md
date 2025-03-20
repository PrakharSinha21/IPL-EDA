# IPL Batsman Performance Analysis
📌 Project Overview
This project provides a comprehensive analysis of IPL batsman performances across different seasons using Python and Pandas. The primary objective is to extract season-wise performance data for a particular batsman based on match and delivery data, enabling insights into their consistency, peak seasons, and overall contribution.

📂 Dataset
The analysis is performed using two CSV files:

matches.csv - Contains match-level details including match ID, season, teams, venue, and match results.
deliveries.csv - Contains ball-by-ball details including batsman runs, balls faced, bowler details, dismissals, and match ID.
🛠️ Features Implemented
Data Merging: Merging matches.csv and deliveries.csv on match_id to get the season column.
Batsman Performance Analysis: Filtering the dataset for a specific batsman.
Season-Wise Aggregation: Grouping data by season to calculate total runs scored by the batsman.
Sorting & Visualization: Sorting and displaying performance across different seasons with tabular and graphical representation.
Additional Insights: Strike rate calculations, boundaries count, and balls faced per season.
