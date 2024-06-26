# Movie Data Analysis Project
## Overview

This repository contains the code and data used to analyze several movie databases. The primary goal of this project is to extract and evaluate various aspects of movies, such as return on investment, ratings by genre, and the best directors, writers, and actors.

## Business Problem

Our project focuses on solving critical challenges faced by stakeholders in the film industry:

- Optimizing Release Days: When should a movie be released to maximize profits?

- Identifying High-Rated Genres: How do movie ratings vary across different genres?

- Highlighting Key Contributors: Who are the top directors, writers, and actors in the highest rated genres?

Through data-driven insights, our project allows stakeholders to make more informed decisions, optimize resources, and enhance overall performance in the film production industry.

### Table of Contents

- [Project Description](project-description)
- [Data Sources](data-sources)
- [Installation](installation)
- [Usage](usage)
- [Analysis and Results](analysis-and-results)
  - [Profit vs. Release Date](profit-vs-release-date)
  - [Ratings by Genre](ratings-by-genre)
  - [Top Directors](top-directors)
  - [Top Writers](top-writers)
  - [Top Studios](top-studios)
  - [Runtime](runtime)
  - [Top Actors](top-actors)
- [Conclusions](conclusions)
- [Recommendations](recommendations)

### Our analysis is divided into several sections, each targeting a specific aspect of the data.
### Data Sources

The data used in this project is sourced from the following movie databases:

- [IMDb](https://www.imdb.com/)
- [The Movie Database (TMDb)](https://www.themoviedb.org/)
- [Box Office Mojo (BOM)](https://www.boxofficemojo.com/)
- [Rotten Tomatoes (RT)](https://www.rottentomatoes.com/)
- [The Numbers (TN)](https://www.the-numbers.com/)

# Data Science Steps

### The project follows these data science steps:

- Data Collection: Gathering data from various movie databases.
- Data Cleaning: Processing and cleaning the data to ensure accuracy and consistency.
- Exploratory Data Analysis: Exploring the data to uncover initial insights and patterns.
- Dataframe Merging: Combine datasets which have common columns. 
- Data Analysis: Conducting the main analysis to answer our key questions.
- Visualization: Visualizing the results to communicate findings effectively.
- Conclusion and Recommendations: Summarizing the findings and providing recommendations.

# Installation

## To run the analysis, you'll need to set up your environment with the necessary dependencies. Follow these steps:

- Clone the repository: https://github.com/Gfatouras/Phase2
- Install requirements: pip install -r requirements.txt

# Analysis and Results
## Profit vs. Release Date

We calculated the ROI for movies by comparing their net profit and their release date.

![image](https://github.com/Gfatouras/Phase2/assets/165408353/93f5ccb5-ef9b-42f5-ab0b-ce85d70d1db6)

![image](https://github.com/Gfatouras/Phase2/assets/165408353/c38b7708-02a9-42b3-8544-cea76397e252)

![image](https://github.com/Gfatouras/Phase2/assets/165408353/bda48d11-5c54-4a12-97b2-ad827f15a257)

## Ratings by Genre

Our genre analysis examines how movie ratings differ across various genres. We use average ratings from IMDb, TN, and TMDb to provide a comprehensive view.

![image](https://github.com/Gfatouras/Phase2/assets/165408353/ea31925c-3d8b-49b5-88ce-4eda003ce691)

Since documentary and animation movies had the highest ratings, we will be focusing on actors, directors, writers, and studios that all worked on these two genres for our final reccommendation.

## Top Directors
We matched the highest ratings to each director, and created a list of the top directors by film ratings.

- Documentary:
  - Amy Berg, James Marsh, Lauren Ross, Jean and John Griesser
- Animation:
  - Brad Bird, Brett Morgan, Don Hertzfeldt and Don Argott

## Top Writers
Similarly, we analyzed the performance of writers. The results highlight those who have consistently delivered high-rated movies within our selected genres.

- Documentary
    - Amy Berg and Marc Monroe
- Animated
    - Brad Bird and Brett Morgan

## Top Studios
We analyzed which studios created the highest rated animation and documentary films.

- Documentary
    - Lionsgate Films
- Animated
    - Buena Vista Pictures
      
## Top Actors
Our analysis also extends to animation voice actors. Showcasing those who have starred in the highest-rated animation films.

- Animated
    - Louie Arnette and Blair Jackson

## Runtime
We also analyzed which runtime results in the highest ratings.

- Documentary
    - 101 minutes
- Animated
    - 115 minutes

# Conclusion
## Profit vs. Release Day:
- 80.71% of all movie profits since 2000 went to movies that were released on a Friday.
- Movies that were released in May, June, July, November, and December saw significantly higher profits than the rest of the months. 
    + 65.3% of total profits went to movies that were released in these 5 months.
    + This is 41.76% of the year, so these 5 months combined see 23% more profit on average.

## Genre Type
- Domestic Fiction v Non-Fiction
    - Non-Fiction films have higher ratings than Fiction films. However, these are the two top level genres of film. The top performing genre in each category are listed below. 
    - Non-Fiction
        - Documentary films
    - Fiction
        - Animated Films
        - 
# Recommendations
## Movie Type
## Documentary:
- Directors: Amy Berg, James Marsh, Lauren Ross, Jean and John Griesser
- Writers: Amy Berg and Marc Monroe
- Studios: Lionsgate Films
- Runtime: 101 minutes
## Animation:
- Directors: Brad Bird, Brett Morgan, Don Hertzfeldt and Don Argott
- Writers: Brad Bird and Brett Morgan
- Actors/Actresses: Louie Arnett and Blair Jackson
- Studios: Buena Vista Pictures
- Runtime: 115 minutes
## Release Date:
- Months: May, June, July, November, December
- Week of month: 3rd
- Day of Week: Friday

## Links
- Presentation: https://docs.google.com/presentation/d/1TgmvEbbpETPElT5eZp1UfDWB7LpRZdMvuUvKGzIyA5U/edit#slide=id.g2e6eb824385_0_165
- Jupyter Notebook: https://github.com/Gfatouras/Phase2/blob/main/Phase_2_Project_-_Movie_Analysis.ipynb
