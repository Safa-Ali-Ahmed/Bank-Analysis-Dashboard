# Bank Analysis Dashboard

## Description
This repository contains a **comprehensive Power BI dashboard** for analyzing Online Sales. It includes data cleaning with Powerquery, exploratory visualizations, and a multi-page Power BI dashboard focusing on cutomers Performance and all staff related to Financial transactions. The dashboard is designed to analyze customers and Financial transactions based on data from 2024. It provides actionable insights for marketers, analysts, and decision-makers to optimize advertising strategies.

## Features

### 1. Data Cleaning Using Powerquery

  - check missing values and remove blank rows
  - remove duplicates or redudancy
  - Change columns data types to  the correct one.
  - renamed columns correctly.
  - Exported cleaned data for Power BI integration.

---

![Customers](https://github.com/Safa-Ali-Ahmed/Bank-Analysis-Dashboard/blob/main/Screen%20Shoots/HomePage.PNG)

### 2. Power BI Dashboard
**Overview**

---Average Tenure:
Customers stay with the bank for an average of 5.01 years, indicating good retention.
---Total Countries Analyzed:
Data covers 3 countries: Spain, Germany, and France.
---Average Number of Products:
On average, each customer holds 2 products.
---Average Salary:
Around $100.09K per year.
---Customer Activity:
5.2K active customers vs 4.8K non-active customers — a slightly higher proportion of active users.
---Max Salary by Country:
Spain has the highest average salary, followed by Germany and then France.
---Products Distribution:
Most customers have 1 or 2 products.
---Gender Distribution:
Slightly more males than females among the customers.


![Customers](https://github.com/Safa-Ali-Ahmed/Bank-Analysis-Dashboard/blob/main/Screen%20Shoots/OverView.PNG)


---

**Insights**

---Customer Churn Rate:
4.1K customers exited (churned), while 5.9K customers remained.
Churn rate is notable, meaning there's room to improve customer retention.
---Exited Customers by Country:
Germany has the highest number of exited customers.
France has the fewest customers who exited.
Spain is in the middle range.
---Exited Customers by Credit Card Ownership:
Customers without credit cards have a slightly higher churn rate compared to those who have cards.
---Exited Customers by Active Membership:
Non-active members are more likely to leave compared to active members.
Indicates that engagement matters a lot for retention.
----Exited Customers by Gender:
Female customers have a slightly higher exit rate than males.
----Balance vs Churn Analysis:
Churn seems to occur across different balance levels, but no extremely strong link is shown — needs deeper analysis.
----Exited Customers by Tenure:
Customers with lower tenure (few years with the bank) are more likely to leave.

![Customers](https://github.com/Safa-Ali-Ahmed/Bank-Analysis-Dashboard/blob/main/Screen%20Shoots/Insights.PNG)

---

**Details**

----Average Age:
The average customer age is 39 years — suggesting a middle-aged customer base.
----Total Credit Count:
460 total credit count (context of this metric could depend on the specific dataset logic).
---Exited Customers by Gender:
55.06% of customers who left the bank are female, 44.94% are male.
---Gender vs Salary:
Males earn higher salaries compared to females on average.
---Credit Card Ownership by Balance:
Customers with credit cards have higher balances than those without.
----Country Balance Comparison:
Customers from France hold the highest total balances, followed by Germany and Spain.


![Customers](https://github.com/Safa-Ali-Ahmed/Bank-Analysis-Dashboard/blob/main/Screen%20Shoots/Details.PNG)

---


## Files Included
- **Dashboard.pbix:** Power BI file with the full dashboard.
- **Dataset.csv:** Cleaned data source used in the dashboard.
- **Documentation.md:** Step-by-step guide on how to use and customize the dashboard.

## How to Use
1. Clone the repository:
   ```bash
   git clone 'https://github.com/Safa-Ali-Ahmed/Bank-Analysis-Dashboard.git'

   ```
2. Open the `Dashboard.pbix` file in Power BI Desktop.
3. Explore the pages and interact with the visualizations.


## Tools & Technologies & Features
- Powerquery
- Power BI: Interactive dashboard design
- Dataset: [Online Sales](https://docs.google.com/spreadsheets/d/1qdGK6hCPle8ZKpjC5jOWcZvzYyB5wt0B/edit?usp=sharing&ouid=113280610288310962621&rtpof=true&sd=true)

---
## Feedback

If you have any suggestions or feedback, feel free to open an issue or connect with me on [LinkedIn](https://www.linkedin.com/in/safaali-da/).

---

## Future Enhancements
- Integration with live data sources.
- Advanced machine learning insights using Python/R integration.
- Adding more custom visuals for deeper analysis.
---
## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

