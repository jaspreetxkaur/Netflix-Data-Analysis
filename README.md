# Netflix Data Analysis

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Titles dataset to identify patterns and insights related to global content production, genre distribution, content ratings, and catalog growth over time.

The analysis focuses on understanding how Netflix's content library has evolved, which countries produce the most content, and what types of movies and TV shows dominate the platform.

The project is implemented using **Python** with data analysis and visualization libraries to extract meaningful insights from the dataset.

---

## Dataset

The dataset used in this project is the **Netflix Titles Dataset**, which contains metadata for movies and TV shows available on Netflix.

Key attributes include:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre (Listed In)

Dataset Source:
https://www.kaggle.com/datasets/shivamb/netflix-shows

---

## Objectives

The main objectives of this project are:

* Perform exploratory data analysis on Netflix's content catalog
* Analyze the distribution of movies vs TV shows
* Identify the countries contributing the most content
* Examine genre popularity and trends
* Study the growth of Netflix content over time
* Analyze rating distribution across titles

---

## Tools and Technologies

* Python
* Pandas – Data manipulation and analysis
* Matplotlib – Data visualization
* Seaborn – Statistical data visualization
* Google Colab – Development environment

---

## Project Workflow

### 1. Data Loading

The Netflix dataset was imported into a Pandas DataFrame to explore its structure and attributes.

### 2. Data Cleaning

Data preprocessing steps included:

* Handling missing values
* Converting date columns to datetime format
* Removing incomplete records for accurate analysis

### 3. Exploratory Data Analysis

The dataset was analyzed to identify trends such as:

* Distribution of Movies vs TV Shows
* Top countries producing Netflix content
* Content growth over time
* Genre distribution
* Content rating patterns

### 4. Data Visualization

Visualizations were created using Matplotlib and Seaborn to present insights clearly through:

* Bar charts
* Trend graphs
* Distribution plots

---

## Analysis Performed

### Movies vs TV Shows Distribution

Analyzed the proportion of movies compared to TV shows in the Netflix catalog.

### Top Countries Producing Content

Identified countries contributing the highest number of titles.

### Content Growth Over Time

Examined how the Netflix catalog has expanded over the years.

### Genre Analysis

Explored the most frequently appearing genres on Netflix.

### Rating Distribution

Analyzed content ratings to understand the target audience of Netflix titles.

### Director Contribution

Identified directors with the highest number of titles on the platform.

---

## Key Insights

* Movies significantly outnumber TV shows in the Netflix catalog.
* The United States contributes the largest number of titles on Netflix.
* Netflix content additions increased rapidly after **2016**, indicating aggressive platform expansion.
* **TV-MA** is the most common rating, suggesting a strong focus on mature audiences.
* Genres such as **Drama** and **International Movies** are among the most frequently appearing categories.

---

## Project Structure

Netflix-Data-Analysis
│
├── data
│   └── netflix_titles.csv
│
├── notebook
│   └── Netflix_Data_Analysis.ipynb
│
├── images
│
├── requirements.txt
│
└── README.md

---

## Requirements

To run this project locally, install the required libraries:

pip install -r requirements.txt

Libraries used:

* pandas
* matplotlib
* seaborn

---

## Future Improvements

Possible extensions of this project include:

* Creating an **interactive dashboard** for exploring Netflix data
* Applying **machine learning models** to predict content popularity
* Developing a **movie recommendation system**
* Performing **genre clustering using NLP techniques**

---

## Author

**Jaspreet Kaur**
Computer Science Student | AI & Data Science Enthusiast

This project is part of a continuous effort to build strong data science and machine learning skills through practical projects.

