# IMDB_Capstone_Project
This repository contains the code and documentation for the Capstone project, which is divided into four phases. Each phase focuses on different tasks and objectives related to data scraping, data manipulation, querying databases, exploratory data analysis (EDA), and machine learning for vote and gross collection predictions.

Project Overview
The goal of this project is to extract movie data from IMDB using web scraping techniques, store the data in CSV files, create SQLite tables, perform SQL queries on the tables, conduct EDA using pandas, and build machine learning models to predict votes and gross collection. The project is divided into the following phases:

#### Phase 1: Web Scraping and Data Preparation
#### Phase 2: SQLite Database and SQL Queries
#### Phase 3: Exploratory Data Analysis (EDA)
#### Phase 4: Machine Learning for Vote and Gross Collection Predictions

### Phase 1: Web Scraping and Data Preparation
In this phase, we scrape the provided IMDB dataset URL and extract movie details. The data is then stored in two separate CSV files based on specified fields. The first CSV file contains information such as movie name, director name, duration, year, ratings, and metascore. The second CSV file includes details like movie name, stars, votes, genre, gross collection, popularity, and certification. The director and stars fields are further divided into subfields to accommodate multiple directors and stars.

### Phase 2: SQLite Database and SQL Queries
In this phase, we create two tables in SQLite and import the data from the CSV files into the respective tables. The first table contains columns for movie name, director name, duration, genre, ratings, and other details. The second table includes columns for movie name, stars, votes, genre, gross collection, popularity, and certification. We then perform various SQL queries on these tables using the SQL workbench or SQLite database. The queries involve filtering and sorting the data based on different criteria, such as directors, duration, ratings, stars, and genres.

### Phase 3: Exploratory Data Analysis (EDA)
In this phase, we merge the two CSV files into a single DataFrame using pandas join operations. This allows us to perform exploratory data analysis on the combined dataset. EDA involves analyzing and visualizing the data to gain insights and identify patterns or trends. The analysis should be conducted in detail, and observations from each analysis should be documented.

### Phase 4: Machine Learning for Vote and Gross Collection Predictions
In this phase, we develop machine learning models to predict votes and gross collection for movies. The code for machine learning is implemented using appropriate models based on the label basis. The project requires building separate models for vote prediction and gross collection prediction. To ensure accurate predictions, we apply techniques such as scaling, hyperparameter tuning, and bias/variance avoidance to avoid underfitting or overfitting. Once the best models are identified, they are saved, and the selection criteria for the best model are explained.

## Repository Structure
The repository is structured as follows:

data/: This directory contains the CSV files generated in Phase 1, which store the scraped data.

database/: This directory contains the SQLite database file created in Phase 2, which stores the tables and data.

scripts/: This directory contains the Python scripts for web scraping, data manipulation, SQL queries, EDA, and machine learning.

README.md: This file provides an overview of the project and instructions on how to use the repository.
