# SanDiego_Water_Quality_Forecasting

This project is a part of the ADS-506 course in the Applied Data Science Program at the University of San Diego.  This project seeks to explore and forecast water quality attributes for Kelp Beds in the South Bay region of San Diego.

-- Project Status: Complete
--------------

# Table Of Contents
- [Contributers](#contributers)
- [Objective](#objective)
    - [Methods Utilized](#methods-utilized)
- [Installation](#installation)
  - [Dependencies](#dependencies)
- [Acknowledgements](#acknowledgements)
  - [Resource](#data-resource)

# Contributers:
* Emanuel Lucban
    * :email: (elucban@sandiego.edu)
* Christopher Richardson
    * :email: (christopherr@sandiego.edu)
* Sean Torres
    * :email: (seantorres@sandiego.edu)

---------------------------
# Objective
The goal of this particular study is to predict the status of kelp beds within a designated area and forecast if water quality parameters stay within EPA standards. The  approach taken is to apply the ARIMA’s residuals to a back-propagation neural network model to tackle seasonality, heteroskedasticity, and non-Gaussian error that can occur in our data. By applying this model to the stated  dataset, the predictions should represent an accurate forecast pattern for the targeted parameters.


## Methods Utilized
  * ARIMA
  * ARIMA Neural Network
  * Differencing

---------------------------
# Installation
Data Exploration and Modeling was all done in [R Studio](https://www.rstudio.com/).

To clone this repository onto your device, use the commands below:

	1. git init
	2. git clone https://github.com/CFRichardson/SanDiego_Water_Quality_Forecasting


## Dependencies
This repo utilizes the following packages:

  * astsa 1.14.3     
  * caret 6.0-88    
  * corrplot 0.90    
  * DataExplorer 0.8.2
  * DMwR 0.4.1
  * dplyr 1.0.7      
  * forecast 8.15  
  * ggplot2 3.3.5  
  * lattice 0.20-44  
  * neuralnet 1.44.2
  * tidyr 1.1.3     
  * tidyverse 1.3.1

---------------------------
# Acknowledgements
We would like to thank SanDiego.Gov for setting up the necessary tools to measure such water quality attributes as well as publicly sharing the recorded data.

## Resource
Data was sourced from [data.sandiego.gov/datasets/monitoring-ocean-water-quality](https://data.sandiego.gov/datasets/monitoring-ocean-water-quality/)

----------------------
<font size = 10> <center>For a better tomorrow!</center> </font>
----------------------
