# Data Analytics Case Study
This is Data in Motion data analysis challenge #1.
This case study was finished using R package tidyverse. Steps are:
1. Install package tidyverse.
   
         # an argument is added to the function that gives it the web address of the repository. Once the data file is downloaded into the proper directory you will then be able to access your newly installed package.
        install.packages("tidyverse", repos = "http://cran.us.r-project.org") 
2. In the code import tidyverse, ggplot2 and dplyr library
   
       library(tidyverse)
       library(ggplot2) # for ploting figure
       library(dplyr) # for sorting
3. Load Data. Save the dataset into local file directory. change working directory to where the file is. load the data into dataframe chipotle_sales.

       setwd("C:/Users/liuch/OneDrive/文档/DataAnalytics/Portfolio/case_study_1")
       chipotle_sales <- read_tsv("chipotle.tsv")
4. Take a glimpse after the data was loaded

       glimpse(chipotle_sales)
5. Start analyze data. Check the final report for analyze report.
