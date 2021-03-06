# Super-short super-basic Data Munging in R and Python

*Giuseppe Paleologo* <paleologo@gmail.com>

2015-04-01

In October 2012 I wrote a document to help translate between R and python pandas idioms for data manipulation. Back then, It was reasonable to cover a good fraction of the operations in the two languages. Today that is no longer the case. Pandas has tripled in size since I first covered its capabilities and is now nearing 200K lines of code. Meanwhile, R has seen intense development of data.table and the release of dplyr, tidyr and magrittr, steps toward a "grammar of data". Pandas and dplyr take different approaches to data manipulation. Pandas takes the "maximalist" approach: it works with 1, 2, and 3-dimensional arrays; and with hierarchical indices, one can represent tree-like data structures (e.g., nested lists); moreover, it allows one to align and operate on numerical arrays. Finally, it has plotting capabilities as well. dplyr takes the "minimalist" approach. It works with 2-D tables only, with a small set of verbs that are easily composable with each other (as well as with base R functions). As a result, the manipulations are easy to write and read. Plotting is delegated to other libraries; so is numerical algebra; so is time series analysis. To learn well the data manipulation capabilities alone of these two languages requires a significant time investment. To reflect these changes, I chose to focus on manipulation of tabular data alone, therefore using a subset of pandas for Python, and of dplyr + tidyr in R. The choice of  the latter is motivated by its balance of conceptual elegance, performance and fast rate of adoption. Pandas' documentation has a session comparing R to pandas, but the idioms presented here are more modern, regular and concise.

I make no claims of completeness, but hope that readers will find this useful to go back and forth between the languages.


* [Super-short super-basic Data Munging in R and Python](https://github.com/contravariant/pandas_dplyr/blob/master/pandas_dplyr.md)

* [Rmarkdown doc of the baby names analysis done in R](https://github.com/contravariant/pandas_dplyr/blob/master/babynames/babynames.pdf)([Rmd](https://github.com/contravariant/pandas_dplyr/blob/master/babynames/babynames.rmd))

* [ipython notebook of the baby names analysis done in pydata](https://github.com/contravariant/pandas_dplyr/blob/master/babynames/babynames_pandas.pdf)([ipynb](https://github.com/contravariant/pandas_dplyr/blob/master/babynames/babynames.ipynb))