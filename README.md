# pda_hw_1


Assignment 1

 

It is important that you learn to write up your results carefully. For each problem assigned for homework, you should carefully describe and justify the analytic methods used and summarize key findings in carefully written English with reference to appropriate tables and figures as needed. Use the papers themselves as templates in how to summarize results.

 

Problem #1

Read in the dataset mcalindon_Big.csv  (hint: use the read.csv function).

 

This dataset contains information on individuals who were involved in a clinical trial that measured their pain on 7 different days over the course of several weeks together with local weather information for each person. This is paper #1 on the syllabus.

 

Construct a dataset which contains just the first observation for each individual (i.e., you should have as many rows as people)

Hint: use the rle function to determine the unique id numbers and the number of rows associated with each id. Then use functions like cumsum to construct the starting and ending row numbers for each individual. This will then allow you to pull off the first row for each person.

 

 a.Summarize the average pain score for each of the 7 days of the study.
b. Regress each pain score on age and use the summary function to create a summary table for each regression Then use the confint function to find the 95% confidence interval for the regression slopes and produce a table with the estimates, standard errors, p-values and confidence intervals of the 7 slopes and put these in a single table.

c.For each individual fit a regression of pain on time. Summarize the slopes and intercepts produced. 

d.Are the slopes or intercepts related to any of the patient characteristics (age, race, income, treatment, sex,  occupation, working status, use of NSAIDs,)?

e.For each individual, compute the correlation between pain scores and average temperature on the dates the pain scores were taken and constuct a graph to display these correlations. Discuss whether pain is correlated with temperature..

 

Problem #2

In the paper by Wang et al. (paper #10 in your syllabus), reproduce Table 2 using just the outcome data without trying to fit the mixed model. In other words, the differences at each time in the two treatment groups should be calculated just as a difference in means with a corresponding confidence interval. It is easist if you fit a simple linear model to produce the effects at each time for each difference compared to baseline. You can then also find the difference of the differences to compare treated and control.  

 

The data will all be in the file Wang.csv. The associated codebook will help you with which variables to use.
