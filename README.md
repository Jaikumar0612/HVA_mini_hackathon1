# IMDb Dataset Analysis - HVA Mini Hackathon1

## Project Overview

This project was developed as part of the HVA Mini Hackathon1, where participants were tasked with analyzing the IMDb dataset. The focus of the project is on understanding various factors that influence the success of movies. 

## Dataset

The dataset used in this analysis is the IMDb Top 1000 movies dataset. It contains information about movies such as title, genre, director, actors, IMDb ratings, gross earnings, and more. 

### Data Cleaning

The initial dataset was cleaned using Microsoft Excel, where irrelevant or inconsistent data entries were removed or corrected. The cleaned dataset was saved as `cleaned_imdb_top_1000.csv` for further analysis.

## Analysis

The cleaned dataset was uploaded to Google BigQuery to perform detailed analysis on the following key areas:

1. **Director's Impact on Earnings**: 
   - Analyzed how movies directed by different directors perform in terms of gross earnings.
   - Identified noticeable trends or patterns in earnings based on the director.

2. **Genre Popularity Over the Years**: 
   - Investigated how different genres have evolved in popularity over time.
   - Assessed which genres have become more or less popular.

3. **Correlation Between IMDb Ratings and Commercial Success**:
   - Explored if there's a relationship between a movie's IMDb rating and its box office earnings.
   - Examined whether higher-rated movies generally perform better commercially.

4. **Impact of Movie Length on Ratings or Earnings**: 
   - Examined whether the duration of a movie influences its IMDb ratings or financial success.
   - Analyzed whether longer or shorter movies tend to have higher ratings or earnings.

5. **Actor Influence on Movie Success**: 
   - Analyzed how the presence of certain actors correlates with a movie's performance in terms of ratings and earnings.
   - Investigated which actors are associated with the highest-rated or highest-earning movies.

## Visualization

The insights derived from the analysis were visualized using Power BI. The visualizations highlight the key findings and trends observed during the analysis. The Power BI report is saved as `HVA_Hackathon.pbix`.

## Repository Contents

- `cleaned_imdb_top_1000.csv`: The cleaned dataset used for analysis.
- `HVA_Hackathon.pbix`: Power BI file containing the visualizations of the analysis.
- `imdb_top_1000.csv`: uncleaned data
- `imdb_dataset_sql_queries.docx`-Queries present in the google big query.
- `README.md`: This file providing an overview of the project.

## Getting Started

To explore the analysis and visualizations, you can access the dataset and analysis directly through Google BigQuery.

1. **Access Google BigQuery**:  
   [Click here to access the Google BigQuery project](https://console.cloud.google.com/bigquery?sq=927474283843:73d3d045da4c41dcbd27dad359b317a0) and explore the queries and data analysis results.
