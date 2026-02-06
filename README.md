# PySpark Logistics Delay Analytics (Big Data Project)

## Overview
This project analyzes large-scale shipment and hub congestion data using PySpark to identify operational bottlenecks and predict shipment delays.

The objective is to support data-driven decision making in logistics operations through scalable data processing, visualization, and predictive modeling.

## Dataset
A course-provided logistics shipment dataset containing:
- shipment records
- origin/destination hubs
- timestamps (scheduled vs actual)
- congestion indices
- delay minutes

Note: The raw dataset is not included due to course/privacy restrictions.

## Tech Stack
- Apache Spark (PySpark) – distributed big data processing
- Python – analysis & visualization
- Matplotlib – charts & dashboards
- Scikit-learn – predictive modeling

## Big Data Pipeline
1. Data ingestion with Spark
2. Cleaning & deduplication
3. Missing value handling
4. Timestamp parsing
5. Feature engineering (hour, weekday, weekend)
6. Aggregation by hub, route, and time
7. Visualization of delay patterns
8. Predictive modeling

## Key Analysis Performed
- Average delay by origin hub
- Average delay by route
- Delay trends by hour of day
- Congestion vs delay relationship
- Weekend vs weekday comparison
- Delay distribution analysis

## Predictive Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### Evaluation
- R² score
- RMSE

Linear Regression achieved the best overall performance.

## Key Insights
- Major hubs show higher congestion and delays
- Routes connected to congested hubs inherit delay risk
- Peak-hour departures significantly increase delays
- Congestion index strongly correlates with delay time

## Repository Structure
- notebooks/ → PySpark analysis notebook
- report/ → full project report
- figures/ → generated visualizations

## Author
Mira Ibrahim AlSalhi  
Data Science & AI Student  
Big Data | Machine Learning | PySpark
