# Data-Literacy Group Project

### Daten
- Brückenstatistiken
- mehr als 50.000 Brücken (rows)
- [Link zu den Daten](https://opendata-esridech.hub.arcgis.com/datasets/da031936bbaa4aad8302b3bcbf9494b5_0/explore?location=51.010145%2C10.441931%2C6.69&showTable=true)
- BIP Landkreise: https://www.statistikportal.de/de/vgrdl/ergebnisse-kreisebene/bruttoinlandsprodukt-bruttowertschoepfung-kreise#alle-ergebnisse
- population density in germany - dataset:
  https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/04-kreise.html


### PP
[Präsentation](https://unitc-my.sharepoint.com/:p:/g/personal/zxozk31_s-cloud_uni-tuebingen_de/EVm-9SQfaCdEnovx00BHWnYB5iVlkjLMcwsPuNIQnTSEbQ?e=S3bRu8)

### Meeting 06.11.: 
- Daten für Population/BIP runterladen -> mit Brückendaten kombinieren
- Feature: Baujahr Überbau, (Baujahr Unterbau), Zustandsnote, Baustoff Überbau, Länge (m), (Zugeordneter Sachverhalt vereinfacht), Traglastindex, (Teilbauwerksstadium)(https://www.bmv.de/SharedDocs/DE/Artikel/StB/traglastindex.html), (Teilbauwerksart), Kreis, Bundeslandname
- Traglastindex: Was bedeuten die unterschiedliche Indize?

### TODO bis 12.11.: 
- Abstract
- Overleaf Dokument
- alle Daten runtergeladen

### TODO bis 05.11.:
- spannende Fragestellung
  - Industrieanstieg allgemein? Krieg? Materialknappheit?
- "cool plot idea" für finalen Report
- erste investigative Plots


### First thoughts (Johanna): 
**Features (columns) that could be interesting:**
- Baujahr Überbau
- Baujahr Unterbau
- Zustandsnote
- Baustoff Überbau
- Länge (m)
- Breite (m)
- Fläche (qm)
- Traglastindex
- Kreis

**Ideas:**
- focus on a subset of `Kreis`e and try to find regional differences
  - either using those `Kreise`e that contain the largest amount of bridges
  - or using `Kreis`e that have similar number of bridges than `Tübingen`
- How does the bridge condition (`Zustandsnote`) depend on `Baujahr`, `Baustoff`, ... and regional factors?
  - regional factors could be population and area (or density)
- possible analysis: 
  - correlation analysis between age (`Baujahr`) and condition (`Zustandsnote`)
  - linear regression/logistic regression (`Zustandsnote` ~ `Baujahr` + `Baustoff` + `Fläche` + population density + ...)
  - dimensionaly reduction? (will be part of the lecture content)


  ### First thoughts (Paulina): 
  **Ideas:**
  - Regional differences looking at 'Kreis' or 'Bundesland'.
    - How do the bridge conditions ('Zustandsnote') differ between regions? 
      - Does that correlate with economic indicators of those regions (need for additional data)?
    - Are there specific regions with significantly older or newer bridges? (Again correlate with economic indicators)
    - How does the distribution of bridge materials ('Baustoff Überbau') vary across different regions?

  - Weather Impact (maybe not that easy to get data for): 
    - Do weather patterns (rain, snow, ice) in different regions affect the 'Zustandsnote'?

### First thoughts (Ines): 
**Ideas:**

Main question:
- In which federal state are bridges in the worst/best condition and which factors influence the condition? (ralated to year of        construction, type of construction, population density)
  -> visualisation on map
- Hypothesis: Federal states with larger populations (e.g. NRW) tend to have more bridges in a bad condition.

- population density in germany - dataset:
  https://www.destatis.de/DE/Themen/Laender-Regionen/Regionales/Gemeindeverzeichnis/Administrativ/04-kreise.html

**Ideas:** (Nina)
- map with mean Zustandsnote
- relation zustandsnote to poputation, density of streets/highways, material, age
