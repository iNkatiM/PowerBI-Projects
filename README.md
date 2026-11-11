## Overwiev
A three-page Power BI report exploring demographic and socioeconomic indicators across countries. The project was created as part of practical BI training and demonstrates data preparation, multi-table reporting, georgraphic visualizations and interactive exploration.

Tools: Microsoft Power BI Desktop, Power Query, built-in Power BI visuals

Project type: Academic / portfolio project

## Analytical Objectives
* Compare countries by birth and death rates.
* Examine fertility alongside national education expenditure.
* Summarize median age and unempoyment across regions.
* Visualize military expenditure and obesity prevalence geographically.
* Explore the relationship between median age and fertility.

## Datasets
The Power BI model contains four tables:
| Table     | Fields used in the report|
| ------------- |:------------------:|
| people_and_society     | Country, region, median age, birth rate, death rate, life expectancy, fertility rate, obesity rate|
| education     |Education expenditure as a percentage of GDP  |
| military |Military expenditure as a percentage of GDP          |
| unemployment     | Unemployment rate|

## Data Preparation and Modelling
The training task included:
* Impoving TSV and CSV data into Power BI.
* Fixing malformed numerical values and inconsistent region names.
* Selecting and renaming relevant columns.
* Integrating country-level indicators, including fuzzy country-name matching.
* Reviewing blank categories caused by unmatched or missing records.
The report contrains field form all four tables. See the `.pbix` file for the model and applied transformations.

## Report Pages
1. Demographic Overview
Four summary cards display county count, median age and life-expectancy extrema. Bar charts compare countries by birth and death rates and juxtapose fertility and education expenditure. A table summarizes median age and unemployment by region.
<img width="1771" height="997" alt="image" src="https://github.com/user-attachments/assets/dea0522b-5267-422a-b8df-c36c40e94e54" />
2. Geographic Indicators
A bubble map shows military expenditure by country; a filled map represents obesity prevalence. A region slicer supports interactive exploraion.
<img width="1668" height="947" alt="image" src="https://github.com/user-attachments/assets/8fcdbe0e-34cc-4cbb-b991-619be6155da6" />
3. Median Age vs. Fertility
A scatter plot compares median age and fertility rate across countries to explore their association.
<img width="1217" height="771" alt="image" src="https://github.com/user-attachments/assets/4e17e5e8-a429-454a-a5b6-d270e611f5ad" />

## Conclusions
* The analysis demonstrates significant demographic and socio-economic differences in 190 countries.
* The most obvious conclusion is the negative relationship between average age and fertility rate. Regional comparisons also reveal differences in population age, unemployment, life expectancy, and government spending.
* By integrating four datasets and developing interactive Power BI visualizations, the project allows comparisons across countries and regions and provides a basis for further demographic analysis.

## Limitations
- Country names and unclear matching can lead to inappropriate or incorrectly matched strings.
- Missing values and empty categories may affect the comparison results.
- The initial figures can be obtained for different accounting years.
- The results are descriptive and should not be interpreted as causal relationships.
- This training report uses built-in Power BI features and does not require custom DAX development.
