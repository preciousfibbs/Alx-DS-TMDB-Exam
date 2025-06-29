# TMDB SQL Exam

## Table of Contents

- [About](#about)  
- [Contents](#contents)  
- [Features](#features)  
- [Usage](#usage)  
- [Requirements](#requirements)  
- [Extended Description](#extended-description)  
- [Author](#author)  

---

## About

This repository contains the **TMDB SQL Exam Jupyter Notebook**, which explores the TMDB (The Movie Database) dataset using SQL queries. The notebook demonstrates querying techniques on movie, actor, genre, keyword, production company, and awards data, aimed at analyzing movie trends, actor roles, and award statistics.

This project is part of my study in the **ALX Data Science Program**.

## Contents

- `TMDB_SQL_Exam.ipynb`: Jupyter Notebook with SQL queries on TMDB data.  
- Dataset: TMDB database in SQLite format (not included here).

## Features

- Retrieve movie details such as titles, release dates, genres, and popularity.
- Analyze Oscar award winners and nominations.
- Explore actor roles and keyword associations.
- Perform complex joins and aggregations using SQL.
- Demonstrate data cleaning and transformation techniques with SQLite.

## Usage

1. Clone this repository or download the notebook.  
2. Ensure you have the TMDB SQLite database (`TMDB.db`) in the working directory.  
3. Open `TMDB_SQL_Exam.ipynb` in Jupyter Notebook or JupyterLab.  
4. Run the cells to execute the SQL queries and explore the dataset.

## Requirements

- Jupyter Notebook or JupyterLab  
- `ipython-sql` extension for running SQL queries inside notebook cells  
- SQLite database file (`TMDB.db`)

## Extended Description

In this project, I tackled a variety of SQL exam questions designed to deepen my understanding of querying a complex movie database (TMDB). The questions required me to explore multiple aspects of the dataset, involving actors, movies, genres, keywords, and awards. Some of the specific challenges I worked on included:

- **Identifying Oscar winners and nominations:** For example, I wrote queries to find who won the Oscar for “Actor in a Leading Role” in 2015, and which award categories had the highest number of actor nominations. This involved filtering by award categories, handling different year formats, and joining award data with actor and movie information.

- **Analyzing movie popularity and genres:** I queried the database to determine the genres with the highest and lowest average popularity scores, as well as finding the production companies with the highest average movie popularity. These tasks sharpened my skills in aggregation (`AVG`), grouping, and sorting.

- **Exploring actor roles and keywords:** I extracted lists of movie titles that specific actors (like Alan Rickman or Vin Diesel) appeared in, including counting unique characters played and filtering movies by keyword presence. This required joining multiple tables (`casts`, `actors`, `keywords`, `movies`) and applying pattern matching.

- **Date and budget filtering:** I filtered movies released within specific date ranges, with constraints on budget and popularity scores, allowing me to practice conditional filtering and date handling in SQL.

- **Database schema exploration:** I practiced querying SQLite system tables to understand the structure of the database, such as listing columns for each table to write accurate queries.

Working through these exam questions gave me hands-on experience in writing complex SQL queries involving multiple joins, subqueries, aggregations, and string operations. It enhanced my ability to interpret real-world datasets, manage data inconsistencies (like year formatting), and extract actionable insights — skills critical for any data analyst or scientist working with relational databases.

## Author
Precious

