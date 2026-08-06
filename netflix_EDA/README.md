# Netflix Data Analysis 📊🎬
## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix dataset to discover meaningful insights about Netflix content, audience targeting, genres, ratings, content growth, and viewing trends.

The analysis helps understand:

-  What type of content dominates Netflix
- Which audience Netflix mainly targets
- How Netflix content evolved over time
- Which countries contribute the most content
- Content duration and genre patterns
## Objectives
- Analyze Movies vs TV Shows distribution
- Understand Netflix audience ratings
- Identify top genres and countries
- Study content growth over years
- Analyze movie durations and TV show seasons
- Discover relationships between multiple features
- Generate meaningful business insights from data

| Feature                | Description               |
| ---------------------- | ------------------------- |
| type                   | Movie or TV Show          |
| release_year           | Year content was released |
| rating                 | Audience rating category  |
| listed_in              | Genre/category of content |
| content_age            | Age of content            |
| added_year             | Year added to Netflix     |
| added_month            | Month added to Netflix    |
| movie_duration_minutes | Movie duration in minutes |
| season_count           | Number of TV show seasons |
| genre_count            | Number of genres          |
| cast_count             | Number of cast members    |
| primary_country        | Main producing country    |



# Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns:
- show_id
- director
- description
- cast
- country
- date_added
- duration
- Handled missing values
## Created new useful features
- Converted duration into:
- movie_duration_minutes
- season_count
## Extracted:
- added_year
- added_month
- Created:
- genre_count
- cast_count
- primary_country
- Fixed datatype inconsistencies


# Feature Engineering

New features created during analysis:

- content_age
- movie_duration_minutes
- season_count
- genre_count
- cast_count
- primary_country
- added_year
- added_month

These features helped generate deeper insights and better visualizations.



# Exploratory Data Analysis (EDA)
## Univariate Analysis

Performed analysis on:

- Type distribution
- Rating distribution
- Genre distribution
- Movie duration
- TV Show seasons
- Country distribution
-  growth over years
- Bivariate Analysis

## Analyzed relationships between:

- Type vs Rating
- Country vs Type
- Rating vs Duration
- Release Year vs Type
- Genre vs Rating
- Multivariate Analysis

## Explored:

- Country vs Type vs Duration
- Added Year vs Rating vs Type
- Release Year vs Duration vs Rating
- Type vs Added Year vs Genre Count
- Type vs Added Year vs Cast Count


# Key Insights
- Movies dominate Netflix content compared to TV Shows.
- TV-MA and TV-14 are the most common ratings.
- Netflix mainly targets adult and teenage audiences.
- Drama and International Movies are the most popular genres.
- Most movies have durations between 80–120 minutes.
- Netflix content growth increased rapidly after 2015.
- United States and India are top content-producing countries.
- Mature audience content dominates most genres.
- Multi-genre content increased in recent years.
- TV Shows usually contain 1–3 seasons.

# Hypothesis
## Hypothesis 1

- Netflix mainly focuses on mature audience content.

### Result:

- Supported by dominant TV-MA and TV-14 ratings.

## Hypothesis 2

- Netflix content growth increased rapidly after 2015.

### Result:

- Strongly supported by yearly content growth analysis.Hypothesis


# Project Outcome

This EDA project helped in:

- Understanding streaming platform trends
- Discovering audience behavior patterns
- Analyzing content strategies
- Building strong data visualization and analysis skills

## Author

Priyanshu Sahu
Netflix Data Analysis Project 🚀
