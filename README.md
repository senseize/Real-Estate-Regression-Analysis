# Real Estate Regression Analysis

## Overview

This is the **second end-of-module project in the Flatiron Online Data Science Course**. The project aims at testing and reinforcing the scientific computing and quantitative methods taught in phase 2 of the Flatiron School curriculum.

**Deliverables** for this project are this [GitHub Repository](https://github.com/senseize/Real-Estate-Regression-Analysis), a [Jupyter Notebook](./Regression-Analysis.ipynb) containing the code along with markup, as well as a [presentation](./Regression-Analysis-Presentation.pdf).

## Business Problem
The fictitious business problem deals with supporting a real estate agency in creating a successful marketing campaign in the King County area  (a northwestern county of the US). 
As main drivers of the campaign’s success I use data science to identify **preferences of potential house buyers** and support with **price predictions**.

## Data & Methodology
The data used was provided by Flatiron School and includes more than 21,000 prices and features of house sales. I opted for the OSEMiN approach, beginning with obtaining, scrubbing and exploring the data, before being able to make interpretations. 

## Results / Key findings

**Time**
 - The best time to launch the marking campain is April/June
 - Winter months and Q1 in general should be avoided to achieve the highest median price

[Boxplot_Month&Quarter](./Images/Boxplot_Month&Quarter.png)

**Location**
 - There are clear differences in sales prices between different King County areas
 - To achieve the highest sales prices, the marketing efforts can be focused selectively

![Zipcodes_Table](./Images/ Zipcodes_Table.png)

**Housing Attributes**
 - **Bedroom, Bathrooms and Floor count** is positively correlated with prices (Floor count however only until 2.5 floors)

![Boxplot_Bedroom&Bathroom_count](./Images/ Boxplot_Bedroom&Bathroom_count.png)
![Boxplot_Floor_count](./Images/ Boxplot_Floor_count.png)

 - **Basement availability** and **renovations** are favorable on prices

![Boxplot_Base_Renov_availability](./Images/ Boxplot_Base_Renov_availability.png)

 - Housing **grades from 9 upwards** and **conditions from 3 upwards** should mark the beginning of the marketing campaign’s focus

![Boxplot_Grade&Condition](./Images/ Boxplot_Grade&Condition.png)

**Regression Models**

![Models_Table](./Images/ Models_Table.png)

## Contact Information

For any questions, please contact me at **kontakt@oliverzimmer.eu**
