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

<img src="./media/ModelComparison.png"/>

Additionally, the MVF and Intensity Graphs for these two models can be seen labelled below.

S Distribution MVF:
<img src="./media/SGraph.png"/>

S Distribution Intensity Graph:
<img src="./media/SDistribution.png"/>

Negative Binomial (Order 2) MVF:
<img src="./media/NB2Graph.png"/>

Negative Binomial (Order 2) Intensity Graph:
<img src="./media/NB2Intensity.png"/>

Range Analysis:
Data ranges had to be analyzed in order for the tool to extrapolate the models and predict future failures. As other tools were unable to work and C-SFRAT was unable to calculate calculate Laplace tests, the ranges were set to extrapolate 20 intervals past the end of the data. Ideally, the Laplace test would be able to determine an optimal range to calculate this bound. However, due to the constraints of the software used, the range of 20 intervals was chosen.

Failure Rate:


Advantages and Distadvantages of Reliability Growth Analysis:






# Assessment Using Reliability Demonstration Chart 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
