# School_District_Analysis
Module 4 - Anaconda, Jupyter
## Overview
The project was requested by the school district to analyze specific metrics using the school and student data.  The analysis needed to factor in cleaning of the names (removing prefixes and suffixes) and removing grades where they have been marked as suspicions and replacing them with NaN. The analysis needed to report on the metrics such as total district review, a summary by school, average scores by grade and school, and looking at scores based on school size, school spend and school type.  

## Results
Removing the grade nine scores from Thomson High School had the below effect on the analysis.

### Affect on School District Analysis
•There was only a small impact on the school district summary:
    •Average math score decreased by 0.1% from 79.0 to 78.9

    •Number of students who passed math decreased by 0.2%, from 75.0% to 74.8%

    •No change to average reading score - it remained 81.9

    •Number of students who passed reading decreased by 0.1% from 85.8% to 85.7%

    •Overall passing decreased by 0.3%, from 65.2 to 64.9%
The results from the original analysis: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20District%20Analysis%20-%20Original.PNG
The revised analysis can be found: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20District%20Analysis%20-%20Revised.PNG

### Affect on School Summary Analysis
•The only school impacted by the change to the grades is Thomson High School

    •The average math score went from 83.41 to 83.35, but if we apply rounding rules to the first decimal place, there is no change to math score. 
    •The average reading score went from 83.8 to 83.9
    •The % who passed math went from 93.27% to 93.19%
    •The % who passed reading went from 97.30% to 97.02%
    •The % who passed both reading and math went from 90.95% to 90.63%

Original School Summary Analysis: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20Info%20-%20Original.PNG
Revised School Summary Analysis: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20Info%20-%20Revised.PNG

## Change in Thomson HS vs other Schools
•When removing the grade nine scores from Thomson HS did not impact the ranking of Thomson High School relative to the other schools in the district.  It remained as the 2nd highest ranked school with and without the grande nine scores included.

Original School Ranking:https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20Ranking%20-%20top%205%20-%20Original.PNG
Revised School Ranking:https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/School%20Ranking%20-%20top%205%20-%20Revised.PNG


## Affect on Scores by Grade, School Spending, School Size and School Type

### Affect on Math and Reading Scores by Grade
•The only impact to the reading scores by grade would be for the grade nine scores in reading in math for Thomson HS.  Rather than showing an average, they would show NaN.  
Math Scores by Grade: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/Math%20Scores%20by%20Grade.PNG
Reading Scores by Grade: https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/Reading%20Scores%20by%20Grade.PNG

### Affect on Score by School Spend
•It would be expected that we might see impact to the spend category that includes Thomson High School - $630-644.  When comparing the original analysis and the revised analysis at the school spending level, there is no change
https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/Analysis%20by%20Spend.PNG

### Affect on Score by School Size
•There was no change to the scores when analyzing the data based on the size of the school (number of students)

https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/Analysis%20by%20School%20Size.PNG

### Affect on Score by School Type
•There was no change on the scores when analyzing the data by School type.  
https://github.com/julianadvds/School_District_Analysis/blob/main/Resources/Analysis%20by%20School%20Type.PNG

## Summary
By removing the grade nine math and reading scores, some, but not all of the results were impacted at the school district level.  Minor changes were seen in the overall district math score which slightly decreased. There was also a change in the percentage of students who passed math, reading and overall passed both math and reading. There was no change to the average reading score in the district.

