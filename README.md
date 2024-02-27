

Resources: I completed this on my own, I did get assistance on the % passing math and reading calculation from my tutor Kelly.

PyCitySchools:
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Total number of unique schools, Total students, Total budget, Average math score, Average reading score
% passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
School name, School type, Total students, Total school budget, Per student budget, Average math score, Average reading score
% passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows. Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows. Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Reading Scores by Grade - Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Scores by School Spending -Create a table that breaks down school performance based on average spending ranges (per student).
Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:
Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

Scores by School Size
Use the following code to bin the per_school_summary.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".
