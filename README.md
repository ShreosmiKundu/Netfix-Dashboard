# 🎬 Netflix Data Analysis Dashboard

## Project Overview

This dashboard was developed to demonstrate advanced data modeling and visualization capabilities in Power BI. The primary goal was to successfully replicate a complex, professional dashboard design using real-world streaming data to perform key content and audience analysis. This project serves as a comprehensive example of data integration, meticulous cleaning, and aesthetic replication.

## Key Features & Insights

| Section | Purpose | Key Metric |
| :--- | :--- | :--- |
| *KPI Section* | Provides an instant overview of catalog size and quality. | Average IMDb Score, Total Shows/Movies Count. |
| *View Rating* | Analyzes audience restrictions (e.g., TV-MA, PG-13). | Percentage breakdown of content by age certification. |
| *Show Duration* | Breaks down the content catalog by runtime. | Distribution of movies by duration (0-60 min, 60-120 min). |
| *Yearly Release* | Tracks content production volume over time. | Total volume of content released per year. |

## Technical Accomplishments

* *Data Modeling:* Successfully established a *One-to-Many relationship* between the Titles and Credits tables to link content metrics with cast/crew data.
* *Data Cleaning:* Solved inconsistencies in the runtime column by isolating *Movie data* to ensure accurate minute-based duration calculations.
* *Custom DAX:* Created measures for complex ratios (e.g., Total Movies, Average IMDb Score) and used *Power Query Bins* for grouping numerical data.
* *Aesthetic Replication:* Used *shape and text box layering* to perfectly integrate icons and achieve the detailed, segmented look of the original dashboard.

***

*File:* Netflix_Dashboard.pbix