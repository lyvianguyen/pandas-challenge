# PyCitySchools

# Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

# District Summary
- Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

- Total number of unique schools

- Total students

- Total budget

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

# School Summary
- Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

- School name

- School type

- Total students

- Total school budget

- Per student budget

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

# Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

# Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

# Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Include the following metrics in the table:

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

# Scores by School Size
Use the following code to bin the per_school_summary.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

# Observations and Conclusions 
- Amongst the 15 schools in the district, there is a total of 39,170 students. Based of the average of the math and reading scores, we can conclude that overall students score higher in reading by about 3 points.
- The top schools with the most students are district school. Charter schools have twice as less students. Despite this observation, the budget per student ranges from $500-$600 across both type of schools. 
- Charters schools have a higher overall pass rate. This can be attributed to their smaller school sizes meaning the ratio of students per teacher is lower. That means teachers can allocate more time to each student. 
- Even though charter and district schools have similar average math and reading scores, the top five performing schools based on overall pass rates are all charter schools and the five lowest performing are district schools. 
- We can see the test scores broken up by grade averages a "B" across the board for charter schools. 
- Conclusion #1: Charter schools rank higher in performance in both math and reading scores. We can draw the correlation of larger school sizes to lower academic performances.
- Conclusion #2: Cabrera High School has the highest overall pass rate of 91.33% with a budget per student of $528. This is actually on the lower end of the spectrum of budget per students compared to Huang High School with $655/student. Huang High School is one of the lowest performing schools. From our dataset, we cannot conclude why a larger budget per student would result in lower academic performance. 
