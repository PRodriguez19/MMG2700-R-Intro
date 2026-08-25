## Week 4

# Introduction to `dplyr`

We have learned how to create objects, work with different data types, and access information stored in a data frame. But most real datasets are not ready to answer our questions right away. We often need to **select certain observations, choose specific variables, create new variables, or organize our data** before we can analyze or visualize it.

The **`dplyr`** package provides a set of functions designed to make these common data manipulation tasks easier. The functions use a consistent and readable syntax, allowing us to describe what we want to do with our data rather than writing complicated code.

`dplyr` is part of the **tidyverse**, a collection of R packages designed to work together for data analysis.

## The Big Picture

Think of `dplyr` as a set of tools for **transforming a dataset into a form that is useful for answering a question**.

When working with a dataset, you might want to:

* **Choose specific rows** — for example, look only at female samples.
* **Choose specific columns** — for example, keep only gene, tissue, and expression.
* **Create or modify variables** — for example, calculate the difference between two measurements.
* **Rename variables** — make column names clearer or more consistent.
* **Rearrange rows** — for example, sort samples from highest to lowest expression.
* **Summarize data** — for example, calculate the mean expression for each tissue.
* **Group data** — perform calculations separately for different categories, such as treatment groups or tissues.

These operations can be combined to move from a **large, messy dataset** to a **smaller, organized dataset that answers a specific biological question**.

For example, imagine you have a dataset containing gene expression measurements from multiple genes, tissues, and experimental groups. You might use `dplyr` to:

**filter > select > create variables > group > summarize**

The specific steps will depend on the question you are trying to answer. Throughout this section, we will learn the individual `dplyr` functions that allow us to perform these tasks and then combine them into more complex data analysis workflows.


### What should you be able to do by the end of this week?

By the end of this week, you should be able to:

+ Describe, reorder and rename factors.
+ Describe the purpose of the `dplyr` package.
+ Describe the concept of a wide and a long table format, and see how to reshape a data frame from one format to the other one.
+ Demonstrate how to join tables.
