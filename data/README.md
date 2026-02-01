# Datasets

This directory contains the data that is used throughout the project. We included four different datasets in our analysis, namely: 
- [Bridges in Germany 2024](https://opendata-esridech.hub.arcgis.com/datasets/da031936bbaa4aad8302b3bcbf9494b5_0/explore?location=51.010145%2C10.441931%2C6.69&showTable=true)
- [Bridges in Germany 2025](https://www.govdata.de/suche/daten/bruckenstatistik)
- [GDP data in Germany](https://www.statistikportal.de/de/vgrdl/ergebnisse-kreisebene/bruttoinlandsprodukt-bruttowertschoepfung-kreise#alle-ergebnisse) and
- [Population data in Germany](https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/04-kreise.html)

The dataset containing the bridges in Germany is more described in the [following file](data_dictionary.md). 
The GDP data includes the GDP for each district in Germany, while the population data contains the population density. 

---

`Brueckenstatistik-2025.csv`: bridge data set from 2025 (used for comparison of condition scores)

`Brückenstatistik_Deutschland_2024.csv`: bridge data set from 2024 (used for comparison of condition scores)

`districts.geojson`: GeoJSON boundaries for German districts (used for plotting the germany map)

`filled_bridge_statistic_germany.csv`: bridge dataset without missing values

`final_bridge_statistic_germany.csv`: final dataset containing also GDP and population data (used in our analysis)

`gdp_dataset.xlsx`: original GDP dataset

`gdp_dataset_cleaned.csv`: preprocessed GDP dataset

`original_bridge_statistic_germany.csv`: original bridge dataset from 2024

`population_dataset.xlsx`: original population density dataset

`population_dataset_cleaned.csv`: preprocessed population dataset

`reduced_bridge_statistic_germany.csv`: bridge dataset with reduced number of columns

`states.geojson`: GeoJSON boundaries for German states (used for plotting the germany map)

---
