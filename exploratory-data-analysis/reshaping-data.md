# Reshaping Data

In previous exercise we have naively established the most significant ports globally, by using the metric of the number of total ships serviced by each port. However, you also might have noticed that it was inconvenient to work with the data, especially the vessel count and vessel type variables, since the same port appeared multiple times due to the number of unique observations of vessel type.

Now we would like to be able to have a closer and more concise look at the individual ports. For this, have another look at the two variables vessel\_type and vessel\_count. How many unique observations does vessel\_type contain (please show us your code)? Do we need to reshape from wide to long, or from long to wide? Reshape accordingly!

Use the reduction of observations and the number of unique observations of the variable vessel\_type as sanity checks for your reshaping.

After reshaping, give use a short overview of your data in a table output, and your reasoning of your sanity check. Again, explain your thought process and extensively comment your code. Do not forget to update your responses to the "Discovering the Data" questions!

> <img src="../.gitbook/assets/R.png" alt="" data-size="line">\
> For reshaping your data set, familiarize yourself with `pivot_wider()` and `pivot_longer()`, which one do you need to use?
>
> For the table output, you can reuse the `knitr::kable()` function. It suffices to just show us the top 10 observations.

> <img src="../.gitbook/assets/p.png" alt="" data-size="line"> \
> @Python please update
