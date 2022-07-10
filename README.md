# School_District_Analysis

## Overview
I was asked by Maria to complete an analysis on school data within the district. The overall goal was to review the school and student data sets, clean the data, and make changes where needed. Jupyter notebook was needed so that I can use the tool to perform my analysis. The original data was messy, students had prefixes and suffixes that did not match or were added in error, and some grade data was incorrect.

## Results
* How is the district summary affected?
** The original district summary listed 15 total schools, 39,170 total students, a budget of $24,649,428.00, 79.0 average math score, 81.9	average reading score, 75% passing math score,	86% passing reading score, and 65% overall passing score.
![2022-07-09 (1)](https://user-images.githubusercontent.com/104965708/178134768-2f5d0e0c-4396-4b35-9763-dc9786c0cb69.png)
** The new district summary lists 15 total schools, 39,170 total students, a budget of $24,649,428.00,	78.99 average math score,	81.88 average reading score,	74.76% passing math score, 85.66% passing reading score, and 64.86% overall passing score.
![2022-07-10](https://user-images.githubusercontent.com/104965708/178135130-44e8ed37-941d-4bf9-b7db-8d5109278276.png)
* How is the school summary affected?
** The initial school summary showed the first 5 schools which were the following:
*** Bailey HS- School Type: District, Total Students: 4976, Total School Budget: $3,124,928, Per Student Budget: $628
*** Cabrera HS- School Type: Charter, Total Students: 1858, Total School Budget: $1,081,356, Per Student Budget: $582
*** Fugueroa HS- School Type: District, Total Students: 2949, Total School Budget: $1,884,411, Per Student Budget: $639
*** Ford HS- School Type: District, Total Students: 2739, Total School Budget: $1,763,916, Per Student Budget: $644
*** Griffin HS- School Type: Charter, Total Students: 1468, Total School Budget: $917,500, Per Student Budget: $625
![2022-07-10 (1)](https://user-images.githubusercontent.com/104965708/178135722-cf2b4a4b-f018-4d41-8082-26db86c2c24f.png)
** The new school summary shows the following:
*** Bailey HS- School Type: District, Total Students: 4976, Total School Budget: $3,124,928, Per Student Budget: $628
*** Cabrera HS- School Type: Charter, Total Students: 1858, Total School Budget: $1,081,356, Per Student Budget: $582
*** Fugueroa HS- School Type: District, Total Students: 2949, Total School Budget: $1,884,411, Per Student Budget: $639
*** Ford HS- School Type: District, Total Students: 2739, Total School Budget: $1,763,916, Per Student Budget: $644
*** Griffin HS- School Type: Charter, Total Students: 1468, Total School Budget: $917,500, Per Student Budget: $625
![2022-07-10 (3)](https://user-images.githubusercontent.com/104965708/178135954-e969a1fc-8ece-4bb3-84bf-cedc9b4cb954.png)
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
** Thomas High School is missing scores for both math and reading for the 9th grade. Even with the missing scores, Thomas High School is listed as number 2 in the top 5 scoring schools list.
![2022-07-10 (4)](https://user-images.githubusercontent.com/104965708/178136394-b72fc3cd-2dec-4150-9aba-0ad10dc450be.png)
![2022-07-10 (5)](https://user-images.githubusercontent.com/104965708/178136397-120c5132-ac43-4f67-aac7-908c3856766f.png)
* How does replacing the ninth-grade scores affect the following:
** Math and reading scores by grade
*** 9th Grade Math: Holden High School is the top school with a 83.8 score. Thomas High School has no score.
*** 9th Grade Reading: Wilson High School	 is the top school with a 83.9 score. Thomas High School has no score.
*** 10th Grade Math: Griffin High School is the top school with a 84.2 score. Huang High School is the lowest scoring school with a 75.9 score.
*** 10th Grade Reading: Cabrera High School is the top school with a 84.3 score. odriguez High School is the lowest scoring school with a 80.6 score.
*** 11th Grade Math: Holden High School is the top school with a 85.0 score. Huang High School and Rodriguez High School both have a 76.4 score.
*** 11th Grade Reading: Shelton High School is the top school with a 84.4 score. Ford High School is the lowest scoring school with a 80.4 score.
*** 12th Grade Math: Wright High School is the top school with a 83.6 score. Ford High School is the lowest scoring school with a 76.2 score.
*** 12th Grade Reading: Holden High School is the top school with a 84.7 score. Huang High School is the lowest scoring school with a 80.3 score.
** Scores by school spending
*** Hernandez High School, Huang High School, and Johnson High School have a spending range of $645-675 per student. Cabrera High School, Holden High School, Wilson High School, and Wright High School have a spending range of <$584 per student.
** Scores by school size
*** Bailey High School has the largest school size with 4976 total students. Holden High School	has the smallest school size with 427 total students.
** Scores by school type
*** Medium school size has the highest overall passing rate of 90.56. The largest school size has the lowest overall passing rate of 58.29.

* Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
By updating the data for Thomas High School, the averages for the passing grades were altered slightly. The previous averages for math were 83.418349	and reading was 83.848930. Thomas High School's new averages are for math 83.350937, and reading 83.896082. The overall passing went from 90.948012 to 90.630324. The overall average did not change by much. To me, this shows that the data that is missing does not really hold enough wait to throw all of the numbers off.
