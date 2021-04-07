# Matplotlib Challenge - Pymaceuticals Inc.

## Table of Contents
  * [Introduction](#introduction)
  * [Observations](#observations)
  * [Data Visualization](#data-visualization)
    * [Bar Charts](#bar-charts)
    * [Pie Charts](#pie-charts)
    * [Box Charts](#box-chart)
    * [Line Charts](#line-charts)
    * [Scatter Charts](#scatter-charts)
    * [Correlation Coeifficient & Linear Regression Model](#linear-regression)
    

# Introduction
## <a name="introduction">Introduction</a>
The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.
249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured.

# Observations

The bar chart displayst 25 unique mice tested on each drug regimen.

The pie chart shows that female versus male mice's was equally distributed.

From the box plot graph, we can see that Ramicane and Capomulin are more effective in treating tumors can be more effective than Infubinol and Ceftamin.

The line plot of tumor volume versus time point for s185 treated with Capomulin shows that the tumor volume decreased from 45 mm3 to about 23 mm3 by the time pass. It seems that Capomulin was very effective in treating the tumor of s185. It would be needed to see line plots of tumor volumes versus the time point of other mice treated with Caomulin as well to prove the indisputable effectiveness of Capomulin.

Looking at the scatter plot with the linear model, we can notice a strong positive correlation between mouse weight and average tumor volume for the Capomulin regimen. The fact that the correlation coefficient was about 0.84 also proves this relationship. From this, we can assume mouse weight can significantly affect tumor volume. In other words, the heavier the mouse weight may cause a larger tumor volume.


# Data Visualizations

# Bar Chart
## <a name="bar-charts">Bar Charts</a>
Bar plot using both Pandas's and Matplotlib's that shows  the number of total mice for each treatment regimen throughout the course of the study.
![image](https://user-images.githubusercontent.com/69221324/113892783-5d3a7c00-9794-11eb-90a8-9f78d0ae6c71.png)


## <a name="pie-charts">Pie Charts</a>
Pie plot using both Pandas's and Matplotlib's that shows the distribution of female or male mice in the study.
![image](https://user-images.githubusercontent.com/69221324/113892809-64fa2080-9794-11eb-9236-ce8a63917022.png)


## <a name="box-chart">Box Charts</a>
Box and whisker plot of the final tumor volume for all four treatment regimens.
![image](https://user-images.githubusercontent.com/69221324/113892835-6c212e80-9794-11eb-9172-d19138d6d068.png)


## <a name="line-charts">Line Charts</a>
Visualization of tumor volume vs. time point a mouse that was treated with Capomulin.
![image](https://user-images.githubusercontent.com/69221324/113892862-72afa600-9794-11eb-9c71-5a400271437c.png)


## <a name="scatter-charts">Scatter Charts</a>
Visualization of mouse weight versus average tumor volume for the Capomulin treatment regimen.
![image](https://user-images.githubusercontent.com/69221324/113892880-76dbc380-9794-11eb-8427-887862c251cd.png)


## <a name="linear-regression">Correlation Coeifficient & Linear Regression Models</a>
Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.
![image](https://user-images.githubusercontent.com/69221324/113892928-82c78580-9794-11eb-8e4e-86d0e115b5db.png)
