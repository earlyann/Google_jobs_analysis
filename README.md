# Exploring and Analyzing SERPAPI.com's Google Jobs API Using Python and NLTK

## Project Overview
The purpose of this project is to streamline the process of my job search and to explore the potential of the Natural Language Toolkit (NLTK) platform for Python. The project aims to develop and refine skills in data extraction from APIs, data analysis using natural language processing, and data visualization.

## Project Objective
The main objective of this project is to explore SERP API's Google Jobs API for acquiring job listings data for personal follow-up and analysis. The project aims to design a script that is repeatable, scalable, and easily modifiable to extract the latest job listings data and analyze it using natural language processing and data visualization. Using the Google Jobs API, the project can aggregate job listings from multiple sources, providing a more comprehensive dataset to work with. The goal is to generate valuable insights from job listings data that can help streamline the job search process and facilitate more informed decision-making for myself.

### Methods Used
-Data Extraction
-Data Exploration
-Data Cleaning
-Natural Language Processing
-Sentiment Analysis
-Named Entity Recognition
-Data Visualization

### Technologies
-Python
-SERP API's Google Jobs API
-Pandas
-Matplotlib
-Natural Language Tool Kit (NLTK)

### Project Description
This project begins with the development of a repeatable, scalable, and easily modifiable function to pull current job listings from SERP API's Google Jobs API, https://serpapi.com/google-jobs-api. This API provides an easy-to-use, RESTful API that returns JSON formatted search engine results.

The notebook utilizes two separate API calls. The first API call is nested in a function that takes the desired job title as an argument. This function is designed to allow easy search for different job titles and pull those into a data frame. For my purposes I made a call for both "Data Analyst" and "Operations Analyst" daily. The notebook then uses the job ID data pulled from the first call to extract the listing-specific information.

![Screen Shot 2023-03-10 at 10 13 18 AM](https://user-images.githubusercontent.com/119711479/224853326-0cfc7c3f-9ab8-4fe6-b23f-39fc67405e4c.png)

The second API call is built as another function that takes one or many data frames as an argument. This function is designed to request additional listing information, including company rating and rating source.

![Screen Shot 2023-03-10 at 10 14 03 AM](https://user-images.githubusercontent.com/119711479/224853336-b1b799f2-91b5-459c-9cae-6940c7a53456.png)

The analytical work is performed in separate notebooks. In the daily analysis, the data is explored using quick visualizations to give an overview of who is listing the jobs, the job titles, and where the jobs are being posted.

The author then explores Python's Natural Language Tool Kit along with Pandas methods and functions to navigate and follow up on the job listings. The job descriptions are tokenized to find the author's desired keywords such as "python," "pandas," "visualization," "SQL," and "tableau." NLTK is then used to parse and summarize the job descriptions to make them shorter. NLTK's sentiment analyzer is run on the job descriptions, and the author also uses the NLTK concordance function to look for salary information and write it to a new column. The author also explores named entity recognition.

The daily data is then complied and analyzed in the complied notebook. Here the effecacy of the NLTK methods are analyzed as well as trends from the endpoint data. 

## Project Status
Complete

### Needs of the Project
-API data extraction
-Data exploration/descriptive statistics
-Data processing/cleaning
-Writeup/reporting

### Output
- Notebook containing the API functions and to call and coallate the data: google_jobs_api.ipynb
- Notebook containing the daily analysis and formatting including visualizations: data_jobs.ipynb
- Folder containing the daily job listing overview visualizations: 
- Notebook for the analysis of the cumulative data collected: compiled_data_analysis.ipynb
- Written analysis of daily findings, method efficacy and cumulative findings. 

### Conclusion
The project aims to showcase the potential of SERP API's Google Jobs API for job listings data analysis. With the help of Python and NLTK, this project aims to provide valuable insights for job seekers to efficiently navigate the job market.


