
# UNICORN Business Analysis
## Table of Contents
- Project Description
- Tools
- Project Structure
- Data analysis and Results
- Contact

## Project Description
### Inrtoduction
E-commerce is becoming an important platform in the trading sector. A diverse types of goods are transacted with E-commerce. Several companies provide the platform of e-commerce among which UNICORN is one of them. In this project, data associated with sells of products in USA through the UNICORN platform was examined.  
### Project specific questions
- How the purchase of goods vary across different customer segments?
- Which regions, states and cities generate the most revenue?
- Which Products are the most profitable and which products are less profitable?
- How the profit of the company evolve over the years?
These are few of the questions addressed by the project.

### Specific Objectives
- Show specific Key Performance Indicators (KPI) of the company using interactive dashboards
- To identify key business problems that negatively impact the profitability of the company.
 

### Significance
The project has a significance of identifying strengthes that the company needs to hold on and weakness that the company need to address to increase profitability and make the business competetive. 

## Tools
Google colab, 
Googlesheets, 
Beekeper Studio,
SQLAlchemy to connect to the Postgress database,
SQL, 
Google slides


## Usage

To reproduce the code, run the googlecolab notebook file Unicorn_project_SQL.ipynb file in the Github Notebook directory of the UNICORN_Project. 


## Project Structure
- Data/: A directory containing the row and processed data of UNICORN. 
- Notebook/: A directory containing googlecolab notebook with an active code.
- Result/: A directory containing an an spreadsheet for analysis of some business metrics and Tabalu dashboad for visualization of KPI interactively.
- README.md/: A file containing an overview of the project.
## Data Analysis and Results

### Data
- The UNICORN data was imported from the postgress database using the SQLalchemy engine. Four tables the database schema were imported separately.
### Data Pre-processing
- The tables were joined based on joining keys.
## Analysis Results
- The UNICORN profit growth rate as percentage  increased enormously from 2015 to 2016. However, that trend was not maintained in the subsequent years i.e. the profit growth rate was stagnant between 2016 and 2017, and even went down in 2018. 
- However, the number of ordered items increased linearly in the same period.

- High discounts mostly starting from 50% to 80% on the products of Furniture, Office Supplies leads to negative profit. Data shows discount and profit inversely proportional in 2018.
![Results](https://github.com/derewor/UNICORN-project/blob/main/Results/Screenshot%202024-09-07%20at%2012.14.07.png)
## Visualization
- The KPI and other metrics were visualized using Tablau
## Authors

- [@derewor](https://github.com/derewor/TravelTide_Customer_Segmentation_projecte)

https://www.linkedin.com/in/dereje-worku-mekonnen-a8345217/

https://www.linkedin.com/in/subrina-sabur-7070222b6/

Poornima C.K.

https://www.linkedin.com/in/sarah-akbar-ali-1981a-2008b-2024c/
