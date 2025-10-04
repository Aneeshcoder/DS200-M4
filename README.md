# DS200-M4

## Haryana MGNREGA CSV Dataset

### Overview

This dataset contains district-wise and year-wise records from the Mahatma Gandhi National Rural Employment Guarantee Act (MGNREGA) scheme. It tracks key performance indicators, fund utilization, employment statistics, and more to monitor the progress and effectiveness of the program.

### Data Structure

- **Format**: CSV (Comma-Separated Values)
- **Rows**: Each row records data for a specific district and year
- **Columns**:
    - `State`: State name for the record
    - `District`: Corresponding district name
    - `Year`: Reporting year
    - `Households`: Number of registered households
    - `Employment Provided`: Number of households actually provided with work
    - `Persondays Generated`: Total days of employment generated
    - `Funds Released`: Monetary allocation or expenditure
    - Other columns may include gender, social category, project types

### Observations and Analysis

''Persondays_of_Central_Liability_so_far'' represents the cumulative number of persondays for which the central government is liable for wage payments under the MGNREGA scheme up to a certain point in time.

- **Plot I**: This line plot shows the general trend that high Persondays generated generally equivalent to high data variation.
- **Plot II**: This scatter plot helps to see the almost linear correlation between the funds spent and the amount of employment generated.
- **Plot III**: This box plot shows that Hisar district generated maximum Persondays while the Faridabad district generated the minimum.
- **Plot IV**: This correlation matrix shows the dependence between various numerical features.
- **Plot V**: This line plot shows an increase in the average wage rate over the years with a sudden surge from 2024-25 to 2025-26.
- **Plot VI**: This histogram plot shows the average days of employement provided per household lies around 20 days.

---

**References:**

[Dataset] Mahatma Gandhi National Rural Employment Guarantee Act (MGNREGA). Open Government Data (OGD) Platform India. Published 13/09/2023, Updated 03/10/2025.  
Available at: [https://www.data.gov.in/resource/district-wise-mgnrega-data-glance](https://www.data.gov.in/resource/district-wise-mgnrega-data-glance).  
Released under the [National Data Sharing and Accessibility Policy (NDSAP)](https://data.gov.in/sites/default/files/NDSAP.pdf?_gl=1*1l5aedz*_ga*MjE0MDExMDExNy4xNzU5NTY3MDg1*_ga_2NLK0N9J6V*czE3NTk1NjcwODQkbzEkZzEkdDE3NTk1NjcxNzAkajYwJGwwJGgw).
