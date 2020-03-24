# [Covid_19.ipynb](https://github.com/flow4u/public/blob/master/Covid_19.ipynb)

A Colab notebook to display the linked data from [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
Any country can be selected, a quick selection can be made per continent.

The countries needed to be added manually when new countries are added to the CSSEGISandData datasets; every day this Colab will be updated with newly added countries.

<details>
  <summary>
    <h3>Graphs</h3>
  </summary>
  <h2>Graph 1: The total numbers per day of a selection of countries</h2>
  <p>normal or log scale for # of people</p>
  <lu>
    <li>Confirmed</li>
    <li>Existing (Confirmed - Recovered - Diseased)</li>
    </li>Deaths</li>
    <li>Recovered + Deaths</li>
  </lu>
### Graph 2: The total numbers per day of a selection of countries
#### normal or log scale for # of people
- daily changes (Confirmed, Deaths, Recovered, Recovered + Deaths)
### Graph 3: Death Progression per country of a selection of countries
#### normal or log scale for # of deaths and # of days
- Death Rate Comparision from 1ste day reported deaths
(China data is shifted 13 days to the right for first death was reported on January 9th, data starts on January 22nd)
### Graph 4: Estimated Recovery Days
- Estimated Recovery Days Lower: (date difference between Confirmed >= (Deaths+Recovered)
- Estimated Recovery Days Upper: (date difference between Confirmed - Deaths >= (Recovered)
### Graph 5: Estimated Mortality Rate 
- Estimated Mortality (% Deaths / (Deaths+Recovered) - high estimate
- Estimated Mortality (% Deaths / (Confirmed) ~ low estimate
</details>

## Updates
- 2020-03-24: Countries updated, auto removal obsolete countries from filters, added graph: Death Rate Comparison
- 2020-03-18: Countries updated, small code change to capture error with small numbers/early days
- 2020-03-17: Countries updated
- 2020-03-15: Countries updated, estimated recovery days upper & lower
- 2020-03-14: Countries updated
- 2020-03-12: Countries updated, CSSEGISandData was currated
- 2020-03-12: Countries added **poor data curration see https://github.com/CSSEGISandData/COVID-19/issues/536
- 2020-03-11: Countries added, political incorrect country names removed, added graph daily changes
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

