### Links

[Tableau Workbook](https://public.tableau.com/app/profile/jing4059/viz/Leadcontaminationindrinkingwater/Leaddashboard) <br>
[Excel sheet](https://github.com/lee-jin81/metis_project_3_business/blob/main/data_business_lead_FINAL.xlsx) <br>
[Slides](https://github.com/lee-jin81/metis_project_3_business/blob/main/slides_business.pdf) <br>
[Write-up](https://github.com/lee-jin81/metis_project_3_business/blob/main/writeup_business.pdf) <br>
[MVP](https://github.com/lee-jin81/metis_project_3_business/blob/main/mvp_business.pdf) <br>
[Proposal](https://github.com/lee-jin81/metis_project_3_business/blob/main/proposal_business.pdf) <br>

# Lead contamination in drinking water in schools

## Abstract 
Lead is a contaminant in drinking water that affects younger children the most, since lead negatively impacts children’s growth, behavior and learning. The Washington State Department of Health initiated lead testing in drinking water at schools although not all schools were analyzed due to lack of funding. The goal of this project was to have the ability to predict which schools are likely to have high lead levels in their drinking water to better allocate water testing based on funding. I analyzed the lead results with Excel, and I used Tableau to visualize and communicate my results. Of the schools that were analyzed, several schools had a level of lead that was far below the safe level.

### Question
Can we identify the common factors in schools with high lead contamination in water?
The government can work with the schools to provide resources to reduce and prevent lead contamination in water to increase the health of the students.

### Data science opportunity
Exposure to lead contamination can affect children’s’ growth, behavior and learning problems. 
We can use data to identify the common factors in school with lead contamination and use this to better address and prevent the problem. 

### Impact hypothesis
By identifying the factors of lead contaminations in water and school that are high risk, the government can work with the schools to improve the water system and implement frequent testing to ensure that the water is safe. 

## Data 
1.	WA School Water Lead Test Data (school year 2018-2019)
Source: https://data.wa.gov/Health/WA-School-Water-Lead-Test-Data/i3jn-y8vx

2.	List of public schools in Washington state (county, city, and district information)
Source 1: https://nces.ed.gov/ccd/schoolsearch/
Source 2: https://www.k12.wa.us/data-reporting/data-portal

One row of data represents the school’s name, school district, county, city, date and time of lead sample collection, and lead concentration. Additional data sets provide demographics of student body at the school and median household income at the county level. 

### Features
Lead concentration, date and time of analysis (day of the week and time of collection), demographics and income.

## Algorithms
Thorough exploratory analysis, cleaning and data aggregation in Excel.

## Tools
* Excel: exploratory data analysis
* Tableau: visualizations and dashboard
