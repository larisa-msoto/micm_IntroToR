# Introduction to programming in R

## Overview

This workshop is beginner-level introduction to programming in R. The course is designed to be taught in two sessions of 3 hours each and is focused on the application of R to the analyzis of tabular data from clinical trials. 

## Requirements

No previous programming experience is required. Having a plain text editor installed is recommended.
   
## Sofware

* [R >4.0](https://www.r-project.org)
* [RStudio](https://www.rstudio.com/products/rstudio/download/)

Once you have setup R and RStudio copy the code below to install the packages required for the workshop.

```{r}
install.packages(c("data.table","datasets","devtools","dplyr","ggplot2","ggthemes","grid","gridExtra","knitr","magrittr","plotly","plyr", "purrr", "RColorBrewer", "readr","rmarkdown","stringr","tidyr","tidyverse","tigris","viridis"))
```

## Workshop Outline

### 1. R basics

**Learning objectives:**

- Familiarize with the language and the logic behind it
- Create a project in R studio 
- Configure the working directory
- Create your first R script 
- Get fluent in R using the console
- Compute arithmetic operations
- Use logical operators on variables
- Learn how to ask for help 
- Get comfortable installing packages

**Module content:**

a) Syntax
b) Aritmetic Operations
c) Creating variables
d) Logical operators
e) Seeking help
f) Installing packages
g) Hands on: basics

### 2. Data types: attributes and built-in functions

**Learning objectives:**

- Understand the differences between classes, objects and data types in R
- Create objects of different types
- Subset and index objects 
- Learn and apply vectorized operations

**Module content:**

a) Vectors
b) Lists
c) Factors
d) Data frames
e) Arrays
f) Coercion
g) Hands-on: data types 

### 3. Basic data manipulation

**Learning objectives:**

- Learn how to read/write data to/from files with different formats (.tsv, .csv)
- Familiarize with basic operations of data frames 
- Index and subset data frames using base R functions
- Manipulate specific data frame columns
- Join data frames by columns and rows 

**Module content:**

a) Reading/writing data
b) Exploring data frames
c) Hands-on: basic data manipulation

### 4. Advanced data manipulation

**Learning objectives:**

- Familiarize with the dplyr syntax
- Create pipes with the operator `%>%`
- Perform operations on data frames using dplyr and tidyr functions
- Implement functions from external packages by reading their documentation in R

**Module content:**

a) Handling data frames with dplyr and tidyr
b) Other useful packages
c) Hands-on: advanced data manipulation 

### 5. Generating visual outputs

**Learning objectives**

- Create basic plots using base R functions
- Understand the connection between data frames and ggplot2
- Create basic graphs with ggplot2
- Use factors to customize graphics in ggplot2
- Learn about RMarkdown syntax to create reports 
- Get familiar with existing RMarkdown templates

**Module content:**

1) Graphics with base R and `ggplot2`
2) Reports with RMarkdown
3) Hands-on: Graphics wth `ggplot2`

### 6. Control structures and functions

**Learning objectives:**

- Understand the concept of environments in R
- Create new functions
- Implement conditional statements 
- Implement a for loop to iterate over a list of files

**Module content:**

1) Creating your own function
2) `if` Statement
3) `for` loop

### 7. Activity: Analyze data from a clinical trial

**Learning objectives:**

- Familiarize with a real-life use of R in the pharma industry environment
- Apply the knowledge from previous modules to create an analysis pipeline


### 8. Software development concepts

**Learning objectives:**

- Develop  good coding practices
- Familiarize with documentation standards 
- Know what to avoid when programming in R

**Module content:**

1) Good coding practices
2) Style guide 

## References

The materials for this workshop were based on the following sources:

[Base R Cheat Sheet](https://iqss.github.io/dss-workshops/R/Rintro/base-r-cheat-sheet.pdf) 
[Google's R Style Guide](https://google.github.io/styleguide/Rguide.html) 
[Mastering Software Development in R](https://bookdown.org/rdpeng/RProgDA/) 


   
*Workshop created as part of the McGill Initiative in Computational Medicine*
