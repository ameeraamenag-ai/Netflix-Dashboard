#  Netflix Content Analysis Dashboard

An interactive Power BI dashboard designed to explore and analyze Netflix's content library. The project focuses on understanding content distribution, ratings, genres, countries, release trends, and the balance between Movies and TV Shows.

## Dashboard Overview

The dashboard provides a visual overview of Netflix's catalog through:

- Total number of titles
- Total Movies and TV Shows
- TV Show percentage
- Average Movie Duration
- Movies vs TV Shows distribution
- Top 10 content ratings
- Top 10 genres
- Top 10 countries
- Content added over the years
- Movies vs TV Shows by release year
- Movie duration distribution

##  Objectives

- Analyze the overall composition of Netflix's content library
- Compare Movies and TV Shows
- Identify the most common genres and ratings
- Explore the geographical distribution of Netflix content
- Understand content growth and release trends over time
- Analyze movie duration patterns

##  Tools & Technologies

- **Power BI Desktop** — Dashboard development & visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures and calculated columns
- **GitHub** — Project documentation and version control

##  Data Preparation

The dataset was cleaned and transformed before visualization. Key preparation steps included:

- Handling missing values
- Cleaning categorical fields
- Standardizing country and rating information
- Separating Movies and TV Shows
- Extracting duration-related information
- Creating calculated fields for analysis
- Creating duration buckets for Movies

##  Key Dashboard Features

### KPI Cards
Provides a quick overview of the Netflix catalog using key metrics such as total titles, Movies, TV Shows, TV Show percentage, and average movie duration.

### Content Distribution
Visualizes the proportion of Movies and TV Shows available in the dataset.

### Ratings, Genres & Countries
Highlights the most frequently occurring ratings, genres, and countries represented in the Netflix catalog.

### Time-Based Analysis
Shows how content has been added and released across different years.

### Duration Analysis
Groups Movies into duration ranges to make movie-length patterns easier to compare.

##  Project Structure

```text
Netflix-Content-Analysis/
│
├── README.md
├── Netflix_Dashboard.pbix
├── data/
│   └── netflix_titles.csv
│
└── screenshots/
    └── dashboard.png
