🎬 **Amazon Prime TV Shows and Movies**
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepmalakale/EDA-AmazonPrime-TVShows-and-Movies/blob/main/EDA_AmazonPrime_TVShows_Movies.ipynb)


**Project Overview**

The Amazon Prime TV Shows and Movies project delves into analyzing Amazon Prime Video’s U.S. content library using two comprehensive datasets. The objective is to uncover patterns, trends, and insights related to:

📊 Content Diversity

🌍 Regional Distribution

⭐ IMDb/TMDB Ratings

🔥 Popularity

🎭 Cast and Crew Involvement

This analysis aims to support content strategy, personalized recommendations, and audience engagement insights for streaming platforms.

📂 Dataset Description

The project utilizes two CSV datasets:

Titles Dataset (titles.csv)

9,871 unique titles

15 attributes:

id – Title ID on JustWatch

title – Name of the title

type – TV show or movie

description – Brief description

release_year – Year of release

age_certification – Age rating

runtime – Length of movie/episode

genres – List of genres

production_countries – Producing countries

seasons – Number of seasons (if TV show)

imdb_id, imdb_score, imdb_votes

tmdb_popularity, tmdb_score

Credits Dataset (credits.csv)

124,235 records of cast and crew

5 attributes:

person_id – Unique person ID

id – Title ID (to link with titles dataset)

name – Actor/Director name

character – Character name (if actor)

role – ACTOR or DIRECTOR

✅ After data cleaning, wrangling, handling null values, and outlier removal, both datasets were merged into a single consolidated dataframe (df) for analysis.

🎯 Business Objective

To analyze Amazon Prime Video’s content library and generate actionable insights regarding:

🎭 Dominant Genres and Formats (TV vs Movies)

🌐 Regional Production Trends

📈 Evolution of the Catalog Over Time

⭐ Audience Engagement through IMDb/TMDB ratings, votes, and popularity

🎬 Key Actors and Directors shaping Prime’s content library

📊 Analysis & Visualizations

The analysis was performed using Google Colab with Python libraries:

🐼 Pandas

🔢 NumPy

📊 Seaborn

📈 Matplotlib

📍 Plotly

Univariate Analysis

📈 Histogram

📊 Bar Plot

🥧 Pie Plot

📦 Box Plot

Bivariate Analysis

📊 Bar Plot

📈 Scatter Chart

📉 Line Chart

📦 Box Plot

🥧 Pie Chart

💥 Bubble Plot

🎻 Violin Plot

🍩 Donut Chart

🗺️ Treemap

Multivariate Analysis

🔥 Correlation Heatmap

🔄 Pair Plot

⚙️ Tech Stack

💻 Platform: Google Colab

🧠 Language: Python

📚 Libraries: Pandas, NumPy, Seaborn, Matplotlib, Plotly

🛠️ Steps to Run the Project

Clone the Repository

git clone https://github.com/your-username/Amazon-Prime-TV-Shows-and-Movies.git


Navigate to the Project Directory

cd Amazon-Prime-TV-Shows-and-Movies


Open the Project in Google Colab

Click the Colab badge below:

Ensure you have internet access for Python library installation.

Install Required Libraries (if running locally)

pip install pandas numpy matplotlib seaborn plotly


Access Dataset

All datasets are stored in the data/ folder:

data/titles.csv → Amazon Prime titles metadata

data/credits.csv → Cast & crew information

Run the Notebook

Execute each cell in order. Visualizations include:

Univariate: Histogram, Bar Plot, Pie Plot, Box Plot

Bivariate: Bar Plot, Scatter Chart, Line Chart, Box Plot, Pie Chart, Bubble Plot, Violin Plot, Donut Chart, Treemap

Multivariate: Pair Plot, Correlation Heatmap

Explore Insights

Analyze trends in Amazon Prime’s content library 📊 Check genres, IMDb ratings, regional distribution, and actor/director analysis. Use visualizations to draw conclusions about content diversity & audience preferences.

✅ Conclusion

The project demonstrates how Amazon Prime’s content catalog has evolved over time, highlighting:

⚖️ The balance between TV shows and movies

🎭 Genre dominance and diversity

🌍 Regional production insights

⭐ IMDb/TMDB ratings’ role in popularity

🎬 Actor and director contributions

These insights can support strategic decisions in content acquisition, personalization, and audience targeting, enabling Amazon Prime to drive growth and subscriber engagement.
