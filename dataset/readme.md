# Share of adults who smoke - Data package

This data package contains the data that powers the chart ["Share of adults who smoke"](https://ourworldindata.org/grapher/share-of-adults-who-smoke?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on March 04, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Prevalence of current tobacco use (% of adults)
Last updated: January 24, 2025  
Next update: January 2026  
Date range: 2000–2020  
Unit: % of adults  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization (via World Bank) (2025) – processed by Our World in Data

#### Full citation
World Health Organization (via World Bank) (2025) – processed by Our World in Data. “Prevalence of current tobacco use (% of adults)” [dataset]. World Health Organization (via World Bank), “World Development Indicators” [original data].
Source: World Health Organization (via World Bank) (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization (via World Bank) (2025)?
The percentage of the population ages 15 years and over who currently use any tobacco product (smoked and/or smokeless tobacco) on a daily or non-daily basis. Tobacco products include cigarettes, pipes, cigars, cigarillos, waterpipes (hookah, shisha), bidis, kretek, heated tobacco products, and all forms of smokeless (oral and nasal) tobacco. Tobacco products exclude e-cigarettes (which do not contain tobacco), “e-cigars”, “e-hookahs”, JUUL and “e-pipes”. The rates are age-standardized to the WHO Standard Population.

Limitations and exceptions: Estimates for countries with irregular surveys or many data gaps have large uncertainty ranges, and such results should be interpreted with caution.

Statistical concept and methodology: The limited availability of data on health status is a major constraint in assessing the health situation in developing countries. Surveillance data are lacking for many major public health concerns. Estimates of prevalence and incidence are available for some diseases but are often unreliable and incomplete. National health authorities differ widely in capacity and willingness to collect or report information. To compensate for this and improve reliability and international comparability, the World Health Organization (WHO) prepares estimates in accordance with epidemiological models and statistical standards.

A statistical model based on a Bayesian negative binomial meta-regression is used to model prevalence of current tobacco use for each country, separately for men and women.

The model has two main components: (a) adjusting for missing indicators and age groups, and (b) generating an estimate of trends over time as well as the 95% credible interval around the estimate.
Depending on the completeness/comprehensiveness of survey data from a particular country, the model at times makes use of data from other countries to fill information gaps. When a country has fewer than two nationally representative population-based surveys in different years, no attempt is made to fill data gaps and no estimates are calculated. To fill data gaps, information is “borrowed” from countries in the same UN subregion. The resulting trend lines are used to derive estimates for single years, so that a number can be reported even if the country did not run a survey in that year. In order to make the results comparable between countries, the prevalence rates are age-standardized to the WHO Standard Population. A full description of the method is available as a peer-reviewed article in The Lancet, volume 385, No. 9972, p966–976 (2015).

### Source

#### World Health Organization (via World Bank) – World Development Indicators
Retrieved on: 2025-01-24  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


## Dataset

The COVID datasets are large and stored externally on Kaggle.

You can download them here:

https://www.kaggle.com/datasets/utsavadhikari/covid-dataset-for-research

**Note:** Please download these files separately before running the code.
