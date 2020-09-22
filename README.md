pandas-challenge: PyCitySchools
======================================================
Version: 1.0.0

Description
---------------
The purpose of this script is to analyze district wide standardized test results. 

## Datasets
Two datasets were used in this analysis: general information about the district high schools and individual student performance on standardized testing.

![alt text](LINK HERE "School Information")

![alt text](LINK HERE "Student Test Scores")

## Analysis

There are some general trends that we observed in the data. As can be seen from the tables below, charter schools have the highest passing rates while district schools have the lowest.

![alt text](https://github.com/rebekahcallkacz/pandas-challenge/blob/master/PyCitySchools/Images/top_5_schools.jpg "Top 5 Schools by % Overall Passing")

![alt text](https://github.com/rebekahcallkacz/pandas-challenge/blob/master/PyCitySchools/Images/bottom_5_schools.jpg "Bottom 5 Schools by % Overall Passing")

![alt text](https://github.com/rebekahcallkacz/pandas-challenge/blob/master/PyCitySchools/Images/school_type_passing_rate.jpg "Average Passing Rates by School Type")

It is also clear that in this district, schools with 2,000 or fewer students have higher average scores and passing rates. 

![alt text](https://github.com/rebekahcallkacz/pandas-challenge/blob/master/PyCitySchools/Images/school_type_passing_rate.jpg "Average Scores by School Size")

Surprisingly, schools that have higher budget allotments per student have lower performing students. 

![alt text](https://github.com/rebekahcallkacz/pandas-challenge/blob/master/PyCitySchools/Images/spending_per_student_passing_rates.jpg "Average Scores by Budget Per Student")

Although this analysis provides us with a general overview of the current patterns of testing performance within this specific district, this does not paint a complete picture. Both educators and educational researchers have raised concern about standardized testing since it is a flawed measure of performance which disadvantages students of color, students with low socioeconomic status (SES) and students with disabilities (FairTest, 2020). In evaluating schools and student performance on standardized testing, it is essential that we also review these factors. For example, one study on student performance in Grades 3-10 found that the student characteristics were almost four times as influential than school characteristics when evaluating math standardized test scores (Singh, 2015). This dataset did not include SES, race or disability status which are all shown to have significant effects on testing performance.  

## References
FairTest. (2020). "FairTest Fact Sheets". fairtest.org

Singh, M. (2015). Influence of socioeconomic disadvantages on mathematics achievement: A multilevel cohort analysis. *The Journal of Educational Research, 108*(5), 347-357.


Instructions
----------------
This script is tailored to two datasets with specific column names and information. If it were to be applied to another dataset, the data would need to be formatted accordingly or the code would need to be modified.

Contributors
----------------
Rebekah Callari-Kaczmarczyk

License and Copyright
--------------------------
&copy; Rebekah Callari-Kaczmarczyk