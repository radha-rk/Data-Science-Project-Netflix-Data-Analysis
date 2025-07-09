# 🎬 Netflix Data Analysis — My First Data Science Project! 📊

Welcome to my very first hands-on Data Science project! 🚀  
In this project, I explored a Netflix movie dataset using Python and performed **Exploratory Data Analysis (EDA)** to discover patterns, trends, and insights related to genres, popularity, and viewer ratings.

---

## 🧠 Objective

To analyze Netflix movie data and answer the following key questions:

- 📌 What is the most frequent movie genre?
- 📌 Which genres receive the highest votes?
- 📌 Which movie is the most and least popular?
- 📌 Which year saw the most movie releases?

This project helped me understand core concepts of data wrangling, visualization, and insight generation using real-world data.

---

## 📁 Dataset Overview

The dataset contains **9,827 records** and includes the following columns:

| Column             | Description                        |
|--------------------|-------------------------------------|
| `Release_Date`     | Movie release date                 |
| `Title`            | Movie title                        |
| `Overview`         | Short description of the movie     |
| `Popularity`       | Popularity score                   |
| `Vote_Count`       | Number of votes received           |
| `Vote_Average`     | Average rating out of 10           |
| `Original_Language`| Language of the movie              |
| `Genre`            | Comma-separated genres             |
| `Poster_Url`       | URL of the movie's poster image    |

---

## 🧰 Tools & Libraries Used

- 🐍 Python 3.x  
- 📒 Jupyter Notebook  
- 🧮 Pandas  
- 📊 Matplotlib  
- 🟦 Seaborn  
- 🔢 NumPy

---

## 🔧 Data Preprocessing

Here’s what I did to prepare the dataset:

- ✅ **Converted `Release_Date`** to year format.
- ✅ **Dropped unnecessary columns**: `Overview`, `Original_Language`, `Poster_Url`.
- ✅ **Categorized `Vote_Average`** into 4 labels:
  - `Not Popular`, `Below Average`, `Average`, `Popular`
- ✅ **Split multiple genres** into individual rows for accurate analysis.
- ✅ **Converted `Genre`** column to categorical data type.

---

## 📈 Visualizations

- 📊 **Genre Distribution**: Bar plot of most frequent genres
- 📊 **Vote Category Distribution**: Count of movies in each vote category
- 📊 **Release Year Histogram**: Year-wise distribution of releases

---

## 💡 Key Learnings

- Learned how to clean and prepare data for analysis
- Practiced categorization and encoding techniques
- Applied data visualization 
- Understood how to extract insights from real-world data

---

## 🌟 Final Thoughts

This project was a great starting point for me to dive into **Data Science**.  
It gave me hands-on exposure to working with datasets, identifying trends, and drawing conclusions with visual support.  
I'm excited to take on more advanced projects and build on this foundation.

---

> ✨ _“The best way to learn data science is to build with data.”_

