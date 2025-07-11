
# Diphtheria Incidence Analysis (1888–2013)

This repository contains an R-based analysis of Diphtheria incidence in the United States, using the Project Tycho dataset. The project explores long-term trends, seasonal patterns, and the historical impact of public health interventions, including widespread vaccination.

---

## 📂 Project Structure


├── Diphtheria_Analysis.Rmd # R Markdown source code
├── Diphtheria_Analysis.html # Rendered report
├── /figures # Folder for plots and figures
├── /data # Raw and processed data files
└── README.md


---

## 📊 Data Description

- **Source:** [Project Tycho](https://www.tycho.pitt.edu/)
- **Time Period:** 1888–2013
- **Variables:**
  - Week ending date
  - State
  - Number of Diphtheria cases reported

---

## 🛠️ Analysis Workflow

The analysis includes the following key steps:

1. **Data Cleaning**
   - Filtered records to include only Diphtheria cases
   - Removed missing or invalid entries
   - Aggregated weekly data into yearly summaries

2. **Exploratory Data Analysis**
   - Visualized overall incidence trends
   - Assessed seasonal distribution of cases
   - Examined geographic differences across U.S. states

3. **Visualization**
   - Created time series plots, heatmaps, and bar charts to highlight important patterns
   - Annotated plots to indicate the introduction of vaccination campaigns

4. **Summary Statistics**
   - Calculated yearly totals and average incidence per 100,000 population (where applicable)

---

## ✨ Key Findings

### Annual Diphtheria Cases

![Annual Diphtheria Cases](figures/diphtheria_annual_trend.png)

**Figure 1.** Annual reported Diphtheria cases in the United States, showing a dramatic decline after vaccine introduction.

---

### Seasonality

![Diphtheria Seasonality Heatmap](figures/diphtheria_seasonality_heatmap.png)

**Figure 2.** Heatmap of Diphtheria cases by month across years, demonstrating clear seasonal peaks.

---

### Geographic Distribution

| State         | Total Cases (1888–2013) |
|---------------|--------------------------|
| New York      | [Fill In]                |
| Pennsylvania  | [Fill In]                |
| Illinois      | [Fill In]                |
| ...           | ...                      |

**Table 1.** Total reported cases by state.

---

## 📈 How to Reproduce

To re-run this analysis:

1. Clone this repository:



#💡 Interpretation Highlights
Trend: Diphtheria incidence decreased substantially over time, especially after the introduction of routine immunization.

Seasonality: The disease showed higher incidence during colder months.

State Variation: Some states reported consistently higher case counts due to population density and reporting practices.


# 🖼️ Figures & Tables

🙏 Acknowledgments
Project Tycho for providing open-access data

RStudio and the R community for tools and packages

[Your Institution or Course Name]







