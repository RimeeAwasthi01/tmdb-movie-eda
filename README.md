# TMDB Movie EDA

Exploratory Data Analysis (EDA) on the TMDB 5000 Movie Dataset using Python, Pandas, Matplotlib, and Seaborn.

---

# Project Overview

This project focuses on analyzing the TMDB 5000 Movie Dataset to uncover trends, patterns, and relationships within the movie industry using data analysis and visualization techniques.

The notebook includes:
- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Exploratory Data Analysis
- Correlation Analysis
- Visualization
- Business Insights

---

# Objectives

- Understand movie industry trends
- Analyze relationships between budget, revenue, popularity, and ratings
- Identify top-performing genres and directors
- Explore release trends over time
- Perform statistical and visual analysis on movie data

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Structure

```text
tmdb-movie-eda/
│
├── tmdb_movie_eda.ipynb
├── README.md
├── requirements.txt
├── .gitignore
```

---

# Dataset

This project uses the TMDB 5000 Movie Dataset consisting of two CSV files:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Dataset Source:  
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Instructions

1. Download the dataset from the link above
2. Extract the ZIP file
3. Place both CSV files inside a `datasets/` folder

Example:

```text
datasets/
├── tmdb_5000_movies.csv
└── tmdb_5000_credits.csv
```

---

# Key Analysis Performed

- Genre Distribution Analysis
- Revenue vs Budget Analysis
- Popularity Analysis
- Vote Count and Rating Analysis
- Correlation Heatmap
- Top Movies by Revenue
- Most Frequent Actors and Directors
- Release Year Trend Analysis
- Runtime Distribution

---

# Key Insights

- Drama, Comedy, and Action are among the most common movie genres.
- Higher-budget movies generally tend to generate higher revenue.
- Popular movies tend to receive more votes.
- Revenue and popularity show meaningful positive correlation.
- Franchise and large-scale productions dominate top revenue rankings.

---

# Correlation Analysis

A correlation heatmap was used to analyze relationships between numerical movie features such as:
- Budget
- Revenue
- Popularity
- Vote Count
- Runtime
- Vote Average

---

# How to Run

## 1. Clone Repository

```bash
git clone https://github.com/your-username/tmdb-movie-eda.git
```

---

## 2. Install Requirements

```bash
pip install -r requirements.txt
```

---

## 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
tmdb_movie_eda.ipynb
```

---

# Future Improvements

- Movie Recommendation System
- Machine Learning Prediction Models
- Interactive Dashboards
- NLP-based Movie Overview Analysis
- Streamlit Web App

---

# Author

Rimee Awasthi


---

# License

This project is for educational and portfolio purposes.
