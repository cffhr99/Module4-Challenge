# Module4-Challenge: School District Analysis
## Overview
The purpose of School District Analysis is to analyz the data of a school district to provide clear results on every schools' performance.
## Resources
*Resources*: All csv files are in [Resources]("")  
*Software*: Python 3.8, Anaconda, Jupyter Notebook
## Results
Due to the potential academic dishonesty by the *9th* grade students of *Thomas High School*, this project was designed for two trials. The first one inclued the full dataset. And the other one omitted the socres of *9th* grade student from *Thomas High School*. The method decided was  to replace the original *9th* grade students' scores with *NaN*.
### How is the district summary affected?
The first table is the district summary of the full dataset.
![old_district_summary]()
The second table it the district summary of the dataset omitting *9th* grade students' scores with *NaN*.
![new_district_summary]()
It was obvious that all numbers from the first table became smaller by omitting *9th* grade students' scores with *NaN*. But the difference was not significant, which means that only one *9th* grade scores' cannot influence a lot on total district.

### How is the school summary affected?
The following tables are the results of school summary and  the first one was from the full dataset.
![old_school_summary]()
![new_school_summary]()
Unlike the district summary, the *9th* grade scores had a significant influence on the school summary. All the results were increased by adding *9th* grade score to dataset for analysis.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
#### Scores by school spending
#### Scores by school size
#### Scores by school type

## Summary
