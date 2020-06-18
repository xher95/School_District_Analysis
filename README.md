# School_District_Analysis
Anaconda, PythonData, Pandas

## Load CSV and store in Pandas DataFrame
- students_complete.csv
- schools_complete.csv
- Count for missing values.
- Cleaned up incorrect data.
- Combined both data into a single datasheet

## Calculate all values
- .count() and .sum() and .mean()

## Determined Passing grade for Math and Reading assessments.
- Separate passing students to new DataFrame for both math and reading.
- Calculated percentages for passing math and reading.
- Added list of values with keys to create a new DataFrame.
- Format df
- Reordered columns

## Determined School Type
- Added total student count per school
- Calculated total school budget, per capita spending, and average math and reading scores.
- Calculated percentage of passing math and reading.
- Calculated students passing both and its percentages

## Sort and showed top five schools and bottom five schools

## Create DataFrame for different categories
- School series by school name for average math and reading scores by:
  - grade
  - school spending
  - school size
  - school type
  
# Challenge

## Thomas High School Score Changes
- import numpy as np
- NaN 9th graders test scores.

## How the Changes Affects the Summaries
### School Summary
  - No changes in students, budget, per student budget, and average math scores.
  - Average reading score dropped by 0.1
  - Percent passing Math dropped by 26.4
  - Percent passing Reading dropped by 27.6
  - Percent overall passing dropped by 25.8
### District Summary
  - No changes in students, schools, total budget, and average Reading score.
  - Average Math score dropped by 0.1
  - Percent passing math, percent passing reading, and percent overall passing dropped by 1.
### Top five schools and bottom five schools
  - Thomas High School ranked second in top five, but was removed after the changes putting Griffin in second and adding Wright High School to the list.
  - No changes in bottom five schools.
### Math and Reading by grade
  - No changes except 9th graders scores were dropped (NaN) for Thomas High.
### Scores by School Spending
  - No changes in average Math and Reading scores.
  - Significant drops in passing percentages.
    1. Passing Math % dropped by 6.5
    2. Passing Reading % dropped by 7.4
    3. Overall Passing % dropped by 6.9
### Scores by School
  - No changes in average Math and Reading scores
  - Significant drops in passing percentages.
    1. Passing Math %, passing Reading %, and overall passing % dropped by 6.
### Scores by School Type
  - No changes in average Math and Reading scores.
  - Percent passing Math and Reading dropped by 4.
  - Overall passing percent dropped by 3.
