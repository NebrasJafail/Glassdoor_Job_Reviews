## Exploring Employee Ratings and Workplace Factors

**Glassdoor Job Reviews Analysis** | DSB-3 | Nebras Jafail

## Overview

Glassdoor contains a large number of employee reviews, making it difficult to identify differences in workplace experiences across companies. This project analyzes employee review data to compare overall ratings and workplace factors across selected companies, and to examine how employee ratings change over time.

## Objectives

1. Compare average overall employee ratings across selected companies.
2. Compare workplace factor ratings across selected companies.
3. Analyze changes in employee ratings over time across selected companies.

## Dataset

- **Source:** Glassdoor employee reviews
- **Initial size:** 838,566 reviews, 18 columns
- **Selected companies:** Microsoft, IBM, Oracle
- **Review period:** 2008-2021
- **Time comparison:** 2009-2020 (complete common years)
- **Main variables:** Overall Rating, Work-Life Balance, Culture & Values, Career Opportunities, Compensation & Benefits, Senior Management

## Data Cleaning & Preparation

- Removed 33,515 duplicate reviews
- Converted review dates to datetime
- Extracted review year
- Selected Microsoft, IBM, and Oracle
- Handled missing values during analysis

## Key Findings

- **Overall rating:** Microsoft has the highest average overall rating among the three companies.
- **Workplace factors:** Microsoft scored higher in most factors, while Oracle had the highest work-life balance rating.
- **Current vs. former employees:** Current employees gave higher average overall ratings than former employees at all three companies. Microsoft showed the largest gap.
- **Over time (2009-2020):**
  - Microsoft had the highest average rating every year.
  - All three companies showed an overall increase in ratings.
  - Microsoft improved the most: 3.40 (2009) to 4.36 (2020).
  - IBM: 2.90 to 3.89.
  - Oracle: 2.97 to 3.64.
 
## Presentation

[View the presentation (PDF)](file:///C:/Users/Nebras-PC/Desktop/DSB3/Projects/Glassdoor_Job_Reviews/Nebras%20Jafail_%20Project%2002.pdf)

## Recommendations

- Monitor workplace factors to identify strengths and areas for improvement.
- Track employee ratings over time to evaluate changes in workplace experience.

## Future Work

- Analyze employee reviews by industry.
- Compare ratings by location.
- Explore additional review characteristics.


## Author

Nebras Jafail, DSB-3
