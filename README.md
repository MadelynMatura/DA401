# DA401
# Overview of the Project


Although universal healthcare (UHC) has recently become a highly politicized topic within the U.S., there has been a longstanding global debate over the efficacy of UHC systems and government roles within these systems. In recent years, many countries have shifted towards policies that support universal healthcare coverage.This study aims to create a generalizable model that identifies on a global scale how population health is affected by government healthcare spending and healthcare system type. Limited attempts have been made to include low, middle and high income countries together in a study like this. Based on evidence mentioned above, I have hypothesized that public health will increase with government health care spending per capita. In addition, countries with UHC legislation will have better public health outcomes in comparison to countries without passed UHC policies. Public health outcomes have been defined as mortality rate and disease burden. Because this study includes all regions and country income levels, I anticipate that there will be some level of discrepancy in health outcome trends within countries of certain regions and income groups. 


# The Data

The independent variable for this study was government healthcare spending per capita in US dollars. The dependent variables were disease burden and mortality rate per each individual country. Disease burden and mortality rates were also compared between countries with and without universal healthcare legislation. The World Health Organization health indicators data set, which is publically available, was used to locate the data for this study (The Global Health Observatory, n.d.). This dataset contains incidence numbers of particular diseases for each country, information on government healthcare expenditures, and healthcare system type data. Health indicator data was pulled into R via the “WHO” package that acts as a client for the World Health Organization API (WHO, 2019). Additional datasets that contained information on pneumonia (Dadonaite & Roser, 2019; Global Burden, 2018) and malaria (Roser & Ritchie, 2018; Global Burden, 2018) were used to supplement the WHO dataset. There were discrepancies in these additional datasets as to how some countries were named. For example, if a country was named “United States of America” in the WHO indicators dataset, it was changed manually in the pneumonia and malaria dataset from “United States” to “United States of America”. Lastly, an individual WHO dataset not included in the WHO’s Global Health Observatory was used to query data on congenital birth defects (WHO-MCEE, 2018). All data sets and code can be found in Appendix A. 



# The Code
The code created for this project takes advantage of the WHO API, using the WHO package in R created by github user expersso. Data wrangling, analyses and visualization has been completed in R.  


# Data Citations

Dadonaite, B. & Roser, M. (2019, Nov). Pneumonia. Our World in Data. Retrieved April 10, 2020 from https://ourworldindata.org/pneumonia#citation 

Global Burden of Disease Study 2017 (GBD 2017) Results. (2018). Global Burden of Disease Collaborative Network. Institute for Health Metrics and Evaluation. Retrieved April 2, 2020 from http://ghdx.healthdata.org/gbd-results-tool

The Global Health Observatory. (n.d.) World Health Organization. Retrieved March 03, 2020,from https://www.who.int/data/gho/data/indicators

Roser, M. & Ritchie H. (2019, October). Malaria. Our World in Data. Retrieved April 3, 2020		 from https://ourworldindata.org/malaria#all-charts-preview

WHO-MCEE estimates for child causes of death 2000-2016. (2018, Feb). The World Health	Organization. Retrieved April 1, 2020 from https://www.who.int/healthinfo/global_burden_disease/estimates/en/index3.html




