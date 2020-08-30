
# Final Report for PyCitySchools Pandas Homework


## Observable trends based on the data

* 1-The performance of `Charter` schools **is significantly better** than the performance of `District` schools. This conclusion is based on the results show in `tables 3 and 9`. On the other hand, `District` schools present a lower performance as can be seen in `tables [4] (./Pandas_Report.md) and [9] (./Pandas_Report.md#school-type-results)

[Here] (./Pandas_Report.md#table-8---school-performances-based-on-school-size)

* 2-From `Table 8`, it is possible to conclude that the **school size** has a direct relation with the `% Overall Passing`. **Small** schools have a higher `% Overall Passing` while **medium** and **large** schools have a lower `% Overall Passing`.

* 3-From `Table 7`, the amount invested per student is inverse proportional to the students' performance on the `% Overall Passing`. The highest overall passing scores are achieved by a school with a lower average spending ranges per student.

## District Summary

#### Table 1 - District's key metrics


|    |   Total Schools | Total Students   | Total Budget   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|---:|----------------:|:-----------------|:---------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
|  0 |              15 | 39,170           | $24,649,428.00 |                78.99 |                   81.88 |            74.98 |               85.81 |               65.17 |

## School Summary

#### Table 2 - Summary of key metrics about each school

| school_name           | School Type   | Total Students   | Total School Budget   | Per Student Budget   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:----------------------|:--------------|:-----------------|:----------------------|:---------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Bailey High School    | District      | 4,976            | $3,124,928.00         | $628.00              |              77.0484 |                 81.034  |            66.68 |               81.93 |               54.64 |
| Cabrera High School   | Charter       | 1,858            | $1,081,356.00         | $582.00              |              83.0619 |                 83.9758 |            94.13 |               97.04 |               91.33 |
| Figueroa High School  | District      | 2,949            | $1,884,411.00         | $639.00              |              76.7118 |                 81.158  |            65.99 |               80.74 |               53.2  |
| Ford High School      | District      | 2,739            | $1,763,916.00         | $644.00              |              77.1026 |                 80.7463 |            68.31 |               79.3  |               54.29 |
| Griffin High School   | Charter       | 1,468            | $917,500.00           | $625.00              |              83.3515 |                 83.8168 |            93.39 |               97.14 |               90.6  |
| Hernandez High School | District      | 4,635            | $3,022,020.00         | $652.00              |              77.2898 |                 80.9344 |            66.75 |               80.86 |               53.53 |
| Holden High School    | Charter       | 427              | $248,087.00           | $581.00              |              83.8033 |                 83.815  |            92.51 |               96.25 |               89.23 |
| Huang High School     | District      | 2,917            | $1,910,635.00         | $655.00              |              76.6294 |                 81.1827 |            65.68 |               81.32 |               53.51 |
| Johnson High School   | District      | 4,761            | $3,094,650.00         | $650.00              |              77.0725 |                 80.9664 |            66.06 |               81.22 |               53.54 |
| Pena High School      | Charter       | 962              | $585,858.00           | $609.00              |              83.8399 |                 84.0447 |            94.59 |               95.95 |               90.54 |
| Rodriguez High School | District      | 3,999            | $2,547,363.00         | $637.00              |              76.8427 |                 80.7447 |            66.37 |               80.22 |               52.99 |
| Shelton High School   | Charter       | 1,761            | $1,056,600.00         | $600.00              |              83.3595 |                 83.7257 |            93.87 |               95.85 |               89.89 |
| Thomas High School    | Charter       | 1,635            | $1,043,130.00         | $638.00              |              83.4183 |                 83.8489 |            93.27 |               97.31 |               90.95 |
| Wilson High School    | Charter       | 2,283            | $1,319,574.00         | $578.00              |              83.2742 |                 83.9895 |            93.87 |               96.54 |               90.58 |
| Wright High School    | Charter       | 1,800            | $1,049,400.00         | $583.00              |              83.6822 |                 83.955  |            93.33 |               96.61 |               90.33 |


## Top Performing Schools (By % Overall Passing)

#### Table 3 - Top 5 performing schools based on % Overall Passing


| school_name         | School Type   | Total Students   | Total School Budget   | Per Student Budget   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:--------------------|:--------------|:-----------------|:----------------------|:---------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Cabrera High School | Charter       | 1,858            | $1,081,356.00         | $582.00              |              83.0619 |                 83.9758 |            94.13 |               97.04 |               91.33 |
| Thomas High School  | Charter       | 1,635            | $1,043,130.00         | $638.00              |              83.4183 |                 83.8489 |            93.27 |               97.31 |               90.95 |
| Griffin High School | Charter       | 1,468            | $917,500.00           | $625.00              |              83.3515 |                 83.8168 |            93.39 |               97.14 |               90.6  |
| Wilson High School  | Charter       | 2,283            | $1,319,574.00         | $578.00              |              83.2742 |                 83.9895 |            93.87 |               96.54 |               90.58 |
| Pena High School    | Charter       | 962              | $585,858.00           | $609.00              |              83.8399 |                 84.0447 |            94.59 |               95.95 |               90.54 |



## Bottom Performing Schools (By % Overall Passing)

#### Table 4 - Bottom 5 performing schools based on % Overall Passing

| school_name           | School Type   | Total Students   | Total School Budget   | Per Student Budget   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:----------------------|:--------------|:-----------------|:----------------------|:---------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Rodriguez High School | District      | 3,999            | $2,547,363.00         | $637.00              |              76.8427 |                 80.7447 |            66.37 |               80.22 |               52.99 |
| Figueroa High School  | District      | 2,949            | $1,884,411.00         | $639.00              |              76.7118 |                 81.158  |            65.99 |               80.74 |               53.2  |
| Huang High School     | District      | 2,917            | $1,910,635.00         | $655.00              |              76.6294 |                 81.1827 |            65.68 |               81.32 |               53.51 |
| Hernandez High School | District      | 4,635            | $3,022,020.00         | $652.00              |              77.2898 |                 80.9344 |            66.75 |               80.86 |               53.53 |
| Johnson High School   | District      | 4,761            | $3,094,650.00         | $650.00              |              77.0725 |                 80.9664 |            66.06 |               81.22 |               53.54 |


## Math Scores by Grade

#### Table 5 - Average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school

| school_name           |     9th |    10th |    11th |    12th |
|:----------------------|--------:|--------:|--------:|--------:|
| Bailey High School    | 77.0837 | 76.9968 | 77.5156 | 76.4922 |
| Cabrera High School   | 83.0947 | 83.1545 | 82.7656 | 83.2775 |
| Figueroa High School  | 76.403  | 76.54   | 76.8843 | 77.1514 |
| Ford High School      | 77.3613 | 77.6723 | 76.9181 | 76.18   |
| Griffin High School   | 82.044  | 84.2291 | 83.8421 | 83.3562 |
| Hernandez High School | 77.4385 | 77.3374 | 77.136  | 77.1866 |
| Holden High School    | 83.7874 | 83.4298 | 85      | 82.8554 |
| Huang High School     | 77.0273 | 75.9087 | 76.4466 | 77.2256 |
| Johnson High School   | 77.1879 | 76.6911 | 77.4917 | 76.8632 |
| Pena High School      | 83.6255 | 83.372  | 84.3281 | 84.1215 |
| Rodriguez High School | 76.86   | 76.6125 | 76.3956 | 77.6907 |
| Shelton High School   | 83.4208 | 82.9174 | 83.3835 | 83.779  |
| Thomas High School    | 83.59   | 83.0879 | 83.4988 | 83.497  |
| Wilson High School    | 83.0856 | 83.7244 | 83.1953 | 83.0358 |
| Wright High School    | 83.2647 | 84.0103 | 83.8368 | 83.645  |



## Reading Score by Grade

#### Table 6 - Average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school

| school_name           |     9th |    10th |    11th |    12th |
|:----------------------|--------:|--------:|--------:|--------:|
| Bailey High School    | 81.3032 | 80.9072 | 80.9456 | 80.9125 |
| Cabrera High School   | 83.6761 | 84.2532 | 83.7884 | 84.288  |
| Figueroa High School  | 81.1986 | 81.4089 | 80.6403 | 81.3849 |
| Ford High School      | 80.6327 | 81.2627 | 80.4036 | 80.6623 |
| Griffin High School   | 83.3692 | 83.7069 | 84.2881 | 84.0137 |
| Hernandez High School | 80.8669 | 80.6601 | 81.3961 | 80.8571 |
| Holden High School    | 83.6772 | 83.3246 | 83.8155 | 84.6988 |
| Huang High School     | 81.2903 | 81.5124 | 81.4175 | 80.306  |
| Johnson High School   | 81.2607 | 80.7734 | 80.616  | 81.2276 |
| Pena High School      | 83.8073 | 83.612  | 84.3359 | 84.5912 |
| Rodriguez High School | 80.9931 | 80.6298 | 80.8648 | 80.3764 |
| Shelton High School   | 84.1226 | 83.442  | 84.3738 | 82.7817 |
| Thomas High School    | 83.7289 | 84.2542 | 83.5855 | 83.8314 |
| Wilson High School    | 83.9398 | 84.0215 | 83.7646 | 84.3177 |
| Wright High School    | 83.8333 | 83.8128 | 84.1563 | 84.0732 |


## School Spending Results

#### Table 7 - School performances based on average spending ranges (Per Student)

| Spending Ranges Per Student   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:------------------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| < $591                        |              83.4554 |                 83.9338 |          93.46   |             96.61   |             90.3675 |
| $591-628                      |              81.8998 |                 83.1553 |          87.1325 |             92.7175 |             81.4175 |
| $628-641                      |              78.9909 |                 81.9172 |          75.21   |             86.09   |             65.7133 |
| >$641                         |              77.0236 |                 80.9574 |          66.7    |             80.675  |             53.7175 |



## School Size Results

#### Table 8 - School performances based on school size

| School Size        |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:-------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Small (<1500)      |              83.6649 |                 83.8921 |          93.4967 |             96.4467 |             90.1233 |
| Medium (1500-3000) |              80.905  |                 82.8227 |          83.5563 |             90.5887 |             76.76   |
| Large (>3000)      |              77.0633 |                 80.9199 |          66.465  |             81.0575 |             53.675  |

## School Type Results

#### Table 9 - School performances based on school size

| School Type   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:--------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Charter       |              83.4739 |                 83.8964 |          93.62   |             96.5862 |             90.4313 |
| District      |              76.9567 |                 80.9666 |          66.5486 |             80.7986 |             53.6714 |