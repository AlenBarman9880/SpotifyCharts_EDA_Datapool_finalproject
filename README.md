# 🎧 Spotify Charts Analysis: Trends, Insights & Visualizations

**Author:** Alen Barman  
**Date:** October 2024

---

## 📖 Overview

This project performs an Exploratory Data Analysis (EDA) of the **Spotify Charts** dataset to understand how songs and artists perform across time and regions. Using Python for EDA and Power BI for interactive visualizations, the analysis uncovers seasonal, regional, and overall trends in streaming behavior and provides actionable insights for the music industry.

---

## 🎯 Objectives

- Identify top-performing songs and artists over time.  
- Analyze regional listening preferences and cultural differences.  
- Detect seasonal and temporal patterns in streaming behavior.  
- Provide actionable recommendations for marketing, playlist curation, and release planning.

---

## 📊 Dataset Overview

- **Source:** Kaggle – *Spotify Charts* (Dhruvil Dave)  
- **Approx. Size:** ~20,000 records covering multiple regions  
- **Key Columns:**  
  - `Title` — Song name  
  - `Artist` — Performer(s)  
  - `Region` — Country/area of listeners  
  - `Date` — Chart ranking date  
  - `Rank` — Song’s daily position  
  - `Streams` — Number of plays  
  - `Day of Week` — For weekly trend analysis

---

## ⚙️ Methodology

1. **Data Collection:** Downloaded the Spotify Charts dataset from Kaggle.  
2. **Data Cleaning:** Removed duplicates, handled missing values, standardized formats, and converted `Date` to datetime.  
3. **Exploratory Data Analysis (EDA):** Performed descriptive statistics and trend analyses by day, month, quarter, and year using Python (Pandas, Matplotlib).  
4. **Visualization:** Built interactive dashboards in Power BI to visualize trends, regional differences, and seasonal patterns.  
5. **Reporting:** Compiled insights and recommendations into a summarized report.

---

## 🔍 Key Insights

### 🌤️ Seasonal Trends
- Listener engagement increases around holidays and weekends.  
- Certain genres and tracks show clear seasonal spikes.

### 🌎 Regional Popularity
- Regions often have unique top artists and tracks; local preferences matter.  
- Global hits coexist with region-specific favorites—useful for targeted campaigns.

### ⏳ Overall Popularity Trends
- Streaming volume shows long-term growth.  
- A subset of artists and songs demonstrates sustained chart dominance.

---

## 💡 Implications

- **Artists & Labels:** Optimize release timings and tour schedules based on peak listening periods.  
- **Streaming Platforms:** Improve recommendation algorithms and curate region-specific playlists.  
- **Marketers:** Tailor campaigns to regional and seasonal listener behavior.  
- **Analysts:** Use trends to forecast future popularity and inform strategic decisions.

---

## 🧩 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib) — EDA & preprocessing  
- **Power BI** — Interactive dashboarding and visual storytelling  
- **Excel** — Data validation and quick summaries  
- **Jupyter Notebook** — EDA notebook and reproducible analysis

---

## 📈 Deliverables

- `Stock_EDA.ipynb` — Jupyter notebook with EDA (note: rename appropriately for Spotify)  
- `PowerBI_Dashboard.pbix` — Power BI dashboard file (interactive visuals)  
- `Spotify_Report.pdf` — Summarized findings and recommendations  
- `dataset/spotify_charts.csv` — Cleaned dataset (if included)

---

## 📂 Suggested Repository Structure

📁 spotify-charts-analysis/
│
├── README.md
├── notebooks/
│ └── spotify_eda.ipynb
├── powerbi/
│ └── spotify_dashboard.pbix
├── report/
│ └── spotify_report.pdf
└── data/
└── spotify_charts_clean.csv

---

## 🚀 How to Reproduce

1. Clone the repo: `git clone https://github.com/YourUsername/spotify-charts-analysis.git`  
2. Install required Python packages (example):
   pip install pandas numpy matplotlib jupyter
3. Open the EDA notebook: notebooks/spotify_eda.ipynb and run the cells.
4. Open the Power BI file (powerbi/spotify_dashboard.pbix) in Power BI Desktop to explore interactive visualizations.
5. Read report/spotify_report.pdf for the summarized insights and recommendations.

## 🏁 Conclusion

The Spotify Charts analysis highlights how temporal and regional factors shape streaming trends. The combination of Python-led EDA and Power BI dashboards provides a robust workflow for transforming raw streaming data into actionable insights for artists, platforms, and marketers.

