+++
title = "ECON 480 - Econometrics"
+++

## Syllabus 
[[**Fall 2018**](https://www.dropbox.com/s/g19k5rr57qtqvzo/ECON_480_F2018_Safner_Syllabus.pdf?dl=0)] | [[Fall 2017](https://www.dropbox.com/s/sclrmnmgr055ie0/ECON_480_F2017_Safner_Syllabus.pdf?dl=0)] | [[Fall 2016](https://www.dropbox.com/s/uw6n6bk0bu0lzit/ECON_480_Safner_Syllabus.pdf?dl=0)]

[Course Content on Github](http://github.com/ryansafner/ECON480Fall2018), see [this post](https://ryansafner.com/post/econometrics-slides-on-github/) for more. 

> There are three kinds of lies: lies, damned lies, and statistics. - Benjamin Disraeli

Econometrics is the application of statistical tools to quantify and measure economic relationships in the real world. It uses real data to test economic hypotheses, quantitatively estimate causal relationships between economic variables, and to make forecasts of future events. The primary tool that economists use for empirical analysis is ordinary least squares (OLS) linear regression, so the majority of this course will focus on understanding, applying, and extending OLS regressions. 

I have three goals for everyone taking this course:<br> (1) to understand and evaluate statistical and empirical claims<br> (2) to understand research design and hypothesis testing<br> (3) to gain experience working with, interpreting, and communicating real data. I am less concerned with forcing you to memorize and recite proofs of statistical estimator properties, and more concerned with the development of your intuitions and the ability to think critically as an empirical social scientist - although this will require you to demonstrate proficiency with some intermediate statistical and mathematical tools. 

To these ends, in addition to lectures about the estimation methods, you will read several journal articles with an eye to understanding and appraising their empirical claims, use *R*---a leading professional software package---to complete problem sets using data, and write a brief empirical paper using data. By the end, you should feel comfortable working with economic data and understanding the empirical claims of others. *R* is an extremely powerful open source statistical software package that is used by economists, statisticians, and data scientists. It is very valuable and much of this course is geared towards training you how to use and apply it. The best training, of course, is for you to simply learn by doing. 

| Lecture | Date | Slides | Handouts | R Practice Problems | Homework |
|---|---|----|---|---|---|
| 1. Introduction to Econometrics | Aug 27 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture1.pdf) |  [Stats Preliminary Quiz](https://www.dropbox.com/s/lognhmhv1m8bk29/Econometrics%20Preliminary%20Quiz.pdf?dl=0) ([Answers](https://www.dropbox.com/s/47oqq47s89gtwg5/Econometrics%20Preliminary%20Quiz%20Answers.pdf?dl=0)) |  | | | 
| 2. The Quest for Causality | Aug 29 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture2.pdf)|  |  |  | |
| 3. Data and Descriptive Statistics | Sept 5 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture3.pdf)| <ul><li>[Probability Review](https://www.dropbox.com/s/g5uwfu5p8yopd67/Probability%20Review.pdf?dl=0)<li>[The Summation Operator](https://www.dropbox.com/s/88961yofeyfiquc/Summation%20Operator.pdf?dl=0)</ul> |  |  | |
| 4. Random Variables | Sept 10 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture4.pdf)|  |  |  | |
| 5. Meet R | Sept 12 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture5.pdf)|  | [R Practice #1](https://github.com/ryansafner/ECON480Fall2018/blob/master/R%20Practice/RPractice1.pdf) ([Answers](https://github.com/ryansafner/ECON480Fall2018/blob/master/RPractice1Answers.pdf))  | [HW #1](https://github.com/ryansafner/ECON480Fall2018/blob/master/HW1.pdf) | 
| 6. Correlation and Linear Regression Basics | Sept 17 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture6.pdf) | <ul><li>[Covariance and Correlation](https://www.dropbox.com/s/r8mmg8bhjogdow6/Covariance%20and%20Correlation.pdf?dl=0) <li>[Deriving OLS Estimators](https://www.dropbox.com/s/ealyfurfpqnicmy/Deriving%20OLS%20Estimators.pdf?dl=0)</ul> | | | 
| 7. Goodness of Fit and Bias | Sept 24 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture7.pdf) | [Unbiasedness of OLS](https://www.dropbox.com/s/efz15bffah2beh9/Unbiasedness%20of%20OLS.pdf?dl=0) | | | | 
| 8. Precision of OLS and Hypothesis Testing | Sept 27 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture8.pdf) | [Inferential Statistics](https://www.dropbox.com/s/ortzh50jvydpk5p/Inferential%20Statistics%20Handout.pdf?dl=0) | | | | 
| 9. Regression Diagnostics and Plotting with `ggplot2` | Oct 1 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture9.pdf) | | [R Practice #2](https://github.com/ryansafner/ECON480Fall2018/blob/master/R%20Practice/RPractice2.pdf) ([Answers](https://github.com/ryansafner/ECON480Fall2018/blob/master/R%20Practice/RPractice2Answers.pdf)) | [Homework #2](https://github.com/ryansafner/ECON480Fall2018/blob/master/Homework/HW2.pdf) | 
| 10. Omitted Variable Bias | Oct 23 |  [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture10.pdf) | | | |
| 11. Multivariate OLS Estimators | Oct 29 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture11.pdf) | | | | 
| 12. Model Specification Strategies | Oct 31 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture12.pdf) | [Writing an Empirical Paper](https://www.dropbox.com/s/80d23r9f0lp9o5u/Writing_an_Empirical_Paper.pdf?dl=0) | | [Homework #3](https://github.com/ryansafner/ECON480Fall2018/blob/master/Homework/HW3.pdf) | 
| 13. Dummy Variables | Nov 7 | [Slides](https://github.com/ryansafner/ECON480Fall2018/blob/master/Lectures/Lecture13.pdf) | [Testing Differences in Group Means](https://www.dropbox.com/s/cz1z5o0i3hcp0pe/Testing_Differences_in_Group_Means.pdf?dl=0) | | |