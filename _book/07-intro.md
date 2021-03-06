# Applied Analytics Overview

**Analytics** is the systematic computational analysis of data or statistics.


::: {.rmdimportant}

It is used for the discovery, interpretation, and communication of meaningful patterns in data. It also entails applying data patterns towards effective decision-making. 

:::

It can be valuable in areas rich with recorded information; analytics relies on the simultaneous application of statistics, computer programming and operations research to quantify performance.

Organizations may apply analytics to business data to describe, predict, and improve business performance. 

Specifically, areas within analytics include predictive analytics, prescriptive analytics, enterprise decision management, descriptive analytics, cognitive analytics, Big Data Analytics, retail analytics, supply chain analytics, store assortment and stock-keeping unit optimization, marketing optimization and marketing mix modeling, web analytics, call analytics, speech analytics, sales force sizing and optimization, price and promotion modeling, predictive science, graph analytics, credit risk analysis, and fraud analytics. 

Since analytics can require extensive computation (think: big data), the algorithms and software used for analytics harness the most current methods in computer science, statistics, and mathematics.

::: {.rmdimportant}

Do you recall the Target pregnancy story?  Can you extrapolate this to real life?

:::

# Analytics 1 -- Feel Good About It?

- R basics
- Data wrangling
- Modeling (lm, glm, etc.)
    + lm
    + glm
    + test & training data
    + measures of fit, confusion matrix
    

## Learning goals

> By the end of the course, you will be able to...

::: {.rmdnote}

[Data Science Model](https://d33wubrfki0l68.cloudfront.net/571b056757d68e6df81a3e3853f54d3c76ad6efc/32d37/diagrams/data-science.png)

:::

## Toolkit for reproducibility 

- Scriptability →  R
- Literate programming (code, narrative, output in one place) →  R Markdown
- Version control →  Git / GitHub

## Resources We'll Use (R4DS, mostly)

1)	Explore
2)	Wrangle
3)	Program
4)	Model
5)	Communicate

## Explore

3) Data visualisation
4) Workflow: basics
5) Data transformation
6) Workflow: scripts
7) Exploratory Data Analysis
8) Workflow: projects


## Wrangle

9) Introduction
10) Tibbles
11) Data import
12) Tidy data
13) Relational data
14) Strings
15) Factors
16) Dates and times

##	Program

17) Introduction
18) Pipes
19) Functions
20) Vectors
21) Iteration

##	Model

22) Introduction
23) Model basics
24) Model building
25) Many models

##	Communicate

26) Introduction
27) R Markdown
28) Graphics for communication
29) R Markdown formats
30) R Markdown workflow


# Assignment 1

Let's make sure we feel good about BADM 371 material.  

All open notes/internet/R4DS/etc., **but all work must be your own**.

::: {.rmdimportant}

Use the starwars data (dplyr package) to answer/do:

1. Who is the tallest individual?  Shortest?
2. How many homeworlds are there?
3. Which homeworld has the most individuals?  Fewest?  Average # of idividuals per homeworld?
4. Make a plot of all individuals with mass on the x axis and height on the y axis.
5. Put a best fit line on this plot.
6. Who is the biggest outlier in this dataset?
7. Calculate BMI for all these individuals.  What is the average BMI for all individuals?
8. What is the average BMI for each homeworld?
9. Which homeworlds have the greatest percentage of individuals with BMI's greater than the average you found in #8 above?
10. How many individuals have no missing data?  Which variables have the most missing data?

:::
