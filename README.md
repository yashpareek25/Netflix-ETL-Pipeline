# Netflix ETL Pipeline

## Overview
End-to-end ETL pipeline for Netflix content dataset using Python and Pandas on Kaggle Notebooks.

## Technologies Used
- Python
- Pandas
- SQLite
- Plotly
- Kaggle Notebooks

## Dataset
- Source: Kaggle — Netflix Movies and TV Shows by Shivam Bansal
- Records: 8,807
- Columns: 12

## Pipeline Architecture
netflix_titles.csv
↓
Pandas — Data Extraction
↓
Data Quality Check
↓
Data Cleaning & Transformation
↓
Feature Engineering
↓
SQLite Database
↓
Plotly Visualizations

## Key Stats
- Records after cleaning: 8,794
- Duplicates removed: 13
- Movies: 6,128
- TV Shows: 2,666

## New Features Engineered
| Column | Logic |
|---|---|
| year_added | Extracted from date_added |
| month_added | Extracted from date_added |
| duration_minutes | Minutes for Movies |
| season_count | Seasons for TV Shows |
| primary_country | First country extracted |
| primary_genre | First genre extracted |
