# Description
This repository is the contribution to the Online Courses Dropout Factors Investigation project of Sirius.Courses.

The repository contains the notebook including the investigation of average tries number to solve a task as a potential factor that is able to influence students dropout. The notebook is organized to analyze course data automatically and output graphs of distributions, weekly average tries numbers, students numbers, and hypothesis testing results. It does not include detailed explanations and conclusions that were provided in the final project report.

# Project details
The goal of the project was to investigate what potential factors influence students dropout.

The literature review was performed, and three factors were chosen and constructed. They are an average tries number to solve a task, lagging and the occurrence of a descending trend of a tries number to solve a task. Three hypotheses were suggested in research and mathematical terms. The repository includes the investigation of the average tries number to solve a task only.

The research hypothesis: we believe that the more tries on average a student makes, the more difficult they take a course, and higher the risk of dropout.

The mathematical hypothesis:

- null hypothesis: the average tries numbers of solving tasks equal between each other for students who will dropout a course and finish it successfully
- alternative hypothesis: a null hypothesis is wrong   
# Research results
The recording of 6 courses were analyzed. The distributions of average tries numbers to solve a task among students who got a credit and who dropped out, weekly average tries numbers and students number were visualized. As long as the obtained distributions did not match a normal distribution, the bootstrap method was chosen to test the hypothesis.

The main findings are concluded that the average tries number to solve a task is not recommended to use as a behavioral factor for predicting students dropout if different courses are combined. Nevertheless, using the factor for a separate course is able to show informative results.
