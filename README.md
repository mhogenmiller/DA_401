# DA_401

## Consumers’ Online Experiences with Broadway Musicals: Introducing New Engagement Variables to A Cox Proportional Hazard Model for Show Survival Analysis
 ##

This project brings together data about the attendance rates, number of performances, and search and news history of Broadway musicals to study how they contribute to show lonevity. The novely of the project lies in the fact that no studies have explored the public search behavior in relation to the survival time of shows and analyzed the media resources used here with the samemethods.

### The primary research question in this study is: ###
How do online media outlets responses relate to the longevity of Broadway musicals?  

### There are three main hypotheses in accordance with the research question. ###

Hypothesis 1: Shows with positive Wikipedia synopses will have lower chances of failure than shows with negative or neutral synopses. (Supported) 

Hypothesis 2: The more positive shows’ Google headlines are overall, the less chance of failure the show will have. (Not supported)


Hypothesis 3: Shows with the highest averages during their first weeks on Broadway will have the lowest chances for failure. (Supported)


Hypothesis 4: Shows running during the two months that the Tony nominations are announced and given will have a significantly lower chance of failure than those that are not. (Supported)

Hypothesis 5: Winning Tony awards in major award categories will decrease shows’ hazard risk of failure. (Not Supported)



### Takeaways from this study ###
*      Assessing the public’s interest with shows through search behavior and the materials available to read about shows provided new insights into the importance of such variables in show survival analyses
*     Unlike past studies, this study found that winning Tony awards does not significantly decrease the hazard rate of  musical  failure
*      There are many limitations to data analysis in the field of Broadway both due to limited databases and variety of available variable endpoints


*This portfolio contains* the *code* and *data sets* used to arrive at these conclusions. The code includes five Jupyter Notebooks that each contain the Python code for scraping, cleaning, and calculating Wikipedia, Google headlines, and Google Trends metrics. These metrics were turned into variables and input into a Cox proportional hazard model (Cox PHM), along with other factors such as percent capacity filled and performance trends within shows. The data used to garner these variables (called broadway corgi), as well as the data sets created by the Notebooks, is in the "Data sets" folder in this portfolio. The Broadway_Avg data set is the most important data set in this folder because the proportional hazard model was built on this data. The statistical studies completed using the Cox PHM and other ANOVA and correlational methods was written in R, and the R Markdown file was too large to include in this portfolio.
