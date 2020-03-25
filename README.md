# [Covid_19.ipynb](https://github.com/flow4u/public/blob/master/Covid_19.ipynb)

A [Colab notebook](https://colab.research.google.com/github/flow4u/public/blob/master/Covid_19.ipynb) to display the linked data from [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
Any country can be selected, a quick selection can be made per continent.

The countries needed to be added manually when new countries are added to the CSSEGISandData datasets; every day this Colab will be updated with newly added countries.

## Sources
- [Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
- [Population data from WorldOMeter](https://www.worldometers.info/world-population/population-by-country/)
- [Population data mapped to CSSEGISandData] (https://github.com/flow4u/public/blob/master/Countries%20-%20COVID-19%20countries%20-%20CountriesMapped.csv) 

## Graphs
<details><summary>
  <lu>
    <li>Graph 1: The total numbers per day of a selection of countries</li>
    <li>Graph 2: The total numbers per day of a selection of countries</li>
    <li>Graph 3: Death Progression per country of a selection of countries</li>
    <li>Graph 4: Estimated Recovery Days</li>
    <li>Graph 5: Estimated Mortality Rate</li>
    </summary>
  <hr>
  <h3>Graph 1: The total numbers per day of a selection of countries</h3>
  <p><b>normal or log scale for # of people</b></p>
  <lu>
    <li>Confirmed</li>
    <li>Existing (Confirmed - Recovered - Diseased)</li>
    <li>Deaths</li>
    <li>Recovered + Deaths</li>
  </lu>
</br>
<h3>Graph 2: The total numbers per day of a selection of countries</h3>
<p><b>normal or log scale for # of people</b></p>
<lu>
  <li>daily changes (Confirmed, Deaths, Recovered, Recovered + Deaths)</li>
</lu>
</br>
<h3>Graph 3: Death Progression per country of a selection of countries</h3>
<b>per # of days after 1st death, normal or log scale, absolute or per 1000 people</b>
<lu>
  <li>Death Rate Comparision from 1ste day reported deaths</li>
</lu>
(China data is shifted 13 days to the right for first death was reported on January 9th, data starts on January 22nd)
</br>
<h3>Graph 4: Estimated Recovery Days</h3>
<lu>
  <li>Estimated Recovery Days Lower: (date difference between Confirmed >= (Deaths+Recovered)</li>
  <li>Estimated Recovery Days Upper: (date difference between Confirmed - Deaths >= (Recovered)</li>
</lu>
</br>
<h3>Graph 5: Estimated Mortality Rate</h3>
<lu>
  <li>Estimated Mortality (% Deaths / (Deaths+Recovered) - high estimate</li>
  <li>Estimated Mortality (% Deaths / (Confirmed) ~ low estimate</li>
</lu>
</details>

## Updates
<details><summary></summary>
  <lu>
    <li>2020-03-25: Graph 3 updated, added toggle button between absolute # of death and per 1000 people. For this the dataset <a href="https://github.com/flow4u/public/blob/master/Countries%20-%20COVID-19%20countries%20-%20CountriesMapped.csv", target='blank'>Countries - COVID-19 countries - CountriesMapped.csv</a> is used
    <li>2020-03-24: Countries updated, auto removal obsolete countries from filters, added graph: Death Rate Comparison</li>
    <li>2020-03-18: Countries updated, small code change to capture error with small numbers/early days</li>
<li>2020-03-17: Countries updated</li>
<li>2020-03-15: Countries updated, estimated recovery days upper & lower</li>
<li>2020-03-14: Countries updated</li>
<li>2020-03-12: Countries updated, CSSEGISandData was currated</li>
<li>2020-03-12: Countries added <b>poor data curration see https://github.com/CSSEGISandData/COVID-19/issues/536</b></li>
<li>2020-03-11: Countries added, political incorrect country names removed, added graph daily changes</li>
<li>2020-03-10: Special buttons added: Toggle log/normal, toggle selection of countries per continent</li>
<li>2020-03-10: Additional countries added, all Matlibplot graphs replaced with more user interactive Plotly Express plots</li>
<li>2020-03-08: Additional countries added, user interaction improved</li>
<li>2020-03-06: Additional countries added, country selection redone, graphs in tabs</li>
<li>2020-03-05: Additional countries added</li>
<li>2020-03-04: Additional countries added, a few extra filters</li>
<li>2020-03-03: Additional countries added, death rate upper and lower estimate</li>
<li>2020-03-02: Additional countries added, made it a bit quicker to update filters</li>
<li>2020-03-01: Additional countries added</li>
<li>2020-02-29: Additional countries added, some regrouping for filters, different formulat for %deaths (deaths/(deaths+recovered))</li>
<li>2020-02-28: Additional countries added</li>
<li>2020-02-27: Additional countries added to filters, code improvement to make adding new countries to filters easier</li>
<li>2020-02-26: Additional countries added to filters, Graph 3: Recovered + Deaths added</li>

