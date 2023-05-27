# PHASE 1 FINAL PROJECT

### INTRODUCTION
Microsoft has seen other companies have success in the movie industry and has decided to open its movie studio. It however knows nothing about the movie industry. It has decided to hire you as a Data Scientist to determine the type of films which are most popular at the Box Office. You are then supposed to convert your findings into actionable insights which you are supposed to give to the head of the new movie studio of Microsoft.

### OBJECTIVES
The objective of this project is to:
- Analyse data to determine the type of films which do best at the box office.
- Transform findings to actionable insights to give to head of new Microsoft movie studios.
- Use findings to come up with 3 recommendations with visualisations which is to be given to the head of the movie studio.

## BUSINESS UNDERSTADING

This is the thorough understanding of the problem at hand, so that the respective Data Scientist/scientists can come up with a solution that effectively solves the problem. The business understanding of a Data Science problem is split into various parts which are:
1. Problem Statement
2. Measure of success

### PROBLEM STATEMENT
This is the problem in which as a Data Scientist one is trying to solve. In the case of this project by **Microsoft**, the issue is to determine the type of movies doing best at the box office. The Data Scientist is to then use his findings to provide actionable insights in the form of three recommendations with visualisations. The head of Microsoft's new movie studio is to then use these findings, to know which type of movies to make.

### MEASUREMENT OF SUCCESS
This is the measure of success of the project in relation to the problem statement and the business understanding. For this particular problem here is our measurement of success. To uncover actionable insights through exploratory data analysis (EDA) to identify the types of films that have achieved the highest levels of success at the box office. Success will be measured by analyzing various factors such as box office revenue, audience ratings, genre popularity, and critical acclaim. The goal of this analysis, is to gain a comprehensive understanding of the characteristics and attributes that contribute to a movie's success. This will enable Microsoft's new movie studio to make informed decisions about the types of films they should produce. The success of the project will be reflected in the quality and relevance of the insights generated, which will provide valuable guidance for Microsoft's strategic planning in the movie industry.

## DATA UNDERSTANDING
Data Understanding is a crucial phase in the Data Science process where the Data Scientist dives deep into the available data, aiming to gain a comprehensive understanding of its characteristics, quality, and relevance to the defined problem. This involves exploring the data, identifying patterns and trends, assessing data quality and completeness, and gaining insights that will inform subsequent steps in the analysis. By thoroughly understanding the data, the Data Scientist can make informed decisions on how to preprocess, analyze, and model the data to extract meaningful insights and solve the problem effectively.

For the problem we are trying to solve this can involve several steps as shown below:

### 1. Familiarising ourselves with the data.

For the problem at hand, the data relevant to the question was split into two parts. A database file called **im.db** which is a database of movies released with the following relevant tables:
- Movie Basics
- Movie ratings

The second part are three csv files:
- bom.movie_gross.csv
- rt.reviews.tsv
- title.ratings.csv
- MovieData.csv

Other data has been provided if needed for further analysis.

## DATA PREPARATION

Data preparation is an essential step following data understanding in the Data Science cycle. It involves preparing the data for analysis through meticulous data cleaning tasks. The key objectives of data preparation include:

- **Removing outliers**: Identification and removal of data points that deviate significantly from the overall distribution, as they can adversely impact analysis results.

- **Handling missing values**: Thoroughly checking for missing values and employing appropriate strategies to handle them, such as imputation techniques or assessing the suitability of the missing data for analysis.

- **Identifying and resolving duplicates**: Identifying and removing duplicate records to ensure data integrity and avoid bias in analysis outcomes.

- **Assessing columns with excessive missing values**: Evaluating columns with a substantial number of missing values and determining their relevance to the analysis. Dropping columns that are not essential or exploring alternative strategies for handling missing data.


- **Correcting data types**: Verifying and correcting the data types of variables to align them with their intended representation (e.g., converting numerical data from strings to numeric types).

Data preparation is an iterative and time-consuming process, as it aims to refine the data into an optimal state before analysis. By addressing data quality issues and standardizing formats data preparation ensures that subsequent analysis yields accurate and reliable insights.

For the data at hand we shall now begin the process of data cleaning for each table stated in the Data Understanding section.

## EXPLORATORY DATA ANALYSIS

This is a crucial part of the **CRISP DM (Cross Industry Process for Data Mining)**, the process in which Data Scientists use to find insights from data and possibly even model it if required. **Exploratory Data Analysis** is about going through data which has already been pre-processed through Data Cleaning so as to answer questions about the data. Usually during **EDA** there is a goal in mind and questions that need to be answered. These are questions that stem from the business understanding which includes the **problem statement** and the **business success** criteria. Overall **Exploratory Data Analysis** is an important process in the Data Science cycle used by Data Scientists everywhere in the world.
