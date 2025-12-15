
# Examining the Correlation between Socioeconomic Indicators and Self-Reported Health
This project is a part of the Technical Writing Class at Emory University

## Project Intro/Objective
The purpose of this project is to look at the most relevant variables/socioeconomic factors involved in determining one's health. We primarily looked at variables that are related to healthcare, such as having insurance and a 
certain place for medical care. By finding the relationship between these factors and health, and how these factors interact to correlate with health, we can inform public policy on major changes in specific factors that have the 
most effect on health, and learn what further studies on human health need to be done. 

## Methods Used
* Exploratory Data Analysis
* Model Selection
* Logistic Regression
* Data Visualization
* Predictive Modeling
* etc.

## Technologies
* R
*   GgPlot, GLM Package, Base R
* IPUMS Data Modeling
* etc. 

## Project Description

### Research Questions We're Exploring

1. What is the distribution of certain socioeconomic factors that could relate to heatlh?
- Socioeconomic Factors: Medical Care Place, Insurance Coverage, Private Insurance Coverage, Education Levels, Hours Worked
2. What socioeconomic factors from this dataset are the most relevant in predicting self-reported health?
3. How much does the interaction of socioeconomic factors affect self-reported health? 

### Model and Visualization Techniques
* EDA Plots (Boxplots, Bar Charts, Pie Charts) through GGPlot 
* GLM for Logistic Regression
* LASSO for Model Selection (In Final Project)
* Linear Regression for Hours Worked vs Other Variables (In Final Project)

### Challenges
* Distribution of Independent Variables skewed towards one end, but is also a part of real world datasets
* Not enough socioeconomic indicators relating to demographics, which could also play a role in health
* Counterintuitive correlations for insurance coverage (In Final Project)

### Next Steps
* Testing the impact of income on health, and if it is a confounding variable in many of the relationships in
this project
* Exploring other socioeconomic factors' relationship on health such as race and occupation status


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data and Codebook is being kept Datasets folder    
3. Data processing/transformation scripts and html file are being kept in Analysis folder


## Contributing Members

**Jessie Chen, Email: jessie.chen@emory.edu**

**Sally Choi, Email: yoolim.choi@emory.edu**

**Claire Hamilton, Email: claire.hamilton@emory.edu**

**Keerthy Rangan, Email: keerthy.rangan@emory.edu**

## Tree for Repository:
```text
QTM302WSelfReportedHealthProject/
├── Analysis/
│   ├── eda_code_notebook.Rmd
│   └── eda_code_notebook.html
├── Datasets/
│   ├── nhis_00004.csv
│   └── FILE_8349.pdf
├── renv/
│   ├── activate.R
│   └── settings.json
├── .gitignore
├── QTM302WProject.Rproj
└── renv.lock


