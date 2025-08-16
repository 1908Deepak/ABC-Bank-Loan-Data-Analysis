# ABC Bank Loan Data Analysis 🏦

### Dashboard Link :https://app.powerbi.com/links/Gl1GZMHFWZ?ctid=37d002c9-062c-435d-beff-d1efc9989fe4&pbi_source=linkShare

## Problem Statement

This dashboard helps the bank analyze loan distribution, customer demographics, default risks, and income-credit relationships. It provides a clear view of total loan amount, average income, interest rate, total customers, and loan category distributions.

By analyzing these KPIs and visualizations, decision-makers can monitor default trends, credit risk, loan purposes, and customer segmentation, enabling data-driven lending strategies and risk management.

## Key Objective

To give ABC Bank a single integrated view of loan portfolio performance, focusing on default patterns, credit categories, income levels, and customer profiles


### Steps followed 

Step 1 – Data Loading

- Loaded loan dataset from Google Big Query Database into Power BI.
- Used Get Data → Googel Big Query → Database Name & Authentication.


Step 2: Open Power Query Editor and in the View tab under Data Preview, enabled:

- Enabled:

  - Column distribution

  - Column quality

  - Column profile

- Set profiling to "Based on entire dataset".

Also, changed profiling to “Based on entire dataset”.

Step 3 – Data Quality Checks

- Checked for null values in Country, People Vaccinated, Vaccines.

- Checked for null values in Country, People Vaccinated, Vaccines.

- Date fields formatted properly to enable Year/Month slicers


Step 5 : KPIs
Created card visuals with DAX measures:
- Total Loan Amount
- Average Income
- Interest Rate
- Total Customers

        Total Loan Amount = SUM(LoanData[LoanAmount])
        Average Income = AVERAGE(LoanData[Income])
        Average Interest Rate = AVERAGE(LoanData[InterestRate])
        Total Customers = DISTINCTCOUNT(LoanData[CustomerID])


![KPIs](https://github.com/user-attachments/assets/b7d9583d-3d69-488a-b383-827cefed1555)


Step 5 – Slicers Added

- Year

Step 8 - Publish to Power BI Service 
- Published dashboard for cloud access and sharing with stakeholders.


![Publish_Message](https://github.com/user-attachments/assets/d71b91b6-f867-4b49-aa7c-c1fee9cb5a6d)

# Dashboard :   Introduction Page 

![dashboard_snapo](https://github.com/user-attachments/assets/cfd53ab5-52cc-445f-a4e0-40ecaac83378)

# Dashboard :   Home Page 

![dashboard_snapo](https://github.com/user-attachments/assets/2d784e52-9f1e-4d90-b9a9-db18c083eb2e)

# Dashboard :   Trend Page

![dashboard_snapo](https://github.com/user-attachments/assets/221b3bbe-8c40-4f9f-b8d9-7510c461ede0)


# Dashboard :   Purpose Page

![dashboard_snapo](https://github.com/user-attachments/assets/051a3b51-43a3-42b4-90a4-e09e36656c32)

 
# Dashboard :   Categories Page

![dashboard_snapo](https://github.com/user-attachments/assets/fe069aa1-6f8e-4fa6-9ee2-32c184fd298e)

# Dashboard :   End Page

![dashboard_snapo](https://github.com/user-attachments/assets/5c866925-2c95-487e-8cd1-63fe26d5b561)
 
# Insights

### Loan Portfolio Performance

- High concentration of loans in medium credit categories.

- Risk of defaults higher in low credit score segments.

### Credit Score Insights

- Median credit score varies strongly across categories.
- Lower scores correlate with higher interest & default rates.

### Demographics & Risk
- Married customers hold larger average loans.
- Young age groups (25–35) contribute the most to loan demand


# Conclusion

The ABC Bank Loan Data Analysis Dashboard provides deep insights into loan distribution, credit risk, and customer profiles. By monitoring KPIs and trends, the bank can:

- Reduce default risk

- Optimize lending strategies

- Improve portfolio management


   
## Resources

[Vaccination Dataset](https://drive.google.com/file/d/1h2v2--0-v8EZ0pz7DTSdk4odyGJBJFFK/view?usp=sharing)

[Templates](https://drive.google.com/file/d/1h2v2--0-v8EZ0pz7DTSdk4odyGJBJFFK/view?usp=sharing)



## Authors

- [1908Deepak](https://github.com/1908Deepak)


## Feedback

If you have any feedback, please reach out to us at deepaksingh190810@gmail.com

