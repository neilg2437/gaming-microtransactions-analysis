# gaming-microtransactions-analysis
# Story vs Skin: Profitability and Trends in Gaming Monetization

## 🎮 Project Overview

This project analyzes profitability trends within the gaming industry, focusing on **microtransaction-driven games** versus **single-player story-driven games**. By leveraging data warehousing, data modeling, and interactive dashboards, the project will uncover:

* Revenue growth patterns across monetization models
* Sentiment trends around different game types
* Long-term profitability comparisons between free-to-play and premium games

## 📌 Objectives

* Build an end-to-end analytics pipeline using **Snowflake**, **DBT**, **Python**, and **Tableau**
* Analyze **revenue data**, **player sentiment**, and **game performance metrics**
* Visualize key business insights about gaming industry monetization strategies

## 🗺️ Project Architecture

* **Data Warehouse**: Snowflake (free trial)
* **Transformation**: DBT (Core, free open-source)
* **Data Ingestion**: Python (API pulls, web scraping), optionally AWS S3
* **Analytics & Exploration**: SQL, Python Notebooks
* **Visualization**: Tableau (Student License + Tableau Public)

## 🗂️ Project Structure

```
gaming-microtransactions-analysis/
├── data/                  # Raw datasets, ingestion scripts
├── notebooks/             # EDA and revenue/sentiment analysis
├── dbt/                   # DBT data modeling project
├── tableau/               # Tableau dashboards (.twbx), screenshots
├── snowflake_setup/       # SQL setup scripts
└── README.md              # Project overview
```

## 📊 Planned Analysis

| Focus Area                  | Example Questions                                                     |
| --------------------------- | --------------------------------------------------------------------- |
| **Revenue Trends**          | Which monetization model has grown faster in the last decade?         |
| **Microtransaction Impact** | What % of publisher revenue comes from microtransactions?             |
| **Single-player Longevity** | Do single-player games have longer profitability tails?               |
| **Sentiment Analysis**      | Is there a correlation between user sentiment and monetization model? |
| **Publisher Case Studies**  | Rockstar, Activision, CD Projekt Red revenue patterns                 |

## 📈 Tableau Dashboard Goals

* Interactive **trend lines** for revenue growth by monetization model
* **Sentiment vs Revenue** scatterplots (Metacritic, Reddit)
* **Yearly leaderboards** by game profitability
* **Publisher comparison views**

## ✅ Next Milestones

* [ ] Finalize data sources (SteamSpy, VGChartz, Reddit API, Statista proxies)
* [ ] Build Snowflake schema + DBT models
* [ ] Develop EDA in Jupyter Notebooks
* [ ] Build Tableau dashboards and deploy on Tableau Public
* [ ] Document full project on GitHub with screenshots, insights, and Tableau links

---

Stay tuned for project updates and data deep dives!

📌 **Neil Godbole | Gaming Analytics Series 2025**
