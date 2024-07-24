Collaboration Network Analysis
================

## Project Overview

This project aims to analyze the impcat of behavior adaptation by immune status for COVID-19  based on South Korea's data. 
The data were obtained from Our World in Data (https://ourworldindata.org/coronavirus/country/south-korea) 
The project was done under the supervision of Dr. Youngji Jo and incolaboration with Prof. Bruno Buonomo and Dr. Jaehun Jung.


#### Methods 
We used a compartmental model, that classifies the overall transmission into two parts: transmission occuring among parially immune (vaccinated or habve prior infection) individuals and that occuring among
susceptible  ones. The vaccination and testing rates are influenced by human behavior which intrun influenced by level of prevalence and severity of the disease.
The model is ruled by non-linear ordinary differential equations. We varyed the balues of several behavioral parameters to see their impact on overall burdon of the disease.  


### Numerical simulation

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-pkg_igraph" class="csl-entry">

Csárdi, G., T. Nepusz, V. Traag, S. Horvát, D. Noom, and K. Müller.
2024. *<span class="nocase">igraph</span>: Network Analysis and
Visualization in R*. R Studio.
<https://CRAN.R-project.org/package=igraph>.

</div>

<div id="ref-liu2018covariate" class="csl-entry">

Liu, Qi, Chun Li, Valentine Wanga, and Bryan E. Shepherd. 2018.
“Covariate-Adjusted Spearman’s Rank Correlation with Probability-Scale
Residuals.” *Biometrics* 74 (2): 595–605.

</div>

<div id="ref-tu2024between" class="csl-entry">

Tu, Shengxin, Chun Li, and Bryan E. Shepherd. 2024. *Between- and
Within-Cluster Spearman Rank*. Vanderbilt University Medical Center.
<https://arxiv.org/pdf/2402.11341>.

</div>

<div id="ref-tu2023rank" class="csl-entry">

Tu, Shengxin, Chun Li, Donglin Zeng, and Bryan E. Shepherd. 2023. “Rank
Intraclass Correlation for Clustered Data.” *Statistics in Medicine* 42
(24): 4333–48.

</div>

<div id="ref-yuan2023generating" class="csl-entry">

Yuan, Yelie, Tiandong Wang, Jun Yan, and Panpan Zhang. 2023. “Generating
General Preferential Attachment Networks with R Package Wdnet.” *Journal
of Data Science* 21 (3): 538–56.

</div>

<div id="ref-yuan2021assortativity" class="csl-entry">

Yuan, Yelie, Jun Yan, and Panpan Zhang. 2021. “Assortativity Measures
for Weighted and Directed Networks.” *Journal of Complex Networks* 9
(2): cnab017.

</div>

</div>
