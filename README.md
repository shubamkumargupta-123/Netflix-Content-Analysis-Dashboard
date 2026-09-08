# Netflix Content Analysis Dashboard — Uncovering content and rating trends across a 5,000+ title catalog using Power BI

![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Overview

Streaming platforms release thousands of titles across decades, making it hard to spot patterns in content strategy or audience reception at a glance. This project builds an interactive Power BI dashboard to analyze Netflix's movie and TV show catalog — surfacing how release volume, runtime, and viewer ratings have shifted over time and across content types.

## 📊 Dataset

- **Source:** Netflix TV Shows & Movies dataset (title, release year, runtime, IMDb score, IMDb votes, age certification, content type)
- **Size:** 5,000+ titles across movies and TV shows
- **Period covered:** Multi-decade catalog, filterable by release year

## 🛠️ Tools & Techniques

- **Tool:** Power BI
- **Key techniques:** DAX measures, interactive slicers (content type, release year), column/line/area/combo charts, KPI cards

## 🔍 Approach

1. Loaded and modeled the Netflix catalog dataset in Power BI, structuring title, rating, and metadata fields for analysis.
2. Built a column chart ranking titles by rating votes to surface the most-engaged content.
3. Built line, area, and combo charts tracking title release volume and total rating votes by release year.
4. Added a scatter chart comparing age certification against IMDb score, plus dynamic slicers (content type, release year) and a KPI card totaling IMDb votes for at-a-glance filtering.

## 💡 Key Insights

- **2019 saw the highest volume of new titles added (749)**, closely followed by 2018 (733), 2021 (687), and 2020 (657) — the catalog's most active growth period was 2017–2021.
- **TV-14 content rates highest on average (7.26 IMDb score)**, narrowly ahead of TV-MA (7.07) — and notably outperforms family-oriented ratings like PG (6.21) and G (6.39), which score lower on average.
- **Breaking Bad is the most-engaged single title by IMDb score** (9.5) among the top 5 most-voted titles, while **Inception leads in total rating volume** (19.96M votes), followed by Forrest Gump (17.55M) and Breaking Bad (16.41M).

## 📷 Dashboard Preview

**Titles released per year**
![Titles Per Year](images/titles-per-year.png)

**Top 10 titles by rating votes**
![Top 10 Titles by Votes](images/top10-titles-by-votes.png)

**Average IMDb score by age certification**
![Average Score by Certification](images/avg-score-by-certification.png)

**Movie vs. TV Show split**
![Movie vs Show Split](images/movie-vs-show-split.png)

## 📁 Repository Structure

```
├── README.md
├── Netflix_project.pbix   # Power BI report file
└── images/                # dashboard chart exports for this README
    ├── titles-per-year.png
    ├── top10-titles-by-votes.png
    ├── avg-score-by-certification.png
    └── movie-vs-show-split.png
```

## ▶️ How to Reproduce

**Power BI:** Open `Netflix_project.pbix` in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free download from Microsoft). Use the slicers on the report page to filter by content type or release year.

## 👤 Author

**Shubham Kumar Gupta**
Data Analyst | [LinkedIn](https://www.linkedin.com/in/shubham-kumar-gupta-a4551b191) | [GitHub](https://github.com/shubamkumargupta-123)
