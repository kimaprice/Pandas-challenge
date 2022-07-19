# Pandas-challenge
Homework 3 for bootcamp:  Pandas Challenge (Pandas, Pandas, Pandas) analyzing school and standardized test data

## Background
The local school board and mayor need to make strategic decisions regarding future school budgets and priorities.  To assist in this planning, the school budgets and math and reading test scores have been analyzed to provide the decision makers with the needed anlaysis.

## Data Analysis
Report that includes the following data.

### District Summary
High-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary
DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)
DataFrame that highlights the top 5 performing schools based on % Overall Passing. Includes the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)
DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Includes the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade
DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Table that breaks down school performance based on average spending ranges (per student). Metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size
Table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type
Table that breaks down school performance based on type of school (district or charter).

## Trend Analysis Summary
### Trends:
*  Higher per student spend does not produce higher test results. It was shown in a couple of the tables that there is actually a correlation of more money being spent leading lower test scores. The Scores by School Spending is the most obvious example, but if you look at the top 5 scoring schools and compare them the the bottom 5 scoring schools; this trend is evident in the numbers seen there as well.
*  Smaller school size is indicative of higher test scores and passing rates. It it appears that the schools with fewer students are doing better on the testing based on the Scores by School Size table and comparing the top 5 and bottom 5 schools. This could be due to smaller class sizes and more individalized attention.
*  The testing is consistent across the grades in each school showing that there is not a weakness in teachers in a specific area/grade.
*  While it would be easy to assume that the Charter schools, which appear to have less funding and smaller sizes, are doing better only due to those reasons; there are factors not accounted for in this data. Often charter schools do not have the support services in place (hence the lower funding) for students with learning disabilities. This could be contributing to lower scores in the better funded schools with more students.
