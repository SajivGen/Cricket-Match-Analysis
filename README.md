# Cricket Match Data Analysis

## Project Overview

This project aims to scrape, process, analyze, and visualize cricket match data from Cricsheet. Using Selenium, SQL, Python (pandas, matplotlib, seaborn, plotly), and Power BI, the project extracts key insights into player performance, team statistics, and match outcomes.

## Business Use Cases

**Player Performance Analysis:** Evaluate player stats across formats (Test, ODI, T20, IPL).

**Team Insights:** Compare team performance over time.

**Match Outcomes:** Identify win/loss patterns and trends.

**Strategic Decision-Making:** Provide insights for analysts, coaches, and management.

**Fan Engagement:** Interactive dashboards for exploring match data.

## Approach

### 1. Data Scraping Using Selenium

Automate navigation to Cricsheet.

Download and store JSON files for different match formats.

### 2. Data Transformation

Parse JSON files using pandas.

Create separate DataFrames for Test, ODI, and T20 matches.

### 3. Database Management

Create an SQL database (MySQL/SQLite).

Design tables for test_matches, odi_matches, and t20_matches.

Insert cleaned data using SQLAlchemy or database connectors.

### 4. SQL Queries for Data Analysis

- Write 20 SQL queries to extract insights, such as:

Top 10 batsmen by total runs (ODI)

Leading wicket-takers (T20)

Highest win percentage teams (Test)

Total centuries across formats

Matches with the narrowest margin of victory

### 5. Exploratory Data Analysis (EDA)

Generate 10 visualizations using matplotlib, seaborn, and plotly.

Compile insights into a presentation.

### 6. Power BI Dashboard

Connect Power BI to the SQL database.

Visualize:

Player performance trends (batting, bowling).

Match outcomes by teams.

Win/loss analysis across formats.

Comparative team and player statistics.

## Results

Automated JSON data extraction from Cricsheet.

Structured SQL database for different match formats.

SQL queries providing deep cricket insights.

Dynamic Power BI dashboard for data visualization.

## Technologies Used

Web Scraping: Selenium

Data Processing: Python (pandas, matplotlib, seaborn, plotly)

Database: MySQL/SQLite, SQLAlchemy

Data Visualization: Power BI

## How to Run the Project

Set up dependencies: Install Selenium, pandas, SQLAlchemy, and visualization libraries.

Run the scraper: Execute the Selenium script to download JSON data.

Process data: Transform JSON data into structured DataFrames.

Load into SQL: Insert data into the SQL database.

Execute SQL queries: Run the 20 predefined queries.

Perform EDA: Generate visualizations.

Build Power BI Dashboard: Connect to SQL and create reports.

## Future Enhancements

Automate dashboard updates.

Integrate machine learning for predictive analytics.

Expand analysis to include more detailed match insights.

This project provides valuable cricket insights using data-driven techniques, enhancing both strategic decision-making and fan engagement.
