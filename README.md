# nba-injury-analysis
NBA workload vs injury risk analysis using SQL and Tableau
# NBA Workload vs Injury Risk Analysis

## Overview
This project analyzes the relationship between NBA player workload (games played and minutes played) and injury risk. The goal is to understand whether higher workloads increase injury likelihood and to identify safe workload ranges.

---

## Business Question
How do games played and minutes played impact injury risk among NBA players, and does age influence this relationship?

---

## Tools Used
- SQL (data analysis)
- Excel (data cleaning)
- Tableau (data visualization)

---

## Data Sources
- NBA player statistics dataset (minutes, games played, performance)
- NBA injury dataset (injury occurrence, games missed)
- Player age data

---

## Data Cleaning
- Standardized player names across datasets
- Handled missing values
- Created new fields:
  - Minutes per game
  - Injury flag (0 = no injury, 1 = injured)
  - Age groups (Under 25, 25–29, 30–34, 35+)

---

## Analysis Performed
- Compared average minutes played between injured and non-injured players
- Analyzed injury rates by workload buckets
- Examined injury risk across age groups
- Evaluated combined effect of age + workload on injuries

---

## Dashboard
Interactive dashboard built in Tableau Public:  
👉 [Add your Tableau link here]

---

## Key Insights
- Injury rates increase with higher average minutes played
- Older players show higher injury risk at the same workload levels
- Moderate workloads (25–30 minutes) appear to balance performance and injury risk

---

## Recommendations
- Limit excessive minutes for high-risk age groups
- Increase rest for players with heavy schedules
- Monitor players exceeding workload thresholds

---

## Project Structure
- /data → raw and cleaned datasets
- /sql → SQL queries used for analysis
- /images → charts and visuals
- /dashboard → dashboard link or files

---

## Future Improvements
- Include multiple seasons for deeper analysis
- Add advanced performance metrics (efficiency ratings)
- Improve injury prediction modeling
