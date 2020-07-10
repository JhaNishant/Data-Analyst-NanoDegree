# Diamonds Data Exploration

## Dataset

There are 1,000 diamonds in the dataset with 10 features (gender, ethnicity, 
parental_level_of_education, lunch, test_preparation_course, math_score, 
reading_score, writing_score, percentage & grade). 
The dataset can be found from kaggle [here](https://www.kaggle.com/spscientist/students-performance-in-exams)


## Summary of Findings

In the exploration, I found that there was a strong relationship between all
score features with modifying effect from the test preparation course & 
gender. The relationship between scores was almost found to be linear also 
with the engineered feature, percentage. Majority of students scored B & C 
grade. The gender ratio was found to be almost 1:1 with  females being a 
little more in presence, in the dataset. It was found that female students 
did comparitively better than male students. Only around 1/3rd of students 
have completed the test preparation course. Students who completed the test 
preparation course, had high percentages as compared to the students who
didn't complete the test preparation course.

Outside of the main variables of interest, I verified the relationship between
parental level of education and total score in percentage. For the dataset 
given, this was an interesting interaction. It showed that students whose
parents have completed master's degree scored the best. And students whose 
parents have only completed high school had a comparitively low performance 
in terms of percentage.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the test preparation
course & gender on the total score in percentage. I start by introducing the
distribution of score features, followed by distribution of grades, then 
plotted the barplot on total score in percentage by test preparation course &
gender.
