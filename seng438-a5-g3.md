**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       | 3  |
|-----------------|---|
| Student Names:  | Avijot Girn  |
|                 | Aaron Frerichs  |
|                 | Ethan Subasic  |
|                 | Jesse Gerbrandt  |

# Introduction

# 

# Assessment Using Reliability Growth Testing 
| Result of model comparison (selecting top two models)                                                    | 5   |
| Result of range analysis (an explanation of which part of data is good for proceeding with the analysis) | 5   |
| Plots for failure rate and reliability of the SUT for the test data provided                             | 15  |
|                                                                                                          |     |
| A discussion on decision making given a target failure rate                                              | 10  |
|                                                                                                          |     |
| A discussion on the advantages and disadvantages of reliability growth analysis                          | 5   |

Result of Model Comparison:
Using the C-SFRAT tool, multiple models were able to be compared in order to discover the most accurate model to depict the data analyzed. The following methods were compared using this tool:
-IFR generalized Salvia & Bollinger
-S Distribution
-Discrete Weibull (Order 2)
-Discrete Weibull (Type III)
-Geometric
-Negative Binomial (Order 2)
-Truncated Logistic

The two most effective models found were the S Distribution and Negative Binomial (Order 2) methods. Using the C-SFRAT tool, Model Comparison was used to deduce these two models as the most effective. As shown in the figure below, these 2 models have the closest Critic to 1. This points to these models being the most accuate to the input data.






# Assessment Using Reliability Demonstration Chart 
 It can be observed that the use of RDC (Reliability Demonstration Chart) for the evaluation of a project, yields diverse outcomes based on the chosen metrics. The three figures presented below demonstrate that the dependability of the program could either be acceptable or not reliable enough based on the MTTF being used.

 ![1 fail per 500s](/media/RDC1fp500s.png)
 _1 fail per 500 seconds_

For an acceptable failure rate of 1 failure for every 500 seconds, the software displays a clearly acceptable behaviour as the curve of fails is seen to drop deep into the green. By the metric set here the software is reliable enough and should be easily accepted.
#
![1 fail per 1000s](/media/RDC1fp1000s.png)
 _1 fail per 1000 seconds_

The selection of the MTTF value used in this graph was based on data analysis, a value was chosen where the RDC mostly remained within the continue testing range. This value also demonstrated then effects of halving and doubling the MTTF value clearly, as seen in the previous (halving) and succeeding (doubling) graphs. For an acceptable failure rate of 1 failure for every 1000 seconds, the software is much less acceptable by the new metrics since the project is under more harsh requirement not to fail. Though the software is much less acceptable than the pervious image the data mostly stays out of the failure zone and after enough run time even stabalizes in acceptable area, so this software is still acceptable enough. Additional testing may be needed in order to ensure the reliability of the software and to observe any discernible trends that may lead to a more obvious acceptance or rejecction.
#
![1 fail per 2000s](/media/RDC1fp2000s.png)
 _1 fail per 2000 seconds_

For the failure rate of 1 failure every 2000 seconds the curve shoots straight up and consitently sits in the red rejection zone for the entire duration of testing. For this metric the program has demonstraited complete failure and should not be accepted.
# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
