Bash Math
=========

Bash Math is a series of scripts used for performing calculations on
tabular data from bash scripts. For example, to compute the mean of a
the third column of numbers in a TSV, run:

    cut -f3 file.tsv | mean

The scripts are:

* `mean` -- Compute the mean of a column of data
* `median` -- Computer the median
* `variance` -- The variance
* `stddiv` -- Standard deviation
* `sumtotal` -- Add up all numbers

The names were chosen mostly to avoid namespace conflicts with
existing Unix commands.

The easiest way to install is `pip install bashmath`