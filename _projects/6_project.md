---
layout: page
title: What Affects Glassdoor Company Ratings?
description: An Analysis of Data Scientist Job Postings' Tone and Other Potential Factors
img: assets/img/glassdoor.jpg
importance: 1
category: academic
---

## Overview
This project investigated the impact of job posting tone on Glassdoor company ratings, with a particular focus on data scientist positions in medium to large-sized US companies. Our team utilized sentiment analysis tools to examine whether the neutrality and subjectivity of job postings correlated with company ratings. We aimed to provide valuable insights that could help job seekers make more informed decisions when assessing potential employers based on job postings.

## Research Question
How do the neutrality and subjectivity of job postings for "Data Analyst" or "Data Scientist" positions on Glassdoor correlate with the company’s overall rating for medium to large-sized US companies (500 to 5000 employees)?

## Approach & Methodology
1. **Data Collection**: The project utilized datasets sourced from Kaggle, which contained information on Data Analyst and Data Scientist job postings, company ratings, salary estimates, and other relevant variables for medium to large-sized US companies.
2. **Sentiment Analysis**: Employed the **Vader** sentiment analysis tool to measure the neutrality of job descriptions. Used **TextBlob** to assess the subjectivity of the job postings. Both tools were applied to analyze the tone of job postings and quantify its potential influence on company ratings.
4. **Statistical Analysis**: Conducted **Pearson correlation tests** to investigate relationships between the tone of job postings (neutrality and subjectivity) and company ratings. Performed **ANOVA one-way tests** and **linear regression models** to analyze other potential factors, such as salary estimates, and their correlation with company ratings.
5. **Ethics & Privacy Considerations**: All datasets used were publicly available, and no personal or sensitive information was included. The analysis strictly adhered to ethical guidelines for handling public datasets, ensuring the privacy and integrity of the data.

## Key Findings
+ **Weak Correlation Between Job Posting Tone and Company Ratings**: Our initial sentiment analysis showed a weak correlation between the tone of job postings and company ratings, suggesting that further investigation into other variables is necessary.
+ **Salary Correlation**: Inferential statistics revealed a stronger positive correlation between company ratings and salary estimates, indicating that salary may be a more significant factor in company ratings than the tone of job postings.
+ **No Statistically Significant Results**: No significant correlation was found between the neutrality or subjectivity of job postings and company ratings, which points to the potential importance of other factors in determining company ratings.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Sentiment Analysis**: Vader, TextBlob
- **Statistical Methods**: Pearson Correlation, ANOVA, Linear Regression

## Limitations
+ The study was limited to Data Analyst and Data Scientist roles within the United States, which may affect the generalizability of the findings to other industries and geographic locations.
+ The reliance on sentiment analysis algorithms introduces potential biases due to the limitations of these tools in accurately interpreting human language nuances.

## Skills Demonstrated
- Sentiment Analysis (Vader, TextBlob)
- Statistical Analysis (Correlation, Regression)
- Data Cleaning and Preprocessing
- Data Visualization and Reporting

[GitHub Repo](https://github.com/pranjlikhanna/Data-Science-in-Practice-COGS-108-Project))


