# Customer-Segmentation

## Explained: Blog (Step-by-Step Explaination)
https://medium.com/swlh/customer-segmentation-in-online-retail-cohort-analysis-eb352085e64b

## Tools: Jypter Notebook, 

## Cohort Analysis
A cohort is a set of users who share similar characteristics over time. Cohort analysis groups the users into mutually exclusive groups and their behaviour is measured over time.

### Cohort Analysis: Retention Rate
Since, we will be performing Cohort Analysis based on Transaction records of Customers, we will be Dealing with Mainly:                                                             
· Invoice Data                                                                                                                                                                     
· CustomerID                                                                                                                                                                       
· Price                                                                                                                                                                             
· and Quantity columns in this Analysis                                                                                                                                             

Step 1: Month Extraction from InvoiceDate Column
Step 2: Assigning Cohorts to Each Column
Step 3: Assigning Cohort Index to each transaction
Step 4: Calculating number of unique customers in each Group of (CohortDate,Index)
Step 5: Retention rate Calculation
Step 6: Visualizing the Above Retention rate

