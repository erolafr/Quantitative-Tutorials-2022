
# Session 2 - Quantitative Tutorials

## Week 7 - Data Visualization

Dr. Erola Fenollosa (she/her)

26/10/2021

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
build the code to import that dataset into R and prepare a significant
plot form it. It could be any plot: a map, an histogram, a boxplot, a
scatterplot, a barplot, etc. I will ask you to send to me via email your
plot in a word file with a figure caption that describes it with enough
detail. To help you with this I prepared this document.

### 1. Data visualization is an art

Show examples of good visualizations. The one about the artists palette,
or the movies timelapses for instance.

### 2. Data visualization objectives

Non-excluent data visualization aims:

- Data analysis: expose example of spatial data analytics.

- Expose results

- Communicate: communicate an idea or a result of an analysis. Images
  communicate better than tables.

- Explore: Exploratory data analysis (EDA) benefits from data
  visualization as they help understand the nature and characteristics
  of a variable set. Interactive visualizations are very useful to
  explore better the data following successive questioning.

- Data in its context: understand the value of a particular information
  within its context, for example a company’s number of total sells in a
  ranking.

- Find patterns and outliers: for example seek seasonality dynamics,
  hidden maps, extreme values, etc.

### 3. How to create a good visualization

- **Define your Take Home Message (THM)**: this is the first step and
  must be considered carefully. Define what do you want to tell to your
  targeted audience. Are you trying to show a trend? Are you trying to
  find data outliers? Define the aim of your visualization. Writting the
  figure caption with a heading title may help on this process.
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
  red colour scale.
- Check that your are **not missing anything essential**: if it’s a map,
  does it have a scale? If the data has variation, have you included a
  way to represent it (standard error, jittered points, etc). If you’re
  showing something with colour or shape did you include a legend? Is
  the ink/information ratio balanced? Do not add ink to the plot that
  does not give extra information. The human eye is not prepared to
  compare areas and angles avoid pie charts.
- **Code the figure**
- **Test it** with friends, is it autoexplanatory?

### 4. Statistics and data visualizations

Statistics are essential when we communicate our results. Can you think
of how statistics can support your visualization?
