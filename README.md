# covid-19_un
Analyzing correlations between UN country-level statistics and COVID-19 deaths per country

## Table of Contents
1. [Requirements](#requirements)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Requirements <a name="requirements"></a>
* Libraries included in the Anaconda distribution of Python
* Python versions 3.*.

## Project Motivation <a name="motivation"></a>
Some countries are doing better than others at controlling the coronavirus and the deaths caused by it. As the pandemic continues to severely impact the lives of basically everyone, we grow more and more curious to understand why. 

Using data on COVID-19 deaths, and country data from the UN, the goal of the analysis was to answer the following questions:

1. Did it help countries to have more time to prepare?
2. What country-level stats correlate the most with the number of deaths?
3. What country-level stats correlate the most with the number of deaths per capita?

## File Descriptions <a name="files"></a>
* COVID-19 x UN stats analysis.ipynb: 
  * Notebook containing the analysis
* country_profile_variables.csv:
  * Some UN country-level statistics
* country_matching.csv:
  * Lookup table for country names
  
The data regarding COVID-19 deaths is obtained by the code directly from Johns Hopkins repository, [here](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv).

## Results <a name="results"></a>
The main findings of the code can be found at the post available [here](https://medium.com/@marcelo.cardoso.work/more-doctors-more-covid-19-deaths-no-11c19eec4439).

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
Credit goes to [Johns Hopkins](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv) for the data on COVID-19, and the UN data was found in SRK’s Kaggle dataset [here](https://www.kaggle.com/sudalairajkumar/undata-country-profiles#country_profile_variables.csv). You can find the Licensing for the data and other descriptive information at those links. Additional credits to jjrunner for the README template found [here](https://github.com/jjrunner/stackoverflow). Otherwise, feel free to use the code here as you would like!



