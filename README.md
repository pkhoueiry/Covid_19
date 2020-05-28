# Covid_19 cases in Lebanon
## Computational Biology Lab (Pierre Khoueiry lab at the American University of Beirut)

COVID 19 cases in Lebanon and a selection of other countries for comparison from Our World In Data (https://ourworldindata.org)

NEW: Added (Deaths section below) the Total confirmed cases vs Total confirmed deaths highlighting the % of death for severla countries at once

https://pkhoueiry.github.io/Covid_19/

### Lebanon's current state (based on daily reports)

| Confirmed | 1168 (+7)|
| Recovered | 692      |
| Deaths    | 26      |
| Active    | 450     |


### Trajectories since the 100th confirmed case

The below shows confirmed cases since 100th case. Ideally is to reach a plateau (straight line) and conserve it.
 
<iframe src="https://ourworldindata.org/grapher/covid-confirmed-cases-since-100th-case?country=LBN+FRA+DEU+ITA+USA+CHN+KOR+ESP" style="width: 100%; height: 600px; border: 0px none;"></iframe>

### Confirmed cases

Data is shown by default in LOG allowing us to compare trends between Lebanon and other countries that have large number of cases.

Numbers on the plots may be delayed as compared to the current state of each country. The major aims from the plots is to show the trends and to compare data between countries. More info can be found on https://ourworldindata.org

Daily confirmed COVID-19 cases, rolling **7-day average** which is ideal to see the trend

<iframe src="https://ourworldindata.org/coronavirus-data-explorer?yScale=log&zoomToSelection=true&country=FRA~DEU~IRN~ITA~JOR~LBN~SAU~USA~CHN~KOR~OWID_WRL~ESP&casesMetric=true&dailyFreq=true&aligned=true&smoothing=7" style="width: 100%; height: 800px; border: 0px none;"></iframe>

Per million confirmed cases reflect the spread in different countries normalized to the population size.

<iframe src="https://ourworldindata.org/grapher/total-confirmed-cases-of-covid-19-per-million-people?yScale=log&tab=chart&country=OWID_WRL+ITA+IRN+FRA+GBR+LBN+USA+DEU+SAU+KOR+CHN+ESP" style="width: 100%; height: 600px; border: 0px none;"></iframe>

### Deaths

Daily confirmed COVID-19 deaths per million, 3-day rolling average showing the trend 

<iframe src="https://ourworldindata.org/grapher/daily-covid-deaths-per-million-3-day-avg?tab=chart&yScale=log&year=2020-03-19&country=OWID_WRL+ITA+IRN+FRA+GBR+LBN+USA+DEU+SAU+KOR+CHN+ESP" style="width: 100%; height: 600px; border: 0px none;"></iframe>

Total confirmed cases VS Total confirmed deaths

<iframe src="https://ourworldindata.org/grapher/covid-19-total-confirmed-cases-vs-total-confirmed-deaths?country=LBN" style="width: 100%; height: 600px; border: 0px none;"></iframe>



