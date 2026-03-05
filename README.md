# COVID-19 Data Analysis

## Project Overview
This project analyzes global COVID-19 data to understand trends in testing, confirmed cases, deaths, and recoveries.  
Using Python data analysis libraries, the project visualizes relationships between population, testing levels, and pandemic outcomes across continents.

The goal of this analysis is to uncover meaningful insights and patterns using exploratory data analysis (EDA) and data visualization techniques.

---

## Dataset
- **Source:** Kaggle
- **Dataset:** COVID-19 Global Dataset
- **Description:** The dataset contains global COVID-19 statistics including:
  - Population
  - Number of tests conducted
  - Confirmed cases
  - Deaths
  - Recoveries
  - Continent-wise data
  - Date-wise pandemic trends

---

## Libraries Used
The following Python libraries were used for data analysis and visualization:

- **Pandas** – Data cleaning and manipulation  
- **Matplotlib** – Data visualization and plotting  
- **Seaborn** – Advanced statistical visualizations  

---

## Installation
Clone the repository:

```bash
git clone https://github.com/yourusername/covid-19-data-analysis.git
Analysis & Insights
1. Population vs Tests
Insights

The graph shows a positive relationship between population size and number of tests conducted.

Higher population regions perform more tests, indicating testing scales with population demand.

2. Tests vs Reported Cases
Insights

Increase in testing leads to higher reported cases.

This shows that case numbers depend strongly on testing levels.

3. Cases vs Deaths
Insights

As the number of COVID cases increases, the number of deaths also rises.

Severity Indicator

Higher case counts are associated with increased mortality, highlighting the seriousness of widespread infection.

4. Cases vs Recoveries
Insights

Recoveries rise consistently with increasing confirmed cases.

The strong positive trend indicates effective treatment and patient recovery over time.

The gap between cases and recoveries reflects active or critical cases.

5. Population by Continent
Insights

🌍 Asia has the highest population among all continents.

🌍 Oceania has the lowest population among all continents.

🌍 Population distribution differs significantly across continents.

6. Tests by Continent Over Time
Insights

📊 Shows COVID-19 tests conducted by continent over time.

🥇 Some continents consistently performed more tests than others.

📈 Trends highlight how testing efforts changed across dates.

7. Cases by Continent Over Time
Insights

🦠 Africa reported the highest number of COVID-19 cases over time.

🦠 Oceania reported the lowest number of COVID-19 cases over time.

📊 Other continents like Asia, Europe, and the Americas had comparatively fewer cases.

📈 The plot shows trends in how cases changed across continents over dates.

8. Deaths by Continent Over Time
Insights

📊 The plot shows the number of deaths reported over time for each continent.

🥇 The continent with the tallest bars on most dates had the highest deaths during that period.

📈 Trends highlight increases or decreases in deaths across continents over time.

9. Recoveries by Continent Over Time
Insights

💚 Africa reported the highest number of COVID-19 recoveries over time.

📊 Other continents like Asia, Europe, and the Americas had comparatively fewer recoveries.

📈 The plot shows trends in how recoveries changed across continents over dates.

10. Recovery Trends Across Continents
Insights

💚 Africa reported the highest number of COVID-19 recoveries over time.

📊 Other continents like Asia, Europe, and the Americas had comparatively fewer recoveries.

📈 The plot highlights how recovery numbers evolved across continents over time.

Project Structure
covid-19-data-analysis
│
├── data
│   └── covid_dataset.csv
│
├── notebooks
│   └── covid_analysis.ipynb
│
├── plots
│   └── visualizations
│
├── README.md
└── requirements.txt
Conclusion

This project demonstrates how data analysis and visualization can be used to understand the global impact of COVID-19. By analyzing relationships between testing, cases, deaths, and recoveries, the project highlights important pandemic trends across different continents.

cd covid-19-data-analysis
