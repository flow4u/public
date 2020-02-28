

# [Covid_19.ipynb](https://github.com/flow4u/public/blob/master/Covid_19.ipynb)

**Update**
- 2020-02-28: Additional countries added
- 2020-02-27: Additional countries added to filters, code improvement to make adding new countries to filters easier
- 2020-02-26: Additional countries added to filters, Graph 3: Recovered + Deaths added

A Colab notebook to display the linked data from [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
A number of filters can be applied: All, Mainland China, All excl Mainland China, Asia, Europe, Russia, Indian, Western (Europe +
Japan + North America + Australia, Middle East, Others)

The filters need to be updated manually when new countries are added to the CSSEGISandData datasets.

### Graph 1
- Confirmed
- Infected (Confirmed - Recovered - Diseased)
### Graph 2
- Recovered
- Deaths
### Graph 3
- Confirmed
- Recovered
- Recovered + Deaths
### Graph 4
- Recovery Days (date difference between Confirmed >= (Deaths+Recovered)
- Mortality (% Deaths / Confirmed)
