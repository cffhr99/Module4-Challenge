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
As the removal of 9th grade math and reading scores, Thomas High School was the second top-performing school. After omitting these scores, Thomas High School's rank was decreased.
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
If the "NaN" on *9th* grade scores of *Thomas High School* was as "0" and all other grades of *Thomas High School* did not count *9th* student to the total, it only influenced *9th* grade result and all other grades maintained their results. 

#### Scores by school spending
|Scores by School Spending:      |      |  |
| ------------- |:-------------:| -----:|
|Before      | |  |
|Avg_math:     83.41  | Avg_Reading: 83.84      | %Passing_Reading:    97.31|
|After  
|Avg_math:     59.84  |Avg_Reading:     60.24    | %Passing_Reading:    69.66|

#### Scores by school size
*Thomas High School* is in school size bin Medium(1000-2000). Scores before and after differs by medium schoool size as follows:

|Scores by School Size:     |      |  |  |  |
| ------------- |:-------------:|:-----:|:-----:|:------:|
|Before      | |  | | |
|Avg_math:   83.37  | Avg_Reading: 83.86   | %Passing_Reading: 96.79| %Passing_math:  93.60 | %Overall Passing:  94.82 |
|After  
|Avg_math:    78.7 |   Avg_Reading: 79.1    | %Passing_Reading:     91| %Passing_math:     88 |  %Overall Passing:     90 |
#### Scores by school type
| Scores by School Type:   |      |  |  |  |
| ------------- |:-------------:|:-----:|:-----:|:------:|
|Before      |School Type | Avg_math  |Avg_Reading | %Passing_Reading |
|          |Charter   |83.5| 83.9 |97 |
|After  
|          |Charter  | 80.5|80.9 | 93|
## Summary
