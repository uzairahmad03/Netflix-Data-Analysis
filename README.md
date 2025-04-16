# Netflix Data Analysis
![NETFLIX](Images/thibault-penin-AWOl7qqsffM-unsplash.jpg)

This project explores Netflix's content catalog through detailed data analysis to uncover insights into trends, genres, and production patterns. Using Python and libraries like Pandas, Matplotlib, and Seaborn, the analysis covers aspects such as the distribution of movies vs. TV shows, top genres, country-wise content production, and content release trends over the years. The goal is better to understand Netflix’s global content strategy and user preferences.

## Introduction
This project dives into Netflix's dataset to uncover insights about its content library. Using Python and data visualisation tools, we explore trends in genres, content types, release years, and country distributions. The goal is to analyse patterns and understand how Netflix's content offering has evolved over time.
Interactive visualisations and summary statistics help highlight key findings, making it easier to spot content trends and regional preferences.

## About Netflix
Netflix is a global streaming service that offers a wide variety of TV shows, movies, documentaries, and original content across multiple genres and languages. Founded in 1997, it has grown to become one of the world’s leading entertainment platforms, with millions of subscribers in over 190 countries.
The platform is known for its data-driven approach to content recommendations and has produced award-winning originals like Stranger Things, The Crown, and Money Heist. Its constantly evolving library reflects global viewing trends and regional preferences.

## Business Task
Netflix has established itself as a leader in data science, artificial intelligence, and machine learning, especially in developing advanced recommendation systems that analyse customer behaviour and viewing patterns. Imagine you are in a data-focused role with access to a dataset containing over 9,000 movies. Your task is to analyse this data to answer key questions that will support Netflix in making well-informed business decisions.

Questions to Explore:

What is the most common genre of movies released on Netflix?

Which movie has the highest average vote score?

Which movie has the highest popularity, and what is its genre?

Which movie has the lowest popularity, and what is its genre?

Which year saw the highest number of movies released?

In this project, I take on the role of a data analyst tasked with examining a dataset containing over 9,000 Netflix movies. The objective is to extract meaningful insights that can help inform strategic business decisions. Through this analysis, I aim to answer important questions related to genre trends, viewer ratings, movie popularity, and yearly production patterns.

### Ask Phase
The Ask phase is the foundation of the data analysis process, where we define the business goals and frame the right questions to guide the analysis. For this project, the objective is to support Netflix in making data-driven content decisions by understanding user preferences, content performance, and production trends.

Based on the dataset of over 9,000 movies, the key business questions to address are:

What is the most frequent genre of movies released on Netflix?

Which movie has received the highest average vote?

Which movie has the highest popularity, and what is its genre?

Which movie has the lowest popularity, and what is its genre?

Which year saw the highest number of movies released?

These questions will help uncover viewing patterns, popular content types, and historical production trends, ultimately contributing to better content planning and user engagement strategies.

### PREPARE PHASE
Guiding Questions

Q1: Where is your data located?

A1: The dataset used for this project is publicly available and was accessed through an online source. It contains information on over 9,000 Netflix movies, including metadata such as genres, popularity scores, vote averages, and release years.

Q2: How is the data organised?

A2: The dataset is structured in a tabular format, with each row representing a unique movie and each column containing attributes like title, genre, vote average, popularity, and release date. I used Python for data processing and analysis, employing libraries such as Pandas and NumPy to clean, merge, and format the data as needed. Unnecessary columns were removed, and new columns were created to support deeper analysis.

Q3: Are there issues with bias or credibility in this data? Does your data ROCCC?

A3: The data meets the ROCCC standards—Reliable, Original, Comprehensive, Current, and Cited. It was collected from reputable sources and appears to be free of major bias or credibility issues. It provides a broad view of Netflix’s content library, making it suitable for trend analysis and business insights.

Q4: How did you verify the data’s integrity?

A4: Data integrity was verified by checking for missing values, duplicate records, and incorrect data types. I used Python to perform data cleaning tasks such as handling null values, standardising formats, and converting columns to appropriate types. This ensured the dataset was consistent and ready for accurate analysis.

Q5: How does it help you answer your question?

A5: The Netflix movie dataset contains detailed information necessary to answer our key business questions, such as identifying popular genres, high-performing movies, and yearly content trends. By exploring metrics like genre frequency, vote averages, and popularity scores, we can gain valuable insights into user preferences and content performance.

Q6: Are there any problems with the data?

A6: Minor issues such as missing values and inconsistent data types were present. These were addressed using Python-based cleaning techniques, ensuring the data was fully prepped and reliable for the analysis phase.

### PROCESS PHASE
Guiding Questions:

Q1: What tools are you choosing and why?

A1: I used Python for processing the Netflix dataset due to its powerful data handling libraries like Pandas, NumPy, and Matplotlib/Seaborn for visualisation. Python's intuitive syntax and strong community support make it ideal for performing data cleaning, transformation, and exploratory analysis efficiently. These tools allowed me to preprocess and structure the data for effective analysis.

Q2: Have you ensured your data’s integrity?

A2: Yes, I ensured the integrity of the data by identifying and handling missing values, correcting inconsistent data types, and removing duplicates. The dataset was cleaned and structured into a single, cohesive DataFrame that was fully ready for in-depth analysis.

Q3: Have you documented your cleaning process so you can review and share those results?

A3: Yes, the entire data cleaning and preprocessing workflow has been clearly documented in a Jupyter Notebook. Each step is annotated with explanations, making it easy to review, understand, and reproduce the results.

### ANALYZE PHASE

The Analyze phase focuses on exploring the cleaned dataset to uncover meaningful insights that answer the business questions defined earlier. Using Python libraries such as Pandas for data manipulation and Matplotlib and Seaborn for visualization, I performed detailed exploratory data analysis (EDA) on the Netflix movie dataset. This phase involves identifying trends, comparing categories, and uncovering patterns related to Netflix’s content offerings.

#### Key analyses conducted include:

- Content Type Distribution:
      A comparison of the number of movies versus TV shows to understand Netflix’s focus on different content formats.

- Genre Trends:
     Identification of the most common movie genres on Netflix, providing insight into user preferences and Netflix’s content strategy.

- Popularity and Ratings:
      Analysis of movies with the highest and lowest popularity scores and vote averages, along with their genres, to understand what kind of content resonates most with viewers.

- Release Year Analysis:
      Exploration of content release trends over the years to highlight Netflix’s expansion and content production growth.

- Country-Wise Production:
      Insights into which countries produce the most content on Netflix, revealing regional content contributions and diversity.

Through visualizations such as bar charts, line graphs, and heatmaps, the analysis phase brings clarity to large volumes of data, helping identify trends and outliers. These findings support Netflix in making informed decisions about future content acquisition, production strategies, and user engagement efforts.

#### SHARE PHASE

In the Share phase, the focus is on communicating the insights uncovered during the analysis in a clear, engaging, and accessible way. For this project, I used Tableau to create a series of interactive visualizations that effectively present the key findings from the Netflix dataset.

Tableau was chosen for its powerful data visualization capabilities, allowing complex data to be translated into intuitive dashboards and charts. The visualizations are designed to help stakeholders quickly grasp important patterns and trends in Netflix’s content library.

Key visualizations include:

- Content Type Breakdown: A pie chart or bar graph showing the distribution of movies versus TV shows, offering a quick view of Netflix’s content focus.

- Top Genres: A horizontal bar chart highlighting the most frequent genres, helping identify what types of content dominate the platform.

- Popularity & Ratings: Scatter plots and highlight tables showcasing the highest and lowest-rated movies by average vote and popularity score, along with their respective genres.

- Yearly Content Trends: A line graph visualizing the number of movies released each year, revealing production trends and growth over time.

- Country-Wise Content Production: A world map or heatmap displaying the number of movies produced per country, illustrating Netflix’s global reach and regional diversity.

These dashboards make it easy for decision-makers to explore the data interactively, filter results, and draw their own insights. By transforming raw data into visual stories, the Share phase ensures that the analysis is not only technically sound but also actionable and easy to understand for both technical and non-technical audiences.
