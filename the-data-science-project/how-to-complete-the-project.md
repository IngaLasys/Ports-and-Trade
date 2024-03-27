# How to Complete the Project

Once you see the exercises of this semester's project you may wonder: How should I complete these exercises? What am I supposed to write? Do key words suffice, or should I write full sentences? What does "commenting code" mean? How should I document what I do?

In the following we will give you some tips and tricks on how to complete your project – take them as our expectations we have towards you.\
After some general advice, there will also be some programming language specific information, so read this section carefully and refer back to it during the completion of the project.

If there are any open questions feel free to ask your peers or your mentor.

<details>

<summary>Citing sources</summary>

Perhaps some of you are working with data for the first time and you do not know the convention of how to cite - this is absolutely no problem and we are delighted to have you! \
\
As you may have seen in the news papers, articles, or other sources, if graphs or statistics are depicted, they always show sources in notes or captions. Since we are dealing with publicly available data from the IMF and the UN, we need to correctly cite the sources! For this, you can either have a look at how we cite the graphs we show, but for your general learning we encourage you to have a look at the original source of the data and look how they want you to cite the source. To make things easy, look at this [FAQ page from the PortWatch website](https://portwatch.imf.org/pages/faqs). Correct citing is expected in the advanced part too, please refer to the [Sources](sources.md) page.

</details>

<details>

<summary>Non-code text questions</summary>

You may come across some questions where you are asked to describe some characteristics of the data set, such as in the question [Discovering the Data](../exploratory-data-analysis/discovering-the-data.md). For these questions, in a few sentences, write down what you have discovered and what you think. Key words do not suffice, treat us like an audience who does not know at all and is also learning alongside you.&#x20;

</details>

<details>

<summary>Code questions</summary>

Equally, you may come across questions where you need to code and explain to us. In the section [Discovering the Data](../exploratory-data-analysis/discovering-the-data.md), we have explicitly marked them with "(code)", however, we expect you to read the following questions closely to understand what is asked of you, and comment code extensively. \
Again, key word answers do not suffice, a couple of short sentences will get the job done. \
Extensively commenting code could look like this:

```r
ships <- data_set %>%
mutate(did_something = do(something)) %>% #'transform' the variable something into did_something
select(var1, did_something) #keeping var1 and the transformed did_something for later use (specify later use)
```

Note that the above code chunk is written in R language , the comments are added using #(text). But similar applies to Python.\
The more extensive your commenting is, the better it is for yourself since you can later refer back to your own code "library" you have built, and still have the explanations of the code you used, as well as the meaning behind new variables you generated noted down, for yourself or the potential readers.

If you generate new variables, we also recommend to you to always note down the name of the newly generated variable, what original variable you used and how you transformed it, as well as the new meaning. You can call it a "variable book", and if you are dealing with large data sets, such as questionnaires, this is frequently part of the data documentation. While we do not expect of you to write a separate file with new variable names, it is best practice to, after extensively commenting code, also separately note down the above explained information for new variables.

</details>

<details>

<summary>R: Solving the project in Markdown</summary>

As we will explain to you in the introduction workshop, you will solve the questions in [RMarkdown](https://rmarkdown.rstudio.com/lesson-1.html). Specifically, you need to hand in the .Rmd file as well as the knit html file. Please **do not** complete your tasks in RScript, we only want to see RMardown. If you missed the coding meetup where we introduce RMarkdown or read this script before the first meetup and are curious to learn more now, klick on the above hyperlink.&#x20;

Your written code should be in code chunks, with the required comments. Please name each chunk according to what task you complete. In the chunk where you load all the libraries you may turn off any output, in all other chunks we want to see your output as well as any warnings or error messages as final output (thus, it is best to solve all exercises without error messages!).&#x20;

When you are asked to give output as table, we do not want to see the entire data set, a few rows suffice! And of course, explain any new variables you have added when you are asked to show a table output.

</details>

<details>

<summary>Python: PLEASE ADD!</summary>



</details>
