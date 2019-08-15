Homework 1
================
Dr. Michele Weigle

CS 625, Fall 2019

## Setting up your report

The first thing to do is put in your name in the

    author: "Dr. Michele Weigle"

line at the top of this file. You’ll do this for every report that you
submit.

*Remove this section before submitting your report*

## Setting up R

The command below will load the tidyverse package. If you have installed
R, RStudio, and the tidyverse package, it should display a list of
loaded packages and their
    versions.

``` r
library(tidyverse)
```

    ## ── Attaching packages ───────────────────────────────────────────────────────────────── tidyverse 1.2.1 ──

    ## ✔ ggplot2 3.2.0     ✔ purrr   0.3.2
    ## ✔ tibble  2.1.3     ✔ dplyr   0.8.3
    ## ✔ tidyr   0.8.3     ✔ stringr 1.4.0
    ## ✔ readr   1.3.1     ✔ forcats 0.4.0

    ## ── Conflicts ──────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

## R Markdown

1.  *Create an ordered bulleted list with at least 3 items*

2.  *Write a paragraph that demonstrates the use of italics, bold, bold
    italics, and code.*

3.  *Create an example of a fenced code block.*

4.  *Create a level 4 heading*

## R

#### Data Visualization Exercises

1.  *Run ggplot(data = mpg). What do you see?*

2.  *How many rows are in mpg? How many columns?*

3.  *What does the drv variable describe? Read the help for ?mpg to find
    out.*

4.  *Make a scatterplot of hwy vs cyl.*

5.  *What happens if you make a scatterplot of class vs drv? Why is the
    plot not useful?*

#### Workflow: basics Exercises

1.  *Why does this code not work?*

<!-- end list -->

``` r
my_variable <- 10
my_varıable
```

2.  *Tweak each of the following R commands so that they run correctly:*

<!-- end list -->

``` r
library(tidyverse)

ggplot(data = mpg) + 
  geom_point(mapping = aes(x = displ, y = hwy))

fliter(mpg, cyl = 8)
filter(diamond, carat > 3)
```

3.  *Press Alt + Shift + K. What happens? How can you get to the same
    place using the menus?*

## Tableau

*Insert your the image of your final bar chart here*

1.  *What conclusions can you draw from the chart?*

## Observable and Vega-Lite

#### Intro to Observable notebook

*Insert the URL to your Observable notebook here*

1.  *What changes did you make to the notebook?*

2.  *What happens when you select a range of items in the scatterplot at
    the end of the notebook?*

#### Intro to Vega-Lite notebook

*Insert the URL to your Vega-Lite Observable notebook here*

1.  *What changes did you make to the notebook?*

*Insert your saved chart image here*

## References

*Insert the list of sites you used as references as an unordered list
with named links here. This is required.*

***Make sure that you Knit your R Markdown into a GitHub-readable
Markdown file that is synced with your GitHub repo.***
