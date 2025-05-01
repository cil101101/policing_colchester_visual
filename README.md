📊 Crime & Weather Analysis in Colchester (2024)
This project explores the relationship between crime patterns and weather conditions in Colchester, UK, using publicly available street-level police data and climate records for the year 2024. It is the final project for the MA304 module.

🧠 Objective
To analyze whether and how daily weather factors (e.g., temperature, precipitation) influence the frequency and type of crimes committed. This study also investigates spatial and seasonal trends using statistical and interactive visualizations.

📁 Datasets
crime24.csv – Street-level crime reports from Colchester (via UK Police API)

temp24.csv – Daily weather observations from a regional station (via Ogimet Climate Data)

🔧 Tools & Libraries
Developed using R and the following packages:

tidyverse

lubridate

ggplot2

corrplot

leaflet

plotly

dygraphs

🧹 Data Preprocessing
Crime dates were normalized to full date strings (e.g., "2024-01" → "2024-01-01").

Weather data was directly parsed.

Both datasets were merged on the date column to allow joint analysis.

📈 Key Analyses & Visualizations
Descriptive Stats: Frequencies, bar/pie charts by crime type.

Time Series: Daily crime count fluctuations and seasonal patterns.

Weather Correlation: Temperature vs. crime count scatter plots and correlation matrices.

Geospatial Mapping: Interactive maps identifying crime hotspots in Colchester.

🔍 Insights
Anti-social behaviour and criminal damage were the most reported crimes.

There is a weak but positive correlation between temperature and crime.

Crime counts tend to peak in warmer months, suggesting seasonal patterns.

Interactive maps highlight geographic clusters of crime activity.

📎 How to Use
Clone the repository.

Open the R Markdown or HTML file (MA304_final.html) for full results.

Ensure required R libraries are installed.

Run analyses in RStudio to explore or reproduce results.

📄 License
This project is licensed under the MIT License. See LICENSE for more details.

👤 Author
Iling Chen (2400990)
University of Essex, MA304 – Data Analysis Project
Submitted: April 2025
