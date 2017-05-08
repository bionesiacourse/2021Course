---
title: "VWC 2017 Bioinformatics Workshop"
output: 
  html_document:
    toc: yes
    toc_depth: 2
---

## General Information

This workshop introduces methods, tools, and software for reproducibly managing, manipulating, analyzing, and visualizing large-scale biomedical data using the R statistical computing environment.

**_IMPORTANT_: [Click here for instructions on setting up your computer for any of these workshops](setup.html).** Each workshop involves lots of hands-on practice coding, and you'll need to download and install some free software **_prior to our first class_**. This may take up to an hour or so, and please do not hesitate to [email us](people.html) _prior to the workshop_ if you are having difficulty.

**When:**  
May 22-23, 2017  
9:00am - 5:00pm

**Where:** BioConnector Classroom, 1212 Health Sciences Library (_downstairs one floor, to the right_)

**Instructor: Stephen Turner.** Stephen Turner, Ph.D. is faculty in the Department of Public Health Sciences, and director of the [Bioinformatics Core](http://bioinformatics.virginia.edu) at the UVA School of Medicine.

- Email: <a href="http://www.google.com/recaptcha/mailhide/d?k=01Wp6BFjxhU6BE1ONDOeDAZg==&amp;c=hClvy-RObaqm8ONK69PMtLKUh74mVHLjokUJXLgkUHk=" onclick="window.open('http://www.google.com/recaptcha/mailhide/d?k\07501Wp6BFjxhU6BE1ONDOeDAZg\75\75\46c\75hClvy-RObaqm8ONK69PMtLKUh74mVHLjokUJXLgkUHk\075', '', 'toolbar=0,scrollbars=0,location=0,statusbar=0,menubar=0,resizable=0,width=500,height=300'); return false;" title="Reveal this e-mail address">s...</a>@virginia.edu
- Web: [stephenturner.us](http://stephenturner.us)
- Twitter: <a href="https://twitter.com/genetics_blog">@genetics_blog</a>
- Blog: [gettinggeneticsdone.com](http://www.gettinggeneticsdone.com/)
- GitHub: [github.com/stephenturner](https://github.com/stephenturner/)


## Course Schedule

### Session 1: Intro to R

This novice-level introduction is directed toward life scientists with little to no experience with statistical computing or bioinformatics. This interactive introduction will introduce the R statistical computing environment. The first part of this workshop will demonstrate very basic functionality in R, including functions, functions, vectors, creating variables, getting help, filtering, data frames, plotting, and reading/writing files.

### Session 2: Advanced Data Manipulation with R

Data analysis involves a large amount of janitor work -- munging and cleaning data to facilitate downstream data analysis. This session assumes a basic familiarity with R and covers tools and techniques for advanced data manipulation. It will cover data cleaning and "tidy data," and will introduce R packages that enable data manipulation, analysis, and visualization using split-apply-combine strategies. Upon completing this lesson, students will be able to use the _dplyr_ package in R to effectively manipulate and conditionally compute summary statistics over subsets of a "big" dataset containing many observations.

### Session 3: Advanced Data Visualization with R and ggplot2

This session will cover fundamental concepts for creating effective data visualization and will introduce tools and techniques for visualizing large, high-dimensional data using R. We will review fundamental concepts for visually displaying quantitative information, such as using series of small multiples, avoiding "chart-junk," and maximizing the data-ink ratio. After briefly covering data visualization using base R graphics, we will introduce the _ggplot2_ package for advanced high-dimensional visualization. We will cover the grammar of graphics (geoms, aesthetics, stats, and faceting), and using ggplot2 to create plots layer-by-layer. Upon completing this lesson, students will be able to use R to explore a high-dimensional dataset by faceting and scaling arbitrarily complex plots in small multiples.

### Session 4: Introduction to RNA-seq Data Analysis

This session focuses on analyzing real data from a biological application - analyzing RNA-seq data for differentially expressed genes. This session provides an introduction to RNA-seq data analysis, involving reading in count data from an RNA-seq experiment, exploring the data using base R functions and then analysis with the DESeq2 Bioconductor package. The session will conclude with downstream pathway analysis and exploring the biological and functional context of the results.

## Optional sessions

### Elective 1: Reproducible Research & Dynamic Documents

Contemporary life sciences research is plagued by reproducibility issues. This session covers some of the barriers to reproducible research and how to start to address some of those problems during the data management and analysis phases of the research life cycle. In this session we will cover using R and dynamic document generation with RMarkdown and RStudio to weave together reporting text with executable R code to automatically generate reports in the form of PDF, Word, or HTML documents.

### Elective 2: Essential Statistics

This session will provide hands-on instruction and exercises covering basic statistical analysis in R. This will cover descriptive statistics, t-tests, linear models, chi-square, clustering, dimensionality reduction, and resampling strategies. We will also cover methods for "tidying" model results for downstream visualization and summarization.

## Software requirements

All the software we're using in class is open-source and freely available online. This setup must be completed _prior to class_, as we will not have time for troubleshooting software installation issues during class. See the [setup instructions](setup.html), and follow all instructions under the major headings for:

- [R](setup.html#r)
- [R+RStudio+Packages](setup.html#r+rstudio+packages)
- [Bioconductor](setup.html#bioconductor)
- [RMarkdown](setup.html#rmarkdown)
- [RNA-seq](setup.html#rna-seq)
- [Getting data](setup.html#get_data)

You'll need to download _all_ the data. As [described in the setup page](setup.html#get_data), navigate to the [data page](data.html) and download _all_ the relevant datasets, saving them to a folder that's easy to find.


## FAQ

### What's this workshop all about? 

This workshop introduces methods, tools, and software for reproducibly managing, manipulating, analyzing, and visualizing large-scale biomedical data. Specifically, the course introduces the R statistical computing environment and packages for manipulating and visualizing high-dimensional data, covers strategies for reproducible research, essential statistics and survival analysis, and culminates with analysis of data from a real RNA-seq experiment using R and Bioconductor packages.

### What are the pre-requisites?

_There are none!_ This class doesn't assume any knowledge of programming or using a command-line interface, but if you've ever had any experience here, the content won't come as so much of a shock. But _don't panic._ Command-line interfaces and programming languages like R are _incredibly powerful_ and will be utterly transformative on your research. There's a learning curve, and it's near-vertical in the beginning, but it's surmountable and the payoff is worth it! **_This is not a statistics class_** -- some general knowledge of statistics and study design is helpful, but isn't strictly required. If time allows, there is an [optional session on statistics](r-stats.html) that we can cover.

### Where do I get additional help?

Glad you asked! [See here](help.html).

### Do I need a laptop?

**YES.** You must have access to a computer on which you can install software. The class will be a mix of lecture, discussion, but primarily live coding. You must bring your laptop to each session. Bring your charging cable also.



----

<small>**_Attribution_:** Course material is inspired by and/or modified in part from [Jenny Bryan's Stat 545 course](http://stat545-ubc.github.io/), [Software Carpentry](http://software-carpentry.org/), [Data Carpentry](http://datacarpentry.org/), [David Robinson's blog](http://varianceexplained.org/), [Marian Schmidt's MSU NGS Workshop](https://github.com/marschmi/NGS2015_RMarkdown_Reproducibility), [Vanderbilt Department of BioStatistics Datasets](http://biostat.mc.vanderbilt.edu/wiki/Main/DataSets?CGISESSID=10713f6d891653ddcbb7ddbdd9cffb79), and likely many others.</small>