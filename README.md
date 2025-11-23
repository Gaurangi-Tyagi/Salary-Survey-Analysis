Salary Survey Analysis — Tableau Prep & Tableau Dashboards

This project presents an end-to-end data cleaning and visualization workflow on a global salary survey dataset.
Using Tableau Prep, the raw data was standardized and transformed into a reliable, analysis-ready format.
The cleaned dataset was then visualized using Tableau Desktop to uncover patterns in salaries across job titles, genders, countries, and experience levels.

This repository demonstrates practical data cleaning, transformation, and dashboard-building skills — similar to what is required in data analytics and BI roles.




Tools & Technologies

Tableau Prep → Data cleaning & workflow automation

Tableau Desktop → Visualizations & dashboards

Excel / CSV → Reference tables (e.g., currency exchange rates)

PowerPoint → Final presentation of insights

Data Cleaning Workflow (Tableau Prep)

Source: Cleaning steps and workflow screenshot from pages 6–10 of the PPT 





Key transformations:

Currency Standardization

Merged “Other Currency” into a single Currency column

Joined external exchange-rate table (Excel/CSV)

Converted all salary fields into USD for consistent comparison

Job Title & Gender Cleaning

Grouped free-text gender responses into:
Male, Female, Other / Prefer not to say

Merged similar roles (e.g., “Software Developer” + “Engineer” → “Software Engineer”)

Low-frequency job titles grouped under Other

Experience Bucket Transformation

Converted ranges (e.g., “1–3 years”, “5–10 years”) into numeric values

Enabled median/average experience calculations

Allowed sorting & trend analysis

Outlier & Missing Value Handling

Removed incomplete or unrealistic salary entries

All cleaning steps are available in the Tableau Prep workflow:
/tableau-prep-flow/Salary Survey.tfl





Visualizations & Dashboards (Tableau Desktop)

Dashboards before and after cleaning are available in:
/tableau-visualizations/

Screenshots are available in:
/dashboard-screenshots/

Before Cleaning

Salary charts showed extreme spikes due to unnormalized currencies and inconsistent job titles
(Example: the very high bar for JPY/Other currencies on page 5 )

After Cleaning

Salary distributions appear realistic and aligned

All salary comparisons are now shown in USD

Job roles and genders are standardized

Country-level trends are clearer and more accurate





Key Insights from the Analysis
1. Significant salary variation across job titles

The salary distribution chart (page 3) shows salaries ranging from under $50K to well over $300K depending on job title. Tech and engineering roles stand out with higher compensation.

2. Noticeable salary differences across genders

Gender-based charts (pages 4 & 13) reveal that median salaries differ by gender for many job titles.

3. Currency inconsistencies led to misleading results before cleaning

Before conversion, some currencies (like JPY or “Other”) produced unrealistic salary spikes.
After standardization to USD, the salary distribution became meaningful.

4. Country-level salary patterns show global inequality

The world map visualization (page 14) shows clear geographic salary gaps —
countries in North America, Western Europe, and parts of the Middle East display the highest averages.

5. Salary growth with experience varies by country

The multi-country trend chart (page 15) shows that some countries experience steady salary growth with experience, while others show fluctuating trends.


