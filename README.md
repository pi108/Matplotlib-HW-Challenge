# Matplotlib-HW-Challenge
This folder pertains to the analysis of a dataset, provided by Pymaceuticals, from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated across 10 drug regimens, over the course of 45 days, wherein the tumor development in the mice were observed and measured. 

## Folder Contents
It contains the following:
1.	A Jupyter Notebook files with code that generates the results of the analysis on the screen, and also saves the output to CSV or PNG files as applicable. 
2.	A word document (called Analysis Report) which contains a report with the key insights and supporting charts.
3.	A folder called Resources that contains the source dataset that was used for the analysis.
4.	A folder called Output that contains the CSV and PNG files that will be created by the code in the Jupyter Notebook file.

## Dataset Details
The dataset had the following details for 780 distinct purchases made by 576 players: • Mouse ID • Sex • Age (months)• Weight (g) • Tumor Volume (mm3) • Drug Regimen

## Analysis Tools
The dataset was analyzed using pandas (which is a software library written for the Python programming language for data manipulation and analysis), and matplotlib (which is a Matplotlib is a plotting library for the Python programming language). 

## Key Findings
A detailed analysis of the data identified the following key insights that we believe should help Pymaceuticals with valuable insights regarding the most promising Drug Regimens:
### 1. Mice treated with Capomulin and Ramicane had the LOWEST Average Tumor Volume
Of the 10 total Drug Regimens in the entire Dataset, Pymaceuticals asked us to analyze the 4 most promising Drug Regimens (Capomulin, Ceftamin, Infubinol and Ramicane) . Based on our analysis of these 4 promising Drugs, the 2 best Drugs were Capomulin and Ramicane as they had the lowest average tumor volumes at the end of the test trials.
### 2. Mice treated with Capomulin and Ramicane had the HIGHEST survival rate
Of the 10 total Drug Regimens in the entire Dataset, Pymaceuticals asked us to analyze the 4 most promising Drug Regimens (Capomulin, Ceftamin, Infubinol and Ramicane). Based on our analysis of these 4 promising Drugs, the 2 best Drugs in terms of survival rate were Capomulin and Ramicane. Of the 25 Mice that started the drug trials, in the Case of treatment by Capomuline, 21 of the 25 Mice survived. In the case of treatment by Ramicane, 20 of the 25 Mice survived.
### 3. There was a POSITIVE CORRELATION between Weight and Average Tumor Volume for the mice treated with Capomulin and Ramicane
Given findings 1 and 2 above, we decided to focus on the 2 most promising Drugs Capomulin and Ramicane, and looked at the relationship between Weight (g) and the Average Tumor Volume (mm3). We found a positive relationship between Weight (g) and the Average Tumor Volume (mm3). For Capomulin, the correlation was 0.84 and the Regression Line Equation was Y = 0.95 X + 21.55. For Ramicane, the correlation was 0.81, and the Regression Line Equation was Y = 0.77 X + 25.16.
