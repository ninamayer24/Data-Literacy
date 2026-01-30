
## Summaries

This project includes two aggregated summary tables derived from the cleaned bridge dataset. They provide quick, interpretable statistics.

### 1) Summary by federal state (`Bundeslandname`)
Each row represents one German federal state.

**Columns**
- `Bundeslandname`: Federal state name  
- `count`: Number of bridges in the state  
- `mean_zust`: Mean bridge condition score (average condition)  
- `median_zust`: Median bridge condition score (robust central tendency)  
- `mean_age`: Mean bridge age in years  

### 2) Summary by district (`Kreis`)
Each row represents one German district (county level).

**Columns**
- `Kreis`: District name  
- `count`: Number of bridges in the district  
- `mean_zust`: Mean bridge condition score  
- `median_zust`: Median bridge condition score  
- `mean_age`: Mean bridge age in years  
