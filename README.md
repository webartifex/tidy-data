# Tidy Data

The purpose of this repository is to illustrate how the data cleaning process described
    in the paper "[Tidy Data](tidy-data.pdf)" by Hadley Wickham, a member of the
    [RStudio](https://rstudio.com/) team, can be done in
    [Python](https://www.python.org/).

The paper was published in 2014 in the [Journal of Statistical Software](https://www.jstatsoft.org/article/view/v059i10).
The author offers it for free [here](http://vita.had.co.nz/papers/tidy-data.html).
Furthermore, the original [R](https://www.r-project.org/) code is available [here](https://github.com/hadley/tidy-data).

After installing the dependencies for this project (cf., the [installation notes](https://github.com/webartifex/tidy-data#installation)
    below), it is recommended to first read the paper to get the big picture and
    then work through the six Jupyter notebooks listed below.


## Summary


### Definition

**Tidy** data is defined as data that comes in a table form adhering to the
    following requirements:
1. each variable is a column,
2. each observation a row, and
3. each type of observational unit forms a table.

This is equivalent to [Codd's 3rd normal form](https://en.wikipedia.org/wiki/Third_normal_form),
    a concept from the theory on relational databases.
A dataset that does *not* satisfy these properties is called **messy**.


### Tidying Data

The five most common problems with messy data are:

- column headers are values, not variable names
  (cf., [notebook 1](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/1_column_headers_are_values.ipynb))
- multiple variables are stored in one column
  (cf., [notebook 2](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/2_multiple_variables_stored_in_one_column.ipynb))
- variables are stored in both rows and columns
  (cf., [notebook 3](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/3_variables_are_stored_in_both_rows_and_columns.ipynb))
- multiple types of observational units are stored in the same table
  (cf., [notebook 4](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/4_multiple_types_in_one_table.ipynb))
- a single observational unit is stored in multiple tables
  (cf., [notebook 5](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/5_one_type_in_multiple_tables.ipynb))


### Case Study

A case study (cf., [notebook 6](https://nbviewer.jupyter.org/github/webartifex/tidy-data/blob/master/6_case_study.ipynb))
    shows the advantages of tidy data as a standardized input to statistical functions.


## Installation

Get a local copy of this repository with [git](https://git-scm.com/).

`git clone https://github.com/webartifex/tidy-data.git`

If you are not familiar with [git](https://git-scm.com/), simply download the latest
    version of the files in a zip archive [here](https://github.com/webartifex/tidy-data/archive/master.zip).

This project uses [poetry](https://python-poetry.org/docs/) to manage its dependencies.
Install all third-party packages into a [virtual environment](https://docs.python.org/3/library/venv.html).

`poetry install`

Alternatively, use the [Anaconda Distribution](https://www.anaconda.com/products/individual)
    that *should* also suffice to run the provided notebooks.
