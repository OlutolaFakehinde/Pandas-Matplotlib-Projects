# PROJECTS

## Introduction
These projects I "walked-through" with my tutor and mentor.

This first project in Pandas analysed "IT Developers Survey" with dataset of 89,184 rows by 84 columns

The project in Matplotlib analysed data from a wharehouse sales department with 78 rows by 6 columns

## Project in Pandas
The dataset surveyed various IT developers in many different parts of the world.

### IT Developers Survey

We imported pandas as pd and numpy as np and uploaded the two datasets of the project: 'Developer survey/survey_results_public.csv' with 89,184 rows by 84 columns and 'Developer survey/survey_results_schema.csv' with 78 rows by 6 columns into Jupyter Notebook as DataFrame.

We investigated the datasets in various forms

#### Queries
Some of the queries answered are:
- Type of working conditions of the developers
- Extract Age, EdLevel, Employment of developers in index 30, 67, and 90
- Developers that have been coding for more than 10 years.
- Developers that earn above 10000 - (either professionally or not)
- Developers that earn more than 10,000 per year, their RemoteWork and EdLevl
- Developers that earn above 10,000 and from Nigeria

#### Exercise
My exercise was to find:
1. What is the age range of people who work remotely in the US?
2. How many developers are from USA, India, UK and Nigeria?
3. What is the average salary of Nigerian developers?
4. What percentage of Nigerian developers use Python?

The link to the dataset [here](https://insights.stackoverflow.com/survey)

## Project in Matplotlib and Pyplot
Various examples of graphs from Matplotlib were demonstrated

### Sales Dataset
We We imported pandas as pd, numpy as np and matplotlib from which pyplot as plt was imported. Later, seaborn as sns was introduced to give more styles into the charts.

We uploaded Sales dataset for a wharehouse sales department, with 78 rows by 6 columns, where some vehicle parts are sold.

The 8 columns hold: date; wharehouse; client_type; production_line; quantity; unit_price; total and payment.

### Charts
The following chats were plotted:
- plot quantity column
- plot quantity column with 'title', 'xlabels' and 'ylabels'
- a line chart showing the daily trend of sales based on total amount made
- a scatter plot
- a bar chart showing number of warehouse
- a bar chart showing number of warehouse
- plot a horizontal bar chart showing number of warehouse
- histogram showing the quantity
- pie charts of the production_line
- subplots showing quantity and amount on separate graphies side by side

## Conclusion
From the various charts plotted, an excellent performance of the Sales department can be evaluated
