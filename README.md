# DataSciencePracticum-1

The data set contains the records of the jobs run by a large computer system. Each job is associated with a user name, has a submission time, start time and end time, and several other attributes. The exercise is to write a program to extract statistical information from the data set. The example code is written in Python, but you can use the languages of your choice as long as you can produce the results.

Download these data files:

data file

If you are using Python, the data file can be easily read by the read_hdf function in Pandas (https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_hdf.html). See the example code below.

Contents:

Assignment
Generate a “report” as a single pdf format containing the following information that is readable by a lay person.

Assignment 1-1
Answer the following question:

How many jobs are run by each user? (e.g. user1: 34, user2: 21, …)
How many jobs are run by each group? (e.g. group1: 324, group2: 24, ..)
For each group, list the number of users, and list all of these users users (i.e. the users having the same “group” field). For examplle: group 1 (4 users): user2, user32, user41, user56
Assignment 1-2
Compute the CPU-hours, defined as (h_rt)*(slots), used by each group by generating a diagram similar to the following.

Sort the results in an decreasing order. Your plot should look like the following in which the labels of the vertical axis are the names of the groups and the labels of the horizontal axis are the CPU-hour values:


Assignment 1-3
Compute the total number of jobs corresponding to each “slot” number by generating a plot like the following one.

Note that the number of jobs corresponding to “slots=1” is much larger so we will not display it in order to avoid distorting the results. At the end, you should get a diagram similar to the following one:

