# Project Name
> Lending Club Case Study (loan risk analysis)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Conclusions](#conclusions)


## General Information
- Prepare a driving factor for risk analysis for a finance company. 
- Business wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
- Using loan.csv dataset from US of year 2007-2011
- Understand the dataset and clean for analysis.
- Missing columns can be filled with appropriate calculated values. 

## Technologies Used
- Python - version 3.10.8
- Pandas - version 2.2.1
- numpy - version 1.26.4
- Matplotlib - version 3.8.3
- seaborn - version 0.13.2

## Acknowledgements
-- This project is developed as an assignment give by IIIT, Bangalore. 


## Conclusions
- Variables which are impacting the defaulter and can help with risk analysis:
-- term: Short duration loan with less amount are spiked with defaulter
-- grade : specific graded has more defaulter
-- funded_amnt_inv and annual_inc are depended on each other 
-- dti_range : higher range for more defaulters count. but can see same trade for valid payers too)
-- purpose: mostly for debt consolidation
-- int_rate : Higher for defaulters
-- issue_d : For year 2010, 2011 (just after recession in US) we can see spike for defaulters and more loan count.


## Contact
Created by [@ritesh9835] & [] - feel free to contact us!