# Tidy Data

The purpose of this repository is to re-do the work described in the paper
[Tidy Data](tidy-data.pdf) by Hadley Wickham (member of the RStudio team) in
Python.

The paper was published in 2014 in the Journal of
[Statistical Software](https://www.jstatsoft.org/article/view/v059i10). The
author offers it for free download
[here](http://vita.had.co.nz/papers/tidy-data.html). Furthermore, the original
R code is available in a Github
[repository](https://github.com/hadley/tidy-data)

After installing this project, it is recommended to first read the paper to get
the big picture and then work through the six Jupyter notebooks (listed further
below).

See installation notes at the bottom.

## Summary


### Definition

**Tidy** data is defined as data that comes in a table form adhering to the
following requirements:

1. Each variable forms a column.
2. Each observation forms a row.
3. Each type of observational unit forms a table.

This is equivalent to Codd's 3rd normal form (in the context of relational
databases). A dataset that does not satisfy these properties is called
**messy**.


### Tidying messy Data

The five most common problems with messy data are as follows:

- Column headers are values, not variable names
[[notebook](1_column_headers_are_values.ipynb)]
- Multiple variables are stored in one column
[[notebook](2_multiple_variables_stored_in_one_column.ipynb)]
- Variables are stored in both rows and columns
[[notebook](3_variables_are_stored_in_both_rows_and_columns.ipynb)]
- Multiple types of observational units are stored in the same table
[[notebook](4_multiple_types_in_one_table.ipynb)]
- A single observational unit is stored in multiple tables
[[notebook](5_one_type_in_multiple_tables.ipynb)]

Further, a [case study](6_case_study.ipynb) shows the advantages of tidy data
(as standardized input/output to statistical functions).

## Download & Installation

Create a local copy of this repository with:

`git clone https://github.com/webartifex/tidy-data.git`

This project uses [pipenv](https://docs.pipenv.org/) to manage its
dependencies.

To install all third-party Python packages in the most recent version into a
project-local virtual environment, run:

`pipenv install`

To install all packages with the same version as of the time of creating this
project (for exact reproducability), run:

`pipenv install --ignore-pipfile`
