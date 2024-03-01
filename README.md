# Amazon Prime Titles Dataset Analysis

## Overview
This dataset contains information about movies and TV shows available on Amazon Prime. It includes various details such as the type of content (movie/TV show), title, director, cast, country of origin, release year, rating, duration, genres, and a brief description.

## Dataset Description
- `show_id`: Unique identifier for each title
- `type`: The type of content (Movie/TV Show)
- `title`: Title of the movie or TV show
- `director`: Director of the movie or TV show
- `cast`: Cast involved in the movie or TV show
- `country`: Country where the movie or TV show was produced
- `date_added`: Date when the title was added to Amazon Prime
- `release_year`: Year of release of the title
- `rating`: Rating of the title
- `duration`: Duration of the title (different units for movies and TV shows)
- `listed_in`: Genres the title belongs to
- `description`: Brief description of the title

## Data Cleaning and Preprocessing
The dataset underwent several cleaning steps:
1. Handling missing values by filling or removing them.
2. Correcting data types for specific fields.
3. Parsing and standardizing certain columns for uniformity.

## Exploratory Data Analysis (EDA)
We performed various analyses, including but not limited to:
- Univariate analysis to understand distributions of individual variables.
- Bivariate and multivariate analyses to explore relationships between different variables.
- Text analysis for genre popularity and keyword extraction from titles and descriptions.

## Visualizations
Several visualizations were created using Matplotlib and Seaborn, including histograms, box plots, scatter plots, and heatmaps to better understand the data's distributions and relationships.

## Insights and Observations
Key insights derived from the analysis include:
- Trends in content types and release years.
- Popularity of genres.
- Correlations between various numerical variables.
- Common themes and keywords across titles.

## Further Research and Analysis
Potential areas for further investigation could involve:
- A deeper analysis of genre-specific trends.
- Comparative analysis with datasets from other streaming platforms.
- Advanced text analytics for sentiment analysis or thematic categorization.
