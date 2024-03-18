# Grade analysis
Python juptyer notebooks and excel sheets used to analyze IIM Indore IPM-23 batch grade data. 

# Results

# Term-I

## Overall GPA Data :

### *Correlation between course GPA in term-1:*

- As observed, almost all subjects were postively correlated with each other, indicating a high scoring student in one subject is likely to score highly in other subjects as well. One course that stood out with an exceptionally weak correlation with other subjects is **Dance/Drama - 1**. Although positively correlated, the degree of correlation is near negligble.
- LSE had the second weakest correlation with relatively low correlation with most quantitative subject but a higher correlation with Sociology-I
- It must also be noted that MicroEconomics is closely related with quants subjects as opposed to social sciences.

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled.png)

- The highest degree of correlation was noted between SM-I and DC with a correlation coefficient of **0.83.**

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%201.png)

### Correlation with tentative scores of Term2 subjects:

- Here, once more, a similar trend of high correlation among quant subjects are observed with Prob, Macr and IC sharing a high degree of correlation with MIE, DC and SM-1.
- It is interesting that ITDS has a relatively weaker correlation with all term 1 subjects that could indicate that it is a new ‘type’ of course.

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%202.png)

### *Distribution of CGPA:*

CGPA were roughly normally distributed, passing the Lilliefors test with a p-value of **0.5413.** 

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%203.png)

# Component-Wise Data:

## Time series analysis:

### Course-wise inter component analysis:

- In Micro 1, CP was generally linked to marks unlike other subjects.
- It also shows a good link between all components with an avg corr of **0.716**

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%204.png)

- In SM-I and DC, mid-term and end-term exams had stronger correlation than other combinations. This might be because length of exams play a role in how students score in these exams.

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%205.png)

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%206.png)

- In all courses with projects, both group & individual projects were very weakly correlated with written test components although individual projects were slightly positively correlated.

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%207.png)

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%208.png)

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%209.png)

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%2010.png)

1. Student Profiling: 
    - Different types of students: climbers, holders and tumblers.
    - Allows you to see performance over time and closest academic rivals

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%2011.png)

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%2012.png)

1. Students with similar academic profile: 

This method used correlation coefficient between the time series rank data to figure out which students had similar rank movements to you. This is a better alternative to simply seeing who had the closest grades as it also factors in correlation in performance accross time and individual events such as a particular project or end term. 

![Untitled](Results%20aec4266ebd154604bd87e70b674dba48/Untitled%2013.png)
