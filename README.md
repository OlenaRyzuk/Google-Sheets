# Cohort Analysis of Game Players

## Description
This project contains a **cohort retention analysis** of game players over a 10-month period, together with engagement metrics (DAU, WAU, Stickiness). The goal is to understand player retention, user activity trends, and engagement dynamics.

## Key Cohort Data
- **Cohort size at Month 0:** 216 users  
- **Active users at Month 9:** 27 users  
- **Overall retention from Month 0 → Month 9:** 13%  
- **Month 9 cohort retention:** 57%

## Engagement Metrics
- **DAU (Daily Active Users):** increasing over time.  
- **WAU (Weekly Active Users):** also increasing, showing expansion of the active user base.  
- **Stickiness (DAU/WAU):** stable — daily vs. weekly usage ratio is consistent.

## Key Insights
- The steepest drop-off occurs in the first months after onboarding.  
- After Month 5, retention stabilizes, forming a loyal core of players.  
- Growing DAU and WAU confirm that the game continues to attract and activate more players.  
- Stable Stickiness indicates consistent user activity patterns.  

## Project Data
All data for this analysis is available in a single **Google Sheet**:
- [View Cohort & Engagement Data](https://docs.google.com/spreadsheets/d/1cOm9vqfeQqBHWsLseepIOG3EaPkCYMUiG6ga8GIjV8s/edit?usp=sharing) — includes:  
  - Monthly active users  
  - Cohort retention table  
  - DAU, WAU, and Stickiness metrics  
  - Optional slicers for interactive analysis 

## Technologies Used
- Google Sheets (pivot tables, slicers, retention analysis, engagement metrics)

## Methodology
1. Cohorts were created by players’ first activity month (Month 0 = onboarding).  
2. For each cohort, active users were counted for every subsequent month.  
3. In this case we use **Absolute retention (%)** = active users at Month N ÷ initial cohort size.  
4. DAU and WAU were calculated as unique active users per day/week; Stickiness = DAU ÷ WAU.

## Business Takeaways
- **Positive growth in DAU & WAU:** the games are attracting and activating new users.  
- **Stable Stickiness:** users maintain consistent engagement patterns.  

## Recommendations  
- Improve onboarding to reduce early churn.
- Consider re-engagement campaigns for players who drop off between Months 1–4.
