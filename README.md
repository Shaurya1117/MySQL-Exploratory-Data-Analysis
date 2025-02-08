Dataset Overview (layoffs.csv)
The dataset contains 2,361 records and 9 columns, capturing details about company layoffs, industry, location, funding, and percentage of employees laid off.

Key Columns:
company – Name of the company.
location – City where layoffs occurred.
industry – Industry type (e.g., Tech, Retail, Finance).
total_laid_off – Number of employees laid off.
percentage_laid_off – % of workforce affected.
date – Date of layoffs.
stage – Funding stage of the company (e.g., Series A, Post-IPO).
country – Country where layoffs occurred.
funds_raised_millions – Amount of funding raised (in millions).

Observations:
✅ Some columns contain missing values (e.g., total_laid_off, percentage_laid_off, industry, stage, funds_raised_millions).
✅ Date is stored as a string (object) and should be converted into a DATE format in MySQL.
✅ This dataset is useful for analyzing layoff trends, industries most affected, and correlation with funding stages.

I've created SQL queries for Exploratory Data Analysis (EDA) using MySQL on the layoffs dataset.

📌 Queries Include:
✅ Data cleaning (handling missing values, formatting dates)
✅ Industry-wise layoffs
✅ Top 5 affected countries
✅ Monthly layoff trends
✅ Companies with the highest layoff percentage
✅ Impact of funding on layoffs
