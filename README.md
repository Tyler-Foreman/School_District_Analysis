# Overview of School District Analysis

In this project, we are looking to analyze an entire high school district of 15 schools - and their students standardized test scores. We will analyze each schools funding and test scores to show trends in each schools performance. We will deliver this information to the superintendent and school board to aide them in making decisions on budgets and priorities for next year.

Within our analysis we had to modify our original results, as the school board informed us of academic dishonesty for Thomas High School(THS) 9th grade scores. We have since removed these scores and students from our overall analysis for Thomas High School and the district.

# School District Analysis Results

After creating a Jupyter notebook to manipulate and structure the data we needed to perform this analysis, we have put together the following answers for the superintendent and school board.

## How is the district summary affected?
- When we remove the 461 9th graders from THS, we have a new value of 38,709 students in the district to perform our analysis.
- The average math score is slightly impacted, dropping 0.1 points and the average reading score is unchanged.
- The passing percentages are also slightly impacted; the percentage passing math falls 0.2 points. The percentage passing reading falls 0.1 points. The percentage overall passing is impacted the most and falls 0.3 points. 

**Initial District Summary**

![Initial School District Summary](/Resources/initial_district_analysis.png "Initial School District Summary")

**Refactored District Summary**

![Refactored School District Summary](/Resources/refactored_district_analysis.png "Initial School District Summary")

## How is the school summary affected?
- When omitting the THS 9th grade test scores, there is a small impact to the average scores and % passing.
- The average math score for THS fell 0.06 points. Surprisingly the average reading score for THS increased 0.05 points in this change.
- The passing percentages were also slightly impacted; the percentage passing math fell 0.09 points. The percentage passing reading fell 0.29 points. The percentage overall passing is impacted the most, falling 0.32 points.

**Initial School Summary**

![Initial School Summary](/Resources/initial_school_analysis.png "Initial School Summary")

**Refactored School Summary**

![Refactored School Summary](/Resources/refactored_school_analysis.png "Refactored School Summary")

## How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other high schools?
- There is really no impact in replacing the 9th grade test scores for THS in how they ranked against the other schools. Thomas High School was the second best ranked school, in terms of overall passing percentage, prior to replacing the 9th grade test scores. They retained this position as the second best ranked school in our updated analysis.

**Initial Top Schools Summary**

![Initial Top Schools Summary](/Resources/initial_top_school_summary.png "Initial Top Schools Summary")

**Refactored Top Schools Summary**

![Refactored Top Schools Summary](/Resources/refactored_top_school_summary.png "Refactored Top Schools Summary")

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade:
- There is no change to any other grade or school when we replaced THS ninth-grade scores. In our updated dataframe, the THS ninth-grade scores are now replaced with NaN.

### Scores by school spending:
- Since THS has a per student budget of $638 - they will fall in the third bin of $630-644 in our school spending dataframe. There is a very nominal change in the raw data scores and percentages - however when these scores are formatted properly and rounded there is no observed change between the original analysis and the updated analysis.

### Scores by school size:
- Since THS has a student count of 1,635 students - they will fall in our medium school size bin in our school size dataframe. There is a very nominal change in the raw data scores and percentages - however when these scores are formatted properly and rounded there is no observed change between the original analysis and the updated analysis.

### Scores by school type:
- Since THS is a charter school - their scores were calculated with other charter school types in our school type dataframe. There is a very nominal change in the raw data scores and percentages - however when these scores are formatted properly and rounded there is no observed change between the original analysis and the updated analysis.

# Summary

In our revised school district analysis in which we removed the Thomas High School ninth-grade scores it is clear there is little impact to the math/reading scores by grade. There is also little change in the scores by school spending, school size or school type. Based on this inconsequential change in the data, it would be our recommendation for the school board to move forward with their original decisions for the budget and priorities next year.