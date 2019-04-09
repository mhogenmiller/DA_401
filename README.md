# DA_401

## Title ##

This project brings together data about the attendance rates, number of performances, and search and news history of Broadway musicals to study how they contribute to show lonevity. The novely of the project lies in the fact that no studies have explored the public search behavior in relation to the survival time of shows and analyzed the media resources used here with the samemethods.

*The primary research question in this study is:* 
How do online media outlets responses relate to the longevity of Broadway musicals?  

There are three main hypotheses in accordance with the research question.

1 Positive synopses will correspond overwhelmingly to shows that have longer runs.

2 The more positive a shows Google headlines are overall, the  longer survival time the show will have.

3 Shows with the highest averages during their first weeks and post tony winning periods will have longer longevities

*Results* of this study_____________________

*Further Implications*_______________________

*This portfolio contains* the *code* and *data sets* used to arrive at these conclusions. The code includes five Jupyter Notebooks that each contain the Python code for scraping, cleaning, and calculating Wikipedia, Google headlines, and Google Trends metrics. These metrics were turned into variables and input into a Cox proportional hazard model (Cox PHM), along with other factors such as percent capacity filled and performance trends within shows. The data used to garner these variables (called broadway corgi), as well as the data sets created by the Notebooks, is in the "Data sets" folder in this portfolio. The Broadway_Avg data set is the most important data set in this folder because the proportional hazard model was built on this data. The statistical studies completed using the Cox PHM and other ANOVA and correlational methods was written in R, and the R Markdown file was too large to include in this portfolio.
