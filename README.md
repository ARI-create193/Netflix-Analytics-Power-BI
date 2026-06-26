# 🎬 Netflix-Analytics-Power-BI

An interactive Power BI dashboard that analyzes Netflix's content library — covering movies, TV shows, genres, ratings, and global content distribution.

## Dashboard Preview
<img width="1442" height="805" alt="Screenshot 2026-06-26 123553" src="https://github.com/user-attachments/assets/c21445af-11f3-4efe-be99-afe572037f2e" />

## 📊 Overview

This dashboard provides a 360° view of Netflix's catalog, helping uncover trends in content type, genre popularity, regional availability, and audience ratings. Built using Power BI with dynamic slicers for **Year**, **Type**, and **Country**.

## ✨ Key Features

- **KPI Cards** – Quick snapshot of Total Movies (6.13K), Total TV Shows (2.68K), Total Titles (8.8K), Genres Count (515), and Countries Count (198)
- **Movies vs TV Shows** – Donut chart showing content split (69% Movies, 30% TV Shows)
- **Content Added by Year** – Trend line comparing Movie vs TV Show additions over time
- **Top 10 Genres** – Horizontal bar chart highlighting the most common genres (Dramas, Documentaries, Stand-Up Comedy, etc.)
- **Average Rating Gauge** – Visual gauge showing overall average content rating (3.63/5.00)
- **Total Titles by Country** – Interactive world map (choropleth) showing global content distribution
- **Top 10 Countries by Content** – Bar chart ranking countries by title count (US leads with 3,210 titles)
- **Count of Titles by Rounded Rating** – Distribution of content across rating buckets
- **Titles Added by Year** – Area chart tracking Netflix's content growth from 2008–2021

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design & data modeling
- **DAX** – Calculated measures and KPIs
- **Power Query** – Data cleaning and transformation
- **Bing Maps Visual** – Geographic data visualization

## 📂 Folder Structure

```
netflix-analytics-dashboard/
│
├── Netflix_Dashboard.pbix      # Main Power BI dashboard file
│
├── icons/                       # UI icons used in the dashboard
│   ├── comedy.png
│   ├── countries.png
│   ├── eraser.png
│   ├── live-camera.png
│   ├── movies-app.png
│   ├── netflix.png
│   └── television.png
│
├── Netflix_Dashboard.pbit      #Template File
│
├── dataset/                    # Raw dataset used in the dashboard
│   └── netflix_titles.csv
│
└── README.md
```

## 📁 Dataset

The dashboard is built on the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows), containing metadata such as title, type, genre, country, release year, and rating.

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/netflix-analytics-dashboard.git
   ```
2. Open `Netflix_Dashboard.pbix` in **Power BI Desktop**
3. Use the **Year**, **Type**, and **Country** slicers to filter and explore the data interactively

## 📌 Key Insights

- Movies dominate the catalog (~69%), but TV Show additions have grown steadily since 2016
- Dramas, Documentaries, and Stand-Up Comedy are the top genres on the platform
- The United States and India are the top two content-producing countries
- Content additions peaked around 2018–2019, followed by a slight decline

---
⭐ If you found this project useful, consider giving it a star!
