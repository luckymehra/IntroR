# Introduction to R
<!--
---
title: "Introduction to R"
---
-->


An introduction to R for plant pathologists originally written by Drs. Sydney E. Everhart
and Zhian N. Kamvar

This repository is intended to serve as an additional resource for the short 
workshop to be given at Kansas State Univeristy in summer of 2019. The source code can be found at 
https://github.com/luckymehra/IntroR.

## About 

This introduction to R is designed to be a companion to a workshop lasting 4 
hours introducing plant pathologists to the basics of R by using a 
[real world stripe rust example]. 

## Goals

As a result of taking this workshop you should be able to:

 - find, download, and load necessary packages for analysis
 - load tabular data into R
 - understand the basics of data manipulation in R
 - know what a data frame, vector, and function are
 - summarize data
 - visualize data
 - troubleshoot commmon problems

[real world stripe rust example]: http://www.apsnet.org/edcenter/advanced/topics/EcologyAndEpidemiologyInR/DiseaseProgress/Pages/StripeRust.aspx "APS Education Center: Using the area under the disease progress curve to compare disease severity"

## Website

This website is meant to serve as a companion to the workshop. The pages located
in the **Workshop** tab are rendered versions of R scripts located in the top 
level of https://github.com/luckymehra/IntroR. As the workshop is designed to
be interactive where the participants are given some control over what direction
we should take the analyses, the scripts here are only to serve as guidelines.

These scripts follow these conventions:

 - R code is presented how it would appear in the R console with the first line
   prefixed with `>` and subsequent lines prefixed with `+`. The intent is to
   encourage the user to type the commands instead of copy and paste.
 - There will be instances where the command is a `stop()` command. These are
   points in the workshop where we stop the participants and ask them to talk 
   amongst themselves, take a short survey, or find information using R's help
   function.



The website located at http://luckymehra.github.io/IntroR can be build via the
`make` program:

```make
make clean # run this to build the site from scratch
make
```

Note: if the README.md is changed, make will force-update the index.Rmd and in
turn force update the corresponding HTML.
