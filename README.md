# Mt. Rainier Snowfall Analysis
This project is an investigation into the snowfall boundary changes on Mt. Rainier. It encompasses hyperspectral image classification and time series analysis to provied insights into the snowfall. 

## Description
The purpose of this project is to utilize hyperspectral imaging and classification analysis to predict the boundary of snowfall on Mt. Rainier. Understanding the snowfall is useful for many reasons, if snowfall is shown to be heavy, then the following months could see heavy flooding from the snow melt runoff. Alternatively, light snowfall could result in drought throughout Eastern Washington because there isn’t enough melt from the mountain. And generally, understanding snow boundaries on the mountain helps us to understand the state of our current climate and understand patterns in the snowfall. To approach this problem, the USGS Earth Explorer and SNAP tools are used to collect and analyze the satellite images. Pixel data is extracted from these images and used to model and classify using algorithms KNN and SVM. Finally, time series analysis is applied and future radiance levels are predicted and run through the classification models previously made.
## Getting Started

### Dependencies

* jupyter notebook
* python
* sklearn
* seaborn
* matplotlib
* pandas
* numpy
* pmdarima
* SNAP and the USGS Earth Explorer were used to collect data, but not neccesary for use of project as is

### Installing

* ipynb and data files found in main

### Executing program

* run all cells in notebook


## Authors
Ariel Harris


## Acknowledgments

Inspiration, code snippets, etc.
* [USGS Earth Explorer](https://earthexplorer.usgs.gov/)
* [SNAP Software](https://step.esa.int/main/download/snap-download/)


