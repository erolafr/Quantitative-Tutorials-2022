
# Session 2 - Quantitative Tutorials

## Week 7 - Data Visualization

Dr. Erola Fenollosa (she/her)

\*\*/10/2021

### Introduction

The aim of this tutorial is to learn how to create a good visualization.
Moreover, through this tutorial we are going to discuss which
statistical techniques may help us test hypothesis regarding data
distribution, differences between populations or specific trends.

### 0. Pre-Tutorial

In the last session I asked you to choose a dataset to continue this
tutorials through a project-oriented approach. The dataset must contain
at least 50 observations and categorical and numerical variables. It can
be both a dataset of your own or a public dataset (from Kaggle, UCI,
Data.world etc.)

In addition to that, before the next session it is required that you
**build the code to import that dataset** into R and **prepare a
significant plot form it**. It could be any plot: a map, an histogram, a
boxplot, a scatterplot, a barplot, etc. I will ask you to **send to me
via email your code and your plot in a word file with a figure caption**
that describes it with enough detail. To help you with this I prepared
this document.

Writting a good figure caption is not an easy work. Find a scientific
article you like and analyse with details the authors include in the
figure caption. See here an example from [Fenollosa et
al. (2020)](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-020-00607-3).

![Figure example from Fenollosa et al.,
2020](https://user-images.githubusercontent.com/31477298/200793324-af6afd3d-54e4-4e38-ba03-b063be0cf9f3.png)

### 1. Data visualization is an art

Data visualization in biology is extremely necessary (Wong, 2012:
<https://www.nature.com/articles/nmeth.2258.pdf?origin=ppub>), but it is
an art discipline itself. Please take a dive in this portal to explore
the potential of data visualizations and explore at least one
visualization type: <https://datavizproject.com/>

Remember you can find R code to prepare those graph types here:
<https://r-graph-gallery.com/>

### 2. Data visualization objectives

Non-exclusive data visualization aims:

- **Explore**: Exploratory data analysis (EDA) benefits from data
  visualization as they help understand the nature and characteristics
  of a variable set. Interactive visualizations are very useful to
  explore better the data following successive questioning.

- **Data in its context**: understand the value of a particular
  information within its context, for example a company’s number of
  total sells in a ranking.

- **Find patterns and outliers**: find out of the range values and
  identify hidden patterns, for example seek seasonality dynamics or
  hidden maps.

### 3. How to create a good visualization

- **Define your Take Home Message (THM)**: this is the first step and
  must be considered carefully. Define what do you want to tell to your
  targeted audience. Are you trying to show a trend? Are you trying to
  find data outliers? Define the aim of your visualization and which
  question are you trying to answer. Writing the figure caption with a
  heading title may help on this process.
- **Choose a plot type:** There are plenty of plot types, generally
  there are the following categories: those that **compare** data
  groups, define **distributions**, and .
- **Draw by hand your plot**: This will help you coding the figure as
  will make you detail the elements that it must include.
- **Prepare the data**: Do you need any extra information? Do you need
  perhaps to calculate the mean and standard error by group, or
  standarise the data?
- **Pick aesthetic palette**: Consider color-blind palettes. Make your
  figure intuitive: if your colour scale is temperature pick a blue to
  red colour scale. Function is way more important than aesthetics.
- Check that your are **not missing anything essential**: if it’s a map,
  does it have a scale? If the data has variation, have you included a
  way to represent it (standard error, jittered points, etc). If you’re
  showing something with colour or shape did you include a legend? Is
  the ink/information ratio balanced? Do not add ink to the plot that
  does not give extra information. The human eye is not prepared to
  compare areas and angles avoid pie charts.
- **Code the figure**
- **Test it** with friends, the plot must be autoexplanatory. Check the
  readability of the different elements and the logic of its
  disposition.

### 4. Statistics and data visualizations

Statistics are essential when we communicate our results. Can you think
of how statistics can support your visualization?
