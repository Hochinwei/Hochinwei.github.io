---
layout: page
title: Resources
subtitle: A collection of resources I have developed for research and education.
---

# Introduction to Power Analysis

One of my most popular open educational resources is a beginners guide demonstrating how to perform a power analysis using different software. You can download the guide on the [Open Science Framework](https://osf.io/zqphw/). It currently covers:

- Some background on the statistics and rationale behind power analysis
- Power analysis using G*Power
- Power analysis using jamovi
- Power analysis for factorial designs using the SuperPower app

If you use the guide, please consider citing it: Bartlett, J.E. (2022, February 1). Introduction to Power Analysis: A Guide to G*Power, jamovi, and Superpower. https://osf.io/zqphw/. DOI: 10.17605/OSF.IO/PCFVJ.

# ScholaRship

With my colleagues from the University of Glasgow and Edinburgh, we have started writing a series of tutorials on using R for the scholarship of teaching and learning. We recognised many resources out there either do not focus on scholarship research or do not use realistic messy data you could expect when working with student data. We are steadily building the book as a resource and currently we have: 
- [Introduction](https://emilynordmann.github.io/scholaRship/intro.html) - Here we outline the motiviation behind our book and what knowledge we expect to engage with the book. 
- [Creating synthetic datasets](https://emilynordmann.github.io/scholaRship/creating-synthetic-datasets.html) - I led on our first substantive chapter to demonstrate creating synthetic data sets when ethics concerns might limit sharing data from participants. Previous tutorials were highly technical or focused on topics researchers in the scholarship of teaching and learning might not resonate with, so we wanted to write an accessible introduction. 

# APA-style manuscripts with RMarkdown and papaja demonstration 

For our Methods and Metascience group at the University of Glasgow, I delivered a talk on using papaja ([Aust & Barth, 2022](https://github.com/crsh/papaja)) to create reproducible APA-style manuscripts. When you download the template, it is easy to see how you complete the YAML, but as a template, the bulk of the manuscript is blank. Therefore, I created a mock example using just a few packages to show how you can use it for your own study. You can access the talk slides and mock example files [here on my Github repo](https://github.com/BartlettJE/papaja_demo).   

# OSF preregistration R Markdown template

When I preregister a study, my favourite template to use was the OSF preregistration challenge. Now that the challenge has finished, the COS have created an updated template. When you select a template on the OSF, there is the option to include an R script to demonstrate something like a power analysis or planned analysis. I thought it would be a good idea to streamline this process and combine the preregistration template with the power of R.

I created a .Rmd file with the OSF preregistration template headers and information. Now you can write your preregistration using R Markdown and provide any code and output directly, making it fully reproducible. You can download the template here on my [Github page](https://github.com/BartlettJE/BartlettJE.github.io/blob/master/RMarkdown-scripts/OSF%20preregistration%20template.Rmd).

For an example of how it can be used, you can find the preregistration for one of my studies on the OSF. The final knitted version of the document is available as a [PDF](https://osf.io/hjk5u/) for easy reading, and the [.Rmd file](https://osf.io/fqs6j/) is available for reproducibility. You can also find a [YouTube](https://youtu.be/VdhtdsKtac0) video of a workshop I presented demonstrating how you can use the template for preregistration.

# Creating Experiments Using OpenSesame Guide

I wrote a guide on how to create cognitive tasks in OpenSesame. It is aimed at absolute beginners and includes minimal code. There are currently three tasks included: the Stroop task, Eriksen Flanker task, and a Go NoGo task with images. The guide and images for the third task are available on my [OSF](https://osf.io/tm3z2/) project page for cognitive tasks.

## Cognitive task scripts using OpenSesame and PsychoPy

I built several experiments using OpenSesame and PsychoPy for my PhD and for undergraduates to use in their dissertations. You may find it useful to adapt one of the cognitive tasks I have built for your own research. You can download them from the [OSF](https://osf.io/awjcn/).  

The current list of available tasks is:
- Go-NoGo Task (OpenSesame)
- Eriksen Flanker Task (OpenSesame)
- Dot Probe Task (OpenSesame and PsychoPy)
- Anti-Saccade Task (PsychoPy)

# Introduction to JASP guide

I wrote a guide to transition students from using SPSS to JASP. You can access both the [guide](https://osf.io/p2hzg/) and the [data sets](https://osf.io/7x8hj/) I used for the examples on the Open Science Framework. The sourcing of the data sets are credited to Kevin McIntyre who made them available on the [Open Stats Lab](https://sites.trinity.edu/osl).

The guide currently covers the following topics:
- How to navigate around JASP
- Getting basic descriptive statistics and plots
- Assessing parametric assumptions
- Conducting independent and paired samples T-Tests
- Calculating the correlation between two variables
- One-way repeated measures and independent samples ANOVA
- Bayesian paired samples T-Test
