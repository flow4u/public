

# [Covid_19.ipynb](https://github.com/flow4u/public/blob/master/Covid_19.ipynb)

**Update**
- 2020-03-11: Countries added, political incorrect country names removed
- 2020-03-10: Special buttons added: Toggle log/normal, toggle selection of countries per continent  
- 2020-03-10: Additional countries added, all Matlibplot graphs replaced with more user interactive Plotly Express plots
- 2020-03-08: Additional countries added, user interaction improved
- 2020-03-06: Additional countries added, country selection redone, graphs in tabs
- 2020-03-05: Additional countries added
- 2020-03-04: Additional countries added, a few extra filters
- 2020-03-03: Additional countries added, death rate upper and lower estimate
- 2020-03-02: Additional countries added, made it a bit quicker to update filters
- 2020-03-01: Additional countries added
- 2020-02-29: Additional countries added, some regrouping for filters, different formulat for %deaths (deaths/(deaths+recovered))
- 2020-02-28: Additional countries added
- 2020-02-27: Additional countries added to filters, code improvement to make adding new countries to filters easier
- 2020-02-26: Additional countries added to filters, Graph 3: Recovered + Deaths added

A Colab notebook to display the linked data from [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
A number of filters can be applied (e.g. Europe, Asia, Asia excl Mainland China, Mainland China)

The filters need to be updated manually when new countries are added to the CSSEGISandData datasets.

### Graph 1 (normal or log scale of # of people)
- Confirmed
- Existing (Confirmed - Recovered - Diseased)
- Deaths
- Recovered + Deaths
### Graph 2
- Estimated Recovery Days (date difference between Confirmed >= (Deaths+Recovered)
### Graph 3
- Estimated Mortality (% Deaths / (Deaths+Recovered) - high estimate
- Estimated Mortality (% Deaths / (Confirmed) ~ low estimate
