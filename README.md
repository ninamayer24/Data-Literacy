# Data-Literacy Group Project

### Daten
- Brückenstatistiken
- mehr als 50.000 Brücken (rows)
- [Link zu den Daten](https://opendata-esridech.hub.arcgis.com/datasets/da031936bbaa4aad8302b3bcbf9494b5_0/explore?location=51.010145%2C10.441931%2C6.69&showTable=true)

### TODO bis 05.11.:
- spannende Fragestellung
  - Industrieanstieg allgemein? Krieg? Materialknappheit?
- "cool plot idea" für finalen Report
- erste investigative Plots

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/20ddfacb-554f-46f2-820a-aa9aa9dd79c9" />
Mitte/Ende 1930er: kleiner Peak
Reichsautobahn-Programm, viele Brücken 1936–39

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

