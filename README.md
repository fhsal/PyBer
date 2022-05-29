# PyBer Ride Sharing Analysis

CWRU Data Analytics Module Five Challenge


## Overview of Project

The project involved loading data into panda data frames, merging grouping and visualizing data and capabilities such as loc, formatting, pivot, resample and matplotlib.  

### Purpose

The purpose of the challenge was to gain insight into trends and factors by aggregate and summarize the data for ride fares and counts by city type and date along dimensions such as total fares, fares by type of city and fares per driver.  

## Analysis 

The analysis had several components:

(1) loading the csv files into dataframes and merging them together;  and

(2) building the basic sums and averages for things such as total fares and rides, and per-unit stats such as average fare per city type and driver; then combining them into an overall summary dataframe and formatting it; and 

(3) creating a dataframe grouped by both date and city type and using it as a basis from which to create a pivot df with an index of date, columns by city type and fares sum as values; 

(4) resampling the pivot dataframe, by week, and using this df to drive a line-graph visualization of the ride fares by city type over time


## Summary

Removing the Thomas High School 9th grader scores causes the averages for Math, Reading and Overall to fall slightly.  It also lowers the same set of stats for the budget and population range aggregations - where Thomas High School meets the grouping criteria (school type, school size and budget range). 

### Specific metrics impact 

The several school district metrics impacted by removing the Thomas High School students from the data and analysis are summarized below.  Note that the dark VS Code images are "before" and the lighter Jypyter Notebook images are "after" in the bulleted items shown here.  

- The average test scores were lowered for both Math and Reading 

**Before:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/before_Avg_scores.png)

**after:**  

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/after_Avg_scores.png)


-The percent passing scores were lowered for Math, Reading and Overall

**Before:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/before_passing_percent.png)

**After:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/after_passing_percent.png)


- The Spending Ranges Per Student roll-ups were impacted where Thomas High School is represented in the $631-645 grouping

**Before:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/before_spending.png)

**After:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/after_spending.png)

- The Size Ranges  roll-ups were impacted where Thomas High School is represented in the medium grouping

**Before:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/before_size.png)

**After:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/after_size.png)

- The school type roll-ups were impacted where Thomas High School is represented in charter grouping

**Before:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/before_type.png)

**After:**

![img](https://github.com/fhsal/PyCity_Schools/blob/main/Images/after_type.png)
