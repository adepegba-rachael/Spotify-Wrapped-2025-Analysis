# 🎧 Spotify Wrapped 2025 Analysis

<img width="300" height="169" alt="Image" src="https://github.com/user-attachments/assets/9b2e17ef-a92a-4463-97dc-c0fd357d0b8e" />

## 📌 Project Overview

This project explores Spotify Wrapped 2025 data to identify the key factors that influence song popularity in the modern music streaming era. Using Microsoft Excel and Power BI, the analysis examines trends in streaming performance across song characteristics, artist attributes, and market patterns.

The goal is to answer the central question:

> **What factors influence the popularity of songs on Spotify in 2025?**

---

## 🎯 Objectives

1. Identify top-performing songs and artists based on streams and chart performance
2. Analyze genre popularity and contribution to total streams
3. Examine characteristics of popular songs (danceability, energy, valence, acousticness, BPM)
4. Evaluate the impact of release year on song popularity
5. Assess geographic distribution of top-performing songs
6. Analyze the effect of song duration on popularity
7. Investigate the relationship between chart position and streaming performance

---

## 📂 Dataset Description

The dataset contains information on top Spotify songs in 2025, including:

* Song title and artist
* Total streams (in billions)
* Genre
* BPM (tempo)
* Duration (seconds)
* Release year
* Artist country
* Audio features:

  * Danceability
  * Energy
  * Valence
  * Acousticness
* Peak global chart position

---

## 🛠 Tools Used

* **Microsoft Excel**

  * Pivot Tables
  * Charts
  * Correlation Analysis
  * Regression Analysis

* **Power BI**

  * Interactive Dashboard
  * Data Visualization

---

## 📊 Analysis & Findings

### 🔹 1. Top Songs & Artists

* A small number of artists dominate total streams
* The United States contributes the highest share of top-performing songs

---

### 🔹 2. Genre Popularity

* Pop and mainstream genres account for the largest share of total streams
* Listener preferences remain concentrated around widely accessible genres

---

### 🔹 3. Song Characteristics (Top Songs vs Others)

Comparison of average values:

| Feature      | Top Songs | Other Songs |
| ------------ | --------- | ----------- |
| Danceability | 0.715     | 0.673       |
| Energy       | 0.673     | 0.640       |
| Valence      | 0.701     | 0.657       |
| Acousticness | 0.121     | 0.160       |
| BPM          | 110       | 109.75      |

**Insight:**

* Top songs tend to be slightly more danceable, energetic, and positive
* They are also less acoustic
* Differences are present but not very large

---

### 🔹 4. Release Year Trend

**Correlation Analysis:**

* Weak positive relationship (r ≈ 0.28)

**Regression Analysis:**

* R² ≈ 0.081
* Coefficient ≈ 0.013
* P-value ≈ 0.045 (statistically significant)

**Insight:**

* Newer songs tend to perform slightly better
* However, release year explains only a small portion of popularity

---

### 🔹 5. Geographic Analysis

| Country      | Total Streams (Billions) |
| ------------ | ------------------------ |
| USA          | 34.55                    |
| South Korea  | 2.74                     |
| UK           | 1.82                     |
| Colombia     | 1.71                     |
| South Africa | 1.55                     |
| Others       | < 1.5                    |

**Insight:**

* The USA dominates global streaming performance
* Other countries contribute smaller but notable shares

---

### 🔹 6. Duration Analysis

| Duration Category | Avg Streams |
| ----------------- | ----------- |
| Short (<180s)     | 0.979       |
| Medium (180–240s) | 0.907       |
| Long (>240s)      | 0.923       |

**Regression Results:**

* R² ≈ 0.006
* P-value ≈ 0.58 (not significant)

**Insight:**

* Short songs perform slightly better on average
* However, duration is not a statistically significant factor

---

### 🔹 7. Chart Performance vs Streams

* Scatter plot shows a weak positive relationship
* Better chart positions generally align with higher streams

**Insight:**

* Chart success contributes to visibility
* But does not fully determine streaming performance

---

## 🔥 Key Insights

* Song popularity is influenced by multiple factors, not a single variable
* Audio features such as danceability and energy show slight influence
* Newer songs have a small but statistically significant advantage
* Song duration has minimal impact on streaming performance
* Geographic dominance plays a major role, with the USA leading
* Chart performance is related to streams but not strongly predictive

---

## 🧠 Conclusion

The analysis shows that a typical hit song in 2025 is moderately energetic, danceable, and recently released. However, popularity is driven by a combination of factors including artist influence, audience preferences, and market exposure. No single variable strongly determines success, highlighting the complexity of the modern music streaming landscape.

---

## 📊 Dashboard

The project includes:

* Excel Dashboard (Pivot-based)
* Power BI Interactive Dashboard

These dashboards provide visual insights into trends, comparisons, and relationships within the dataset.

---

## 🚀 How to Use This Project

1. Open the Excel file to explore data analysis and pivot tables
2. View the dashboard sheet for insights
3. Open the Power BI file (.pbix) for interactive visualization

---

## 📎 Author

**Adepegba Rachael**
Data Analysis Project – Spotify Wrapped 2025

---
I am open to collaborate on Data Analysis and Visualuzation related projects. You can reach me via email (rachael4adepegba@gmail.com) or LinkedIn(Adepegba Rachael)
