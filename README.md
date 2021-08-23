# Regression Model for Student Grade Forecasting
This model aims to predict student grades in the future by taking the initial and final grades as a reference, as well as student learning time and free time as additional factors.
## Input
The input of this model are:
- G1 or the initial grade students have in the scale of 0 - 1.
- G2 or the recent grade students have after taking some time studying and doing evaluation test, in the scale of 0 - 1.
- study-time is the rank of how many hours students spent on studying in a week.

    | Rank | study time |
    | ------ | ------ |
    | 1 | <2 hours/week |
    | 2 | 2-5 hours/week |
    | 3 | 5-10 hours/week |
    | 4 | >10 hours/week |
- free-time is the rank of how many hours students didn't spent on doing academic productive activities in a week.

    | Rank | free time |
    | ------ | ------ |
    | 1 | <2 hours/week |
    | 2 | 2-5 hours/week |
    | 3 | 5-10 hours/week |
    | 4 | 10-15 hours/week |
    | 5 | >15 hours/week |
## Output
The output of this model is the predicted grade in a scale of 0 - 1.
