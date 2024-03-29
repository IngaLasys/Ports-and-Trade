# Merging Data Sets

Now we would like to merge ports and geographical\_location data. As you may have seen in the DataCamp courses, you need unique variables to do so. Notice, that `geographical location` countains country and portname information, while the `ports` dataset contains a variable "fullname" which is the combined information. \
In the first step, split the "fullname" variable into two variables (note, you should use the data set which you have transformed from long to wide). \
After splitting that variable in two, merge with the geographical location data set.

Advice: be careful with US ports and look at the formatting ! Some few ports may include states, while names of other ports do not. Outline the problem you find.

> <img src="../.gitbook/assets/R.png" alt="" data-size="line">\
> Use `dplyr`'s `seperate()` and `mutate()` for the relevant variables.\
> Consider using `dplyr` package for merging, on the cheat sheet you can find multiple different ways to merge with `x_join()`. Select the one that is the most useful to you.\
> By now you should be comfortable showing us table outputs, a few rows should suffice.

> <img src="../.gitbook/assets/p.png" alt="" data-size="line"> \
> @python please add
