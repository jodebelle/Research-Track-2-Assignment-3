-----------------------------------------
# Research-Track-2-Assignment-3

This jupyter notebook was made in order to compare the efficiency of my code with my colleague's code of the first assignment in RT1. 
In order to do that, statistical analysis were carried out to test which implementation performed better.
About 25 readings were made but only 17 were comoplete and thus used for this analysis.
   
 ---------------------------------------------------------- 
Times recorded from my implementation and my colleague's
 
--------------------------------------------------------------------- 
Mean and standard deviation from my implementation and my colleague's

--------------------------------------------------------------------
Bar plot comparing the times of my implementation and my colleague's:
![image](https://github.com/jodebelle/Research-Track-2-Assignment-3/assets/114078097/d814cdb4-c21c-47c7-b646-b55106370706)

-----------------
Shapiro Wilk test
Shapiro Wilk test was used to determine whether the data is normally distributed or not.
The null hypothesis H0 states that my code performs better than my colleague's code, the robot assembles all the tokens faster.
A significance of 0.05 was considered in order to decide whether it is a normal distribution.
If the P-value is greater that the significance level, we can conclude that the data is normally distributed and the null hypothesis cannot be rejected.
Otherwise, the null hypothesis is rejected and it is not considered as normally distributed.

The data is not normally distributed for my sample.
P-value = 0.000987845822237432 | Significance level = 0.05

The data is not normally distributed for the colleague.
P-value = 0.048140328377485275 | Significance level = 0.05

---------
"""T-Test"""
A T-test was carried in order to see if there is a significance difference between the means of two groups.
We can observe my T-value is higher than the one from the table which shows a relatively important difference between the mean times of the two groups.

Relative T-value = -6.321260895301887 | P-value = 1.0163497262539235e-05
Independent T-value = -3.9500011155860695 | P-value = 0.0004029763202838483

The calculated t-value is larger than the table value: 3.9500011155860695 > 2.12
This means we can reject the null hypothesis H0.
