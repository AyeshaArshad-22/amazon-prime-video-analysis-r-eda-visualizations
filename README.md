📊 Amazon Prime Video Titles Analysis
R-Based Exploratory Data Analysis (EDA) & Data Visualization Project

🔎 Overview

This R-based Exploratory Data Analysis (EDA) project performs advanced Data Visualization and Streaming Content Analytics on the Amazon Prime Video Titles dataset.

The objective is to uncover:

🎬 Movies vs TV Shows distribution patterns

🌍 Country-wise content production trends

🎭 Genre popularity insights

📅 Release year growth trends

⭐ Audience rating distribution

⏱ Movie duration analysis

📈 Streaming platform expansion patterns

This project demonstrates how data can be transformed into actionable insights using modern R programming and visualization techniques.

🎯 Project Objectives

Perform structured data cleaning and preprocessing

Conduct in-depth exploratory data analysis

Build 20+ professional visual analytics dashboards

Extract meaningful content trend insights

Demonstrate strong data storytelling capabilities

🗂 Dataset

The Amazon Prime Video Titles dataset contains metadata about movies and TV shows available on the platform.

Column	Description
title	Name of the movie or TV show
type	Movie or TV Show
description	Content summary
listed_in	Genre(s)
country	Country of origin
release_year	Year released
duration	Movie length or episode duration
rating	Audience rating (PG, R, etc.)

📁 Place amazon_prime_titles.csv inside the data/ directory.

📁 Project Structure
AmazonPrimeEDA/
│
├── data/
│   └── amazon_prime_titles.csv
│
├── R_scripts/
│   ├── data_cleaning.R
│   ├── visualizations.R
│   └── wordcloud_analysis.R
│
├── output/
│   └── figures/
│
├── requirements.txt
└── README.md
📊 Key Visualizations (20+)

This project includes advanced visualizations built using ggplot2 and supporting libraries:

📌 Bar Chart – Movies vs TV Shows

🌍 Top 10 Countries by Content

🎭 Top 10 Genres

📅 Release Year Histogram

⏱ Movie Duration Histogram & Boxplot

🔥 Heatmap (Content Type vs Year)

☁ Word Cloud (Frequent Description Terms)

🕸 Radar Chart (Country Comparison)

🗺 Treemap (Genre Distribution)

🫧 Bubble Chart (Country Content Volume)

📑 Facet Plots (Genre by Type)

🔗 Correlation Plot (Release Year vs Duration)

📊 Stacked Bar Chart (Ratings Distribution)

📈 Area Chart (Content Growth Over Time)

📉 Density Plot (Duration Spread)

📈 Key Insights

✔ Movies dominate the platform compared to TV Shows
✔ Significant growth post-2010 indicates streaming expansion
✔ Drama and Comedy are the most popular genres
✔ USA, India, and UK lead in content production
✔ Common themes include family, relationships, life, and adventure
✔ Content diversity has increased over recent years

🧠 Skills Demonstrated

Data Cleaning & Transformation

Exploratory Data Analysis (EDA)

Advanced Data Visualization using ggplot2

Text Mining & Word Cloud Generation

Statistical Trend Analysis

Data-Driven Storytelling

Streaming Media Analytics

⚙ Technologies & Libraries

R Programming

ggplot2

tidyverse

dplyr

tidyr

reshape2

wordcloud

tm

fmsb

treemap

corrplot

RColorBrewer

lubridate

📦 Requirements

Install packages manually:

tidyverse
ggplot2
dplyr
tidyr
reshape2
RColorBrewer
wordcloud
tm
fmsb
treemap
VennDiagram
corrplot
lubridate

Or install automatically:

packages <- readLines("requirements.txt")
install.packages(packages)
🚀 How to Run

1️⃣ Clone the repository

git clone [https://github.com/yourusername/AmazonPrimeEDA.git](https://github.com/AyeshaArshad-22/amazon-prime-video-analysis-r-eda-visualizations)

2️⃣ Move dataset to data/ folder

3️⃣ Open RStudio

4️⃣ install requirements and run code file (requirements.txt file is provided)

🔎 SEO Keywords

Amazon Prime Video Analysis, Movies Dataset, TV Shows Dataset, R Programming Project, R EDA Project, Data Visualization in R, Streaming Content Analysis, Genre Trends Analysis, Release Year Analysis, Ratings Distribution, Heatmap in R, Word Cloud in R, Treemap Visualization, Radar Chart in R, Bubble Chart Analysis, Correlation Plot in R, ggplot2 Project, Data Analytics Portfolio
🎯 Conclusion

This project demonstrates strong analytical and visualization capabilities using R. It transforms raw streaming content data into structured insights, highlighting content distribution, genre dominance, country contributions, and platform growth patterns.

Ideal for:

📌 Data Analyst Portfolio
📌 Business Intelligence Projects
📌 Academic Submissions
📌 Streaming Platform Research
📌 Resume Project Showcase

⭐ If you found this project useful, consider starring the repository.

