# Data Dictionary - bridges

This document describes the features (columns) in the bridges dataset (n = 50,000+ rows). The dataset is sourced from [ESRI Open Data](https://opendata-esridech.hub.arcgis.com/datasets/da031936bbaa4aad8302b3bcbf9494b5_0/explore?location=51.010145%2C10.441931%2C6.69&showTable=true).

The meaning, data type, and possible values of each feature are detailed below.

---

## Features 

| Feature Name | Short Description |
|--------------|-------------------|
|Bauwerksname | Official name of the bridge structure. |
| Baujahr Überbau | Year of construction of the superstructure of the bridge.|
| Baujahr Unterbau | Year of construction of the substructure of the bridge. |
| Zustandsnote | Condition rating of the bridge on a scale from 1 to 4? |
| Baustoff Überbau | Main material used in the superstructure (Überbau) of the bridge. |
| Länge (m) | Length of the bridge in meters. |
| Zugeordneter Sachverhalt vereinfacht | Simplified classification of the bridge (either Autobahn (A) or Bundesstraße (B)). |
| Traglastindex | Load capacity index of the bridge, indicating the maximum load it can safely carry. |
| Teilbauwerksstadium | Stage of the partial structure of the bridge. |
| Teilbauwerksart | The kind of bridge structure (e.g., beam bridge, arch bridge, etc.). |
| Landkreis | The district where the bridge is located. |
| Bundeslandname| The federal state where the bridge is located.| 

---

## Feature Details

### Bauwerksname
- **Description**: Official name of the bridge structure.
- **Data Type**: String
- **Possible Values**: Various bridge names

### Baujahr Überbau
- **Description**: Year when the superstructure of the bridge was constructed.
- **Data Type**: Integer
- **Possible Values**: Years (e.g., 1950, 2000)

### Baujahr Unterbau
- **Description**: Year when the substructure of the bridge was constructed.
- **Data Type**: Integer
- **Possible Values**: Years (e.g., 1950, 2000)

### Zustandsnote
- **Description**: Condition rating of the bridge.
- **Data Type**: Float
- **Possible Values**:  1,0 – 1,4 (very good condition), 1,5 – 1,9 (good condition), 2,0 – 2,4 (satisfactory condition), 2,5 – 2,9 (adequate condition), 3,0 – 3,4 (insufficient condition) und 3,5 – 4,0 (poor condition)
- **source**: [Zustandsnoten](https://www.govdata.de/suche/daten/zustandsnoten-der-brucken)

### Baustoff Überbau
- **Description**: Main material used in the superstructure of the bridge.
- **Data Type**: Categorical
- **Possible Values**: Concrete, Steel, Wood, etc.

### Länge (m)
- **Description**: Length of the bridge in meters.
- **Data Type**: Float
- **Possible Values**: Positive real numbers (e.g., 10.5, 250.0)

### Zugeordneter Sachverhalt vereinfacht
- **Description**: Simplified classification of the bridge.
- **Data Type**: Categorical
- **Possible Values**: Autobahn (A), Bundesstraße (B)

### Traglastindex
- **Description**: Load capacity index of the bridge.
- **Data Type**: Categorical
- **Possible Values**: See [Traglastindex Explanation](https://www.bast.de/DE/Themen/Infrastruktur/HF_2/Massnahmen/Traglastindex.html?nn=401522)

### Teilbauwerksstadium
- **Description**: Stage of the partial structure of the bridge.
- **Data Type**: Categorical
- **Possible Values**: e.g. Bauwerk unter Verkehr, Bauwerk außer Verkehr, etc.

### Teilbauwerksart
- **Description**: The kind of bridge structure.
- **Data Type**: Categorical
- **Possible Values**: Beam bridge, Arch bridge, Suspension bridge, etc.

### Landkreis
- **Description**: The district where the bridge is located.
- **Data Type**: Categorical
- **Possible Values**: Names of districts in Germany (e.g., Tübingen, München)

### Bundeslandname
- **Description**: The federal state where the bridge is located.
- **Data Type**: Categorical
- **Possible Values**: Names of federal states in Germany (e.g., Baden-Württemberg, Bayern)
---


