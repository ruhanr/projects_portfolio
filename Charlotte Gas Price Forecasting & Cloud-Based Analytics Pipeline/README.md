# Charlotte Gas Price Forecasting & Cloud-Based Analytics

## Overview
This project develops a cloud-based data pipeline and machine learning model to forecast gasoline prices across the Charlotte metropolitan area. Historical gas price data was collected, processed, and integrated with AWS cloud storage to support predictive modeling and geospatial visualization.

## Data Sources
- AAA historical gasoline price data
- GitHub REST API (US-Gas-Prices repository)
- Charlotte-Gastonia-Rock Hill metropolitan area

## Methods
- API-based data extraction and processing using Python
- Cloud data storage and integration using AWS S3 and Boto3
- Historical data reconstruction and weekly aggregation
- Linear Regression for time-series forecasting
- Predictive modeling using 102 weeks of historical data
- Interactive geospatial visualization using ArcGIS

## Results
- Developed an API-to-AWS S3 data pipeline for collecting and storing regional gasoline price data
- Generated 52-week gasoline price forecasts using Linear Regression (R² = 0.37)
- Created interactive ArcGIS visualizations and historical price trend graphs to communicate model predictions
