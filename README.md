# IPL Data Analysis with Apache Spark on Databricks

![Apache Spark](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

A comprehensive **data engineering and analytics project** analyzing IPL cricket data using **Apache Spark on Databricks**. This project demonstrates advanced data processing, SQL analytics, and visualization skills, handling a dataset of **2.5+ million rows** stored in an **AWS S3 bucket**.

---

## 📌 Overview
This project analyzes **15+ years of IPL match data** to uncover insights about player performance, team strategies, and match dynamics. Built with **PySpark on Databricks**, it includes:
- **ETL pipelines** for processing raw CSV data stored in AWS S3
- Advanced Spark operations (Aggregations, Window Functions, Joins)
- SQL-based analytical queries
- Data visualization with **Matplotlib** and **Seaborn**
- Data quality checks, schema enforcement, and optimization

---

## 🛠️ Technologies
- **Apache Spark 3.5.4** (PySpark API)
- **Databricks** (Notebook Environment)
- **AWS S3** (Data Storage)
- **Python 3.13**
- **Matplotlib** and **Seaborn** (Visualization)
- **Spark SQL** (Analytical Queries)

---

## 📂 Datasets
The dataset, sourced from **Sportskeeda**, includes:
1. **Ball-by-Ball Data** (2.5+ million rows, 200+ columns per delivery)
2. **Match Data** (Teams, Venues, Results)
3. **Player Data** (Skills, Career Details)
4. **Team Data**

Sample Schema for Ball-by-Ball Data:


## 🔥 Key Features
**Data Processing**
- **Schema enforcement for data quality**
- **Handling missing values and data cleaning**
- **Derived columns (e.g., high_impact balls, win_category_margin)**
- **Date/time transformations and optimizations for large datasets**

## **Analytical Queries**
Top batsmen per season

Economical bowlers in powerplay overs

Toss impact on match outcomes

Average runs scored by batsmen in winning matches

Team performance after winning toss

## **Visualizations**
Most Economical Bowlers in Powerplay Overs

Impact of Winning Toss on Match Outcomes

Average Runs Scored by Batsmen in Winning Matches

Distribution of Scores by Venue

Team Performance After Winning Toss

## 📊 Key Insights
Impact of Toss: Teams winning the toss and choosing to bat first win 65% of matches
![toss_impact_pd](https://github.com/user-attachments/assets/6981ceed-2be6-469c-b209-44e5e1053bc9)
Teams winning the toss win 58% of matches
![Team-perfomance-after-toss](https://github.com/user-attachments/assets/5fe58860-b1d5-410b-a588-5b4cf8ef6edc)
Average powerplay score increased by 22% from 2010-2020
![average_runs_pd](https://github.com/user-attachments/assets/f17e7745-f7f3-4cc0-965a-f17bc3bf6a1c)
Right-handed batsmen contribute 63% of total runs

Wankhede Stadium has the highest average score (189 runs)
![scores_by_venue_pd](https://github.com/user-attachments/assets/7916a270-8e73-4b2e-95a3-767d97707945)
Top 3 Economical Bowlers in Powerplay Overs: Bowler A, Bowler B, Bowler C
![economical_bowlers_pd](https://github.com/user-attachments/assets/bfd84579-d84c-4264-a237-1d716629182a)

