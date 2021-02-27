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

### Features

- carat: weight of the diamond (A 1 Carat Diamond equals 200 milligrams and weighs about the same as a quarter of a raisin)
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

In order to make a good exploratory analysis, I have done Summary statistics including descriptive statistics:max, min, mean, standard deviation, percentiles, correlations, data types, etc.

Also I made data visualizations charts in order to capture a large amount of data all at once in a clear and concise manner (Box Plots, Bar Plots, Correlation Matrix, etc.).


## Tableau Data Dashboard

Based on the analysis done in the data analysis report, I have plotted in Tableau to corroborate the main insights I have drawn from this data set.
 You can access to the dashbord [here.](https://public.tableau.com/profile/alejandra.mat.as.mart.n#!/vizhome/Diamondsdashboard/DiamondsDashboard?publish=yes)

### Conclusions

- The <strong>carat</strong> is the characteristic with the highest correlation to the <strong>price</strong> of the diamond: the higher the carat (the more it weighs), the higher the price.
- The volume is also highly correlated to the price.
- In terms of <strong>color</strong>, I would have originally thought that diamonds with a D color (100 % colorless), which is the best, would have the highest average price. However, the ones with the highest average price are the J and I (less colorless).
- Diamonds with the highest carat and average price are mainly less colorless (J, I, H).
	

___
### :computer: **Technology stack**
- Python
- Pandas
- Tableau
- Matplotlib
- Numpy
- Seaborn


## :file_folder: Folder structure
```
└── project
    ├── .gitignore
    ├── README.md
    ├── data_analysis_report-summary-statistics.ipynb
    |── data_analysis_report-visualizing-charts.ipynb
    ├── data
    │   ├── diamonds.csv
    |── images
    |── Tableau
    
```
	
---

## :love_letter: Contact
> Email: <alejandramatias32@gmail.com>
> Teléfono: 626118167
