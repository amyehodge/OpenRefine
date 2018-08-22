---
layout: lesson
root: .
title: Examining Numbers in Open Refine
minutes: .
---

# Learning Objectives

* Transform a text column in to a number column.
* Identify and modify non-numeric values in a column using facets.

----------------------------------------------------

# Lesson

## Numbers

When a table is imported into Open Refine, all columns are treated as having text values. We saw earlier how we can sort interpreting column values as numbers, but this did not change the cells in a column from text to numbers.

Be sure to remove an **Text filter** facets from the left margin so that we can examine the whole rodent dataset.

To transform cells in the `recordID` column to numbers, use the column pulldown to **> Edit cells > Common transforms… > To number**. You will notice the `recordID` values change from left-justified to right-justified, and black to green color.

> ## Challenge
>
> Transform three more columns, including **period**, from text to numbers.

### Numeric facet
Sometimes there are non-number values or blanks in a column and we want to find them. We can do that with a **Numeric facet**.

> ## Challenge
>
> For a column you transformed to numbers, edit one or two cells, replacing the numbers with text (such as `abc`) or blank (no number or text).
> Use the pulldown to **> Facet > Numeric facet**, which will add a facet to the left margin.
> Notice that there are several checkboxes in this facet: **Numeric**, **Non-numeric**, **Blank**, **Error**. Below these are counts of the number of cells. You should see checks for **Non-numeric** and **Blank** if you changed some values.
> Experiment with checking or unchecking these boxes to select subsets of your data.

When done examining the numeric data, remove this facet by clicking the **x** in the upper left corner of its panel.

Previous: [Filtering, Excluding and Sorting](02-filter-exclude-sort.html)  Next: [Scripts from OpenRefine](04-scripts.html)
