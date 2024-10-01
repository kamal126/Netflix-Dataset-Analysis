# 🎬 Netflix Dataset Analysis

Welcome to the **Netflix Dataset Analysis** project! In this project, we dive deep into Netflix's extensive collection of TV shows and movies (up to 2021), sourced from [Flixable on Kaggle](https://www.kaggle.com/shivamb/netflix-shows).

## 🚀 Project Overview
This analysis aims to uncover valuable insights by exploring, cleaning, transforming, and visualizing the data. We'll answer key questions like:

- What's the distribution of movies vs. TV shows?
- How has Netflix's content evolved over the years?
- What are the most popular genres?

## 📂 Dataset
The dataset includes information about Netflix's TV shows and movies, such as:
- **Title**
- **Director**
- **Cast**
- **Country**
- **Release Year**
- **Rating**
- **Duration**
- **Type (Movie/TV Show)**

## 🛠️ Steps for Analysis

### 1. Data Inspection 🧐
We start by exploring the dataset's structure using:
- `head()`, `tail()` – To view the first and last few rows
- `shape` and `size` – For dataset dimensions
- `describe()` – Summary statistics

### 2. Data Cleaning 🧹
To ensure clean data:
- `dropna()` – Remove rows with missing values
- `duplicated()` – Detect and handle duplicate records

### 3. Data Exploration 🔍
Gaining deeper insights using:
- `info()` – Overview of columns and data types
- `value_counts()` – Count unique values in each column
- `unique()` and `nunique()` – Find unique data entries

### 4. Data Transformation 🔄
- Creating new columns to analyze the release year or genre trends
- Using `str.contains()` and `str.split()` to extract specific information
- Converting date columns with `to_datetime()`

### 5. Data Visualization 📊
- **Bar Charts** – Using Seaborn to visualize trends, such as the distribution of TV shows vs. movies, or the number of titles released per year.

## 🔧 Tools and Libraries
- **Pandas**: For data manipulation and analysis
- **Seaborn/Matplotlib**: For generating visualizations
- **Jupyter Notebook**: To run our code

## 📈 Key Insights
By the end of the analysis, we hope to answer:
- Which genre dominates Netflix’s library?
- What’s the distribution between movies and TV shows?
- Are there any interesting patterns in content addition across years?

---

Feel free to contribute by submitting pull requests, or fork the project to experiment with your own analysis! 😊
