# IPL-Data-Analysis
IPL Data Engineering &amp; Analytics Project using PySpark and AWS S3. This project processes ball-by-ball IPL cricket data, builds structured schemas, performs feature engineering, and generates insights such as top batsmen per season, most economical bowlers in powerplay, and team trophy counts using Spark SQL and window functions.
# IPL Data Engineering & Analytics using PySpark

## Overview
This project analyzes Indian Premier League (IPL) cricket data till 2017 using **PySpark and AWS S3**.  
The dataset includes **ball-by-ball match data, player information, match results, and team details**.

The goal of this project is to demonstrate **data engineering workflows and sports analytics using Spark**, including data ingestion, schema design, feature engineering, aggregations, and advanced SQL analytics.

---

## Tech Stack

- PySpark
- Spark SQL
- AWS S3
- Python
- Matplotlib
- Pandas
- Window Functions

---

## Dataset

The project uses IPL historical datasets stored in S3:

- Ball_By_Ball.csv
- Match.csv
- Player.csv
- Player_match.csv
- Team.csv

These datasets contain:

| Dataset | Description |
|------|------|
| Ball_By_Ball | Delivery level match data |
| Match | Match results and season details |
| Player | Player information |
| Player_match | Player participation per match |
| Team | Team metadata |

---
