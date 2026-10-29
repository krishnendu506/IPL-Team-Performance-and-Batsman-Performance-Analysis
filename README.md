# 🏏 IPL Team & Batsman Performance Analysis

### An Interactive Sports Analytics Dashboard Using Python & Power BI

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

## 📌 1. Project Overview

The IPL Team & Batsman Performance Analysis project explores Indian Premier League (IPL) cricket data to evaluate team scoring performance, individual batting contributions, bowling effectiveness, season-wise scoring trends, and match outcomes.

Python is used for data cleaning, preprocessing, and exploratory data analysis (EDA), while Microsoft Power BI is used to develop an interactive dashboard for data visualization and performance monitoring.

The primary objective is to transform raw cricket data into meaningful insights that support evidence-based performance evaluation and strategic decision-making.

## 🎯 2. Project Objectives

- Analyze team-wise run contributions and scoring patterns.
- Identify leading batsmen based on total runs.
- Evaluate bowler-wise wicket-taking contributions.
- Compare scoring trends across IPL seasons.
- Explore toss-related patterns and match outcomes.
- Develop an interactive dashboard using Power BI.
- Translate analytical findings into actionable recommendations.

## 🛠️ 3. Tools & Technologies

| Technology | Purpose |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis and documentation |
| Power BI Desktop | Interactive dashboard development |
| Power Query | Data transformation |
| DAX | KPI calculations and analytical measures |
| Git & GitHub | Version control and project documentation |

## 📂 4. Project Structure

```text
IPL-Analytics/
│
├── data/
│   ├── IPL DATASET.csv
│   └── IPL_Cleaned.csv
│
├── notebooks/
│   └── IPL_Analysis.ipynb
│
├── dashboard/
│   └── IPL_Analytics_Dashboard.pbix
│
├── README.md
└── requirements.txt
```

*Note: This is a suggested structure. Keep only files and folders that actually exist in your repository. Do not upload confidential or restricted data.*

## 🔍 5. Data Analysis Workflow

### Step 1: Data Collection
Loaded the IPL dataset from a CSV file using Pandas.

### Step 2: Data Understanding
Examined the dataset's dimensions, column names, data types, missing values, and duplicate records.

### Step 3: Data Cleaning
- Checked missing and duplicate records.
- Standardized column names and categorical values.
- Validated numerical fields and data types.
- Reviewed inconsistent or invalid records.
- Exported the cleaned dataset for further analysis.

### Step 4: Exploratory Data Analysis (EDA)
Performed aggregations and comparisons to investigate team scoring, batsman contributions, bowler wickets, season-wise trends, and match outcomes.

### Step 5: KPI Development
Identified key metrics for monitoring overall scoring, match counts, wickets, and team participation.

### Step 6: Power BI Dashboard Development
Designed interactive KPI cards, charts, and slicers to explore performance by season, venue, innings, and bowling team.

### Step 7: Insight Generation
Interpreted the visualized data to identify patterns, investigate performance differences, and develop potential strategic recommendations.

## 📊 6. Dashboard Preview

The dashboard provides a consolidated view of IPL performance through interactive visualizations.

![IPL Analytics Dashboard](images/IPL_Dashboard.png)

**Dashboard components:**

- **KPI Cards:** Total Matches, Total Runs, Total Wickets, and Total Teams.
- **Team Performance:** Comparison of team-wise run totals.
- **Season Analysis:** Year-wise scoring trends.
- **Batsman Performance:** Comparison of individual run contributions.
- **Bowling Analysis:** Bowler-wise wicket contributions.
- **Toss Analysis:** Visualization of toss-related outcomes.
- **Match Results:** Comparison of batting-first and chasing outcomes.
- **Interactive Filters:** Season, venue, innings, and bowling team.

*Ensure the dashboard image is saved at `images/IPL_Dashboard.png` for the preview to display correctly on GitHub.*

## 📈 7. Key Findings & Analytical Insights

The dashboard provides a starting point for investigating the following areas:

1. **Team Performance:** Compare cumulative run contributions and investigate differences in scoring patterns.
2. **Batsman Performance:** Identify leading run-scorers and examine individual contributions.
3. **Bowling Effectiveness:** Compare wicket-taking contributions and investigate bowling performance.
4. **Seasonal Trends:** Explore changes in aggregate scoring across IPL seasons.
5. **Toss Outcomes:** Investigate relationships between toss-related factors and match results.
6. **Match Strategy:** Compare batting-first and chasing outcomes after validating match-level calculations.

The dashboard displays approximately 402K total runs, 15K total wickets, 1K matches, and 19 teams. These are rounded values from the dashboard and should be verified against the underlying dataset before being reported as exact results.

## 💡 8. Business Insights & Potential Decisions

| Analytical Area | Potential Decision |
|---|---|
| Team scoring | Evaluate scoring consistency and team composition |
| Batsman analysis | Assess batting roles and player contributions |
| Bowling analysis | Evaluate wicket-taking effectiveness |
| Season trends | Establish context-specific performance benchmarks |
| Venue analysis | Investigate venue-specific scoring and match patterns |
| Toss analysis | Compare historical outcomes under different conditions |

These findings can support performance reviews and match preparation. Historical patterns do not guarantee future outcomes and should be evaluated alongside match context and other relevant metrics.

## ⚙️ 9. How to Run the Python Analysis

### Prerequisites

- Python 3.10 or a compatible version.
- Jupyter Notebook or JupyterLab.
- The IPL dataset CSV file.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd IPL-Analytics
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual repository URL.

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Analysis

Open the notebook inside the `notebooks/` directory and execute the cells sequentially.

Update the dataset path in the notebook if your folder structure differs.

### Step 5: Explore the Dashboard

Open `IPL_Analytics_Dashboard.pbix` using Microsoft Power BI Desktop. Refresh the data source if required and interact with the dashboard filters.

## 📁 10. Dataset Information

- **Format:** CSV
- **Domain:** Cricket and sports analytics
- **Data Coverage:** IPL match and player-performance records, subject to the source dataset.
- **Data Preparation:** Python and Pandas
- **Visualization:** Microsoft Power BI

The dataset's exact source, coverage period, number of records, and field definitions should be documented after verification.

## 🚀 11. Future Improvements

- Add batting average, strike rate, and boundary percentage.
- Include bowling economy, average, and strike rate.
- Develop team win-percentage and venue-specific performance analysis.
- Compare batting-first and chasing win rates using unique matches.
- Add season-over-season performance comparisons.
- Improve data validation and automate data-refresh workflows.
- Develop more advanced statistical analysis of factors associated with winning.

## 📚 12. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python and Pandas
- Data Visualization
- KPI Development
- Power BI Dashboard Design
- Business-Oriented Data Interpretation
- Analytical Problem-Solving

## 👨‍💻 13. Author

**Your Name**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

GitHub: YOUR_GITHUB_PROFILE_URL

LinkedIn: YOUR_LINKEDIN_PROFILE_URL

## 📜 14. Disclaimer

This project is intended for educational and analytical purposes. All findings depend on the quality, coverage, and definitions of the underlying dataset. Recommendations represent potential applications of historical analysis and should not be interpreted as guarantees of future match outcomes.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
