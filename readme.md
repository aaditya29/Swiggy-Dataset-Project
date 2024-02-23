# Swiggy Data Analysis

## Background Information

> Project of swiggy data science analysis tasks completed using the Python library. <br>

In this project we use Python Pandas & Python Matplotlib to analyze and answer business questions about swiggy sales data.<br>

We start by cleaning our data. Tasks during this section include:

- Drop NaN values from DataFrame.
- Removing rows based on a condition.
- Change the type of columns (to_numeric, to_datetime, astype).

Once we have cleaned up our data a bit, we move the data exploration section where we explore 5 high level business questions related to our data:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame `(pd.concat)`.
- Adding columns.
- Parsing cells as strings to make new columns `(.str)`.
- Using the `.apply()` method.
- Using groupby to perform aggregate analysis.
- Plotting bar charts and lines graphs to visualize our results.
- Labeling our graphs.

## About Dataset

The Swiggy Restaurant Dataset is a comprehensive collection of data related to restaurants available on the Swiggy food delivery platform.<br>
This dataset provides valuable information about various aspects of restaurants, enabling users to explore, analyze, and gain insights into the restaurant landscape on Swiggy.
