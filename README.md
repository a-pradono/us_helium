<p align="center">
  <img width="300" height="200" src="https://github.com/a-pradono/us_helium/blob/main/Images/header.jpg">
</p>
<p align="center">
Photo by <a href="https://unsplash.com/@anton_konstantinov?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Anton Konstantinov</a> on <a   href="https://unsplash.com/s/photos/blimp?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</p>

## Table of Contents

- [I. Introduction](#i-introduction)
- [II. Data and Methodology](#ii-data-and-methodology)
- [III. Results](#iii-results)
- [IV. Conclusions](#iv-conclusions)
- [Reference](#reference)

## I. Introduction
Helium is one of the most abundant gases in the universe and it is identified as He in the periodic table of elements under the group name of noble gases. Most people know that helium can be used as a lifting gas in blimps and party balloons. However, helium also plays a crucial role in a variety of areas including medical procedures, defense, energy, aerospace, and low-temperature physics technology. Helium is typically found in natural gas fields that have enough helium mixed with the natural gas, so it can be extracted commercially. The United States is one of the leading producers of helium in the world. Therefore, the objective of this project was to create interactive visualizations of helium concentrations across the US. 

## II. Data and Methodology
The data for this project was obtained from Brennan et al. (2021). This dataset provides helium gas concentration (mol%) containing +13K observations from known and publicly wells data in the US. 

<p align="center">
  <img width="300" height="150" src="https://github.com/a-pradono/us_helium/blob/main/Images/workflow.jpg">
</p>

The workflow above illustrates an overview of how I developed interactive data visualizations in this project. To begin with, data has been cleaned once is retrieved from the source. Moreover, automating the extraction of state names was identified using the latitude and longitude data. Finally, the interactive charts that include the animation can be visualized to better understand the distribution of helium concentrations in the US. 

## III. Results
In the first chart below, several parameters were set to create the interactive visualization for the helium concentrations in the US. The color scale bar was assigned based on sample depth (ft) from the helium sample while the size was set based on the value from the helium itself. Once you drag your mouse to the data, the data contains information that includes API number, latitude, longitude, field, formation, sample depth, helium value, and source.

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/us_helium/blob/main/Images/plot01.gif">
</p>
<p align="center">
Interactive chart can be accessed <a href="https://datapane.com/u/apradono94/reports/MA1p5Rk/chart-1/">here</a>
</p>

In the second chart below, the animation of the helium concentrations has been developed based on the sample year. The available helium samples of this data frame have been collected from 1914-2014.

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/us_helium/blob/main/Images/plot02.gif">
</p>
<p align="center">
Interactive chart can be accessed <a href="https://datapane.com/u/apradono94/reports/Y3YVwO7/chart-2/">here</a>
</p>

In the last chart below, the dropdown menu button was added to filter the helium data based on the state location to make people easier to focus just on a specific state.

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/us_helium/blob/main/Images/plot03.gif">
</p>
<p align="center">
Interactive chart can be accessed <a href="https://datapane.com/u/apradono94/reports/E7yl2P3/chart-3/">here</a>
</p>

## IV. Conclusions
The objective of this project was to create interactive data visualizations of the helium concentrations in the US. The conclusions made from this project are:
  * These charts provide an intuitive environment in which users can easily identify and explore the helium distributions.
  * Zoom in to see a more granular view of the most relevant state or by using the filter dropdown button.   
  * In general, plotly express is relatively fast and easy to implement. 
 
 ## Reference
Brennan, S.T., East, J.A., Dennen, K.O., Jahediesfanjani, H., and Varela, B., 2021, Dataset of Helium Concentrations in United States Wells: U.S. Geological Survey data release, https://doi.org/10.5066/P92QL79J
