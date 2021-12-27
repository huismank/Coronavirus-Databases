# Coronavirus-Databases
This repository contains script files I wrote (working with Professor Whitt Kilburn of Grand Valley State University) to create a database of coronvarius, and political variables by state. The original repository used to create this database is currently private. You can message me for access to it. The data currently only extends through the summer of 2021.

# state_covid.csv
state level covid data, politics, economic characteristics

## Codebook

## Coronavirus Cases and Deaths Data

**casesyear-month-day**: These variables give the total number of recorded covid cases in a state in a given month. The year, month and date are recorded in the individual variable names.

**deathsyear-month-day**: These variables give the total number of recorded Covid-19 deaths in a state in a given month. The year, month and date are recorded in the individual variable names.

Source: "The New York Times. (2021). Coronavirus (Covid-19) Data from The New York Times, based on reports from state and local health agencies. Retrieved June 6, 2020 from https://github.com/nytimes/covid-19-data." 
&nbsp;

&nbsp;

## 2016 and 2020 Presidential Election Data

**2016CANDIDATENAME**: These variables give the total number of votes a candidate recieved in a state in the 2016 election.

**2020CANDIDATENAME**: These variables give the total number of votes a candidate recieved in a state in the 2020 election.

Source: MIT County Level Presidential Results 2000-2020
MIT Election Data and Science Lab, 2018, "County Presidential Election Returns 2000-2020", https://doi.org/10.7910/DVN/VOQCHQ, Harvard Dataverse, V9, UNF:6:qSwUYo7FKxI6vd/3Xev2Ng== [fileUNF]
&nbsp;

&nbsp;

## State Social Distancing Policy Indicators:

**Stay At Home Order as ofyear-month-day**: These variables describe the status of stay at home orders in a state on a given date indicated by the title.

**Reopening Statusyear-month-day**: These variables describe the status of reopening in a state on a given date indicated by the title. Reopening implies that Covid-19 restrictions generally have been lifted.

**Emergency Declerationyear-month-day**: These variables describe whether a Covid-19 emergency declaration was in place on the date indicated by the title.

**Non-Essential Business Closures Year-Month-Day**: These variables indicate the status of non-essential business closure policies as of the date.

**Restaurant Limits Year-Month-Day**: Indicates what policies limiting restaurant service were in place as of the date.

**Mandatory Quarantine For Travelers Year-Month-Day**: Indicate whether quarantine was mandatory for travelers as of the date.

**Large Gatherings Ban Year-Month-Day**: Describe what policies limiting, or banning large gatherings were in place as of the date.

**Face Covering Requirment Year-Month-Day**: Describe face covering policies as of the date.

**School Closures  Year-Month-Day**: Describe school closure policies as of the date.

Source: KFF’s State Health Facts. [Data Source: https://www.kff.org/report-section/state-covid-19-data-and-policy-actions-sources/] “State Actions to Mitigate the Spread of COVID-19”. 2021. Retrieved from https://github.com/KFFData/COVID-19-Data/tree/kff_master/State%20Policy%20Actions/State%20Social%20Distancing%20Actions.
&nbsp;

&nbsp;

## Census Bureau Population Demographic and Geographic Divisioning Data

**REGION**: Census Region code

**DIVISION**: Census Division code

**CENSUS2010POP**: 4/1/2010 resident total Census 2010 population

**POPESTIMATE2010**: 7/1/2010 resident total population estimate

**POPESTIMATE2011**: 7/1/2011 resident total population estimate

**POPESTIMATE2012**: 7/1/2012 resident total population estimate

**POPESTIMATE2013**: 7/1/2013 resident total population estimate

**POPESTIMATE2014**: 7/1/2014 resident total population estimate

**POPESTIMATE2015**: 7/1/2015 resident total population estimate

**POPESTIMATE2016**: 7/1/2016 resident total population estimate

**POPESTIMATE2017**: 7/1/2017 resident total population estimate

**POPESTIMATE2018**: 7/1/2018 resident total population estimate

**POPESTIMATE2019**: 7/1/2019 resident total population estimate

**NPOPCHG_2010**: Numeric change in resident total population 4/1/2010 to 7/1/2010

**NPOPCHG_2011**: Numeric change in resident total population 7/1/2010 to 7/1/2011

**NPOPCHG_2012**: Numeric change in resident total population 7/1/2011 to 7/1/2012

**NPOPCHG_2013**: Numeric change in resident total population 7/1/2012 to 7/1/2013

**NPOPCHG_2014**: Numeric change in resident total population 7/1/2013 to 7/1/2014

**NPOPCHG_2015**: Numeric change in resident total population 7/1/2014 to 7/1/2015

**NPOPCHG_2016**: Numeric change in resident total population 7/1/2015 to 7/1/2016

**NPOPCHG_2017**: Numeric change in resident total population 7/1/2016 to 7/1/2017

**NPOPCHG_2018**: Numeric change in resident total population 7/1/2017 to 7/1/2018

**NPOPCHG_2019**: Numeric change in resident total population 7/1/2018 to 7/1/2019

**BIRTHS2010**: Births in period 4/1/2010 to 6/30/2010

**BIRTHS2011**: Births in period 7/1/2010 to 6/30/2011

**BIRTHS2012**: Births in period 7/1/2011 to 6/30/2012

**BIRTHS2013**: Births in period 7/1/2012 to 6/30/2013

**BIRTHS2014**: Births in period 7/1/2013 to 6/30/2014

**BIRTHS2015**: Births in period 7/1/2014 to 6/30/2015

**BIRTHS2016**: Births in period 7/1/2015 to 6/30/2016

**BIRTHS2017**: Births in period 7/1/2016 to 6/30/2017

**BIRTHS2018**: Births in period 7/1/2017 to 6/30/2018

**BIRTHS2019**: Births in period 7/1/2018 to 6/30/2019

**DEATHS2010**: Deaths in period 4/1/2010 to 6/30/2010

**DEATHS2011**: Deaths in period 7/1/2010 to 6/30/2011

**DEATHS2012**: Deaths in period 7/1/2011 to 6/30/2012

**DEATHS2013**: Deaths in period 7/1/2012 to 6/30/2013

**DEATHS2014**: Deaths in period 7/1/2013 to 6/30/2014

**DEATHS2015**: Deaths in period 7/1/2014 to 6/30/2015

**DEATHS2016**: Deaths in period 7/1/2015 to 6/30/2016

**DEATHS2017**: Deaths in period 7/1/2016 to 6/30/2017

**DEATHS2018**: Deaths in period 7/1/2017 to 6/30/2018

**DEATHS2019**: Deaths in period 7/1/2018 to 6/30/2019

(Note: All code descriptions taken from: https://www2.census.gov/programs-surveys/popest/technical-documentation/file-layouts/2010-2019/nst-est2019-alldata.pdf. **The birth, death, and population change measures in 2010 are recorded over the course of three months, whereas the same measures for all other years are taken during the course of an entire year.**).

Source: U.S. Census Bureau (2019). "Annual Population Estimates, Estimated Components of Resident Population
Change, and Rates of the Components of Resident Population Change for the United States, States, and
Puerto Rico: April 1, 2010 to July 1, 2019." Retrieved from [http://www2.census.gov/programs-surveys/popest/datasets/2010-2019/national/totals/nst-est2019-alldata.csv].
&nbsp;

&nbsp;

## State GDP and Personal Income Per Capita

**@year_state_GDP_**: State GDP in the year indicated by the title. According to source notes: "Gross Domestic Product (GDP) is in millions of current dollars (not adjusted for inflation)."

**year_state_personal_income_per_capita**: Personal income per capita in the year indicated by the title. According to source notes: "“Per capita personal income is total personal income divided by total midyear population. BEA state per capita personal income statistics are calculated using Census Bureau midyear population estimates. These annual midyear estimates are based on the 2010 census."

Source: Bureau of Economic Analysis. (2021). Regional Data: GDP and Personal Income [Data file]. Retrieved from https://apps.bea.gov/itable/iTable.cfm?ReqID=70&step=1. Select total industry annual GDP for all states from 1997 to 2020.

Source notes: Data for GDP was obtained using this BEA data tool for regional data: https://apps.bea.gov/itable/iTable.cfm?ReqID=70&step=1. The category "Annual GDP by state" was then selected, and then the sub-category "GDP in current dollars". "NAICS (1997-forward)" was selected as the industrial classification. All 50 states were selected for area, and GDP from all industries was selected as the statistic, with the unit of measurement set at levels. The time period selected was 1997 to 2020. The table produced was exported and uploaded to this repository as “state_gdp.sav”.

Data for personal income was taken using the same BEA data tool: https://apps.bea.gov/itable/iTable.cfm?ReqID=70&step=1, selecting Annual personal income and employment by state, then selecting the category entitled “Personal Income Summary: Personal Income, Population, Per Capita Personal Income”, selecting SAINC1 as the table ID, then selecting "per capita personal income (dollars)" as the statistic. All 50 states are selected as the area, and 2010-2020 for the time period, with the unit of measurement set at levels. The table produced was exported and uploaded to this repository as "state_per_capita_income.csv". 
&nbsp;

&nbsp;

## Drug and Alcohol Induced Deaths

**drug_alcohol_deaths_in_year**: The number of recorded drug and alcohol deaths during the year in the variable title. 

Source: Centers for Disease Control and Prevention, National Center for Health Statistics. Underlying Cause of Death
1999-2019 on CDC WONDER Online Database, released in 2020. Data are from the Multiple Cause of Death Files, 1999-2019, as
compiled from data provided by the 57 vital statistics jurisdictions through the Vital Statistics Cooperative Program. Accessed"
at http://wonder.cdc.gov/ucd-icd10.html on Jun 28, 2021.

Source Notes: The table produced was uploaded to the repository as drug_alcohol_deaths.csv, and formatted for use within github. See the commit history and select the orginal version of this CSV file at the bottom of the table for information about the query used.

For information on what the HHS and CDC define as drug or alcohol induced deaths, see pages 20 and 21 of this report: https://wonder.cdc.gov/wonder/help/CMF/TechnicalAppendix1999.pdf

&nbsp;

&nbsp;

## Unemployment

**Month Year_Unemployed**: Gives the seasonally adjusted percent unemployed rate as of the date in the title. 

Source: “KFF’s State Health Facts. [Data Source: Bureau of Labor Statistics (BLS), Regional and State Employment and Unemployment (Monthly), Civilian labor force and unemployment by state and selected area, seasonally adjusted.] “Unemployment Rate (Seasonally Adjusted)”. Retrieved from https://www.kff.org/state-category/demographics-and-the-economy/unemployment/

Source notes: "The unemployment rate measures unemployment within the civilian non-institutional population aged 16 years and older." https://www.kff.org/other/state-indicator/unemployment-rate/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D
&nbsp;

&nbsp;

## State Government Liberalism, and party proportion indicators

**policysociallib_est**: Estimated social policy liberalism as determined by the models of Caughey et al.

**policyeconlib_est**: Estimated economic policy liberalism as determined by the models of Caughey et al.

**masssociallib_est**: Estimated mass social liberalism as determined by the models of Caughey et al.

**masseconlib_est**: Estimated mass economic liberalism as determined by the models of Caughey et al.

**dempid_est**: Estimated proportion of Democratic identifiers in the public.

**reppid_est**: Estimated proportion of Republican identifiers in the public.

Source: Caughey, Devin; Warshaw, Christopher, 2017, "caughey_warshaw_summary.tab", Replication Data for: Policy Preferences and Policy Change: Dynamic Responsiveness in the American States, 1936–2014, https://doi.org/10.7910/DVN/K3QWZW/5DVZFO, Harvard Dataverse, V2, UNF:6:gclIUlb4vZOuKOkJEYoI9g== [fileUNF]
&nbsp;

&nbsp;

## Self Reported Obesity

**2019_self_reported_obesity**: Percentage of people self reporting as obese in 2019.

**obesity_variable_CI**: The 95% confidence interval of 2019_self_reported_obesity.


Source: Centers for Disease Control and Prevention's Behavioral Risk Factor Surveillance System. (2021, March 31). Adult Obesity Prevalence Maps. Centers for Disease Control and Prevention. http://www.cdc.gov/obesity/data/prevalence-maps.html. 
This data was scraped manually from a CDC website table entitled “Prevalence of Self-Reported Obesity by State and Territory, BRFSS, 2019”, which is based on data from the Behavioral Risk Factor Surveillance System.
&nbsp;

&nbsp;

## Number of Women State Legislators and State Legislator Totals

**2019 % of women in total legislature**: The percentage of woman in both houses of state legislature's as of 2019.

**Total women in senate**: Total women in the senate as of 2019.

**Total Senate**: Total number of senators as of 2019.

**Total Women in House**: Total women in the house as of 2019.

**Total House**: Total members of the house as of 2019.

**Total women in legislature**: Total women house representatives as of 2019

**Total Legis.**: Total number of people in the legislature.

Source: Center for American Women and Politics, Eagleton Institute of Politics, &amp; Rutgers, The State University of New Jersey (Eds.). (2021, June 24). Women in State Legislatures 2021. Cawp. https://cawp.rutgers.edu/women-state-legislature-2021. The data was scraped manually from the cawp linked webpage from a table titled "Women in State Legislatures 2021".
&nbsp;

&nbsp;

## Poverty Rates

**% of total population below poverty line**: Percentage of population living below the poverty line as defined by the U.S Census Bureau poverty threshold. "The U.S. Census Bureau's poverty threshold for a family with two adults and one child was $20,578 in 2019."

Source: KFF's State Health Facts. (2020, October 23). Poverty Rate by Race/Ethnicity. Kaiser Family Foundation https://www.kff.org/other/state-indicator/poverty-rate-by-raceethnicity/?currentTimeframe=0&amp;sortModel=%7B%22colId%22%3A%22Location%22%2C%22sort%22%3A%22asc%22%7D#notes. "KFF estimates based on the 2008-2019 American Community Survey, 1-Year Estimates." Data was taken downloaded from the webpage tool.

&nbsp;

## State Expenditure

**Per Capita State Spending-2019**: State spending per capita as of 2019.

Source: KFF's State Health Facts. (2021, April 7). Total State Expenditures per Capita. Kaiser Family Foundation. https://www.kff.org/other/state-indicator/per-capita-state-spending/?currentTimeframe=0&amp;sortModel=%7B%22colId%22%3A%22Location%22%2C%22sort%22%3A%22asc%22%7D. Data Source: KFF adjustments to data collected in the National Association of State Budget Officers (NASBO) State Expenditure Report Fiscal 2018-2020, November 2020 and 2019 civilian population estimates from the U.S. Census Bureau.
&nbsp;
&nbsp;

&nbsp;

## Heart Disease

**Heart Disease Death Rate Per 100,000**: The Rate of heart disease per 100,000 people in a state.

Source: KFF's State Health Facts. (2021, March 16). Number of Heart Disease Deaths per 100,000 Population. Kaiser Family Foundation. https://www.kff.org/other/state-indicator/number-of-deaths-due-to-diseases-of-the-heart-per-100000-population/?currentTimeframe=0&amp;selectedRows=%7B%22states%22%3A%7B%22all%22%3A%7B%7D%7D%7D&amp;sortModel=%7B%22colId%22%3A%22Location%22%2C%22sort%22%3A%22asc%22%7D. 
KFF Data Sources:  Centers for Disease Control and Prevention, National Center for Health Statistics. Underlying Cause of Death 1999-2019 on CDC WONDER Online Database, released 2021. Data are from the Multiple Cause of Death Files, 1999-2019, as compiled from data provided by the 57 vital statistics jurisdictions through the Vital Statistics Cooperative Program. Accessed at http://wonder.cdc.gov/ucd-icd10.html on February 24, 2021.
&nbsp;

&nbsp;

## Life Expectancy

**Life Expectancy at Birth in years as of 2018**: The Rate of heart disease per 100,000 people in a state.

Source: KFF's State Health Facts. (2021, June 22). Life Expectancy at Birth (in years). Kaiser Family Foundation. https://www.kff.org/other/state-indicator/life-expectancy/?currentTimeframe=0&selectedRows=%7B%22states%22:%7B%22all%22:%7B%7D%7D%7D&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D. Data Source: Arias E, Bastian B, Xu JQ, Tejada-Vera B. U.S. state life tables, 2018. National Vital Statistics Reports; vol 70 no 1. National Center for Health Statistics. 2021, accessed here.
&nbsp;

&nbsp;

## Congressional Cooperative Election Survey Response Averages by State 

#### Note for later review: This codebook will have to be updated when the full documentation for the most recent CCES survey is released. Currently, these descriptions of the questions are based on this reference survey question file: https://dataverse.harvard.edu/file.xhtml?fileId=4462965&version=1.0. 

#### Note: These variables take the average responses of all CCES respondents within a state to the questions indicated in the variable. These are averages of dummy variables with 1 set to indicate that the respondent replied yes to what is described in the variable titles, and 2 set to indicate they replied no, or did not select the option. Averages closer to one indicate that a greater proportion of respondents within a state replied yes to the question, or selected the question answer described. Average values closer to two indicate the opposite.

**has_had_covid**: The average value of a dummy variable for all respondents within a state who indicated they have had covid in the 2020 CCES survey. 1 indicates that survey respondents said they have had covid. 2 indicates they said they had not. An average number closer to one represents a greater proportion of respondents within a state who responded they have had Covid-19.

**family_member_has_had_covid**: Indicator of whether respondents within a state have a family member who has had Covid-19.

**friend_has_had_covid**: Indicator of whether respondents within a state have a friend who has had Covid-19.

**co_worker_has_had_covid**: Indicator of whether respondents within a state have a co-worker who has had Covid-19.

**know_no_one_diagnosed**: Indicator of whether respondents within a state know no one who has been diagnosed with Covid-19.

**hours_reduced**: Indicator of whether respondents within a state have had their hours reduced due to the pandemic.

**hours_reduced_but_restored**: Indicator of whether respondents within a state have had their hours reduced but restored due to the pandemic.

**temporarily_laid_off**: Indicator of whether respondents within a state were temporarily laid off due to the pandemic.

**temporarily_laid_off_but_rehired**: Indicator of whether respondents within a state were temporarily laid off, but rehired due to the pandemic.

**multiple_jobs_lost_one**: Indicator of whether respondents within a state had multiple jobs and lost one due to the pandemic.

**lost_job**: Indicator of whether respondents within a state lost their job due to the pandemic.

**was_not_working**: Indicator of whether respondents within a state were not working prior to the pandemic.

**hours_increased**: Indicator of whether respondents within a state have had their hours increased due to the pandemic.

**additional_job**: Indicator of whether respondents within a state got an additional job due to the pandemic.

**no_change_in_work**: Indicator of whether respondents within a state have had no change in work due to the pandemic

**support_CARES**: Indicator of whether respondents within a state support the federal CARES act.

**support_HEROES**: Indicator of whether respondents within a state support the federal HEROES act.


Source: Schaffner, Brian; Ansolabehere, Stephen; Luks, Sam, 2021, "Cooperative Election Study Common Content, 2020", https://doi.org/10.7910/DVN/E9N6PH, Harvard Dataverse, V1; CCES20_Common_OUTPUT.csv [fileName]
&nbsp;

&nbsp;

## Vaccination By State

**Total Doses Delivered**: Total doses of Covid 19 vaccine delivered to a state.

**Total Doses Administered by State where Administered**: Total doses of Covid 19 vaccine administered in a state.

**Percent of Total Pop with at least One Dose by State of Residence**: Percentage of total state population with at least one dose of Covid 19 vaccine.

**Percent of 18+ Pop with at least One Dose by State of Residence**: See previous

**Percent of Total Pop Fully Vaccinated by State of Residence**: Percentage of total state population fully vaccinated for Covid 19. 

**Percent of 18+ Pop Fully Vaccinated by State of Residence**: See previous

**Total Number of Pfizer doses adminstered**: Total number of Pfizer doses administered in a state. 

**Total Number of Moderna doses administered**: See previous

**Total Number of Janssen doses administered**: See previous


Source: Centers for Disease Control and Prevention. (2021, August 1). COVID-19 Vaccinations in the United States. Data Table for COVID-19 Vaccinations in the United States. https://covid.cdc.gov/covid-data-tracker/#vaccinations. Retrieved August 2, 2021.
&nbsp;

&nbsp;


DECEMBER EDIT: 

Vaccinations by month:
https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc
