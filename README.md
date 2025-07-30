# Netflix Insights: A Comprehensive Data Analysis

This project explores a Netflix dataset to find trends related to content types, genres, ratings, and release patterns. The main goal was to practice data analysis and visualization using Python.

## About the Project

Netflix is one of the most popular streaming platforms, and I wanted to analyze its dataset to understand what kind of content is available and how it's changed over time. Some of the main questions I tried to answer:

- Does Netflix have more TV shows or movies?
- How has content been added over the years?
- Which ratings are most common on Netflix?
- What genres are most frequent?
- Which countries contribute the most content?

This project helped me practice:
- Cleaning real-world data with missing or inconsistent values
- Grouping and filtering data to get specific insights
- Making different types of visualizations to present the findings

## Dataset

I used a public dataset of Netflix titles which includes:
- Title
- Type (Movie / TV Show)
- Genre (listed as ‘listed_in’ in the dataset)
- Country
- Rating (like TV-MA, PG, etc.)
- Date Added (when the content was added to Netflix)
- Duration
- Description

Some columns had missing data, especially ‘country’ and ‘date_added’. I used basic techniques like dropping or filling values based on context.

## Visualizations

These are the main visualizations included:

- Donut Chart: Distribution of TV Shows vs Movies  
- Year-wise Donut Charts (2016–2020): TV Shows vs Movies per year  
- Genre-wise Bar Chart: Top genres based on content count  
- Stacked Bar Chart: Ratings split by content type  
- Horizontal Bar Chart: Top countries by number of titles  

All charts follow a dark-themed (Netflix-style) design using black and red tones.

## Tools & Libraries Used

- Python (3.x)
- Pandas – for data handling and cleaning
- Matplotlib – for visualizations
- Seaborn – for enhanced visuals
- Jupyter Notebook – to write and run the code




