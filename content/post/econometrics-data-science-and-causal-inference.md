---
categories:
- rstats
- teaching
comments: true
date: 2018-09-08T06:57:00
tags:
- rstats
- rmarkdown
- github
- teaching 
- econometrics
title: Econometrics, Data Science, and Causal Inference
---

I see two different aspects of econometrics. 


"Data science" is the hip new catchall term for using statistical software to analyze data for a variety of purposes. It is commonly interpretted as [the intersection of statistics, computer science, and domain expertise (e.g. business, biology, etc)](https://www.google.com/search?q=data+science+venn+diagram). I personally like the definition offered by the following tweet:

[INSERT TWEET]

Data scientists seem to be younger practitioners in industry and academia (especially) that use programming languages like R and Python to wrangle, visualize, and present data to solve empirical problems in their domain of expertise. On the academic and teaching side, it tends to be more hip statisticians, computer scientists, and biologists (bioinformatics). New graduate degree and certifications in "Data Science" or "Data Analytics" seem to be popping up left and right. 

A large part of me wanted to ride the coattails of this hot new trend and call my class something like "Introduction to Data Science." I decided against it for a few reasons that I think are instructive to discuss below. 

First, I would be encroaching the turf of my colleagues in Statistics and Computer Science departments that often have explicit classes called with titles like this. These classes are often a rehash of classic introductory statistics classes (probability, the normal distribution, $t$-tests, the central limit theorem, etc) but where software and simulation tend to replace pure theory and statistical proofs in a much more student-friendly way. It's a lot more intuitive and less tedious to calculate and understand a $p$-value via programming commands or simulation than to learn the theoretical distributions and look up critical values from a table.

Second, although some econometrics textbooks do teach introductory econometrics this way, an econometrics class is much more than just an introductory statistics class (first review probability, distributions, statistical estimators, hypothesis testing, linear regression) that continues on into a few more models and subjects. Econometrics has a particularly opinionated view of statistical models, and often uses them to a very different end than most "data science"-type uses. This is the second aspect, **causal inference.**  

Perhaps the paradigmatic application of "data science" beyond mere descriptive statistics and causal inference is "machine learning" and associated terms and techniques (e.g. "big data," "neural networks," "artificial intelligence," etc). These issues often deal with massive "wide" datasets, frequently with more variables than observations. Take the typical example in marketing and the data privacy debate: a website such as Facebook, which has a ton of information about a user -- locations they visit the website from, who their friends are, what pages they have interacted with, etc. Machine learning techniques try to identify what characteristics predict a certain outcome -- facial recognition using neural networks operates similarly: take a large number of pre-identified images (e.g. a human at some point determined the image indeed contained a face) for *training* an algorithm, pass those images through $n$-number of layers to detect common characteristics of "faces" vs. "not-faces", and then additional subtleties that differentiate one face from another, and after $n$-layers and $m$ features are determined (where both $n$ and $m$ are massive numbers!), then the algorithm can take a new image and determine *if* it includes a face, or, if it is a very good algorithm, *whose* face it is. 

The key feature of this is that it is atheoretical, it is entirely empirical. The algorithm itself has no underlying theory behind what "causes" a face or determines a face, only a purely *empirical* process of identifying patterns statistically by brute force. 

Causal inference, by contrast, whatever some hardcore empirical economists may say about "just letting the data speak for itself", necessitates an underlying theory to explain a relationship or a process. It is certainly true that some theories may be verified or disproven by data, or entirely new theories emerge via analyzing data that may never have otherwise been discovered.

Reading one of the classic modern textbooks on Econometrics, *Stock and Watson*, it seems that econometrics has always been primarily about causal inference.

> QUOTE

However, in the last decade or so, a particular strand of econometrics teachers and practitioners seem to have gotten more pathological about causal inference (I don't use the term pejoratively!). The quintessential tool for understanding causal inference are the Directed Acyclic Graphs (DAGs) popularized by Judea Pearl, or the "Causal calculus" of [NAME]? I see this show up in great teaching texts like Scott Cunningham's *Causal Inference: the Mixtape*.  

