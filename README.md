# IMDB_Movie_Analysis
=============================

## Introduction
------------

This project aims to provide a comprehensive analysis of current box office trends to guide the strategic decisions for our new movie studio. By leveraging data from multiple sources, we aim to identify the types of films that are currently performing best at the box office and translate these findings into actionable insights.

# Objectives
----------

1.  **Identify the Highest Grossing Films**: Determine which movies are leading in box office earnings.
2.  **Determine the Most Common Genres Among Top-Grossing Movies**: Analyze the prevalent genres among the highest-grossing films.
3.  **Analyze the Correlation Between Box Office Performance and Movie Ratings**: Investigate how movie ratings correlate with their box office success.
4.  **Identify the Most Successful Film Studios**: Recognize the studios that produce the most successful films.



Datasets Used In this project
-------------

1.  **`im.db.zip`**: Zipped SQLite database containing `movie_basics` and `movie_ratings` tables.
2.  **`bom.movie_gross.csv.gz`**: Compressed CSV file with box office gross information.

Project Steps
-------------

### 1\. Data Extraction and Cleaning

*   **SQLite Database**:
    *   Extracted and cleaned data from `movie_basics` and `movie_ratings` tables.
    *   Dropped rows with null values in crucial columns like `original_title` and `genres`.
    *   Merged the tables on the `movie_id` column.
*   **CSV File**:
    *   Loaded and cleaned `bom.movie_gross.csv.gz`.
    *   Removed commas and converted the `foreign_gross` column to numeric.
    *   Filled missing values in `foreign_gross` with the median of the column.

### 2\. Data Merging

*   Merged the cleaned data from the SQLite database with the cleaned CSV data using the `title` and `year` columns.

### 3\. Calculated columns

*   Created new columns like `total_gross` by summing `domestic_gross` and `foreign_gross`.
*   Condensed filters using parameters inorder to enhance a more user-friendly dashboard.

### 4\. Visualization and Analysis

*   Generated key visualizations to meet project objectives:
    1.  Bar charts and line graphs to identify highest-grossing films.
    2.  Box plot showing ratings for genre over time .
    3.  Bar chart showing top 6 genres per their income both foreign,domestic and total gross income.
    4.  Line graph indicating top 5 studios per their total gross income.

### 5\. Dashboard Creation

*   Created an interactive dashboard in Tableau, including:
    *   Key Performance Indicators (KPIs).
    *   Dynamic filters using parameters.
    *   Interactive visualizations to explore data insights.

Dashboard Title
---------------

**IMDB_Movie_Analysis**

### 6\. Dashboard visualization
![alt text](image.png)


**Unlocking IMDB_Movie_Analysis: A Comprehensive Analysis of Top-Grossing Genres**

Welcome to our Strategic Insights Dashboard! This tool provides a deep dive into the current trends in the movie industry, offering actionable insights to guide our new movie studio's strategic decisions. Explore the data to discover:

1.  **Highest Grossing Films both domestic,foreign and gross**: Identify the top-performing movies at the bar graph.
2.  **Popular Genres**: Locate the most common genres among high-grossing films.
3.  **Performance and Ratings relation**: Analyze how income success aligns with movie ratings.
4.  **Top 10 movie Studios**: Recognize the studios behind the most successful films.

### 7\. Recommendations.
1.**Focus on Popular Genres**
Prioritize making movies in genres like Action, Adventure, and Animation, which consistently do well at the box office.

2.**Partner with Successful Studios**
Collaborate with studios known for high-grossing films to benefit from their expertise and increase your chances of success.

3.**Create High-Quality Content**
Aim for movies that get good ratings by investing in strong scripts, talented directors, and high production values.

4.**Target International Markets**
Develop strategies to attract international audiences by considering global trends, including diverse cultural elements, and tailoring marketing campaigns to different regions.

5.**Use Data for Decisions**
Regularly collect and analyze data to guide your decisions. Use data analytics tools and hire analysts to monitor trends and adjust strategies.

6.**Invest in Marketing**
Allocate a significant budget for marketing and promotion. Use social media, influencers, and traditional media to maximize visibility and attract audiences.

7.**Try New Formats and Platforms**
Explore new formats like streaming services, virtual reality, and interactive content to stay ahead of industry trends and reach new audiences.


Conclusion
----------

This project provides a solid foundation for understanding the current trends in the movie industry. By leveraging the insights gained from this analysis, our new movie studio can make informed decisions to produce content that resonates with audiences and achieves box office success.

Contact
-------

For any questions or further information, please contact \[Muli Lilian Mwikali\] at \[mulililian2017@gmail.com\].