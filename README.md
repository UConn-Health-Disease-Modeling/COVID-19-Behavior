# COVID-19-model-with-behavior-adaptation
## Project Overview
This repository shares python codes for behavioral COVID-19 model. A compartmental model is used to reperesnet the transmission of the disease 
in the population. The total population is divided in to two based on thier immune status: susceptible and partially-immune (vaccinated or recovered from the disease). People in this group are further sub-divided into 15 compartments based on their disease or vaccination status. In this model the vaccination and testing rate are dependent on the disease status (prevalence and severity) in the population and takes into account the differences risk perception based on immune status. This project aims to analyze the effect of behavior adaptation on care-seeking  and transmission of COVID-19. 

## Content
The present repository contains
###  Codes
- fitting_to_cumm1-BB.ipynb: estimates some of the parameters used in the model in the least square sense.
- Contorplots_new_fit_BB.ipynb: is used to produce a contour plot for peak of active cases with varying information coverage with information delay, reactivity to prevalence and reactivity to severity
- Reduced_reactivity_effect_New_BB.ipynb: is used to simulate active cases for different values of reduced reactivity to information by immune individuals
- Region_stability_New_BB.ipynb: is used to show region of stability of the disease-free equilibrium in the F10, F20 plane. Where F10 and F20 are mandatory primary series vaccination and booster vaccination rates, respectively.
- Role_of_parameters_New_fitting_New_BB.ipynb: is used to simulate the active cases when behavioral effect is considered in the model and not.
- Behavioral_change_param_New_BB.ipynb: is used to simulate the dynamics of testing rate, vaccination rate and active cases under different risk perception to prevalence and severity.
- Tornado_Sensitivity.ipynb: is used to show the sensitivity of parameters to cumulative incidence
### Data

The model is calibrated to the cumulative COVID-19 cases, vaccination and death in South Korea from  February 01, 2022 to May 31, 2022 obtained from https://ourworldindata.org/coronavirus/country/south-korea. The data is provided in 
- selected_Korean_data.csv
- Omicron_wave_Jan_May.csv
- hospitalization.csv
- cum_cases.csv
- 7day_rolling_Ave.csv
- cum_vacc.csv
