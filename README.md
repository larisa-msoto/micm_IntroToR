# Introduction to programming in R

## Overview



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

### R basics
#### Syntax
#### Aritmetic Operations
#### Creating variables
#### Logical operators
#### Seeking help
#### Installing packages

### Data types: attributes and built-in functions
#### Vectors
#### Lists
#### Factors
#### Data frames
#### Arrays
#### Coercion
#### Hands-on: data types 

### Basic data manipulation
#### Reading/writing data
#### Exploring data frames
#### Hands-on: basic data manipulation

### Advanced data manipulation
#### Handling data frames with dplyr and tidyr
#### Other useful packages
#### Hands-on: advanced data manipulation 

### Generating visual outputs
#### Graphics with base R and `ggplot2`
#### Reports with RMarkdown
#### Hands-on: Graphics wth `ggplot2`

### Control structures and functions
#### Creating your own function
#### `if` Statement
#### `for` loop

### Activity: Analyze data from a clinical trial

### Software development concepts
#### Good coding practices

## References

The materials for this workshop were based on the following sources:

[Base R Cheat Sheet](https://iqss.github.io/dss-workshops/R/Rintro/base-r-cheat-sheet.pdf) 
[Google's R Style Guide](https://google.github.io/styleguide/Rguide.html) 
[Mastering Software Development in R](https://bookdown.org/rdpeng/RProgDA/) 


   
*Workshop created as part of the McGill Initiative in Computational Medicine*
