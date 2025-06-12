#  Predicting Student Academic Performance with Machine Learning
 ### A machine learning approach to promote early intervention for at-risk students (SDG 4: Quality Education)

## Introduction
Education is a fundamental human right and a key pillar of sustainable development. In alignment with United Nations Sustainable Development Goal 4 (Quality Education), this project leverages machine learning to predict student academic performance based on personal, social, and academic factors. Early identification of students at risk of underperformance enables targeted support, reduces dropout rates, and enhances learning outcomes.

## Problem Statement
Many students face academic challenges that are not immediately visible until poor performance becomes difficult to reverse. Traditional approaches to identifying struggling learners are often reactive. This project aims to shift the paradigm by using predictive analytics to:

Identify students likely to underperform before final outcomes.

Support schools and educators in delivering personalized interventions.

Improve academic equity and retention rates.

## Analysis

### Correlation

<img src = "Students_Performace_ML/corrtable.png">

From this analysis the key columns can be identified and how the are related to each other. The key focus areas are reading and mathematics. 

### Scatter plot

<img src = "Students_Performace_ML/scatterplot.png">

From this analysis clustering based on gender and the distribution is observered. 

### Predicted vs. Actual

<img src = "Students_Performace_ML/predictedvsactual.png">

The linear regression model achieves an R² score of 0.73, indicating that it explains 73% of the variance in students’ math scores. The mean squared error (MSE) is 72.74, translating to an average prediction error of about 8.5 points. Visually, the predictions follow the expected trend closely but show moderate spread, with slight overprediction for low scorers.

## Summary

This analysis explores the connection between students’ reading skills and their math performance. By using student data, we built a model that predicts how well a student might perform in math based on how well they read.

The results showed a clear relationship: students who have stronger reading skills tend to do better in math as well. While the predictions weren’t perfect, the model was able to estimate math scores with a good degree of accuracy based only on reading performance.

We also observed that:

Improving reading ability alone could lead to better math outcomes for many students.

Targeting both reading and math support together could be even more effective.

This insight is important because it suggests that improving basic literacy can also lift numeracy skills. That means:

Schools can help students perform better in math by strengthening reading programs.

Educators and policymakers can design combined literacy and numeracy interventions to boost learning outcomes more efficiently.

Supporting reading early on may help close learning gaps before they grow wider.

In short, improving reading skills doesn't just help students understand books—it can also improve how they think, solve problems, and succeed across subjects. This contributes directly to the goal of inclusive, equitable, and quality education for all.
