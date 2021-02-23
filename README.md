### Data project Module 2
# Diamonds Analysis 

![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

## Alejandra Matías Martín

Bootcamp: Ironhack - Data Analytics Part Time Nov 2020

---

![image info](./images/diamond.png)	

## Overview

The objective of this project is to analyze a diamond database through two main steps:

1. Building an exploratory data analysis report in order to gain initial insight on our diamonds dataset
2. Building a data dashboard using our diamonds dataset 

### Datasource


- <strong>diamonds_train.csv </strong> - the main dataset.

##### Features

- carat: weight of the diamond
- cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- color: diamond colour, from J (worst) to D (best)
- clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- table: width of top of diamond relative to widest point (43--95))
- price: price in USD
- x: length in mm
- y: width in mm
- z: depth in mm

## Exploratory data analysis report: Instructions

In order to make a good exploratory analysis, we will draw Summary statistics including descriptive statistics 
Summary statistics including descriptive statistics (max, min, mean, standard deviation, percentiles, correlations, etc.) and data types (integer, float, boolean, string, etc.).
Data visualizations charts in order to capture a large amount of data all at once in a clear and concise manner (Box Plots, Histograms, Bar Plots, Scatter Plots, Correlation Matrix, etc.).

| Country       | Job Title      | Gender | Quantity | Percentage |
| :-----------: |:-------------: | :-----:| :-------:| :---------:|
| Spain         | Data Scientist | Female | 25       | 5%         | 
| Spain         | Data Scientist | Male   | 25       | 5%         |



## Tableau Data Dashboard
___
### :computer: **Technology stack**
- Python
- Pandas
- Tableau
- Matplotlib
- Numpy


## :file_folder: Folder structure
```
└── project
    ├── __trash__
    ├── .gitignore
    ├── .env
    ├── README.md
    ├── main_script.py
    ├── cleaning_raw.ipynb
    |
    ├── p_acquisition
    │   ├── m_acquisition.py
    │   └── __init__.py
    |
    |── p_wrangling
    |    ├── m_wrangling.py
    |    ├── __init__.py
    |   
    ├── p_analysis
    │   ├── m_analysis.py
    │   └── __init__-py
    ├── p_reporting
    │   ├── m_analysis.py
    │   └── __init__.py
    |__ results
    |
    └── data
        ├── raw
        ├── processed
    
```
	
---

## :love_letter: Contact
> Email: <alejandramatias32@gmail.com>
> Teléfono: 626118167
