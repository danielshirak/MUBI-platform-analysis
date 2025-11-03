# MUBI-platform-analysis

# 🎬 Streaming Content Strategy Analysis: MUBI Data Insights

## Project Goal
This project provides an **Exploratory Data Analysis (EDA)** of a major streaming platform's movie and rating data to inform key stakeholders (Content Acquisition, Marketing, and Data Engineering) on content performance, audience preference, and data integrity flaws. The core objective was to identify the characteristics that define movie success.


## 💾 About the Data
This project uses a publicly available dataset of the MUBI streaming platform (often described as the "Netflix for art movies"), a platform known for its human-curated selection.

* **Source:** https://www.kaggle.com/datasets/clementmsika/mubi-sqlite-database-for-movie-lovers/data
* **Data Structure:** The analysis focuses primarily on the **`movies`** and **`ratings`** tables.
  

## Methodology

The analysis followed a structured, multi-step EDA process using SQL and Python/Pandas, designed to answer core business questions:

1. **Project Initialization & Data Acquisition:** Defined the strategic context, core business goals, and initial key business questions for the analysis.
2.  **Data exploration & Quality check** Identifying and cleaning critical technical flaws to Construct the tables structure.
3.  **Top rated and popular movies:** Identifying the top-rated and most popular movies and determined thier genres.
4.  **Release Year Trend:** Quantified the preference for older\newer films.
5.  **Director Performance** Find the most and least popular directors.
6.  **Unrated Content:** Quantified the scale of unrated movies and demonstrated the trend.

## Technologies
* **Environment:** Jupyter Notebook (or similar interactive Python environment)
* **Language:** Python 
* **Data Analysis:** Pandas, NumPy
* **Database:** SQLite ($\text{.sqlite}$ file)
* **Visualization:** Matplotlib, Seaborn
* **Querying:** Advanced SQL (CTEs, Conditional Aggregation)
