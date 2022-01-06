# Applied Analytics Overview

**Analytics** is the systematic computational analysis of data or statistics.


::: {.rmdnote}

It is used for the discovery, interpretation, and communication of meaningful patterns in data. It also entails applying data patterns towards effective decision-making. 

:::

It can be valuable in areas rich with recorded information; analytics relies on the simultaneous application of statistics, computer programming and operations research to quantify performance.

Organizations may apply analytics to business data to describe, predict, and improve business performance. 

Specifically, areas within analytics include predictive analytics, prescriptive analytics, enterprise decision management, descriptive analytics, cognitive analytics, Big Data Analytics, retail analytics, supply chain analytics, store assortment and stock-keeping unit optimization, marketing optimization and marketing mix modeling, web analytics, call analytics, speech analytics, sales force sizing and optimization, price and promotion modeling, predictive science, graph analytics, credit risk analysis, and fraud analytics. 

Since analytics can require extensive computation (think: big data), the algorithms and software used for analytics harness the most current methods in computer science, statistics, and mathematics.

##  Feel good about Analytics 1?

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

b)	3 Data visualisation
c)	4 Workflow: basics
d)	5 Data transformation
e)	6 Workflow: scripts
f)	7 Exploratory Data Analysis
g)	8 Workflow: projects


## Wrangle

a)	9 Introduction
b)	10 Tibbles
c)	11 Data import
d)	12 Tidy data
e)	13 Relational data
f)	14 Strings
g)	15 Factors
h)	16 Dates and times

##	Program

a)	17 Introduction
b)	18 Pipes
c)	19 Functions
d)	20 Vectors
e)	21 Iteration

##	Model

a)	22 Introduction
b)	23 Model basics
c)	24 Model building
d)	25 Many models

##	Communicate

a)	26 Introduction
b)	27 R Markdown
c)	28 Graphics for communication
d)	29 R Markdown formats
e)	30 R Markdown workflow



## Learning goals {.build}

By the end of the course, you will be able to...

- gain insight from data
- gain insight from data, **reproducibly**
- gain insight from data, reproducibly, **using modern programming tools and techniques**
- gain insight from data, reproducibly **and collaboratively**, using modern programming tools and techniques
- gain insight from data, reproducibly **(with literate programming and version control)** and collaboratively, using modern programming tools and techniques

# Reproducible data analysis

---

## Reproducibility checklist

### Near-term goals:

- Are the tables and figures reproducible from the code and data?
- Does the code actually do what you think it does?
- In addition to what was done, is it clear *why* it was done? 

### Long-term goals:

- Can the code be used for other data?
- Can you extend the code to do other things?


## For next class

* Flip (or tab!) through R4DS and be able to answer (I **WILL** call on you next class) broadly-speaking what each chapter of the book covers
* Pay particular attention to the visualization chapter and be able to answer (I **WILL** call on you next class) what these terms refer to:
  +    mapping
  +    data
  +    geom
  +    stat
  +    position
    
## ggplot2 components

## Quiz Next Class
* Quiz: explain:
  +    mapping
  +    data
  +    geom
  +    stat
  +    position
  
[link](https://rpubs.com/hadley/ggplot2-layers)

##    mapping

A set of aesthetic mappings, specified using the aes() function and combined with the plot defaults as described in aesthetic mappings. If NULL, uses the default mapping set in ggplot().

##    data

A dataset which overrides the default plot dataset. It is usually omitted (set to NULL), in which case the layer will use the default data specified in ggplot(). The requirements for data are explained in more detail in data.

##     Geoms

The name of the geometric object to use to draw each observation. Geoms are discussed in more detail in geom, and the toolbox explores their use in more depth.

##    Geoms 

can have additional arguments. All geoms take aesthetics as parameters. If you supply an aesthetic (e.g. colour) as a parameter, it will not be scaled, allowing you to control the appearance of the plot, as described in setting vs. mapping. You can pass params in ... (in which case stat and geom parameters are automatically teased apart), or in a list passed to geom_params.

##    stat 

The name of the statistical tranformation to use. A statistical transformation performs some useful statistical summary is key to histograms and smoothes. To keep the data as is, use the “identity” stat. Learn more in statistical transformations.

You only need to set one of stat and geom: every geom has a default stat, and every stat a default geom.

Most stats take additional parameters to specify the details of statistical transformation. You can supply params either in ... (in which case stat and geom parameters are automatically teased apart), or in a list called stat_params.

##    position

The method used to adjusting overlapping objects, like jittering, stacking or dodging. More details in position.

