
# 2023 Stack OverFlow Developer Survey Analysis




## Overview

The primary focus of this project is to clean, transform, and analyze the 2023 Stack Overflow Developer survey in order to gain insights such as which companies pay developers the most, most popular methods of learning to code, and whether the level of pay is affected by coding experience.

## Tools

- R, R Studio
- R Markdown
## Libraries Used

- Tidyverse, ggrepel, RColorBrewer, knitr, kableExtra, skimr

## Data Cleaning / Preparation

- Loaded the necessary libraries then imported the csv file into R
- Used glimpse function to check the data structure
- Selected columns to be used in the analysis and stored them in a new object
- Checked for duplicates and missing values 
- Recoded values in some columns into short descriptive values
- Fixed the incosistent values in one column, then converted it to numeric


## EDA / Data Analysis

- Utilised a bar plot to understand the age distribution of developers
- Identified the top 10 countries with the most developers across the world
- Analysed the data to retrieve the top 10 most used programming languages, used a table to visualize the results.
- Identified the most popular method of learning to code among developers
- Performed a statistical test to ascertain whether there is a significant difference between salaries earned by data scientists and data analysts
- Identified the companies where developers get paid the most (top 5). Visualized the results using a boxplot
- Checked the likelihood of getting a job as a developer if you have a masters degree
- Lastly, I used a scatter plot to check whether there exists a relationship between Coding experience and Yearly compensation of developers


## Interpretation

- Based on our dataset, majority of the developers (33,247) are aged between 25 - 34 years, and as expected, developers aged above 65 years were the least. Out of the 89,184 developers who participated in the survey 18,647 of them were from the United States of America, Germany came second, followed closely by India and the United Kingdom.
- Javascript is the most widely used programming language among developers, HTML/CSS closely follows. Intrestingly, Python which came third, has gained more popularity than SQL over the past year, compared to the 2022 Developer Survey.
- The survey revealed that the most popular method of learning to code among developers was by Other Online resources (e.g, videos, blogs, and forums) which had 24 % popularity. School i.e, Universities/colleges, Books/Physical media, and Online courses / Certifications had 15 % popularity consecutively among developers as their go to method for learning how to code.
-  The Mann Whitney u test indicated that there is a statistically significant difference between the Yearly Compensation given to data scientists and data/business analysts.
- The survey also indicated that Cocolation, Fly.io, Amazon Web Services, Linode, and Cloudfare were the best paying companies to developers. With Cocolation having the highest median annual pay.
- Finally, there is a weak positive relationship between Coding experience and Yearly compensation for developers, this implies that there may be other factors that determine the level of pay other than coding experience.
