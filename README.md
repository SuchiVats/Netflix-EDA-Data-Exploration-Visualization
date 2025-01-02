# Netflix Data Exploration and Visualization

## Project Overview
This project focuses on analyzing Netflix's movie and TV show dataset to generate actionable insights. By exploring various aspects of the dataset, we aim to help Netflix make data-driven decisions about content production and business growth strategies in different countries. The project involves comprehensive exploratory data analysis (EDA), including visualization techniques and generating business insights.

## Dataset Information
The dataset contains a list of all the movies and TV shows available on Netflix. Key attributes in the dataset include:

- **Show_id**: Unique ID for every Movie/TV Show
- **Type**: Identifier - A Movie or TV Show
- **Title**: Title of the Movie/TV Show
- **Director**: Director of the Movie
- **Cast**: Actors involved in the movie/show
- **Country**: Country where the movie/show was produced
- **Date_added**: Date the movie/show was added to Netflix
- **Release_year**: Release year of the movie/show
- **Rating**: TV Rating of the movie/show
- **Duration**: Total Duration - in minutes or number of seasons
- **Listed_in**: Genre
- **Description**: Summary description of the movie/show

## Problem Statement
Analyze the Netflix dataset to generate insights that will aid Netflix in determining which type of shows/movies to produce and how they can grow the business in different countries. Specifically, we will focus on answering the following:

- What type of content is available in different countries?
- How has the number of movies released per year changed over the past decades?
- A comparison between TV shows and movies.
- The best time to launch a TV show.
- Analysis of actors and directors across different types of content.
- Does Netflix focus more on TV Shows or Movies recently?
- What content is available in different countries?

## Project Highlights

### Steps Followed:
1. **Data Exploration**: 
   - Checked the shape and types of the dataset.
   - Identified missing values and performed necessary cleaning.
   
2. **Non-Graphical Analysis**:
   - Analyzed value counts, unique attributes, and basic statistics.
   
3. **Visual Analysis**:
   - Conducted univariate and bivariate visualizations.
   - Plotted distribution of continuous variables using histograms and distplots.
   - Used boxplots for categorical variables and correlation heatmaps.

4. **Missing Value & Outlier Check**:
   - Checked for missing values and outliers. Treatment was performed where necessary.

5. **Business Insights**:
   - Provided insights based on data patterns, distributions, and relationships.

6. **Recommendations**:
   - Actionable, business-oriented recommendations without technical jargon.

## Key Insights
- **Content Distribution by Country**: Identified which countries have the most content available on Netflix.
- **Trend Analysis**: Observed how the number of releases has changed over the years.
- **TV Shows vs Movies**: Netflix has been focusing more on TV shows in recent years.
- **Optimal Launch Period**: Recommended the best periods for launching new TV shows based on historical data.
- **Top Actors & Directors**: Found the most popular actors and directors associated with top-rated shows and movies.

## Recommendations for Netflix:
1. **Content Strategy**: Focus on producing more content in regions with growing Netflix subscriber bases.
2. **Optimal Launch Window**: Schedule new TV show releases around peak viewer engagement periods.
3. **Director and Actor Collaboration**: Work with top directors and actors to enhance the appeal of content.

## Tools and Libraries Used
- **Python Libraries**: pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**: For interactive data analysis and visualization

## Evaluation Criteria
1. Defining Problem Statement and Analyzing Basic Metrics
2. Non-Graphical and Graphical Data Exploration
3. Missing Value & Outlier Treatment
4. Insights and Business Recommendations
