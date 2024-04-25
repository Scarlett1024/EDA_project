# Bike Sharing System: An Alternative Transportation Model
This project is a part of the Technical Writing course (QTM302W) offered at Emory University. 


#### -- Project Status: Completed


## Project Intro/Objective
In this project, we aim to explore the causal relationships between bike sharing rental patterns and environmental variables, uncovering insights that can inform urban planning, transportation policy-making, and the development of more efficient and sustainable mobility solutions. By leveraging the Bike Sharing Dataset, we can gain a deeper understanding of the dynamics shaping urban transportation systems and contribute to efforts aimed at fostering greener, more accessible cities.


### Methods Used
* Inferential Statistics
* Machine Learning: Ordinary Least Squares Regression 
* Data Visualization
* Predictive Modeling


### Technologies
* R 
* R-Quarto
* HTML




## Project Description
The Bike Sharing Dataset, curated by Hadi Fanaee-T at the Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto, Portugal, offers insights into the dynamics of bike sharing systems (Fanaee-T and Gama, 2014). This dataset, sourced from the Capital Bikeshare system in Washington D.C., USA, covers a two-year historical log spanning 2011 and 2012. It provides a comprehensive view of bike rental behaviors, influenced by various environmental and seasonal factors such as weather conditions, precipitation, day of the week, season, and time of day (Dheeru and Karra Taniskidou, 2017). 

In our Analysis we employed Ordinary Least Squares (OLS) regression analysis to forecast the volume of bike rentals. To identify pertinent independent variables for our model, we conducted an analysis of the Pearson correlation coefficients among our independent variables, thus facilitating a comprehensive comprehension of the inherent correlations among the variables under scrutiny. Furthermore, we leveraged diverse visualization methods, such as bar plots, to elucidate the association between our categorical variables and the response variable, namely the count of bike rentals.

Moving forward, we can delve deeper into specific patterns, trends, and correlations within the data, such as different rental behaviors between casual and registered users in different geographic conditions. Additionally, we can explore predictive modeling techniques to forecast rental demand using a time series model.


## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- data visualization
- statistical modeling
- assessments of collinearity, independence, homoscedasticity, and normality of residuals
- writeup/reporting


## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](data/hour.csv) within this repo.
3. Follow setup [instructions](Link to file)


## Directory Structure
``` bash
EDA_project
├── analysis
│   ├── project_files
│   │   ├── figure-html
│   │   │   ├── bar_1.png
│   │   │   ├── bar_2.png
│   │   │   ├── bar_3.png
│   │   │   ├── bar_4.png
│   │   │   ├── bar_5.png
│   │   │   ├── bar_6.png
│   │   │   ├── bar_7.png
│   │   │   ├── bar_8.png
│   │   │   └── bar_9.png
│   │   └── libs
│   │       ├── bootstrap
│   │       │   ├── bootstrap-icons.css
│   │       │   ├── bootstrap-icons.woff
│   │       │   ├── bootstrap.min.css
│   │       │   └── bootstrap.min.js
│   │       ├── clipboard
│   │       │   └── clipboard.min.js
│   │       └── quarto-html
│   │           ├── anchor.min.js
│   │           ├── popper.min.js
│   │           ├── quarto-syntax-highlighting.css
│   │           ├── quarto.js
│   │           ├── tippy.css
│   │           └── tippy.umd.min.js
│   ├── EDA_Code_Notebook.qmd
│   └── EDA_Code_Notebook.html
├── data
│   ├── day.csv
│   └── hour.csv
├── EDA_project.Rproj
├── renv
│   ├── activate.R
│   ├── library
│   │   └── R-4.3
│   │       └── x86_64-apple-darwin20
│   │           └── ALL THE PACKAGES USED
│   ├── settings.json
│   └── staging
└── renv.lock
```

## Contributing Members

|Name     |  Contact Info   | 
|---------|-----------------|
|[Dawit Dean](https://github.com/Uchimata1)| dawit.dean@emory.edu       |
|[Scarlett Wu](https://github.com/Scarlett1024) |     scarlett.Wu@emory.edu    |

