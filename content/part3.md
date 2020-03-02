---
layout: default
title: Formulas for data analysis
nav_order: 4
---

## Formulas for data analysis

### Purpose
- introduce formulas for data manipulation
- introduce formulas for analysis

### Selected formulas

 Below are the formulas used in the lesson. Examples of these formulas in use are readily available online:
 
 - `CONCATENATE()`
 - `COUNTIF()`
 - `SUM()`
 - `AVERAGE()`
 - `STDEV.S()`

### Optional - recoding values

During the lesson Ève had a question about recoding values (e.g. replacing text responses with numerical values).
If the number of possible values is small it may be simplest to make a copy of the column and use *find/replace*. For more complex datasets there are several ways to accomplish this with formulas. 

One formula-based approach uses a combination of `INDEX` and `MATCH`.  You'll need to create a lookup table that includes all possible values for your variable in one column, and the corresponding numerical values in the other. This [Index and Match tutorial](https://www.excel-easy.com/examples/index-match.html) provides syntax and examples that illustrates how the formulas can work together to recode values.  

The `INDEX` and `MATCH` combination is useful whenever you're linking data from two tables using a key that appears in both.

### By the end of this section...

- a new variable/column for "website dissatisfaction score"
- use formulas to calculate counts, sums, means, and standard deviation

