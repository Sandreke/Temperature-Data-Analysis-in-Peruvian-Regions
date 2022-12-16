# Temperature-Data-Analysis-in-Peruvian-Regions

## Motivation:

The last decade was the warmest on record according to [NOAA](https://www.noaa.gov/) temperature data. Due to alarming facts about climate change, [Gustavo](https://www.linkedin.com/in/gustavo-urib/) and [Sandro](https://www.linkedin.com/in/sandroagama/) decided to analyze the behavior of one of the most important climate variables: Temperature.

## Data source:

Searching for sources of information about temperature, we found the [Python](https://www.python.org/) library [Meteostat](https://dev.meteostat.net/python/) that provides easy access to open climate data obtained from national weather services like the [NOAA: National Oceanic & Atmospheric Administration](https://www.noaa.gov/) and [Deutscher Wetterdienst](https://www.dwd.de/EN/Home/home_node.html), and gathered by members of the [World Meteorological Organization](https://public.wmo.int/en).

[Meteostat](https://dev.meteostat.net/python/) allows you to get [temperature](https://dev.meteostat.net/python/daily.html#data-structure) time series data (among other variables) of a certain geographic location if you provide its latitude, longitude and altitude.

## Project:

In order to find specific insights, they concluded by delimiting and analyzing the behavior of temperature in [the regions of Peru](https://en.wikipedia.org/wiki/Regions_of_Peru), which is why we divided the project into:

### *Part 1️: [Web scraping of latitude, longitude and altitude](https://www.linkedin.com/feed/update/urn:li:activity:7009576008534085632/)*

You have to provide latitude, longitude and altitude of each capital of the 25 peruvian regions. So, we decided to web scrape 3 internet pages and merge their data with [Python](https://www.python.org/) 🐍 using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) and [Requests](https://requests.readthedocs.io/en/latest/user/quickstart/) libraries because this geographic information that is not on any internet page

+ Page 1 - 25 regions and their capitals: [Sport-histoire](https://www.sport-histoire.fr/es/Geografia/Lista_departamentos_regiones_Peru.php)
+ Page 2️ - Latitude (°) and longitude (°) of each capital: [Geodatos](https://www.geodatos.net/coordenadas/peru/)
+ Page 3️ - Altitude (m.a.s.l.) of each capital: [INEI](https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1253/cap01/cap01012.xls)

> *Deliverable: 1_get_coordinates*

### *Part 2: Web scraping of temperature in peruvian regions through Meteostat*

### *Part 3: Data visualization of temperature time series using Tableau*

### *Part 4: Descriptive analytics of temperature in peruvian regions*

### *Part 5: Forecasting of temperature time series in peruvian regions*
