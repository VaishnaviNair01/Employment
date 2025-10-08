# Unemployment Data Analysis (India)
Unemployment Data Analysis Project :This project explores key employment indicators - Labour Force Participation Rate (LFPR), Worker Population Ratio (WPR), and Unemployment Rate (UR). Using survey data, it visualizes overall trends 

## Project Overview
This project analyzes key employment indicators in India, including:

- **Labour Force Participation Rate (LFPR)**  
- **Worker Population Ratio (WPR)**  
- **Unemployment Rate (UR)**  

The analysis covers **overall trends** and **gender-wise breakdowns** (Male, Female), providing insights into workforce patterns across different demographics.

---

## Data Source
- The raw employment survey datasets are sourced from the **[Ministry of Statistics and Programme Implementation (MoSPI)](http://mospi.gov.in/)**.  
- Data spans multiple years and includes columns for **year, gender, labor status, weights**, and other demographic information.  

---

## Data Preprocessing
- The dataset was cleaned to focus on the **working-age population**.  
- Missing or irrelevant entries were removed.  
- Columns such as `gender` and `labor_status` were standardized for easier analysis.  

---

## Mapping Labels
- Some variables in the dataset are coded numerically.  
- **Gender codes** were mapped to readable labels: Male, Female, Transgender.  
- **Labor status codes** were mapped to Employed, Unemployed, and Not in labor force.  
- This mapping ensures that the data is interpretable and ready for analysis and visualization.  

---

## Analysis and Visualizations
- **Overall Trends:** LFPR, WPR, and UR were analyzed over the years to observe changes in employment patterns.  
- **Gender-wise Analysis:** Employment indicators were broken down by gender to highlight differences among Male and Female populations.  
- **Distribution Analysis:** The dataset was visualized to show the proportion of each gender in the workforce.  
- Visualizations were created using **Python (Matplotlib)** and **Power BI dashboards** for interactive exploration.  

---
## 📈 Sample Visualizations
[https://github.com/VaishnaviNair01/Employment/blob/main/Labour_gender_pdf.pdf]

---
## Key Insights

- **Labour Force Participation:** The overall Labour Force Participation Rate (LFPR) stands around 55%, with a Workforce Participation Rate (WPR) of ~52%, indicating a small gap accounted for by unemployment.  
- **Unemployment Trends:** The Unemployment Rate (UR) is approximately 5%, showing a modest proportion of the working-age population actively seeking work but currently unemployed.  
- **Gender Disparities:** Male participation in the workforce is significantly higher than female participation, highlighting persistent gender gaps in employment.    
- **Temporal Stability:** Across the years analyzed, the rates remain relatively stable, suggesting that large-scale shifts in labour market dynamics are gradual.  
- **Policy Implications:** Small differences between LFPR and the sum of WPR + UR emphasize the need to focus on accurate data collection and targeted employment programs to capture informal employment trends.  

---

## Tools Used
- **Python:** Data cleaning, analysis, and visualization  
- **Power BI Desktop:** Interactive dashboards  
- **CSV Files:** Cleaned datasets ready for further exploration  

---

## Future Work
- Extend analysis to **urban–rural comparisons**  
- Include **age group analysis**  
- Enhance **Power BI dashboards** with interactive filters and slicers  
- Explore additional demographic insights

  

- ## Author
 Vaishnavi Nair
- M.Sc. in Mathematics and Computing from NIT Hamirpur
