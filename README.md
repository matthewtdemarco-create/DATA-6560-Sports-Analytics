This project analyzes Major League Baseball team-level performance to identify which statistical factors best predict team success in the following season.

Problem and Stakeholder - Front offices, analysts, and coaching staffs rely on performance data to make decisions about roster construction, player development, and long-term strategy. The core problem addressed in this project is identifying which team-level statistics provide meaningful predictive power for future success rather than simply describing past performance.

Dataset Overview - The dataset consists of team-level Major League Baseball statistics compiled across multiple seasons.
Unit of analysis: MLB team per season
Time span: Multiple historical seasons (pre-season to season-end metrics)
Data sources: Publicly available baseball statistics
Key variables: Batting metrics (runs scored, on-base percentage, slugging) Pitching metrics (ERA, WHIP, strikeouts)

Method and Analytical Approach
The analysis followed a structured, checkpoint-based workflow:
Checkpoint 1–3: Problem definition, data acquisition, and variable understanding
Checkpoint 4: Data cleaning, feature selection, and construction of team-level metrics
Checkpoint 5: Exploratory data analysis and visual inspection of key relationships
Checkpoint 6: Baseline predictive modeling and performance evaluation
Checkpoint 7: Model refinement using additional predictors and rate-based metrics
Checkpoint 8: Interpretation of results and reflection on limitations

Key Results
Team run production and on-base related metrics show a stronger relationship with future wins than traditional counting stats alone.
Pitching efficiency metrics improve predictive accuracy when combined with batting indicators.
Models using normalized or rate-based statistics outperform simple raw totals.

How to View or Reproduce the Analysis
Open the main Jupyter Notebook (Data6560.ipynb) to view the full analysis workflow.
Supporting datasets are included in Excel format for transparency and review.
All checkpoints are documented in the reports folder and correspond directly to stages of the analysis.
No advanced setup is required beyond a standard Python environment capable of running Jupyter notebooks.

Repository Map
/data – Raw and cleaned datasets used in the analysis
/reports – Checkpoint 1 through Checkpoint 8 write-ups and final reflections
/figures – Final charts and visualizations referenced in the analysis
/project_notes – Reflection notes and supporting documentation
Data6560.ipynb – Main analytical notebook
README.md – Project overview and navigation guide

Limitations and Next Steps
This analysis is limited by the use of team-level aggregates, which may mask individual player effects and situational factors such as injuries or mid-season trades. Additionally, external variables such as payroll, schedule strength, and managerial changes were not included.
Future work could incorporate player-level data, advanced metrics, or machine learning models to improve predictive performance and robustness.

Matthew DeMarco and I worked with Daniel Saya as part of DATA 6560 – Sports Analytics final project



