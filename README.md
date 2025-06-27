# NBA Data API Web Scraping

## Introduction

In the modern era of sports analytics, **data-driven decision making** has become essential for teams, analysts, and fans alike. The NBA, with its rich history and fast-paced evolution, generates a vast amount of player and team statistics every season. Access to comprehensive, up-to-date, and historical NBA data is crucial for:

- **Performance Analysis:** Understanding player and team trends, strengths, and weaknesses.
- **Predictive Modeling:** Building machine learning models to forecast player performance, team outcomes, or even injury risks.
- **Scouting and Recruitment:** Identifying rising stars and undervalued talent through advanced metrics.
- **Fan Engagement:** Powering fantasy leagues, interactive dashboards, and media content with real stats.
- **Academic Research:** Enabling sports science, economics, and social studies using real-world data.

However, much of this data is locked behind web interfaces or APIs that are not always straightforward to access in bulk. This project addresses that gap by **automating the collection of NBA player statistics** from the official NBA stats API, covering both regular season and playoff data from 2015-16 through the recently concluded 2024-25 season. The resulting dataset is a valuable resource for anyone interested in sports analytics, machine learning, or data science.

## Overview

This project focuses on **web API data scraping** from the NBA's official stats API, collecting player statistics for every season from 2015-16 through 2024-25 (including both Regular Season and Playoffs). The data is saved in an Excel file for further analysis and machine learning applications.

With the conclusion of the 2024-25 NBA season, this dataset enables a wide range of studies and analytics, from player performance trends to advanced ML model development for sports analytics.

## Features

- Scrapes player stats for multiple NBA seasons (2015-16 to 2024-25)
- Collects both Regular Season and Playoff data
- Stores the data in a structured Excel file (`nba_league_leaders_2015-2025.xlsx`)
- Ready for downstream analysis and machine learning projects

## Getting Started

### Prerequisites

- Python 3.8+
- [pandas](https://pandas.pydata.org/)
- [requests](https://docs.python-requests.org/)
- [openpyxl](https://openpyxl.readthedocs.io/)
- [numpy](https://numpy.org/)

Install dependencies:
```bash
pip install pandas requests openpyxl numpy
```

### Usage

1. **Clone this repository** and navigate to the project folder.
2. **Run the Jupyter notebook** `scraping.ipynb` to start scraping NBA data.
3. The script will save the results to `nba_league_leaders_2015-2025.xlsx`.

### Example Output

The Excel file will contain columns such as:
- Year
- Season_type (Regular Season or Playoffs)
- Player stats (PTS, REB, AST, FG%, etc.)

## Project Structure

```
nba-data-scraping/
│
├── scraping.ipynb
├── nba_league_leaders_2015-2025.xlsx
└── README.md
```

## Applications

- **Data Analysis:** Study player and team trends over a decade of NBA seasons.
- **Machine Learning:** Use the dataset for building predictive models (e.g., player performance, clustering, classification).
- **Visualization:** Create dashboards and visualizations for NBA analytics.

## Reference

- [NBA Stats API](https://stats.nba.com/)
- [YouTube Tutorial: NBA Data Scraping](https://www.youtube.com/watch?v=nHtlRlWmTV4)

## License

This project is for educational and research purposes only.

---
*Inspired by the NBA data scraping tutorial by Data Professor.*
