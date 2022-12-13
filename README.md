# Our World In Data - Global Mortality Distributions by Age Groups.

Jamie Dormaar

[Lighthouse Labs Private Career College](https://www.lighthouselabs.ca/en).

W4 Project 3 - Data Visualization and Dashboards with Tableau

Dec 9th, 2022

---

## Project Goals

- Download, familiarize, clean, and transform the data provided in the assignment document [(1)](#ref)
- Acquire additional data to provide more detail and potentially unique or surprising insights to the global mortality data mentioned above [(2)](#ref).
- Clean and transform the additional data for Tableau readiness for relationships/joins, and so that it may also convey meaningful information.
- Utilize the newly acquired skills with Tableau software specialized in generating interactive professional visualizations.
- Display successfully discovered insights effectively with highly informative, yet intuitive visualizations.

<!--
(fill in your description and goals here)
-->

## Introduction

I chose option 2.v from the project assignment (see [Workbook](./Workbook/assignment.md) folder) Using the dataset available from the kaggle website "Cause of Death - Our World in Data" by Ivan Chavezi[(1)](#ref). I also wanted to explore more about this dataset other than the already outlined and described 36 causes of death as accumulated sums around the world.

- for example, this data set contains global annual death summations per country for Neoplasms (meaning "new growths" or cancer). Given that cellular neoplasticity occurs when spontaneous mutations of native cells evade the usually effective and redundant "safety checks" of our tissues; it would make sense that the longer an individual survives, the more probable these infrequent mutations occur. I would therefore suspect that if the total number of a country's deaths were distributed across the ages of the life-span, the data would be skewed to the left.
- Additionally regarding the above example: considering that the average human life expectancy is not constant around the globe, it would follow that the regions with shorter average human life expectancies would experience fewer proportionate numbers of annual deaths attributed to neoplasms.
- I was also interested in exploring how the presence/absence of risk factors (capable of increasing average cellular mutation frequencies such as exposure, food/water contaminants, or air quality etc.) would affect the annual mortality rate and if it would also influence the distribution of the age groups affected.

Refer to references numbered [2-8](#ref) for the sources of the additional data sets discussed above.

<!--
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why.

For Option 2, also identify what your data question was, and how you went through the prompts.)
-->

## Process

- Data tables were initially explored, cleaned and transformed in python using pandas module (see details in "[doodle-doc](./Workbook/W4P3_Tableau_doodle_doc.ipynb)" jupyter notebook).
- Cleaned exported csv files were connected to the Tableau Desktop (student access license), and connections between tables were made using both country "Code" and "Year" columns as unique data id keys for the following relationships:
  ![](./Images/tableau_table_connections.png)

<!--
### Step 1)
### Step 2)
## Methods and Procedure:
-->

## Results:

## Procedure:

## Discussion:

<!--
## Challenges
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time?)
-->

<!--


-->
<a name="ref"/>

## References

<!--1. Surname, F. (2021) Title title of titleynesses of article. _Name of Page._ https://urly-ish.ness.business/goods.live.here-->

1. Ivan Chavezi. "Causes of Death - Our World In Data". Retrieved from: [_kaggle_](https://www.kaggle.com/datasets/ivanchvez/causes-of-death-our-world-in-data?resource=download)

2. Hannah Ritchie, Fiona Spooner and Max Roser (2018) - "Causes of death". Published online at _OurWorldInData.org_. Retrieved from: 'https://ourworldindata.org/causes-of-death'. CC BY 4.0

3. Author(s) Unknown. "Causes of death in children under 5, World, 2019.
   _Annual number of deaths by leading causes in children under 5 years old"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/causes-of-death-in-children-under-5'. CC BY 4.0

4. Author(s) Unknown. "Causes of deaths for children between 5 and 14, World, 2019
   _Annual number of deaths – by cause – for children between 5 and 14 years old"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/causes-of-death-in-5-14-year-olds'. CC BY 4.0

5. Author(s) Unknown. "Causes of deaths for 15 to 49 year olds, World, 2019
   _Annual number of deaths – by cause – for people aged 15 to 49 years old"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/causes-of-death-in-15-49-year-olds'. CC BY 4.0

6. Author(s) Unknown. "Causes of deaths for 50 to 69 year olds, World, 2019
   _Annual number of deaths – by cause – for people between 50 and 69 years"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/causes-of-death-in-50-69-year-olds'. CC BY 4.0

7. Author(s) Unknown. "Causes of deaths for people who were 70 years and older, World, 2019
   _Annual number of deaths – by cause – for people who were 70 years and older"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/causes-of-death-in-70-year-olds'. CC BY 4.0

8. Author(s) Unknown. "Number of deaths by risk factor, World, 2019
   _Total annual number of deaths by risk factor, measured across all age groups and both sexes"_. (2019) **OurWorldInData.org**. 'https://ourworldindata.org/grapher/number-of-deaths-by-risk-factor'. CC BY 4.0

9. Naghavi, Mohsen et al. (2017) "[Global, regional, and national age-sex specific mortality for 264 causes of death, 1980–2016: a systematic analysis for the Global Burden of Disease Study 2016](<https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(17)32152-9/fulltext#seccestitle10>)". _The Lancet_, Volume 390, Issue 10100, 1151 - 1210.
