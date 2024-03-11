# Discovering the Data

The first step in starting any project is loading the data. For the exploratry data analysis part (EDA), we will use [ports](https://1drv.ms/u/s!Ais4tuRZBkegg5gVAG0Yz7-GaV5wtg?e=ySaVSM) and [geographical location](https://1drv.ms/u/s!Ais4tuRZBkegg5gUs1Suv51j\_Wx\_9g?e=9D5Rry) data sets.



After downloading the data set into your working directory, import both data sets, geographical location and ports. Separately for each of the two data sets, describe the data sets. Some questions to guide you along:

* [ ] What kind of data are we dealing with: time series, cross sectional, panel data?
* [ ] How many variables does each data set have? (Code)
* [ ] How many observations per variable do we have? (Code)
* [ ] What do the variable names mean?
* [ ] What variable types are we dealing with? (Boolean,numeric, character, date, etc., Code)
* [ ] Are there any mistakes with the variable types that might make future work difficult if not fixed?
* [ ] Is the dataset in long or wide format? Do you need to change that later?

Some of these questions are best answered in code, while some other questions require you to write us what you think. Key words will not suffice, please do tell your audience your reasoning. If you are unsure on how to answer this question or the other following questions, please go back to the section "How to Complete the Project" where we outline what we expect of your solutions. \
And don't fret, if you cannot answer all questions right now, which we totally do not expect of you, you can answer each question after completing a question further down. Just tell us what you learned, or observed right away!





> <img src="../.gitbook/assets/R.png" alt="" data-size="line">\
> You could use `dplyr`’s `select`, `filter`, `count` and `arrange` function to compute the desired outcome to answer the question. If you haven’t heard of the `dplyr` package yet, take the respective DataCamp course asap!  However, `str()` and `summary()` are also a powerful non-`dplyr` functions for getting started.



> <img src="../.gitbook/assets/p.png" alt="" data-size="line">\
> In order to manipulate big amounts of data, `Pandas` implements different functions to manipulate entries in the Dataframe. Useful functions are: `select`, `filter`, `value_counts` and `max`. If some of those functions seem new to you, don’t scare away from them just now. When it comes to packages and their implementations, there are usually some easy to understand examples that can be found on their wiki page.&#x20;

