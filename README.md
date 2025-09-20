# Google Capstone Projects

This repository contains two data analysis projects completed as part of the Google Data Analytics Professional Certificate:

## 1. Cyclistic Bike-Share Analysis

### Overview
Analysis of Cyclistic's bike-share program data to understand the differences between annual members and casual riders. The project aims to help convert casual riders into annual members through data-driven insights.

### Data
- Time period: April 2021 - March 2022
- Monthly trip data containing ride details including:
  - Trip start and end times
  - Station information
  - Rider types (member/casual)
  - Bike types

### Analysis Features
- Data cleaning and preparation
- Trip duration analysis
- Usage patterns by rider type
- Temporal analysis (daily, weekly patterns)
- Geographic usage patterns
- Visual analytics using Python (matplotlib, seaborn)
- Interactive visualizations with Plotly

## 2. Fitabase Fitness Tracking Analysis

### Overview
Comprehensive analysis of fitness tracking data to understand user behavior and health patterns using various metrics collected through wearable devices.

### Data Components
- Daily Activity Metrics
  - Steps, calories, and intensity minutes
  - Distance covered
  - Activity levels throughout the day

- Detailed Health Metrics
  - Heart rate data (seconds-level granularity)
  - Sleep patterns
  - Weight logs
  - Calorie burn rates
  - MET (Metabolic Equivalent of Task) readings

### Analysis Features
- Data aggregation and cleaning
- Activity pattern analysis
- Sleep quality assessment
- Heart rate analysis
- Correlation studies between different health metrics
- Visual analytics for pattern identification
- Time-series analysis of health metrics

## Technical Implementation
Both projects are implemented using:
- Python for data analysis
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- Jupyter Notebooks for interactive analysis and documentation

## Project Structure
```
├── cyclistic.ipynb           # Cyclistic bike-share analysis notebook
├── fitabase.ipynb           # Fitabase fitness data analysis notebook
├── cyclistic data/          # Monthly trip data files
└── fitabase data/          # Various fitness tracking data files
```