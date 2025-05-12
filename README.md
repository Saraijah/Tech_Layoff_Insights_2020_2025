# Tech Layoffs (2020–2024) Analysis

This project analyzes real-world layoff data from 2020 to 2024, sourced from [Kaggle](https://www.kaggle.com/). The goal is to explore trends in the tech job market during and after the COVID-19 pandemic.

We used **SQL** and **Power Query** to clean and transform the data, and **Microsoft Excel** to visualize key patterns. This analysis helps highlight which industries and companies were most impacted and which remained resilient throughout this period.

Our insights can assist job seekers, industry analysts, and stakeholders in understanding the shifting dynamics of the tech landscape and making more informed decisions.

---

## Key Insights

### No Statistical Outliers Detected
Using the Interquartile Range (IQR) method, no outliers were found in the dataset. Even though 2023 had the highest number of layoffs, it falls within the expected range. A data point would need to be below -119,531.00 or above 186,059.50 to be considered an outlier.

![tech_layoffs_2020_2024](https://github.com/user-attachments/assets/4fba0e38-1784-4777-a4bc-23c00ab05e4c)

---

### Peak in Layoffs in 2023
The year 2023 saw the highest number of layoffs in the dataset. Meanwhile, 2025 (based on data from Q1 only) currently has the fewest.

![tech_layoff_trend_2020_2025](https://github.com/user-attachments/assets/2d4c743e-5006-4725-89d8-1226c1073978)

---

### Monthly Aggregated Layoffs
January had the highest number of layoffs, with a total of 53,998 employees laid off. September had the fewest, with only 6,220 layoffs.

![Month(aggrefated)_Breakdown_tech_layoffs](https://github.com/user-attachments/assets/a371c0c7-7b04-4368-b8c9-cc844c45c436)

---

### Correlation Between Funding and Layoffs
There is a strong positive correlation between the amount of funding a company has raised and the number of layoffs it experienced. Larger, well-funded companies tend to have more employees, so even a small layoff percentage can result in large absolute numbers. However, this doesn't necessarily indicate a higher proportion of the workforce being laid off.

![Relationship_between_capital_and_layoffs](https://github.com/user-attachments/assets/89d7083f-5acf-4d20-9470-497d63841fc3)

---

## Project Structure

- `SQL_Cleaning/` – SQL scripts for data standardization, de-duplication, and transformation  
- `EDA_SQL/` – SQL queries for exploratory data analysis  
- `Visuals/` – Excel charts and screenshots  
- `tech_layoffs_dataset.xlsx` – Cleaned dataset used for analysis  

---

## Tools Used

- **SQL** – Data cleaning and querying  
- **Power Query** – Data transformation in Excel  
- **Microsoft Excel** – Data visualization and analysis  

---

## Conclusion

This analysis reveals important trends in the tech job market from 2020 to 2024. The data shows that:
- 2023 was the peak year for layoffs.
- January was consistently the worst month for layoffs.
- Well-funded companies aren’t immune to workforce cuts.
- COVID-19 and its aftermath had long-lasting effects on tech employment.

---

## Next Steps

- Extend the dataset to include full-year data for 2025  
- Perform predictive analysis to forecast future layoffs  
- Add geographical or sector-based breakdowns if data becomes available

## Additional Analysis

For a short exercise on basic probability and root cause analysis, see the [Probability and RCA File](https://github.com/Saraijah/Tech_Layoff_Insights_2020_2025/blob/main/RCA%20and%20Probability/Tech_Layoffs_2023_Analysis.docx).















