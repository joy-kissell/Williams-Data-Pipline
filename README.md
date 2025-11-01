# Williams-Data-Pipeline

*Tools: Python · MongoDB · Watchdog · Pandas · Dash · Plotly*

## Summary
Developed an automated Python ETL pipeline to load new CSV experiment data into MongoDB, parse key performance metrics, and calculate summary measures over time. Linked the database to an interactive dashboard (Dash + Plotly) for nontechnical lab staff to quickly interpret results and plan upcoming sessions.

## Purpose
For nontechnical lab staff to quickly interpret rat performance metrics and prepare for upcoming sessions

## Problem Solved
Previously, staff had to manually calculate each rat’s last session performance and percent accuracy to decide if the rat could advance to the next stage, which was time-consuming.

## Solution
Built an interactive dashboard (Python, Dash, Plotly) that automatically displays key metrics, allowing staff to immediately see results and plan the next session.

## Impact
  >Reduced setup time for experiments 
  >Enabled data-driven decisions, e.g., adjusting sugar pellet flavors improved performance for some rats, as observed in the dashboard
______________________________________________________________________________
## Key Features
1.	Dropdown menu to select overview, average, or recap webpage
2.	Dynamic filters for Rat ID, Stage, and Metric
3.	Interactive line charts and gauges to visualize daily, weekly, monthly performance
4.	Automated data ingestion and aggregation from experiment logs
5.	Provided actionable insights for lab staff to quickly make experiment decisions
## Example Views from Dashboard
