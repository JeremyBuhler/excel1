---
layout: default
title: Exploring your data
nav_order: 3
---

## Exploring your data

###Purpose
- understand the content, structure, extent, and type of data
- format the data to optimize analysis
- ensure data is represented correctly in Excel


###Does your data look right?

Before analysis it's important to make sure Excel is interpreting your data correctly. Do dates make sense? Are numbers treated like numbers or like text? How are responses to "choose all that apply" questions represented? Are there as many rows as you expected? Is there anything you need to filter out?

Click into each column and check the dropdown options in the *Home -> Numbers* section of the ribbon to make sure the right data type is selected. (The default in Excel is usually *General*.)

###Formatting as a table
Formatting your data **as a table** makes it easier to explore, filter, and identify anomalies. Before doing so, ensure your data has only one header row:

- Use `CONCATENATE()` formula, if necessary, to include all desired information in a new header row
- Copy new header and paste onto itself  *as values* to make sure formulas don't break
- Delete all redundant or unecessary header rows, leaving one only
- Select *Home -> Format as Table*

Once your data is formatted as a table use the arrows in the header to browse/filter the contents.


###By the end of this section...

- only one header row in working copy of your data
- unnecessary columns deleted or hidden (optional)
- data formatted as a table 
- filtered unwanted responses

 