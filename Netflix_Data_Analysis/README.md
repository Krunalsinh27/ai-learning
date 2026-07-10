# Netflix Data Analysis using Python & Pandas

A comprehensive Exploratory Data Analysis (EDA) project on the Netflix Movies and TV Shows dataset using **Python**, **Pandas**, and **NumPy**. This project focuses on data cleaning, feature engineering, and extracting meaningful business insights from Netflix's content library.

---

## Project Overview

The objective of this project is to analyze Netflix's catalog of Movies and TV Shows to understand content distribution, release trends, genres, ratings, countries, and other important characteristics.

The project follows a complete data analysis workflow:

- Data Loading
- Data Understanding
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Insights

---

## Dataset Information

- **Dataset Name:** Netflix Movies and TV Shows
- **Source:** Kaggle
- **Records:** ~8,800+
- **Columns:** 12

The dataset contains information such as:

- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure

```text
Netflix-Data-Analysis/
│
├── data/
│   ├── netflix_titles.csv
│   ├── netflix_cleaned.csv
│   └── netflix_feature_engineered.csv
│
├── Netflix_Analysis.ipynb
│
├── README.md
│
├── requirements.txt
│
└── images/
```

---

## Project Workflow

### Data Loading

- Imported required libraries
- Loaded dataset
- Verified dataset structure

---

### Data Understanding

Performed initial exploration using:

- Dataset Shape
- Data Types
- Column Information
- Summary Statistics
- Missing Value Analysis
- Duplicate Analysis
- Unique Values

---

### Data Cleaning

Performed several preprocessing steps:

- Removed duplicate records
- Handled missing values
- Converted date columns into datetime format
- Removed extra whitespaces
- Reset DataFrame index
- Saved cleaned dataset

---

### Feature Engineering

Created several useful features including:

- Year Added
- Month Added
- Day Added
- Weekday Added
- Quarter Added
- Movie / TV Show Indicator
- Duration Value
- Duration Unit
- Primary Genre
- Country Count
- Cast Count
- Genre Count

---

### Exploratory Data Analysis

Analyzed the dataset to answer business questions such as:

- Movies vs TV Shows
- Top Countries
- Top Genres
- Ratings Distribution
- Content Added by Year
- Content Added by Month
- Weekday Analysis
- Movie Duration Distribution
- Top Directors
- Top Actors
- Oldest and Newest Content
- Country-wise Analysis
- Release Year Trends

---

## Key Insights

Some important findings from the analysis include:

- Movies significantly outnumber TV Shows.
- The United States contributes the largest amount of Netflix content.
- Drama is one of the most popular genres.
- Most Netflix content was added between 2018 and 2020.
- TV-MA is the most common content rating.
- Most movies have a duration between 80 and 120 minutes.
- Netflix's content library has grown rapidly in recent years.

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Handling
- Feature Engineering
- Data Manipulation using Pandas
- Exploratory Data Analysis (EDA)
- Business Insight Generation

---

## Future Improvements

Future enhancements for this project include:

- Data Visualization using Matplotlib
- Advanced Visualizations using Seaborn
- Interactive Dashboards using Plotly
- Machine Learning based Content Recommendation
- Sentiment Analysis on Movie Descriptions

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## Requirements

```text
pandas
numpy
jupyter
```

---

## Author

**Krunalsinh Parmar**

Computer Engineering Student

Aspiring AI Engineer

GitHub: https://github.com/Krunalsinh27

---

## If you found this project useful, consider giving it a Star!