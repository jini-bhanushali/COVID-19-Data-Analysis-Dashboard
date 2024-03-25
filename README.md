# COVID-19-Data-Analysis-Dashboard

This repository contains visualizations and insights derived from a dataset regarding COVID-19 spread across various states of the USA. The dataset, collected till March 7, 2021, comprises 41 attributes and 20780 entries, providing detailed information about each COVID-19 case in the United States.

## About the Dataset

The dataset includes information such as date, state, number of deaths, number of hospitalized patients, negative test results, patients on ventilators, and positive test results, among others. It serves as a valuable resource for studying and analyzing the progression of the COVID-19 pandemic throughout different states of the United States.

## Insights and Visualizations

### Visualization 1: Time Series Analysis
- **Yearly Trends:** The data is filtered on the attribute "year" and divided into four quarters from 2020 to 2021.
- **Number of Deaths:** Shows a linear increase from 20739 deaths at the beginning of 2020 to 28743995 deaths by 2021.
- **Hospitalized Cases:** Exhibits a peak increase from quarter 1 to quarter 2, followed by a linear increase. The number of hospitalized cases starts from 32221 at the start of 2020.
- **Comparison:** Both deaths and hospitalized cases show an overall increase, with a direct relationship observed between the two. Hospitalized cases tend to be approximately 1.5 times more than deaths.

### Visualization 2: Geographical Distribution
- **Statewise Comparison:** Depicts the geographical spread of COVID-19 across the USA, color-coded by the number of deaths in each state.
- **Observations:** States with larger populations, such as New York, Texas, and California, show higher death counts. States like Florida, New Jersey, and Arizona had high hospitalization rates but comparatively fewer deaths.

### Visualization 3: Analysis of Testing Parameters
- **Focus States:** Concentrates on Indiana, Texas, and New York, analyzing total tests, positive reports, and negative reports.
- **Insights:** New York and Texas show no negative cases reported, suggesting potential data issues. Indiana reports fewer missing data compared to the other states.
- **Testing Distribution:** New York conducted the most tests, followed by Texas and Indiana, indicating a correlation between testing volume and population density.

### Dashboard
- **Year 2020 Analysis:** Dashboard filters data for the year 2020, showcasing the trends and relationships between deaths, hospitalizations, and testing parameters.
- **Observations:** Both deaths and hospitalizations show a consistent increase throughout 2020, with some states experiencing adverse effects in the following year.
  <img width="1049" alt="image" src="https://github.com/jini-bhanushali/COVID-19-Data-Analysis-Dashboard/assets/58543237/2a268012-7c82-4e55-8eec-3a4fb39e81a7">

## Technologies Used

### Tableau
- Used Tableau's data integration, visualization, and interactive features to create a compelling dashboard experience.
- **Usage:** 
  - Clone the repository to your local machine.
  - Open the Covid19.twb file using Tableau Desktop.
  - Explore the interactive dashboard to gain insights.

---

## Contributors

- Jini Ashok Bhanushali
---

Feel free to explore the visualizations and insights in detail through the tableau workbook and report attached.
