# Data-project
#Project Overview: 
Hands on web Scraping , gathering , cleaning & analyzing  data

Scraped over 1000 job descriptions from glassdoor using python and selenium

Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.

#Code and Resources Used

Python Version: 3.7

Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, 

Github: https://github.com/arapfaik/scraping-glassdoor-selenium

YouTube : https://www.youtube.com/playlist?list=PL2zq7klxX5ASFejJj80ob9ZAnBHdz5O1t

#Web Scraping

Tweaked the web scraper github repo (above) to scrape 1000 job postings from glassdoor.com. With each job, we got the following:

Job title

Salary Estimate

Job Description

Rating

Company

Location

Company Headquarters

Company Size

Company Founded Date

Type of Ownership

Industry

Sector

Revenue

Competitors


#Data Cleaning

After scraping the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

Parsed numeric data out of salary

Made columns for employer provided salary and hourly wages

Removed rows without salary

Parsed rating out of company text

Made a new column for company state

Added a column for if the job was at the company’s headquarters

Transformed founded date into age of company

Made columns for if different skills were listed in the job description:

Python

R

Excel

AWS

Spark

Column for simplified job title and Seniority

Column for description length



#Exploratory Data Analysis

I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables.
