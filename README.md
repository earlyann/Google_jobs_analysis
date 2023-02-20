Analysis of Google Jobs Data from SERP API

Project Overview
This project is aimed at developing and honing skills in data extraction from APIs, data analysis using natural language processing, and data visualization. The project has a dual purpose, the first being to help the author acquire new skills, and the second to facilitate an efficient search for jobs matching those newly acquired skills.

Project Objective
The goal of this project is to explore the potential of SERP API's Google Jobs API for acquiring job listings data for analysis. The project aims to design a repeatable, scalable, and easily modifiable script to pull the latest job listings data and analyze the data using natural language processing and data visualization.

Methods Used
-Data Extraction
-Data Exploration
-Data Cleaning
-Natural Language Processing
-Sentiment Analysis
-Named Entity Recognition
-Data Visualization

Technologies
-Python
-SERP API's Google Jobs API
-Pandas
-Matplotlib
-Natural Language Tool Kit (NLTK)

Project Description
This project begins with the development of a repeatable, scalable, and easily modifiable script to pull current job listings from SERP API's Google Jobs API. SERP API's provides an easy-to-use, RESTful API that returns JSON formatted search engine results.

The script utilizes two separate API calls. The first API call is nested in a function that takes the desired job title as an argument. This function is designed to allow easy search for different job titles and pull those into a data frame. The script then uses the job ID data pulled from the first call to extract the listing-specific information.

The second API call is built as another function that takes one or many data frames as an argument. This function is designed to request additional listing information, including company rating and rating source.

The analytical work is performed in a separate notebook. Here, the data is explored using quick visualizations to give an overview of who is listing the jobs, the job titles, and where the jobs are being posted.

The author then explores Python's Natural Language Tool Kit along with Pandas methods and functions to navigate and follow up on the job listings. The job descriptions are tokenized to find the author's desired keywords such as "python," "pandas," "visualization," "SQL," and "tableau." NLTK is then used to parse and summarize the job descriptions to make them shorter. NLTK's sentiment analyzer is run on the job descriptions, and the author also uses the NLTK concordance function to look for salary information and write it to a new column. The author also explores named entity recognition.

Project Status
The project is still in progress.

Needs of the Project
-API data extraction
-Data exploration/descriptive statistics
-Data processing/cleaning
-Writeup/reporting

Conclusion
The project aims to showcase the potential of SERP API's Google Jobs API for job listings data analysis. With the help of Python and NLTK, this project aims to provide valuable insights for job seekers to efficiently navigate the job market.


